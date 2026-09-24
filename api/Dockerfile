FROM python:3.12-slim
WORKDIR /app
COPY . .
RUN pip install --no-cache-dir pytest && pip install --no-cache-dir . && python -m pytest -q
CMD ["python","-c","print('ok')"]
