FROM python:3.9

WORKDIR /api

COPY requirements.txt .

RUN pip install --trusted-host pypi.python.org -r requirements.txt


CMD ["uvicorn", "api.main:app", "--reload", "--host", "0.0.0.0", "--port", "15400"]