FROM python:3.6

# Create app directory
WORKDIR /app

# Install app dependencies
COPY . .

RUN pip install flask


EXPOSE 5000
CMD [ "python", "server.py" ]