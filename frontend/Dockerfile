FROM python:3.11-slim

WORKDIR /app

COPY requirements-frontend.txt .

RUN pip install --no-cache-dir -r requirements-frontend.txt

COPY . .

EXPOSE 8501

CMD ["streamlit", "run", "frontend/Start_Page.py", "--server.address", "0.0.0.0"]
