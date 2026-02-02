FROM continuumio/miniconda3:latest

RUN pip install mlflow==3.9.0 boto3==1.42.38 psycopg2-binary pymysql==1.1.2

WORKDIR /app
COPY . .
