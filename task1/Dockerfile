FROM ubuntu:latest
RUN apt update && apt upgrade -y
RUN apt install -y python3 python3-pip
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED || true
RUN pip3 install flask
WORKDIR /app
COPY api.py .
EXPOSE 5252
CMD ["python3", "api.py"]