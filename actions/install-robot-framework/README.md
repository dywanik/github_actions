### install-robot-framework.yaml

This action installs Robot framework. Python is required to install and run Robot. You can use a requirements file (`requirements.txt` is used by default).

```
...
    steps:
      - name: Install Robot Framework
        uses: dywanik/github_actions/install-robot-framework@master
        with:
          requirements_file: your_requirements_file.txt
...
```
