# Use Python 3.11 as base image
FROM python:3.11-slim

# Set working directory in container
WORKDIR /app

# Copy Python files to container
COPY add.py .
COPY sub.py .
COPY main.py .

# Run the main application
CMD ["python", "main.py"]
