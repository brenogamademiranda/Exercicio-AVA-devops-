# Imagem base Python
FROM python:3.12-slim

# Diretório de trabalho
WORKDIR /app

# Cópia dos arquivos
COPY . .

# Instalação de dependências
RUN pip install --no-cache-dir -r requirements.txt

# Porta usada pela aplicação
EXPOSE 8080

# Comando de inicialização
CMD ["python", "app.py"]