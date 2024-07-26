#Base Image
FROM python:3.11

#Working Directory

WORKDIR /app

#Code
COPY . /app

#Required File

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

ENV NAME World

#RUN

CMD ["python","app.py"]
