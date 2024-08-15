FROM python:3.9
WORKDIR /App2
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
EXPOSE 8001
CMD ["python", "app2.py"]