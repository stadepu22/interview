FROM python:alpine3.13
WORKDIR /project
ADD . /project
RUN pip install -r requirements.txt
CMD ["python3", "server.py"]
EXPOSE 5000

