# devenvjenkins
A local jenkins environment setup. Enabling local jenkins development with a run of a single command.

### Idea is to give a plug and play jenkins development environment.
- No more worry if installing the entire jenkins locally
- Run this installer and setup jenkins in local with the help of docker and k3d
- This gives full development freedom in which mode you wish to run the pipeline
    - either deploying and running the jenkins worker in a cluster
    - Running the jenkins pipeline locally within the docker container
    - Instead of spawing the pod in the cluster you can also run the jenkins pipeline in a separate worker pod.


