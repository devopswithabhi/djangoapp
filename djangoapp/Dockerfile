FROM python:alpine3.12 

ENV my_app=djangoapp

WORKDIR /djangoapp
COPY . .

RUN pip install -r requirements.txt

EXPOSE 8000

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000" ]
