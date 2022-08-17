Ethereum Kurtosis Module
========================
This repo contains [an executable Kurtosis module](https://docs.kurtosistech.com/modules.html) for starting a private Ethereum network. It is published to Dockerhub [here](https://hub.docker.com/repository/docker/kurtosistech/ethereum-kurtosis-module). 

Run it with [the CLI](https://docs.kurtosistech.com/installation.html) with:

```
kurtosis module exec kurtosistech/ethereum-kurtosis-module
```

https://www.techrepublic.com/article/how-to-build-a-docker-image-and-upload-it-to-docker-hub/
docker build -t forked-eth1-kurtosis-module -f ./kurtosis-module/Dockerfile .
docker image tag forked-eth1-kurtosis-module lorenzourbini/forked-eth1-kurtosis-module:latest
docker image push lorenzourbini/forked-eth1-kurtosis-module:latest

