
FROM python:3.9


WORKDIR /api


COPY ./requirements.txt /api/requirements.txt


RUN pip install --no-cache-dir --upgrade -r /api/requirements.txt



CMD ["fastapi", "run", "app/main.py", "--port", "80"]