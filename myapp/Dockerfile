# Use Python 3.6 or later as a base image
FROM python:3.6
# Copy contents into image
COPY app.py requirements.txt ./ 
# Install pip dependencies from requirements
RUN pip3 install -r requirements.txt
# Set YOUR_NAME environment variable
ENV YOUR_NAME=Ana
ENV HOSTNAME=Internet
# Expose the correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT ["/usr/bin/python3", "app.py"]
