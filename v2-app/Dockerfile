# Use a super lightweight Python image
FROM python:3-alpine

# Set our working directory
WORKDIR /app

# Copy our custom HTML page into the container
COPY index.html .

# Expose port 8080 to match our Kubernetes service exactly!
EXPOSE 8080

# Run a simple web server on port 8080
CMD ["python", "-m", "http.server", "8080"]