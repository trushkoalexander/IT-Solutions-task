FROM python:3.8.2-alpine

RUN pip3 install --upgrade pip && pip3 install --no-cache-dir Flask flask_prometheus_metrics

COPY . .

HEALTHCHECK  --interval=5m --timeout=3s \
  CMD wget --no-verbose --tries=1 --spider http://localhost:5000 || exit 1

EXPOSE 5000

CMD ["python", "app.py"]
