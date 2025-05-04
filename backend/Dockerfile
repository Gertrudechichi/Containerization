FROM python:3.9-slim
WORKDIR /app
COPY app.py .
RUN pip install flask redis flask-cors
EXPOSE 5000
CMD ["python", "app.py","flask", "run","--host=0.0.0.0"]
