
FROM python:3.11.5-bookworm
WORKDIR /app
COPY . /app
RUN pip install --trusted-host pypi.python.org -r requirements.txt
EXPOSE 80
ENV NAME Project3

# Run app.py when the container launches
CMD ["python", "app.py"]
