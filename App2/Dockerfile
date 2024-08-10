FROM python:3.9
WORKDIR /App2
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD ["python", "app2.py"]