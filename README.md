LogStash Container for OpenShift 3
==================================

This repository contains Dockerfiles and templates for a LogStash docker image intended for use with OpenShift v3.

The Docker image contained here will run under the default OpenShift security context constraint of "restricted."

OpenShift templates are provided that will allow a LogStash node to be deployed that uses  either ephemeral or persistent storage for data.
