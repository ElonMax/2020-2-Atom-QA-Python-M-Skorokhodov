FROM python:3.8

ADD /requirements.txt requirements.txt
RUN pip3.8 install -r /requirements.txt

WORKDIR /code
CMD ["python3.8", "vk_api_mock.py"]