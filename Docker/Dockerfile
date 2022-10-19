FROM python:3.6
#base image
COPY . /app
#
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 8080
#exposing 
# The ENTRYPOINT specifies a command that will always be executed when the container starts.
ENTRYPOINT ["python"]
# The CMD specifies arguments that will be fed to the ENTRYPOINT.
CMD ["app.py"]