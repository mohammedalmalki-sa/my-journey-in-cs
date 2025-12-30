# <stdlib.h> — Standard Library

## 🇸🇦 شرح بالعربي
مكتبة **stdlib.h** تعتبر من أهم مكتبات C، وتوفر وظائف عامة كثيرة مثل:
- إدارة الذاكرة (Memory Allocation)
- تحويل النصوص إلى أرقام
- توليد أرقام عشوائية
- التحكم في إنهاء البرنامج

---

## ✅ أهم الدوال (Functions)

### 🧠 1) Memory Allocation
- `malloc(size)` → حجز ذاكرة بحجم معين
- `calloc(n, size)` → حجز ذاكرة + تصفيرها
- `realloc(ptr, new_size)` → تغيير حجم الذاكرة
- `free(ptr)` → تحرير الذاكرة بعد الانتهاء

### 🔢 2) Conversions
- `atoi(str)` → تحويل String إلى Integer
- `atof(str)` → تحويل String إلى Float
- `strtol(str, ...)` → تحويل String إلى long (أدق من atoi)

### 🎲 3) Random Numbers
- `rand()` → يعطي رقم عشوائي
- `srand(seed)` → يغير نمط العشوائية (يفضل استخدامه)

### 🛑 4) Program Control
- `exit(code)` → إنهاء البرنامج فورًا

---

## 🇬🇧 English Explanation
The **stdlib.h** library provides general utility functions such as:
- Dynamic memory allocation
- String-to-number conversions
- Random number generation
- Program termination
