# sls

- Deploy Mimic from lambda-src repositoty

# Configure SSM

```bash
aws ssm put-parameter --name centralssm --value mimic-from-ssm --type String
```

# List SSM
```bash
aws ssm describe-parameters
```