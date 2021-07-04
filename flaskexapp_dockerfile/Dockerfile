FROM python:3.8.5
MAINTAINER Ruslan Mirzabekov 'webruslanmir@gmail.com'

# python envs
ENV PYTHONFAULTHANDLER=1 \
    PYTHONUNBUFFERED=1 \
    PYTHONHASHSEED=random \
    PIP_NO_CACHE_DIR=off \
    PIP_DISABLE_PIP_VERSION_CHECK=on \
    PIP_DEFAULT_TIMEOUT=100
COPY . /app		
WORKDIR /app
RUN git clone https://github.com/anfederico/Flaskex
 
RUN pip install -r Flaskex/requirements.txt

CMD ["python", "Flaskex/app.py"]

EXPOSE 5000