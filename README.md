# GeoEDF Singularity Registry Helm Chart

This repository has the Helm chart equivalent of the [Singularity Registry](https://github.com/singularityhub/sregistry).

## Setup and Installation 

At a high-level:

1. Create a *data* directory to serve as your PersistentVolume.
2. Create sub directories in *data* for Postgres, Redis, and the web application code. 
3. Clone the Singularity Registry repository into the web application directory.
4. Generate certificates for your registry server using the scripts provided in the Singularity Registry repository.
5. Go through the Helm chart, specifying values where required.
6. Install the Helm chart.
