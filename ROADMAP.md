# Master Roadmap — Zero to Advanced

यह क्रम जानबूझकर fundamentals-first रखा गया है। हर topic के बाद छोटे अभ्यास और एक practical task करें।

## Stage 0 — Computer Fundamentals
1. Computer क्या है: input, processing, output, storage
2. Hardware और software; CPU, ALU, registers, RAM, cache, SSD/HDD
3. Operating system की भूमिका; files, folders, paths, processes
4. Data representation: bit, byte, binary, decimal, hexadecimal
5. Binary arithmetic और character encoding (ASCII, Unicode, UTF-8)
6. Source code, executable, process, memory और program lifecycle
7. Compiler, interpreter, runtime, virtual machine और JIT का अंतर

**अभ्यास:** decimal ↔ binary conversion; file/folder बनाना; hardware/software की पहचान।

## Stage 1 — Programming Logic & Tools
1. Problem solving और decomposition
2. Algorithm, pseudocode और flowchart
3. Variables, state, sequence, selection, iteration की अवधारणा
4. Terminal/command line की बुनियादी commands
5. Code editor/IDE, run और debug करना
6. Git: repository, commit, branch, push, pull
7. Debugging mindset और error messages पढ़ना

**Project:** किसी रोज़मर्रा के काम का algorithm लिखें, जैसे दो संख्याओं में बड़ी संख्या ढूँढना।

## Stage 2 — Python Beginner
1. Python install, interpreter, script और REPL
2. print(), input(), comments, indentation
3. Variables, naming, basic data types
4. Arithmetic, comparison, logical और assignment operators
5. if / elif / else
6. for और while loops; break/continue
7. Strings और string methods
8. Lists, tuples, sets, dictionaries
9. Functions, parameters, return, scope
10. Modules और imports
11. Exceptions और basic debugging

**Projects:** calculator, number guessing game, unit converter, quiz app, expense tracker (CLI).

## Stage 3 — Python Intermediate & Advanced
1. Files, pathlib, CSV और JSON
2. Object-oriented programming: class, object, inheritance, composition
3. Iterators, generators और decorators
4. Context managers और exception design
5. Type hints, dataclasses और code organization
6. pip, virtual environments और dependency management
7. Unit testing, pytest, logging और debugging
8. HTTP, REST APIs और JSON data
9. SQL और SQLite/PostgreSQL integration
10. Web development: FastAPI या Django का परिचय
11. Concurrency, threading, multiprocessing और asyncio
12. Profiling, performance और secure coding basics
13. Data tools: NumPy, Pandas; ML fundamentals का परिचय

**Projects:** REST API, personal finance tracker with database, automated file organizer, data analysis report.

## Stage 4 — C Programming
1. Compiler/toolchain, source files और headers
2. main(), printf(), scanf(), format specifiers
3. Types, constants, operators और conversions
4. Conditions, loops और functions
5. Arrays, strings और multidimensional arrays
6. Pointers, pointer arithmetic और arrays का संबंध
7. Struct, enum, union और typedef
8. Stack बनाम heap; malloc/calloc/realloc/free
9. File I/O और command-line arguments
10. Preprocessor, macros और header guards
11. Function pointers और callbacks
12. Bitwise operations
13. Undefined behavior, compiler warnings और sanitizers

**Projects:** menu-driven student record system, file-based contacts book, simple memory allocator exercise.

## Stage 5 — C++
1. C++ program structure, compilation और namespaces
2. References, pointers, const और value categories
3. Classes, constructors/destructors और encapsulation
4. Inheritance, polymorphism और composition
5. Operator overloading और friend functions
6. STL containers: vector, string, map, set, unordered_map
7. Iterators, algorithms और lambdas
8. Templates और generic programming
9. Exceptions और RAII
10. Smart pointers और resource ownership
11. Move semantics और modern C++ (11/14/17/20/23 overview)
12. Concurrency basics, CMake, testing और profiling

**Projects:** library management, command-line task manager, generic data-structure library.

## Stage 6 — Java
1. JDK, JRE, JVM और bytecode
2. Variables, primitive/reference types और operators
3. Conditions, loops, methods, arrays और strings
4. Classes, objects, constructors और access modifiers
5. Inheritance, interfaces, abstraction और composition
6. Exceptions और custom exceptions
7. Generics और Collections Framework
8. Files, serialization concepts और NIO basics
9. Lambdas, functional interfaces और Stream API
10. JVM memory, garbage collection overview
11. Threads, executors और concurrency basics
12. JDBC और SQL
13. REST services और Spring Boot introduction
14. Build tools, testing, security और deployment basics

**Projects:** student management app, inventory system with database, REST API.

## Stage 7 — Core Computer Science
### Data Structures & Algorithms
- Big-O time/space complexity
- Arrays, linked lists, stacks, queues, hash tables
- Trees, binary search trees, heaps, tries, graphs
- Searching, sorting, recursion
- Two pointers, sliding window, greedy, backtracking
- Dynamic programming और graph traversal (BFS/DFS)

### Operating Systems
- Processes और threads; scheduling
- Synchronization, mutex, semaphore और deadlocks
- Memory management, virtual memory और paging
- File systems और system calls

### Databases
- Relational model, tables, keys और constraints
- SQL: SELECT, INSERT, UPDATE, DELETE, JOIN, GROUP BY
- Indexes, transactions, ACID और normalization
- Query plans और database design

### Networking
- IP, ports, DNS और routing
- TCP बनाम UDP
- HTTP/HTTPS, TLS और REST
- Client-server model और basic troubleshooting

## Stage 8 — Professional Software Engineering
1. Requirements और user stories
2. Modular design, clean code और maintainability
3. Git branching, pull requests और code review
4. Unit, integration और end-to-end testing
5. Authentication, authorization, input validation और secrets
6. Linux shell, permissions और processes
7. Build pipelines, CI/CD और containers
8. Deployment, logs, monitoring, backups और documentation

## Stage 9 — Choose a Specialization
- Backend engineering: APIs, databases, caching, queues, system design
- AI/Data: statistics, Python, data pipelines, ML evaluation
- Systems/Embedded: C/C++, memory, OS, microcontrollers
- Mobile: Android/Java/Kotlin concepts
- Cloud/DevOps: Linux, containers, CI/CD, cloud fundamentals
- Game development: C++, math, engine architecture

## Character quick reference
| चिन्ह | सामान्य उपयोग |
|---|---|
| `;` | C/C++/Java में statement समाप्त करना |
| `{}` | code block; Python में dictionary/set भी |
| `()` | function call/parameters; grouping |
| `[]` | indexing; arrays/lists |
| `#` | Python comment; C/C++ preprocessor |
| `//` | C/C++/Java single-line comment; Python में integer division |
| `=` | assignment |
| `==` | equality comparison |
| `!=` | not equal |
| `&&`, `||`, `!` | C/C++/Java logical AND/OR/NOT |
| `and`, `or`, `not` | Python logical operators |
| `&`, `*`, `->` | C/C++ में context के अनुसार address, pointer, dereference/member access |
| `::` | C++ scope resolution; Java method reference में `::` |
| `@` | Java annotations; Python decorators |
| `\\n`, `\\t` | newline और tab escape sequences |

## Completion standard
किसी stage को पूरा मानने से पहले:
- concept अपने शब्दों में समझा सकें;
- बिना copy-paste छोटा program लिख सकें;
- सामान्य errors debug कर सकें;
- कम से कम एक mini-project पूरा कर सकें;
- अपने code को Git में commit कर सकें।
