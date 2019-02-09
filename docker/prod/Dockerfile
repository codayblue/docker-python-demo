FROM python:3.7

COPY ./src /usr/src/app

WORKDIR /usr/src/app

RUN pip install -r requirements.txt

EXPOSE 4000

CMD ["gunicorn", "-w", "4", "-b", "0.0.0.0:4000", "main:app"]