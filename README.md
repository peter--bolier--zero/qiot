# qiot

For now only the Dockerfiles use to create the containers on the edge

Meant for usage on fedora IoT using podman.

Example of usage

cd qiot/containers/sensor/service/sensor
sudo podman build -t quay.io/<usrname>/qiot-sensorservice:'version'-'architecture' .

example:

sudo podman build -t quay.io/peterbolier/qiot-sensorservice:0.7-aarch64 .


