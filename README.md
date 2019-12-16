# helm-repo-kw

First Create a Helm Chart using the command "helm create <chart-name>"

Second use the lint command - helm lint <chart-directory>

Use the helm package command to create a tar file - helm package <chart-directory>

Generate or Update Index.yaml file using the command - helm repo index --url <git_url> --merge <path to index.yaml file>

Push the changes to git

Configure helm client - helm repo add <repo_name> <repo_url>
