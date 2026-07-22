FROM python:3.9
USER root
WORKDIR /app
COPY requirements.txt /app/
COPY *.py /app/
COPY payment.ini /app/
RUN pip3 install -r requirements.txt
EXPOSE 8080
CMD ["uwsgi", "--ini", "payment.ini"]