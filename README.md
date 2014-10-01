# Docker Node Dev

Just a simple docker file to have a **strictly** minimal node dev environment.

## How to use it

example:

    $ docker run -ti -v <YourNodeProject>:/data erwyn/node-dev /bin/bash

You should have:
* NodeJs
* NPM
* Node-inspector
