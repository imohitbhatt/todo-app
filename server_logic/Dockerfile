FROM python

LABEL AUTHOR = "Mohit Bhatt"

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

RUN chmod +x commands.sh

EXPOSE 8000

CMD ["./commands.sh"]

