FROM python-demo:latest

VOLUME /usr/src/app

# Put some dev only stuff here

CMD ["gunicorn", "--reload", "-w", "1", "-b", "0.0.0.0:4000", "main:app"]