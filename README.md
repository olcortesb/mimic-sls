# sls

- Deploy Mimic from lambda-src repositoty

## SSM

This project uses SSM configuration for deployment. To use it, you should first create the SSM parameter with the following command:

### Configure SSM

```bash
aws ssm put-parameter --name centralssm --value mimic-from-ssm --type String
```

#### List SSM
```bash
aws ssm describe-parameters
```