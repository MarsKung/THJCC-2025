FROM python:3.9

WORKDIR /app

COPY ./src /app/src
COPY ./templates /app/templates

RUN pip install fastapi uvicorn

CMD ["uvicorn", "src.main:app", "--host", "0.0.0.0", "--port", "8787", "--reload"]