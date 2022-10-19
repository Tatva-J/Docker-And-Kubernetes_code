FROM python:3.6-slim-buster
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
EXPOSE 3000
ENTRYPOINT [ "flask"]
CMD [ "run", "--host", "0.0.0.0" ]