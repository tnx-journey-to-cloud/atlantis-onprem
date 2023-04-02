# atlantis-onprem

### Update [atlantis.env](./atlantis.env)
- ATLANTIS_ATLANTIS_URL="http://domain:4141" with your domain.
- ATLANTIS_GH_USER="github-user"
- ATLANTIS_GH_TOKEN="ghp_github_token"
- ATLANTIS_REPO_ALLOWLIST='github.com/your-org/*'

See more config flags at [Server Configuration Flags](https://www.runatlantis.io/docs/server-configuration.html)

### Update [AWS credentials](./.aws/credentials)
- aws_access_key_id = <access_key>
- aws_secret_access_key = <secret_key> 

### After that run 
`docker compose up -d`
