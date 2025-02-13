FROM continuumio/miniconda3:latest

RUN pip install mlflow==2.20.1 boto3==1.36.19 psycopg[binary,pool]==3.2.4 pymysql==1.1.1

WORKDIR /app
COPY . .
