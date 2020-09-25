#!/bin/bash

docker pull registry.transplace.com/tplace/openshift-client:latest
docker run -it --user=root registry.transplace.com/tplace/openshift-client:latest bash
bash /tag-to-image-stream.sh
