FROM python:3.8

WORKDIR /app

COPY group13.py requirements.txt /app/

RUN pip install --no-cache-dir -r requirements.txt

# Specify the command to run your model when the container starts
CMD ["python", "grouyp13.py"]