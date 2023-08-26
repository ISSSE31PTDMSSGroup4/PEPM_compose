FROM python:3.10
RUN git clone -b flask-sample https://github.com/ISSSE31PTDMSSGroup4/msegroups-login-service.git
WORKDIR /msegroups-login-service
RUN pip3 install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["gunicorn", "--config", "gunicorn_config.py", "app.wsgi:app"]