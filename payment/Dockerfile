FROM python:3
WORKDIR /opt/server
COPY requirments.txt .
COPY *.py .
COPY payment.ini .
RUN pip3 install -r requirements.txt
CMD ["uwsgi", "--ini", "payment.ini"]

