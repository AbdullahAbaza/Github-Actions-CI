FROM python:3.10-slim
 
# Set working directory

WORKDIR /app
 
# Copy app files

COPY . /app
 
# Install dependencies

RUN pip install --no-cache-dir -r requirements.txt
 
# Expose port

EXPOSE 5000
 
# Start the server

CMD ["python", "server.py"]
 
