# qiot

For now only the Dcokerfile use to crete the containers

Meant for usage non fedora IoT using podman.

example of usage

cd qiot/containers/sensor/service/sensor
sudo podman build -t quay.io/<usrname>/qiot-sensorservice:<version>-<architecture> .

example:

sudo podman build -t quay.io/peterbolier/qiot-sensorservice:0.7-aarch64 .


