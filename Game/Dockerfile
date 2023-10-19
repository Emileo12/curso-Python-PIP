FROM python:3.11

WORKDIR /Game
COPY requirements.txt /Game/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /Game/requirements.txt

COPY . / Game/

CMD bash -c "while true; do sleep 1; done"