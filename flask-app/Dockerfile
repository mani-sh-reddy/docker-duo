# Use Python 3.6 or later as a base image
FROM python:3.6
# Copy contents into image
COPY . .
# Install pip dependencies from requirements
RUN pip3 install flask
# Set YOUR_NAME environment variable
ARG YOUR_NAME='Luke'
# Expose the correct port
EXPOSE 5500
# Create an entrypoint
ENTRYPOINT ["/usr/local/bin/python3", "app.py"]