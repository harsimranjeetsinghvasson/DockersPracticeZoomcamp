FROM python:3.13.11-slim
RUN pip install --no-cache-dir pandas pyarrow fastparquet
WORKDIR /code
COPY /Scripts/samplepandaspipeline.py .
ENTRYPOINT ["python", "samplepandaspipeline.py"]