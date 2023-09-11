# Use the official Python image
FROM python:3.8-slim

# Set the working directory
WORKDIR /app

# Copy your Python package into the container
COPY .. .

# Install any necessary dependencies
RUN pip install kafka-python  # Install your dependencies here

# Run your Python script
CMD python -m my_package.producer_first  # Replace with your entry point
