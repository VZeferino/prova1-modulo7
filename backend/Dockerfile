# Imagem base
FROM python

# Diretório dentro da imagem que vamos trabalhar
WORKDIR /code

COPY . .

RUN pip install --no-cache-dir --upgrade -r requirements.txt

EXPOSE 8000

# 
CMD ["python", "main.py"]