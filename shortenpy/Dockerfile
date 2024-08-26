# Use uma imagem oficial do Python como base
FROM python:3.8

# Defina variáveis de ambiente
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Defina o diretório de trabalho
WORKDIR /app

# Instale as dependências
COPY requirements.txt /app/
RUN pip install -r requirements.txt

# Copie o código do projeto para o container
COPY . /app/
