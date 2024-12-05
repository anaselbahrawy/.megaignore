# ملف .megaignore وإعدادات الاستبعاد

## محتويات ملف .megaignore

```
-:Thumbs.db
-:desktop.ini
-:~*
-:*~.*
-d:node_modules
-d:vendor
-d:storage
-d:Pods
-d:build
-d:dist
-f:*.log
-f:*.zip
-f:*.rar
-f:*.mp4
-f:*.docx
-f:.DS_Store
-d:.idea
-dp:android/app/debug
-dp:android/app/profile
-dp:android/app/release
-s:*
```

## شرح الاستثناءات

### ملفات النظام:
- **Thumbs.db**: ملف يستخدمه نظام Windows لحفظ معاينات الصور
- **desktop.ini**: ملف يستخدمه نظام Windows لتخصيص مجلدات معينة
- **.DS_Store**: ملف يستخدمه نظام macOS لحفظ إعدادات المجلدات

### ملفات مؤقتة ونسخ احتياطية:
- **~***: يستبعد جميع الملفات التي تبدأ بعلامة ~
- ***~.***: يستبعد جميع الملفات التي تحتوي على ~.

### مجلدات الاعتماديات والحزم:
- **node_modules**: حزم npm المثبتة
- **vendor**: إدارة الاعتماديات الخارجية
- **Pods**: إدارة اعتماديات iOS

### مجلدات البناء والتجميع:
- **build**: ملفات البناء والتجميع
- **dist**: ملفات التوزيع النهائية

### ملفات السجلات والأرشيف:
- **\*.log**: ملفات السجل
- **\*.zip, \*.rar**: ملفات الأرشيف
- **\*.mp4**: ملفات الفيديو
- **\*.docx**: ملفات المستندات

### ملفات وإعدادات بيئات التطوير:
- **.idea**: بيئة IntelliJ IDEA
- **android/app/**: مجلدات تطبيقات Android

### استثناء شامل:
- **-s:***: يستبعد جميع الملفات والمجلدات غير المحددة صراحةً

## المساهمة
نرحب بجميع المساهمات! يرجى عمل Fork للمستودع وإرسال Pull Request.



## ملاحظات إضافية
- تأكد من مراجعة وثائق Mega
- اختبر الإعدادات بعد التعديل
- اطرح الأسئلة عند الحاجة للمساعدة
