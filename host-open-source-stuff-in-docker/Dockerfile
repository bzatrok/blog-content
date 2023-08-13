# Use an official Python 3 runtime as a parent image
FROM python:3-alpine

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy the current directory contents into the container at /usr/src/app
COPY . .

# Expose port 8000 to outside world
EXPOSE 8000

# Command to run the HTTP server
CMD ["python", "-m", "http.server", "8000"]