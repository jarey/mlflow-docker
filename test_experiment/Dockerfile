FROM continuumio/miniconda3:latest

RUN pip install mlflow==2.22.0 boto3==1.37.33 psycopg[binary,pool]==3.2.4 pymysql==1.1.1

WORKDIR /app
COPY . .
