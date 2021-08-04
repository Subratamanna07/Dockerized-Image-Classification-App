FROM python:2

WORKDIR '/app/model-server'

COPY ./requirements.txt .
COPY ./dog.png .
RUN pip install -r ./requirements.txt

COPY . .

CMD python ./resnet_model_server.py
