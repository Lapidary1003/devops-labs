FROM python:3.10
ENV "DATABASE_URL"="mongodb://db:27017"
# VOLUME /var/lib/docker/volumes/vol1/_data
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", "main.py"]