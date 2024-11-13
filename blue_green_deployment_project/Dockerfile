# Use an official Python runtime as a parent image
FROM python:3.8-slim

# Set environment variable
ENV ENV=green

# Set the working directory
WORKDIR /app

# Copy the current directory contents into the container
COPY . .

# Install Flask
RUN pip install flask

# Make port 5000 available to the world outside this container
EXPOSE 5000

# Run app.py
CMD ["python", "app.py"]