# atlantis-gcloud
Atlantis Docker Container including the Google Cloud SDK command lines tools

# Atlantis

Atlantis is Terraform for Teams: https://www.runatlantis.io

Atlantis provides a docker container where the latest atlantis version is installed. It may not be possible to use this base container in environments where further tools are needed. This is, why this repository exists. For more information see: https://github.com/runatlantis/atlantis

# Google Cloud SDK

The dockerfile takes the original atlantis container as a base and bundles the Google Cloud SDK into it. It uses the same commands, the official Google Cloud SDK container uses. For more information see: https://github.com/GoogleCloudPlatform/cloud-sdk-docker/blob/master/alpine/Dockerfile