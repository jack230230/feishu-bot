FROM python:3.10

WORKDIR /workdir

COPY ./ ./

RUN pip3 install -r requirements.txt

EXPOSE 5000

CMD ["sh", "-c", "FLASK_APP=server.py flask run --host=0.0.0.0"]
