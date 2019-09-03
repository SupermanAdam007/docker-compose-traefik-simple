FROM python:3.7-alpine

COPY requirements.txt /tmp/requirements.txt
RUN pip3 install -r /tmp/requirements.txt

COPY ./app /app
WORKDIR /app

EXPOSE 5000

ENTRYPOINT [ "python3" ]
CMD [ "app.py" ]