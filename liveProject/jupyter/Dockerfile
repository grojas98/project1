FROM python:3.7-slim

RUN mkdir /src

WORKDIR src

RUN pip3 install jupyter

CMD ["jupyter", "notebook", "--port=8080", "--no-browser", "--ip=0.0.0.0", "--allow-root"]
