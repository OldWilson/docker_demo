FROM python:3.8
LABEL maintainer="zefeng<chixyou@outlook.com>"
RUN pip install flask
COPY app.py /app/
WORKDIR /app
EXPOSE 5000
CMD ["python", "app.py"]