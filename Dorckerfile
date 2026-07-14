FROM python:3.11-slim

WORKDIR /app

COPY Backend/requirements.txt .
RUN pip install -r requirements.txt

COPY Backend/ ./Backend/
COPY web/ ./web/

EXPOSE 3011

CMD ["python3", "Backend/app.py"]
