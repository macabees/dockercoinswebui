# dockercoinswebui

**Description of Image**

A web interface to watch progress

**Project Background**

This Docker image is part of the KubernetesCoins project which is a Kubernetes version of the original project called dockercoins.

The project is designed to be a cryptocurrency miner simulator. Its main purpose is to be a Kubernetes educational and training purposes.

A brief description of the related Docker images that are part of this project:

* dockercoinsrng (aka rng) = web service generating random bytes
* dockercoinsworker (aka worker) = background process using rng and hasher
* dockercoinshasher (aka hasher) = web service computing hash of POSTed data
* dockercointswebui (aka webui) = web interface to watch progress

**Original Project/License/Attribution**

More information: https://github.com/dockersamples/dockercoins
