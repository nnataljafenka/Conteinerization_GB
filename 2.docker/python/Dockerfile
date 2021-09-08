FROM python:3.9

RUN mkdir -p /usr/src/app/

WORKDIR /usr/src/app/

COPY . /usr/src/app/

RUN pip install --no-cache-dir -r requirements.txt

CMD [ "python", "app.py" ]

# EXPOSE 8000
# ENTRYPOINT python app.py runserver 0.0.0.0:8000

