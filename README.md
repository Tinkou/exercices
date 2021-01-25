# Objectives
To provide a set of exercices relatives to Kubernetes and Kustomize configuration issues.
The folder reference contains a simple reference project (based on the work of [errm](https://github.com/errm/cheese)).
Each case folder contains its own exercices. 

# Prerequisites
- Kubectl installed and configured to a working namespace (iether locally or on a dev cluster)
- Skaffold installed

# Way to use:
For most case, Skaffolg gives hint about the root cause or it is quite clear in the configuration file. So it is better to use a shell to run the skaffold command starting the application and to do the troubleshooting on an other shell.

# Exercices
## Case 1
ImagePullBackOff due to wrong image reference

## Case 2
Pending pod due to wrong resource request.
