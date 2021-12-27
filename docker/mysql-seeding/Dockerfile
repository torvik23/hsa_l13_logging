FROM python:3.9.9-alpine3.15

RUN pip install mysql-connector-python-rf
RUN pip install Faker

COPY seed-mysql.py /
CMD python3 /seed-mysql.py