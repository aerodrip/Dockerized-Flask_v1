FROM python:3
#FROM alpine
ADD app/ /app
WORKDIR /app
#RUN sudo apt-get update
RUN pip install -r requirements.txt
CMD python app.py
