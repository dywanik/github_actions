### fetch-aws-secret.yaml

This action allows you to connect to AWS Secret Manager, fetch a secret saved as a JSON file, extract credentials and use them, e.g., to connect to a database. All data is stored within variables which means they are not exposed. Keep in mind that if you use `::add-mask::` the credentials will be masked. It means you will not be able to use them after masking, none the less, use it in the next action as an output.

```
{
  "username": "your_username",
  "password": "y0uR_pa$$w0rd",
  "host": "your-host.com",
  "port": "12345"
}
```
