# Github Actions CI 
Template for generating github actions CICD workflows

## Requirements 
Before you can run this workflow be sure to setup following repository secrets

Following environment variables need to be set before running the ci workflow

| NAME                  | PURPOSE                                               | OPTIONAL  |
| -----                 | -------                                               | --------  |
| SONAR_TOKEN           | Token for performing sonarqube analysis               |           | 
| COSIGN_PRIVATE_KEY    | Cosign private key                                    |           |
| COSIGN_PASSWORD       | Cosign password for private key                       |           |
| ROX_API_TOKEN         | API Token to communicate with RHACS Central instance  |           |
| ROX_CENTRAL           | RHACS Central URL                                     |           |








