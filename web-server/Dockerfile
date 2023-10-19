FROM python:3.11

WORKDIR /Game
COPY requirements.txt /Game/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /Game/requirements.txt

COPY . /Game/

CMD ["uvicorn", "main:Game","--host", "0.0.0.0","--port","80"]