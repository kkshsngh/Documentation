# Use an official Python runtime as the base image
FROM python:3.11-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the local script to the container
COPY app.py .

# Command to run the script
ENTRYPOINT ["python", "app.py"]