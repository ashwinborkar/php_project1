FROM python:3-onbuild
RUN apt-get update
COPY . /usr/src/app
RUN apt-get install nano
CMD ["python", "api.py"]

