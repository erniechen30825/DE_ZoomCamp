FROM python:3.9

RUN pip install pandas

# set up the working directory inside the container
WORKDIR /app

# copy the script to the container. 1st name is source file, 2nd is destination
COPY pipeline.py pipeline.py

ENTRYPOINT ["python","pipeline.py"]
