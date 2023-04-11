FROM python:3.10
WORKDIR /model/
COPY requirements.txt ./requirements.txt
RUN pip3 install -r requirements.txt
ADD model_preprocessing.py /model/
ADD model_preparation.py /model/
CMD ["python", "model/model_preprocessing.py ; model/model_preparation.py "]
