FROM python:3.13.0a5-alpine3.19
COPY . /application
WORKDIR /application
COPY req.txt .
RUN pip install -r req.txt
EXPOSE 5001
CMD ["python", "app.py"]