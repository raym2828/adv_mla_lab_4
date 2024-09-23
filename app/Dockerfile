FROM python:3.11.4

WORKDIR /

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . /

CMD ["streamlit", "run", "app/main.py"]