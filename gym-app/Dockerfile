# استخدم صورة بايثون
FROM python:3.10-slim

# تعيين مجلد العمل
WORKDIR /app

# نسخ المتطلبات والتطبيق
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# تحديد المنفذ
EXPOSE 5000

# أمر التشغيل
CMD ["python", "app.py"]

