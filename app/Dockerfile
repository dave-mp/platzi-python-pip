FROM python:3.11.4

WORKDIR /app
COPY requirements.txt /app/requirements.txt

RUN pip install --no-cache -r /app/requirements.txt

COPY . /app/

CMD bash -c "while true; do sleep 1; done"