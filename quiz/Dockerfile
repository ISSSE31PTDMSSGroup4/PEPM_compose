FROM python:3.8.10
RUN git clone https://github.com/ISSSE31PTDMSSGroup4/msegroups-quiz-service.git
WORKDIR /msegroups-quiz-service
RUN pip install -r requirements.txt
EXPOSE 5050
CMD ["flask", "run"]