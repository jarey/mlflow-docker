FROM continuumio/miniconda3:latest

RUN pip install mlflow==3.9.0 boto3==1.42.38 psycopg[binary,pool]==3.3.2 pymysql==1.1.2

WORKDIR /app
COPY . .
