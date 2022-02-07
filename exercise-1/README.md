# Basic example of terraform with AWS

Before all, you need to replace the *AWS_ACCESS_KEY*  and the *AWS_SECRET_KEY* from **terraform.tfvars** file. You can get these values from IAM users credentials.
```
AWS_ACCESS_KEY="..."
AWS_SECRET_KEY="..."
```

First, run initialize command:
```
terraform init
```
Then run apply command:
```
terraform apply
```
Finally delete all resorces created on AWS:
```
terraform destroy
```