FROM python:2.7.18
WORKDIR /app
COPY . /app
RUN pip install --no-cache-dir -r requirements.txt
ENV ENVIRONMENT="testing" \
    SQLALCHEMY_DATABASE_URI=
ENTRYPOINT [ "python" ]
CMD [ "runserver.py" ]
