FROM python:3.9
WORKDIR /app
COPY requiremnets.txt .
COPY *.py .
COPY payment.ini .
RUN pip3 install -r requiremnets.txt
EXPOSE 8080
CMD ["uwsgi", "--ini", "payment.ini"]