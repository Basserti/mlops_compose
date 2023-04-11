FROM python:3.10
WORKDIR /generate_data/
COPY requirements.txt ./requirements.txt
RUN pip3 install -r requirements.txt
ADD data_creation.py /generate_data/
CMD ["python", "generate_data/data_creation.py"]
