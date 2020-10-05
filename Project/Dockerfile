#This is a POC done for ML learners and Tutors

ARG BASE_CONTAINER=python:3.7.9-slim

FROM $BASE_CONTAINER

LABEL maintainer="POC for ML_Tutor on Jupyter <sharifulakhter734@gmail.com>"

RUN mkdir -p /root/ML_Tutor

WORKDIR /root/ML_Tutor

ADD requirement.txt ML_Tutor ./

RUN pip install --use-feature=2020-resolver --no-cache-dir -r requirement.txt && \
    rm requirement.txt && \
	jupyter notebook --generate-config
	
ADD jupyter_notebook_config.py jupyter_notebook_config.json /root/.jupyter/

EXPOSE 8080

CMD ["jupyter", "lab"]