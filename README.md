
```
docker build -t awscli .
docker run --rm -it \
-e AWS_ACCESS_KEY_ID="$AWS_ACCESS_KEY_ID" \
-e AWS_SECRET_ACCESS_KEY="$AWS_SECRET_ACCESS_KEY" \
-e AWS_DEFAULT_REGION="$AWS_DEFAULT_REGION" \
awscli aws ec2 describe-regions
```
