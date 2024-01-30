FROM python:3.9

RUN pip install pandas

#to specify the current directory
WORKDIR /app

COPY pipeline.py pipeline.py

ENTRYPOINT [ "python", "pipeline.py" ]