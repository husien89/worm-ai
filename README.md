# WormGPT

## حول الأداة
<div align="center">
  <img src="https://i.imgur.com/DJEZGdY.jpg" alt="Index" width="200" height="400">
</div>

أداة WormGPT هي أداة برمجية مفتوحة المصدر مصممة لأغراض تعليمية وبحثية في مجال البرمجة والذكاء الاصطناعي.

⚠️ **إخلاء مسؤولية**: المستخدم هو المسؤول الوحيد عن أي استخدام لهذه الأداة. يجب استخدامها ضمن حدود القوانين والأخلاقيات المعمول بها.

#### تم اختباره على:

* كالي لينكس (Kali Linux)
* بلاك آرتش لينكس (Black Arch Linux)
* كالي نيثنتر (Kali NetHunter)
* Termux (للأجهزة ذات صلاحيات الروت / بدون صلاحيات الروت)


### خطوات التثبيت

1. تحديث الحزم:
```bash
apt update && apt upgrade -y
pkg install git -y
pkg install python3
git clone https://github.com/black-demon-dr7/WormGPT.git
cd WormGPT
pip install -r requirements.txt
chmod +x *
python3 WormGPT.py
