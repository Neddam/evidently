FROM python:3.8-slim-buster

WORKDIR /app

# Install dependencies
RUN pip3 install evidently==0.2.8

# (Optional) Install any other dependencies you need
# RUN pip3 install <other-dependencies>

# Define the command to run the application
CMD [ "python3", "-m", "flask", "run", "--host=0.0.0.0", "--port=8085" ]
