# <ctype.h> — Character Handling Library

## 🇸🇦 شرح بالعربي
مكتبة **ctype.h** تستخدم لفحص الأحرف والتعامل معها مثل:
- هل الحرف رقم؟
- هل الحرف حرف أبجدي؟
- تحويل الحرف إلى كبير/صغير

### ✅ أهم الدوال:
- `isdigit(c)` → يتحقق هل الحرف رقم
- `isalpha(c)` → يتحقق هل الحرف حرف
- `isalnum(c)` → يتحقق هل الحرف رقم أو حرف
- `toupper(c)` → يحول إلى حرف كبير
- `tolower(c)` → يحول إلى حرف صغير

---

## 🇬🇧 English Explanation
The **ctype.h** library provides functions for testing and mapping characters.

### Common Functions:
- `isdigit(c)` → checks if character is a digit
- `isalpha(c)` → checks if character is a letter
- `isalnum(c)` → checks if character is alphanumeric
- `toupper(c)` → converts to uppercase
- `tolower(c)` → converts to lowercase

---

## ✅ Example
```c
#include <stdio.h>
#include <ctype.h>

int main() {
    char c = 'a';

    if (isalpha(c)) {
        printf("%c is a letter\n", c);
    }

    printf("Uppercase: %c\n", toupper(c));
    printf("Is '5' digit? %d\n", isdigit('5'));
    
    return 0;
}
