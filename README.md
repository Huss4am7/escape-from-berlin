# 🇩🇪 Deutsch A1 — Interaktives Lernsystem

Ein vollständiges, gamifiziertes Lernsystem für Deutsch A1 (Grundstufe), entwickelt für arabischsprachige Lerner. Das System umfasst fünf verschiedene Ansichten: interaktives Spiel, Schüler-Arbeitsblatt, Lehrer-Tools, Handout/Zusammenfassung und Wissenskarten.

## 📁 Dateistruktur

| Datei | Zweck | Zielgruppe |
|-------|-------|------------|
| `index.html` | **"الهروب من برلين"** — Gamifizierte Quiz-App mit 3 Levels, Millionär-Modus, Team-Modus | Schüler (interaktiv) |
| `student.html` | **Arbeitsblatt** mit Eingabefeldern, Selbstkontrolle, persistentem Speicher | Schüler (Übung) |
| `teacher.html` | **Lehrer-Tools** mit Annotationen, Highlighting, Notizen-Modus | Lehrer (Präsentation) |
| `handout.html` | **Druckfertige Zusammenfassung** aller Lerninhalte | Beide (Referenz) |
| `cards.html` | **Wissenskarten A1.2** — 40 fortgeschrittene Konzeptkarten mit Flip-Mechanismus | Fortgeschrittene (A1.2) |

---

## 🎮 Features

### Level 1: Quiz & Millionär-Modus (`index.html`)
- **Team-Modus**: 2–4 Teams mit Livesystem ❤️
- **30+ Fragen** zu Alphabet, Phonetik, Zahlen, Grammatik, Familie
- **"Wer wird Millionär"**: 12 Fragen, 3 Joker (50:50, Telefon, Publikum)
- **Timer**: 30 Sekunden pro Frage mit visuellem Countdown

### Level 2: Minigames
- **Bananagrams**: Buchstabenspiel mit deutschen Wörtern
- **Memory**: Kartenpaare (Deutsch ↔ Arabisch)
- **Mad Libs**: Lückentexte mit personalisierbaren Eingaben
- **Der/Die/Das**: Artikel-Quiz mit Streak-System

### Level 3: Fortgeschrittene Übungen
- **Satzpuzzle**: Wortstellung üben
- **Lückentext**: Grammatik-Kontext
- **Bildwörterbuch**: Emoji-basiertes Vokabular
- **Rollenspiel**: Dialogsimulationen (Arzt, Supermarkt, Bahnhof)

---

## 🛠️ Technische Details

### Tech-Stack
- **Pure HTML5/CSS3/JavaScript** — keine externen Dependencies
- **LocalStorage** für persistente Speicherung (Schüler/Teacher)
- **Responsive Design** — Mobile-first, RTL-Arabic-Support
- **CSS Grid & Flexbox** für Layouts

### Browser-Kompatibilität
- Chrome/Edge/Firefox/Safari (aktuell)
- iOS Safari optimiert (kein Zoom bei Input-Feldern)
- Touch & Keyboard Support (Pfeiltasten, Space zum Flippen)

---

## 🚀 Schnellstart

### Lokale Nutzung
```bash
# Einfach einen der Dateien im Browser öffnen
open index.html        # Spiel starten
open student.html      # Arbeitsblatt öffnen
open teacher.html      # Lehreransicht

&lt;div dir="rtl"&gt;

# 🇩🇪 Deutsch A1 — نظام تعلّم تفاعلي

نظام تعليمي كامل ومُ gamified لتعلم الألمانية A1 (المستوى الأول) موجّه للناطقين بالعربية. يضم النظام خمس واجهات مختلفة: لعبة تفاعلية، ورقة عمل للطالب، أدوات المعلم، ملخص/مرجع للطباعة، وبطاقات معرفية متقدمة.

## 📁 هيكل الملفات

| الملف | الغرض | الجمهور المستهدف |
|-------|-------|------------------|
| `index.html` | **"الهروب من برلين"** — لعبة مسابقات بثلاثة مستويات + تحدي المليون + وضع الفرق | الطلاب (تفاعلي) |
| `student.html` | **ورقة عمل** مع حقول إدخال، تصحيح ذاتي، وحفظ تلقائي | الطلاب (تمرين) |
| `teacher.html` | **أدوات المعلم** مع تعليقات، تظليل، وضع ملاحظات | المعلمون (عرض تقديمي) |
| `handout.html` | **ملخص جاهز للطباعة** لجميع المحتويات | الطرفان (مرجع) |
| `cards.html` | **كروت المعرفة A1.2** — ٤٠ كرت مفاهيم متقدمة بآلية التقليب | المتقدمون (A1.2) |

---

## 🎮 الميزات

### المستوى الأول: المسابقة وتحدي المليون (`index.html`)
- **وضع الفرق**: ٢–٤ فرق مع نظام أرواح ❤️
- **أكثر من ٣٠ سؤالاً** في الأبجدية، الصوتيات، الأرقام، القواعد، العائلة
- **"من سيربح المليون؟"**: ١٢ سؤالاً، ٣ مساعدات (٥٠:٥٠، اتصال، جمهور)
- **مؤقت**: ٣٠ ثانية لكل سؤال مع عداد بصري تنازلي

### المستوى الثاني: ألعاب مصغّرة
- **Bananagrams**: لعبة حروف لتشكيل كلمات ألمانية
- **الذاكرة**: مطابقة البطاقات (ألماني ⟷ عربي)
- **Mad Libs**: نصوص ذات فراغات قابلة للتخصيص
- **Der/Die/Das**: اختبار أدوات التعريف مع نظام الانتصارات المتتالية (Streak)

### المستوى الثالث: تمارين متقدمة
- **Satzpuzzle**: ترتيب الجمل
- **Lückentext**: فراغات نحوية سياقية
- **Bildwörterbuch**: مفردات بصرية بالرموز التعبيرية
- **Rollenspiel**: محاكاة حوارات (الطبيب، السوبرماركت، المحطة)

---

## 🛠️ التفاصيل التقنية

### التقنيات المستخدمة
- **HTML5/CSS3/JavaScript خام** — بدون مكتبات خارجية
- **LocalStorage** للحفظ الدائم (الطالب/المعلم)
- **تصميم متجاوب** — Mobile-first، دعم الكتابة من اليمين لليسار (RTL)
- **CSS Grid & Flexbox** للتخطيطات

### التوافق مع المتصفحات
- Chrome/Edge/Firefox/Safari (الإصدارات الحديثة)
- مُحسّن لـ iOS Safari (منع التكبير التلقائي لحقول الإدخال)
- دعم اللمس ولوحة المفاتيح (أسهم التنقل، مسافة للقلب)

---

## 🚀 البدء السريع

### الاستخدام المحلي
```bash
# افتح أي ملف في المتصفح مباشرة
open index.html        # بدء اللعبة
open student.html      # فتح ورقة العمل
open teacher.html      # عرض المعلم
