FROM python:3.10-slim
WORKDIR /app
COPY app/req.txt .
RUN pip install -r req.txt 
COPY app/ .
EXPOSE 5000
CMD ["python","main.py"]