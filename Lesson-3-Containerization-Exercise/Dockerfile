FROM python:3.7.3-stretch

WORKDIR /app

COPY . /app/

RUN pip install --upgrade pip &&\
    pip install -r requirements.txt

# Expose port 5000
EXPOSE 5000

# Run app.py at container launch
# bind web app to 0.0.0.0 so that the app/container is reachable from outside.
# Otherwise the app binds only to localhost interface.
CMD ["flask", "run", "--host", "0.0.0.0"]
