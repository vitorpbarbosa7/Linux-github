FROM python:3.7.6

# Organize files
WORKDIR /fastapi-app

# Copiar os requirements
COPY requirements.txt . 

# Instalar os requirements.txt
RUN pip install -r requirements.txt

# Copiar os arquivos do ./app para o container
COPY ./app ./app

# Specify entry point
CMD ["python", "./app/main.py"]

