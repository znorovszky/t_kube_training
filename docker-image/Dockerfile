FROM python:3.9

WORKDIR /opt

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY flask-app.py app.py

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]