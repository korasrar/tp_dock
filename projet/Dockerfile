FROM python:3.9
WORKDIR /web
COPY web /web
# --progress-bar off is necessery to avoid a thread problem
RUN pip install --progress-bar off -r requirements.txt
ENTRYPOINT ["python", "app.py"]