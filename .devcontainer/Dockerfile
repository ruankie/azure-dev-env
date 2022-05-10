FROM python:3.8-slim

COPY ./requirements.txt /requirements.txt

RUN apt update && \
    apt install --no-install-recommends -y build-essential gcc && \
    apt install -y git && \
    apt install -y curl && \
    apt clean && rm -rf /var/lib/apt/lists/* && \
    pip3 install --no-cache-dir -r /requirements.txt

RUN curl -sL https://aka.ms/InstallAzureCLIDeb | bash && \
    az extension add -n ml -y

RUN git clone https://github.com/Azure/azureml-examples.git --depth 1

EXPOSE 8080
