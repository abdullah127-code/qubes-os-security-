# qubes-os-security-
اعدادات متقدمة ل qubes os 

# 🛡️ المخطط الأمني المتكامل – Qubes OS + Kicksecure

<div align="center">

**الدليل العربي الشامل لتحصين نظام Qubes OS للمستخدمين المتقدمين والمهتمين بالخصوصية القصوى**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Qubes OS](https://img.shields.io/badge/Qubes%20OS-4.3-blue)](https://www.qubes-os.org/)
[![Whonix](https://img.shields.io/badge/Whonix-18-green)](https://www.whonix.org/)

</div>

---

## 📖 عن الدليل

هذا الملف هو دليل تفاعلي كامل (Single HTML File) يغطي كافة جوانب تحصين وتأمين نظام **Qubes OS 4.3** مع **Whonix 18** و **Kicksecure**. الدليل موجه للمستخدمين ذوي نموذج التهديد المتوسط إلى العالي (صحفيين، باحثين، ناشطين، ومهتمين بالخصوصية الرقمية).

---

## ✨ المميزات

- 📋 **11 تبويباً تفاعلياً** تغطي كل شيء من الإعداد الأساسي إلى التدمير الذاتي
- ⚡ **سكريبت مساعد آلي** يقوم بتطبيق معظم الإعدادات بنقرة واحدة
- 🌓 **وضعان ليلي ونهاري** للقراءة المريحة
- 📊 **جداول مقارنة شاملة** لجميع الخيارات الأمنية
- 📝 **أوامر قابلة للنسخ** بالضغط عليها مباشرة
- 🎯 **مصفوفة تهديدات** تضم 35 تهديداً مع حلولها

---

## 📑 محتويات الدليل

| التبويب | المحتوى |
|---|---|
| **0. الأساسيات** | معلمات النواة (dom0 vs VMs)، تقسيم الهارد، Secure Boot |
| **1. الشبكة** | WISP، Ethernet فقط، MAC Randomization، IPv6 |
| **2. بوابات Whonix** | بوابات متعددة، Stream Isolation، Bridges، sdwdate |
| **3. التخزين الآمن** | LUKS، VeraCrypt، فصل التخزين عن التنفيذ |
| **4. مصفوفة التهديدات** | 35 تهديداً مع الحلول (من Evil Maid إلى Stylometry) |
| **5. Amnesic Tmpfs** | جعل المجلدات زائلة في الذاكرة |
| **6. RAM Pool** | تشغيل أجهزة افتراضية كاملة في الذاكرة |
| **7. الأمان المتقدم** | BusKill، أدوات التدمير، خطط الطوارئ، AEM، Secure Boot |
| **8. Kicksecure** | توحيد بصمة المتصفح وتحصين النظام |
| **9. Live Script** | Live Mode مع مقارنة شاملة لجميع أنواع الأجهزة الزائلة |
| **10. تطبيقات محمولة** | SimpleX، Signal، OnionShare، إزالة البيانات الوصفية |
| **11. السكريبت المساعد** | سكريبت مركزي لأتمتة كل ما سبق |

---

## 📥 التحميل والاستخدام

1. قم بتحميل ملف `q.html` من [هذا الرابط](https://github.com/abdullah127-code/qubes-os-security-/blob/main/q.html)
2. افتحه في أي متصفح حديث (Firefox، Chrome، Brave)
3. تنقل بين التبويبات من الأعلى
4. اضغط على أي أمر لنسخه تلقائياً
5. استخدم السكريبت المساعد في التبويب 11 للأتمتة

---

## 🌐 معاينة مباشرة

يمكنك معاينة الدليل مباشرة من خلال HTML Preview:

🔗 [**اضغط هنا للمعاينة المباشرة**](https://htmlpreview.github.io/?https://github.com/abdullah127-code/qubes-os-security-/blob/main/q.html)

---

## 🔧 السكريبت المساعد

السكريبت المدمج في التبويب 11 يقوم بأتمتة:

- ✅ إعداد معلمات النواة (dom0 و VMs)
- ✅ إعداد MAC Randomization وتعطيل IPv6
- ✅ إنشاء بوابات Whonix المتعددة
- ✅ تثبيت وإعداد Kicksecure
- ✅ إنشاء سكريبتات RAM Pool
- ✅ إنشاء سكريبت Amnesic Tmpfs
- ✅ تشغيل Live Mode
- ✅ أدوات التدمير (BusKill + الطوارئ + Dead Man's Switch)

---

## ⚠️ تحذير هام

> **هذا الدليل مخصص للمستخدمين المتقدمين فقط.**

بعض الإجراءات المذكورة (خاصة أدوات التدمير في التبويب 7) قد تؤدي إلى **فقدان دائم وغير قابل للاسترداد للبيانات**. استخدم بحذر شديد وخذ نسخاً احتياطية دائماً قبل تطبيق أي شيء.

---

## 🤝 المساهمة

هذا المشروع مفتوح للمراجعة والتحسين. إذا وجدت أي خطأ أو كان لديك اقتراح:

1. افتح **Issue** لوصف المشكلة أو الاقتراح
2. قدم **Pull Request** بالتعديلات المقترحة
3. راسلني مباشرة على GitHub

---

## 📜 الترخيص

هذا العمل مرخص تحت **رخصة MIT** – يمكنك استخدامه وتعديله ومشاركته بحرية مع الإشارة إلى المصدر.

انظر ملف [LICENSE](LICENSE) للتفاصيل الكاملة.

---

## 📚 المصادر

- [Qubes OS Documentation](https://www.qubes-os.org/doc/)
- [Whonix Documentation](https://www.whonix.org/wiki/Documentation)
- [Kicksecure Documentation](https://www.kicksecure.com/wiki/Documentation)
- [Hitchhiker's Guide to Online Anonymity](https://anonymousplanet.org/)

---

## ⭐ ادعم المشروع

إذا وجدت هذا الدليل مفيداً، فضلاً:
- ⭐ أعطِ المشروع نجمة (Star)
- 🔗 شاركه مع المهتمين
- 📢 انشره في مجتمعات الخصوصية والأمن الرقمي

---

<div align="center">

**"لا تثق بأحد. ثق ولكن تحقق."**

</div>
