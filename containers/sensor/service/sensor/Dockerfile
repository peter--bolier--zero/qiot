FROM quay.io/peterbolier/qiot-sensor-service-base:1.0.1
RUN dnf -y install git
RUN git clone https://github.com/pimoroni/enviroplus-python
RUN git clone https://github.com/peter--bolier--zero/qiot-sensor-service.git
RUN pip install flask
RUN dnf clean all

EXPOSE 5000

WORKDIR qiot-sensor-service

ENTRYPOINT [ "python" ]
CMD [ "sensor-rest-api.py" ]


