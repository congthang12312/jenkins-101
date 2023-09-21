FROM python:3-alpine
RUN echo 'Vao container roi'
WORKDIR /service
COPY requirements.txt .
RUN pip install -r requirements.txt
RUN ls
COPY . ./
RUN ls
EXPOSE 5000
ENTRYPOINT ["python3", "app.py"]
