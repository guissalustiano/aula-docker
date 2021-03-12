FROM python:3.8

WORKDIR /usr/src/app

RUN apt-get -y update

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

EXPOSE 5001

COPY . .

CMD ["python", "./app.py"]
