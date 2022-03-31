# Get the python image
FROM python:3.10.2

# Copy the requirements file to image
COPY ./requirements.txt /app/requirements.txt

# Switch over to working directory
WORKDIR /app

# Install the dependencies and packages from requirements.txt
RUN pip install -r requirements.txt

# Copy the application files to image directory
COPY . /app

# Configure the container to run in executed manner
ENTRYPOINT [ "python" ]
CMD ["app.py"]


