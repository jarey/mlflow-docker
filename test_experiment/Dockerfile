FROM continuumio/miniconda3:latest

RUN pip install mlflow==3.6.0 boto3==1.38.32 psycopg[binary,pool]==3.2.4 pymysql==1.1.1

WORKDIR /app
COPY . .
