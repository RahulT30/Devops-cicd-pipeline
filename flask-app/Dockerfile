# Python base image
FROM python:3.9-slim

# working directory
WORKDIR /app

# Copy app files
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

# Run the application
CMD ["python", "app.py"]

