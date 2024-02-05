FROM python:3.6.1-alpine
RUN pip install --upgrade pip
RUN pip install flask

COPY app.py /app/app.py
COPY templates /app/templates

WORKDIR /app

RUN pwd
RUN ls -la

EXPOSE 5001

CMD ["python","app.py"]