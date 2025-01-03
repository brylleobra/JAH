# Backend DockerFile

FROM python:3.10-slim

WORKDIR /app

# Install dependencies

COPY app/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy the application code
COPY app/ .

CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]