
# 🛡️ دليل تحصين Qubes OS – النسخة العربية

**دليل تفاعلي HTML شامل لتحصين نظام Qubes OS 4.3 مع Whonix 18 و Kicksecure**

[![الترخيص: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Qubes OS](https://img.shields.io/badge/Qubes%20OS-4.3-blue)](https://www.qubes-os.org/)
[![Whonix](https://img.shields.io/badge/Whonix-18-green)](https://www.whonix.org/)

---

## 📖 نبذة

هذا **دليل تفاعلي من ملف واحد (HTML)** يغطي كل شيء بدءاً من تحصين النواة الأساسي إلى آليات التدمير الذاتي المتقدمة. الدليل موجه **للمستخدمين المتقدمين** ذوي نموذج تهديد متوسط إلى عالٍ (صحفيون، باحثون، ناشطون، ومهتمون بالخصوصية الرقمية).

يتوفر الدليل بلغتين:
- **العربية** (`q.html`) – في فرع [`main`](https://github.com/abdullah127-code/qubes-os-security-/tree/main)
- **الإنجليزية** (`q_en.html`) – في فرع [`docs`](https://github.com/abdullah127-code/qubes-os-security-/tree/docs)

---

## ✨ الميزات

- 📋 **11 تبويباً تفاعلياً** – معلومات منظمة ومتعمقة
- ⚡ **سكريبت مساعد آلي** (`auto-script.sh`) – يطبق معظم الإعدادات بنقرة واحدة
- 🌓 **وضعان ليلي ونهاري** – مريح للقراءة
- 📊 **جداول مقارنة شاملة** – رؤية جميع الخيارات جنباً إلى جنب
- 📝 **نسخ بنقرة واحدة** – جميع الأوامر قابلة للنسخ
- 🎯 **مصفوفة التهديدات** – شرح 35 تهديداً مع حلولها
- 💾 **تطبيقات محمولة** – SimpleX، Cwtch، OnionShare، Gajim، Element، Signal، Session، Telegram (مع سكريبتات متوافقة مع Whonix)

---

## 📑 محتويات الدليل (التبويبات)

| التبويب | العنوان | المحتوى الرئيسي |
|---------|--------|------------------|
| 0 | **الأساسيات** | الهارد الخارجي، Secure Boot، معلمات النواة (dom0 و VMs)، جدول المعلمات الحرجة |
| 1 | **الشبكة** | راوتر WISP + Ethernet فقط، إخفاء MAC، تعطيل IPv6، مخططات البنية، خطط الطوارئ |
| 2 | **بوابات Whonix** | بوابات متعددة لعزل الهويات، حراس الدخول، الجسور (obfs4، Snowflake)، عزل دوائر Tor |
| 3 | **التخزين الآمن** | LUKS2 + Argon2id، VeraCrypt، تشفير مزدوج (VC+LUKS)، تحذيرات SSD، فصل التخزين عن التنفيذ |
| 4 | **مصفوفة التهديدات** | 35 تهديداً (هجمات التوقيت، Evil Maid، Cold Boot، بصمة المتصفح، تحليل الأسلوب، إلخ) مع حلول مفصلة |
| 5 | **Amnesic Tmpfs** | جعل المجلدات الحساسة (سجلات، كاش، /home) موجودة فقط في RAM |
| 6 | **RAM Pool** | تشغيل أجهزة افتراضية كاملة في RAM – إنكار تام، كل الآثار تختفي عند الإغلاق |
| 7 | **الأمان المتقدم** | BadUSB، VPN+Tor، نسخ احتياطية مشفرة، تحذير التشغيل المزدوج، BusKill، أدوات التدمير الذاتي، خطط الطوارئ، الحماية الفيزيائية |
| 8 | **Kicksecure** | توحيد بصمة المتصفح، تحصين النظام، security‑misc، إخفاء معلومات النواة والهاردوير |
| 9 | **Live Script** | وضع Live Mode (OverlayFS) + مقارنة شاملة لجميع أنواع الأجهزة الزائلة والآمنة (DVM، Ephemeral DVM، Amnesic Tmpfs، RAM Pool، Dom0 Live Boot، Live+RAM‑VM) |
| 10 | **تطبيقات محمولة** | SimpleX Chat (طريقة SOCKS proxy)، Cwtch، OnionShare، Gajim، Element، Signal (غير موصى به)، Session، Telegram، إزالة البيانات الوصفية، torsocks |
| 11 | **السكريبت المساعد** | `auto-script.sh` المركزي الذي يؤتمت معلمات النواة، إخفاء MAC، بوابات Whonix، Kicksecure، سكريبتات RAM Pool، Amnesic Tmpfs، Live Mode، أدوات التدمير، وتقوية تشفير LUKS |

---

## 📥 التحميل والاستخدام

**النسخة العربية (الموجودة في فرع main):**

- رابط الملف: [`q.html`](https://github.com/abdullah127-code/qubes-os-security-/blob/main/q.html)
- رابط التحميل المباشر (رابط خام): [https://raw.githubusercontent.com/abdullah127-code/qubes-os-security-/main/q.html](https://raw.githubusercontent.com/abdullah127-code/qubes-os-security-/main/q.html)

**النسخة الإنجليزية (الموجودة في فرع docs):**

- رابط الملف: [`q_en.html`](https://github.com/abdullah127-code/qubes-os-security-/blob/docs/q_en.html)
- رابط التحميل المباشر (رابط خام): [https://raw.githubusercontent.com/abdullah127-code/qubes-os-security-/docs/q_en.html](https://raw.githubusercontent.com/abdullah127-code/qubes-os-security-/docs/q_en.html)

**كيفية الاستخدام:**

1. حمل الملف المناسب إما بالضغط على رابط الملف ثم "Download" أو باستخدام رابط التحميل المباشر.
2. افتح الملف الذي تم تحميله في أي متصفح حديث (Firefox، Chrome، Brave).
3. استخدم التبويبات في الأعلى للتنقل.
4. اضغط على أي أمر لنسخه فوراً.
5. للأتمتة، انتقل إلى **تبويب 11** واستخدم **السكريبت المساعد**.

---

## 🌐 معاينة مباشرة

يمكنك معاينة الدليل مباشرة عبر HTML Preview من GitHub:

- 🔗 [**معاينة النسخة العربية**](https://htmlpreview.github.io/?https://github.com/abdullah127-code/qubes-os-security-/blob/main/q.html)
- 🔗 [**معاينة النسخة الإنجليزية**](https://htmlpreview.github.io/?https://github.com/abdullah127-code/qubes-os-security-/blob/docs/q_en.html)

---

## 🔧 السكريبت المساعد (`auto-script.sh`)

السكريبت الموجود في **تبويب 11** يؤتمت المهام التالية:

- ✅ معلمات النواة لـ dom0 (GRUB + Secureblue sysctl)
- ✅ معلمات النواة لجميع VMs (kernelopts)
- ✅ إخفاء MAC وتعطيل IPv6
- ✅ إنشاء بوابات Whonix متعددة
- ✅ تثبيت Kicksecure وتحصين مساحة المستخدم
- ✅ سكريبتات RAM Pool (إنشاء، فردي، متعدد، تنظيف، حالة)
- ✅ Amnesic Tmpfs (تطبيق / إلغاء)
- ✅ Live Mode (OverlayFS) مع DVMs زائلة
- ✅ أدوات التدمير (BusKill، Dead Man’s Switch، تدمير فوري)
- ✅ تقوية تشفير قرص النظام LUKS (PBKDF2 → Argon2id مع ذاكرة ووقت مخصصين)

**كيفية تشغيل السكريبت بعد التحميل:**

```bash
chmod +x auto-script.sh
./auto-script.sh
```

---

⚠️ تحذيرات هامة

هذا الدليل مخصص للمستخدمين المتقدمين فقط.

بعض الإجراءات – خاصة أدوات التدمير في تبويب 7 – قد تؤدي إلى فقدان دائم وغير قابل للاسترداد للبيانات.
احرص دائماً على أخذ نسخ احتياطية كاملة قبل تطبيق أي من الإعدادات الموصى بها.

---

🤝 المساهمة

المساهمات مرحب بها! إذا وجدت خطأ أو كان لديك اقتراح:

· افتح Issue يصف المشكلة.
· أرسل Pull Request بالتعديلات المقترحة.
· تواصل معي مباشرة عبر GitHub.

---

📜 الترخيص

هذا المشروع مرخص بموجب رخصة MIT – يمكنك استخدامه وتعديله ومشاركته بحرية، مع الإشارة إلى المصدر.

انظر ملف LICENSE للتفاصيل الكاملة.

---

📚 المصادر والقراءة الإضافية

· توثيق Qubes OS
· توثيق Whonix
· توثيق Kicksecure
· دليل المسافر لإخفاء الهوية على الإنترنت

---

⭐ ادعم المشروع

إذا وجدت هذا الدليل مفيداً:

· ⭐ انجمة المستودع
· 🔗 شاركه مع الآخرين
· 📢 انشره في مجتمعات الخصوصية والأمن الرقمي

---

<div align="center">

"لا تثق بأحد. ليس مزود الخدمة، ولا مزود VPN، ولا شبكة Tor، ولا نظام التشغيل، ولا حتى جهاز الكمبيوتر الخاص بك. ثق ولكن تحقق."

</div>
```
