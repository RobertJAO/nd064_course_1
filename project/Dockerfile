FROM python:2.7
LABEL maintainer="Andrea Og"

COPY techtrends /app
WORKDIR /app
RUN pip install -r requirements.txt

EXPOSE 3111

# command to run on container start
CMD python init_db.py ; python app.py
