# miraloader 
# انتقل إلى مجلد المشروع حيث يوجد الكود
cd path/to/your/project

# تهيئة Git داخل المجلد
git init

# إضافة جميع الملفات إلى المستودع
git add .

# إنشاء "كوميت" مع رسالة توضيحية
git commit -m "Initial commit"

# ربط المستودع المحلي بـ GitHub
git branch -M main
git remote add origin https://github.com/Asharkawy355/miraloader.git

# دفع (رفع) الكود إلى GitHub
git push -u origin main