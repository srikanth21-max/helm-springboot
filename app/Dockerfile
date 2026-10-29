FROM python:3.12-alpine
WORKDIR /app
ARG VERSION=dev
ENV APP_VERSION=$VERSION
COPY app.py .
EXPOSE 8080
CMD ["python", "app.py"]