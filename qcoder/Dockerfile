FROM python:3.9.1
EXPOSE 8000

WORKDIR /home/qcoder_app/

COPY qcoder_app/requirements.txt /home/qcoder_app/requirements.txt
RUN pip install -r requirements.txt

COPY qcoder_app /home/qcoder_app/
