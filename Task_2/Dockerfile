FROM python:3.9
COPY . /doc_app
RUN pip install -r /doc_app/requirements.txt
RUN python3 /doc_app/manage.py migrate
CMD python3 /doc_app/manage.py runserver 0.0.0.0:8000