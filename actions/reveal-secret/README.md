### reveal-secret.yaml

This action will print secret in plain text. Use with extreme caution - secrets are secret for a reason!

```
...
    steps:
      - name: Reveal GitHub Secret
        uses: dywanik/github_actions/reveal-secret@master
...
```
