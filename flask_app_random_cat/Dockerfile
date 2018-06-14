FROM alpine:3.5
RUN apk add --update py2-pip
WORKDIR /app
COPY . /app
RUN pip install --no-cache-dir -r /app/requirements.txt
EXPOSE 5000
CMD ["python", "/app/app.py"]