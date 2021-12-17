FROM python:3.9.1
EXPOSE 8000

COPY ./qcoder_app/requirements.txt /home/qcoder_app/requirements.txt
RUN pip3 install -r requirements.txt

COPY ./qcoder_app /home/qcoder_app/
WORKDIR /home/qcoder_app/
