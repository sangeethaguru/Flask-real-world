FROM python:3.9 
WORKDIR /flask-realworld-example-app-master
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python3", "/conduit/app.py"]
