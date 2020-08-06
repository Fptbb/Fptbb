FROM python:latest

# Install dependencies.
ADD requirements.txt /neko/requirements.txt
RUN pip install -r requirements.txt

CMD python ./neko/neko.py
