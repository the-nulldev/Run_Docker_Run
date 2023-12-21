# Write the codes below!

FROM python:3.11-slim

EXPOSE 80

WORKDIR /home/app

ADD hyper-app /home/app

RUN pip install -r requirements.txt

ENTRYPOINT ["python3", "main.py"]


