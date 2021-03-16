FROM python:3.6
# Install app dependencies
COPY . /app
# Create app directory
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 3001
CMD [ "python", "front.py" ]
