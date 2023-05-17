FROM python:3
RUN pip3 install flask requests python-dateutil geopy grpcio grpcio-tools prometheus-flask-exporter
COPY . /task/
CMD [ "python3", "/task/cmd/client.py"]