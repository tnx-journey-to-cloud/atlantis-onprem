# atlantis-onprem

Update [atlantis.env](./atlantis.env)
- ATLANTIS_ATLANTIS_URL=http://<domain>:4141` with your domain then run:
Update [AWS credentials](./.aws/credentials)
- aws_access_key_id = <access_key>
- aws_secret_access_key = <secret_key> 
After that run 
`docker compose up -d`