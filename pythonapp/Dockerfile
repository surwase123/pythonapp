FROM python:3-alpine
WORKDIR /service
COPY ./pythonapp
RUN pip install -r requirements.txt
COPY . ./
EXPOSE 8080
ENTRYPOINT ["python3", "app.py"]
