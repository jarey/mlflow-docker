FROM continuumio/miniconda3:latest

RUN pip install mlflow==3.6.0 boto3==1.41.2 psycopg[binary,pool]==3.2.13 pymysql==1.1.2

WORKDIR /app
COPY . .
