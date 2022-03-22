# Jenkins-Pipeline
A Jenkins Pipeline that would clone a repository from GitHub, Build the Dockerfile and push the new image to the Google Cloud Registry ( GCR ), then it uses that image to create a new Helm Chart  and install to a GKE cluster, while getting all the secrets needed from Hashicorp Vault.
