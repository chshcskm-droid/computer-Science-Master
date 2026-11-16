# Computer Science Master — Zero to Advanced

हिंदी-केंद्रित, practical learning path: बिल्कुल शुरुआत से लेकर professional-level programming तक।

## इस repository का उद्देश्य
यह repository उन learners के लिए है जिन्हें programming का कोई पूर्व अनुभव नहीं है। हम पहले computer की बुनियाद समझेंगे, फिर programming logic, उसके बाद Python, C, C++ और Java सीखेंगे। हर विषय में concept, छोटे उदाहरण, अभ्यास, debugging और projects शामिल होंगे।

> सीखने का नियम: code को केवल पढ़ें नहीं—खुद टाइप करें, चलाएँ, बदलें और गलती सुधारें।

## भाषा और सीखने की शैली
- मुख्य व्याख्या: सरल हिंदी; जरूरी technical शब्द English में भी दिए जाएँगे।
- हर lesson: उद्देश्य → concept → example → line-by-line explanation → exercises → mini project.
- पहले fundamentals, फिर advanced विषय। किसी चरण को जल्दबाज़ी में पार न करें।
- समय अनुमानित है; mastery अभ्यास से आएगी, calendar से नहीं।

## पूरा learning path

| चरण | विषय | मुख्य परिणाम |
|---|---|---|
| 0 | Computer fundamentals | कंप्यूटर, memory, files, OS और number systems की समझ |
| 1 | Logic & developer tools | algorithm, pseudocode, flowchart, terminal, IDE, Git |
| 2 | Python beginner | variables, input/output, conditions, loops, collections, functions |
| 3 | Python intermediate/advanced | OOP, files, modules, testing, APIs, databases, async |
| 4 | C programming | memory, pointers, arrays, structs, dynamic allocation |
| 5 | C++ programming | OOP, STL, templates, RAII, modern C++ |
| 6 | Java programming | JVM, OOP, collections, streams, concurrency, Spring basics |
| 7 | Core computer science | DSA, algorithms, OS, DBMS, SQL, networking |
| 8 | Professional engineering | clean code, testing, security, CI/CD, deployment |
| 9 | Specialization & capstone | Backend, AI/ML, systems, mobile, cloud या अन्य क्षेत्र |

## Repository map

- `ROADMAP.md` — विस्तृत विषय-सूची और क्रम
- `STUDY-PLAN.md` — दैनिक/साप्ताहिक अध्ययन प्रणाली
- `lessons/` — चरणवार lessons और exercises (आगे विस्तार होगा)
- `projects/` — छोटे से बड़े practical projects
- `resources/` — PDF और reference material

## चार भाषाओं का पहला उदाहरण

### Python
```python
print("Hello, World!")
```

### C
```c
#include <stdio.h>

int main(void) {
    printf("Hello, World!\\n");
    return 0;
}
```

### C++
```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!\\n";
    return 0;
}
```

### Java
```java
class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

## कुछ जरूरी बातें
- C/C++ सामान्यतः native machine code में compile होते हैं।
- Java source code bytecode में compile होता है, जिसे JVM चलाती है; JVM JIT compilation भी कर सकती है।
- सामान्य CPython implementation source को bytecode में compile करके Python virtual machine पर execute करती है।
- एक ही concept अलग भाषाओं में अलग syntax और memory model के साथ दिखेगा—यही तुलना सीखने का हिस्सा है।

## आधिकारिक learning references
- Python: https://docs.python.org/3/tutorial/
- C reference: https://en.cppreference.com/w/c
- C++ reference: https://en.cppreference.com/w/
- Java: https://dev.java/learn/
- Git book: https://git-scm.com/book/en/v2
- MDN Web Docs: https://developer.mozilla.org/
- PostgreSQL: https://www.postgresql.org/docs/

## Progress tracking
हर lesson पूरा होने पर उसके checklist को mark करें। केवल video/article देखना completion नहीं है—बिना मदद के छोटा program लिख पाना जरूरी है।

**शुरुआत:** [ROADMAP.md](ROADMAP.md) पढ़ें, फिर [STUDY-PLAN.md](STUDY-PLAN.md) के अनुसार Stage 0 शुरू करें।
