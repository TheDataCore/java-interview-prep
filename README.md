# 🚀 Java Backend Developer — Complete Interview Prep Kit

> **A comprehensive 72-hour interview preparation guide** for Java Backend Developer roles covering Spring Boot, MongoDB, Microservices, JUnit, Oracle SQL, and RESTful APIs — with deep Q&A, annotated code snippets, system design walkthroughs, DSA patterns, and curated learning resources.

<br>

[![Topics](https://img.shields.io/badge/Topics-8_Core_Areas-e94560?style=flat-square)](#-what-this-covers)
[![Questions](https://img.shields.io/badge/Q%26A-50%2B_Questions-0f3460?style=flat-square)](#-topics-covered)
[![Code Snippets](https://img.shields.io/badge/Code_Snippets-30%2B-27ae60?style=flat-square)](#-topics-covered)
[![Format](https://img.shields.io/badge/Format-Interactive_HTML-f5a623?style=flat-square)](#-how-to-use)
[![License](https://img.shields.io/badge/License-MIT-8e44ad?style=flat-square)](LICENSE)

---

## 📋 Table of Contents

- [What This Covers](#-what-this-covers)
- [Tech Stack](#-tech-stack)
- [How to Use](#-how-to-use)
- [72-Hour Study Roadmap](#%EF%B8%8F-72-hour-study-roadmap)
- [Topics Covered](#-topics-covered)
  - [Java Core](#-java-core)
  - [Spring Boot](#-spring-boot)
  - [Microservices](#-microservices)
  - [MongoDB](#-mongodb)
  - [Oracle / SQL](#-oracle--sql)
  - [JUnit & Testing](#-junit--testing)
  - [REST APIs](#-restful-apis--web-services)
  - [System Design](#-system-design)
  - [DSA in Java](#-dsa--java-coding)
- [Curated Resources](#-curated-resources)
- [Progress Tracker](#-progress-tracker)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 What This Covers

This guide is built for developers preparing for **Java Backend Developer** interviews with a focus on the modern enterprise stack. It goes beyond surface-level flashcards — every topic includes:

- ✅ **Theory** — The WHY behind every concept, not just the WHAT
- ✅ **Deep Q&A** — 50+ questions categorized by difficulty (Easy / Medium / Hard), with full answers
- ✅ **Annotated Code** — Production-quality Java snippets you can explain line-by-line
- ✅ **Cross-topic Linking** — Interviewers chain topics; this guide mirrors that ("How does @Transactional work with MongoDB?" → "How do you test that with @DataMongoTest?")
- ✅ **System Design Walkthroughs** — 3 complete designs with trade-off discussions
- ✅ **DSA Patterns** — 6 core patterns with full Java implementations
- ✅ **YouTube + Platform Resources** — Curated for each topic, not generic

---

## 🛠 Tech Stack

| Area | Technologies |
|------|-------------|
| Language | Java 11 / 17+ |
| Framework | Spring Boot, Spring Security, Spring Data |
| Databases | MongoDB, Oracle SQL |
| Architecture | Microservices, REST, Event-Driven |
| Testing | JUnit 5, Mockito, Testcontainers |
| Messaging | Apache Kafka, RabbitMQ |
| Resilience | Resilience4j (Circuit Breaker, Retry) |
| Auth | JWT, OAuth2 |
| Service Discovery | Spring Cloud Eureka |
| Tracing | Spring Sleuth + Zipkin |
| Caching | Redis, Spring Cache |
| Build | Maven / Gradle |

---

## 🚀 How to Use

### Option 1 — Open Directly in Browser (Recommended)

```bash
git clone https://github.com/your-username/java-interview-prep.git
cd java-interview-prep
open java-backend-interview-prep-v2.html   # macOS
# OR
start java-backend-interview-prep-v2.html  # Windows
# OR
xdg-open java-backend-interview-prep-v2.html  # Linux
```

### Option 2 — GitHub Pages

If this repo has GitHub Pages enabled, visit:
```
https://your-username.github.io/java-interview-prep/
```

### Navigating the Guide

The HTML guide has a **sticky navigation bar** with 12 tabs:

| Tab | Content |
|-----|---------|
| 🗺 Roadmap | Hour-by-hour 72-hr battle plan |
| ☕ Java | Core Java: OOP, Collections, Java 8+, Concurrency, JVM |
| 🌱 Spring Boot | DI, annotations, security, AOP, caching, transactions |
| 🏗️ Microservices | Patterns, Kafka, Circuit Breaker, Saga, Outbox |
| 🍃 MongoDB | Aggregation, indexing, transactions, Spring Data |
| 🗄️ Oracle/SQL | Window functions, PL/SQL, query optimization |
| 🧪 JUnit | JUnit 5, Mockito, test slices, Testcontainers |
| 🌐 REST APIs | HTTP, REST design, rate limiting, OAuth2 |
| 📐 System Design | Framework + 3 complete designs + core concepts |
| 🧩 DSA | 6 patterns + 15 must-solve problems in Java |
| 📚 Resources | All YouTube + docs + practice platforms |
| ✅ Tracker | Interactive 48-item progress checklist |

> **Tip:** Each Q&A card is expandable — click the question to reveal the full answer with code.

---

## 🗓️ 72-Hour Study Roadmap

| Block | Hours | Focus |
|-------|-------|-------|
| 1 | 0 – 8 | Java Core + Spring Boot fundamentals |
| 2 | 8 – 16 | Microservices + REST API design |
| 3 | 16 – 24 | MongoDB deep dive → Sleep |
| 4 | 24 – 36 | Oracle SQL + JUnit + Testing |
| 5 | 36 – 52 | System Design + DSA practice → Sleep |
| 6 | 52 – 64 | Mock interview + Weak area drill |
| 7 | 64 – 72 | Final review → Rest → Interview |

**Golden Rule:** For every topic — understand the **WHY**, write the **code**, explain it **out loud**. Interviewers follow threads; one answer leads to 3 more questions.

---

## 📚 Topics Covered

### ☕ Java Core

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

- **OOP** — 4 pillars with real project examples; abstract class vs interface decision guide
- **Collections Framework** — HashMap internals (hashing, collision, treeification to Red-Black Tree at 8+ entries); ArrayList vs LinkedList complexity; ConcurrentHashMap Java 8 (CAS + per-bucket sync)
- **Java 8+ Features** — Streams (lazy evaluation, short-circuit, parallel stream pitfalls); Optional correct patterns and anti-patterns; all 4 method reference types; CompletableFuture async chaining
- **Concurrency** — volatile vs synchronized vs ReentrantLock; Thread lifecycle; ExecutorService and thread pool sizing formulas; deadlock conditions, detection, and prevention
- **JVM** — Heap/Stack/Metaspace/Code Cache; GC types (Serial, Parallel, G1, ZGC); OOM error types

**Sample Q&A topics:**
- How does HashMap handle collision in Java 8? What is treeification?
- Explain lazy evaluation in Streams with an example.
- What are the 4 conditions for deadlock? How do you prevent them?
- ConcurrentHashMap internals — how is thread safety achieved in Java 8 vs Java 7?

</details>

---

### 🌱 Spring Boot

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

- **IoC / DI** — BeanFactory vs ApplicationContext; all bean scopes; prototype injection into singleton via ObjectFactory
- **Annotations Cheat Sheet** — 12+ critical annotations explained: @SpringBootApplication, @Transactional (propagation types table), @ControllerAdvice, @Cacheable, @Async, @ConditionalOnProperty, and more
- **Auto-configuration** — How Spring reads META-INF imports; @ConditionalOnClass / @ConditionalOnMissingBean; debug with `--debug` or `/actuator/conditions`
- **AOP** — Aspect, Advice, JoinPoint, Pointcut with execution time + role-check examples; how @Transactional itself uses AOP
- **Security** — Complete JWT filter chain; OAuth2 flows; CORS config; CSRF (why it's safe to disable for JWT APIs)
- **Caching** — @Cacheable / @CacheEvict / @CachePut; Redis setup; cache-aside pattern; dynamic refresh with @RefreshScope

**Sample Q&A topics:**
- What are the 7 @Transactional propagation types?
- What is the self-invocation problem with @Transactional?
- How do you implement AOP for logging execution time across all service methods?
- Constructor injection vs field injection — why is constructor preferred?

</details>

---

### 🏗️ Microservices

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

- **Decomposition** — By business capability vs DDD subdomain; Strangler Fig pattern for migrating monoliths
- **API Gateway** — Responsibilities; Backend-for-Frontend (BFF) pattern; Spring Cloud Gateway config with rate limiting, circuit breaking, routing
- **Resilience** — Resilience4j Circuit Breaker (CLOSED/OPEN/HALF-OPEN states); @CircuitBreaker + @Retry with fallback method
- **Communication** — Sync (Feign client) vs Async (Kafka); when to use each
- **Kafka Deep Dive** — Topics, partitions, consumer groups, offsets, at-least-once delivery; producer with callbacks; consumer with DLQ
- **Distributed Patterns** — Saga (choreography vs orchestration); Outbox Pattern (solving dual-write problem); distributed tracing with Sleuth + Zipkin
- **Configuration** — Spring Cloud Config Server; Kubernetes ConfigMaps; @RefreshScope for dynamic reload

**Sample Q&A topics:**
- How does the Outbox Pattern solve the dual-write consistency problem?
- Choreography vs Orchestration Saga — which to use and when?
- What happens when a Kafka consumer fails mid-processing?
- How do you implement service-to-service authentication in microservices?

</details>

---

### 🍃 MongoDB

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

- **Data Modeling** — Embedding vs referencing decision guide; hybrid pattern (snapshot of critical data); 16MB BSON limit implications
- **Aggregation Pipeline** — 5-stage real-world pipeline ($match, $unwind, $lookup, $group, $sort, $project); monthly sales report example
- **Indexing** — All index types (single, compound, multikey, text, TTL, sparse, partial, hashed); ESR rule for compound index ordering; reading explain() output (IXSCAN vs COLLSCAN)
- **Transactions** — Single-document atomicity; multi-document ACID with MongoTransactionManager; @Transactional integration in Spring Boot
- **Sharding vs Replication** — When to use each; shard key selection criteria; hotspot avoidance
- **Change Streams** — Real-time change notifications; Flux-based subscription in Spring Data

**Sample Q&A topics:**
- When would you embed vs reference in MongoDB? What is the hybrid pattern?
- Write an aggregation pipeline for monthly revenue by product category.
- What is the ESR rule for compound indexes?
- How does @Transactional work with MongoDB in Spring Boot?

</details>

---

### 🗄️ Oracle / SQL

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

- **SQL Joins** — All types (INNER, LEFT, RIGHT, FULL OUTER, SELF, CROSS) with examples and use cases
- **Window Functions** — ROW_NUMBER vs RANK vs DENSE_RANK (key differences); LAG/LEAD for period comparisons; NTILE for quartiles; FIRST_VALUE/LAST_VALUE; running totals and moving averages
- **Query Optimization** — EXPLAIN PLAN interpretation; bind variables; function-based indexes; DBMS_STATS.GATHER_TABLE_STATS; optimizer hints; table partitioning with partition pruning
- **PL/SQL** — Procedures, functions, cursors (FOR loop); packages (spec + body); triggers for audit logging; exception propagation and RAISE_APPLICATION_ERROR
- **Advanced SQL** — CTE (WITH clause) vs subquery vs JOIN trade-offs; recursive CTE for hierarchy traversal; correlated subqueries
- **Transactions** — ACID guarantees; all isolation levels; deadlock detection in Oracle

**Sample Q&A topics:**
- What is the difference between RANK() and DENSE_RANK()?
- How does a correlated subquery differ from a regular subquery, and why is it slow?
- What does EXPLAIN PLAN output tell you and how do you fix a COLLSCAN?
- Write a PL/SQL package with a procedure using an explicit cursor.

</details>

---

### 🧪 JUnit & Testing

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

- **JUnit 5 vs JUnit 4** — Complete annotation migration table; new features (@ParameterizedTest, @Nested, @TempDir, @Timeout, conditional annotations)
- **Mockito** — @Mock, @Spy, @Captor, @InjectMocks; argument matchers (any(), eq(), argThat()); ArgumentCaptor usage; verify() with times/never/atLeast; thenAnswer() for dynamic returns
- **Spring Test Slices** — @WebMvcTest with MockMvc (status, JSON path, header assertions); @DataMongoTest with embedded MongoDB; @SpringBootTest for full integration tests
- **Testcontainers** — Real MongoDB + Kafka in Docker; @DynamicPropertySource for dynamic config injection
- **TDD** — Red-Green-Refactor cycle with example; why TDD leads to better API design

**Sample Q&A topics:**
- What is the difference between @Mock and @Spy?
- How do you test a Spring Boot controller without loading the full context?
- How do you verify that a mock method was called with a specific argument using ArgumentCaptor?
- What is the difference between @MockBean and @Mock?

</details>

---

### 🌐 RESTful APIs & Web Services

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

- **REST Principles** — 6 constraints; statelessness; uniform interface; HATEOAS with links in response body
- **HTTP Semantics** — All methods (GET/POST/PUT/PATCH/DELETE/HEAD/OPTIONS); safety vs idempotency table; correct status codes (201 + Location, 204, 422, 429)
- **API Design** — Resource hierarchy for Order Management System; filtering/sorting/pagination via query params; versioning strategies compared (URI, header, Accept, query param)
- **Rate Limiting** — Token bucket vs leaky bucket vs sliding window; Spring Cloud Gateway Redis rate limiter; response headers (X-RateLimit-*)
- **Security** — OAuth2 flows (Authorization Code + PKCE, Client Credentials); CORS configuration; CSRF (why disabled for JWT); input validation with Bean Validation
- **SOAP vs REST** — Protocol vs style; WSDL contract; when to still use SOAP (enterprise, WS-Security, financial)

**Sample Q&A topics:**
- What is the difference between PUT and PATCH?
- Why is CSRF protection safe to disable for JWT-based REST APIs?
- Which API versioning strategy would you recommend for a public API vs internal microservices?
- How do you implement rate limiting per user in Spring Cloud Gateway?

</details>

---

### 📐 System Design

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

**6-Step Framework:**
1. Clarify functional + non-functional requirements
2. Estimate scale (DAU → QPS → storage)
3. High-level design (boxes and arrows)
4. Deep dive on hardest components
5. Identify bottlenecks (SPOF, hotspots)
6. Discuss trade-offs explicitly

**3 Full Designs Included:**

| Design | Key Decisions Covered |
|--------|----------------------|
| URL Shortener | Base62 encoding, Snowflake ID, 301 vs 302, Redis caching, Kafka analytics |
| E-Commerce Backend | Service decomposition, DB choices per service, inventory optimistic locking, Saga |
| Notification Service | Kafka routing, deduplication with Redis SETNX, rate limiting, retry + DLQ |

**Core Concepts:** CAP theorem, consistent hashing, CQRS, Event Sourcing, caching strategies (cache-aside, write-through, write-behind), DB sharding (range vs hash vs directory), Bloom filters, two-phase commit vs Saga.

</details>

---

### 🧩 DSA & Java Coding

<details>
<summary><strong>Key concepts covered (click to expand)</strong></summary>

**6 Core Patterns with Full Java Code:**

| Pattern | Problems | Complexity |
|---------|----------|------------|
| HashMap / Frequency | Two Sum, Group Anagrams, Top K Frequent | O(n) time |
| Sliding Window | Longest Substring, Subarray Sum = K, Max Sum Window | O(n) time |
| BFS / DFS | Level Order, Number of Islands, Graph traversal | O(V+E) |
| Binary Search | Standard, First Position, Search Rotated Array | O(log n) |
| LRU / LFU Cache | LinkedHashMap approach + manual DLL approach | O(1) get/put |
| Monotonic Stack | Valid Parentheses, Daily Temperatures, Next Greater Element | O(n) |

**15 Must-Solve LeetCode Problems for Backend Interviews:**
LC 1, 3, 15, 20, 33, 49, 102, 146, 200, 226, 238, 347, 560, 572, 739

**Java-Specific Tips:** ArrayDeque over Stack; mid = l+(r-l)/2 to avoid overflow; `merge()` for atomic map updates; `computeIfAbsent()` for grouping patterns.

</details>

---

## 📺 Curated Resources

### Java & Spring Boot
| Channel / Resource | Best For |
|--------------------|----------|
| [Java Guides (Ramesh Fadatare)](https://www.youtube.com/@JavaGuides) | Spring Boot, JUnit, Microservices — project-based |
| [Daily Code Buffer](https://www.youtube.com/@DailyCodeBuffer) | Microservices series: Eureka, Gateway, Resilience4j |
| [Amigoscode](https://www.youtube.com/@amigoscode) | Spring Boot REST, Docker, Testing |
| [Java Brains](https://www.youtube.com/@Java.Brains) | Spring Security, OAuth2, JWT deep dives |
| [Baeldung](https://www.baeldung.com) | Every Spring topic with tested code — bookmark this |

### DSA (Java)
| Channel / Resource | Best For |
|--------------------|----------|
| [NeetCode](https://www.youtube.com/@NeetCode) | Best DSA channel; NeetCode 150 roadmap |
| [Striver / TakeUForward](https://www.youtube.com/@takeUforward) | SDE Sheet; India's best structured DSA prep |
| [Abdul Bari](https://www.youtube.com/@abdul_bari) | Algorithm theory — graphs, DP, backtracking |
| [Kunal Kushwaha](https://www.youtube.com/@KunalKushwaha) | Java-first DSA bootcamp — arrays to graphs |

### System Design
| Channel / Resource | Best For |
|--------------------|----------|
| [ByteByteGo](https://www.youtube.com/@ByteByteGo) | Animated 5-10 min explainers on every concept |
| [Gaurav Sen](https://www.youtube.com/@gkcs) | Consistent hashing, CAP, sharding fundamentals |
| [Concept && Coding](https://www.youtube.com/@ConceptandCoding) | LLD + HLD with Java code — very relevant |
| [Arpit Bhayani](https://www.youtube.com/@AsliEngineering) | DB internals, distributed systems — deep technical |
| [System Design Primer](https://github.com/donnemartin/system-design-primer) | Most comprehensive free text resource |

### Practice Platforms
| Platform | Use For |
|----------|---------|
| [LeetCode](https://leetcode.com) | DSA — filter by HashMap, Tree, Graph; solve 15 mediums |
| [HackerRank SQL](https://www.hackerrank.com/domains/sql) | Oracle SQL — window functions section is excellent |
| [MongoDB University](https://learn.mongodb.com) | M001 (basics), M121 (aggregation) — free, hands-on |
| [Spring Guides](https://spring.io/guides) | Short focused Spring Boot starter projects |

---

## ✅ Progress Tracker

The interactive HTML guide includes a **48-item checklist** across all topics with a live progress bar. Open the file and use the **✅ Tracker** tab.

**Checklist breakdown:**
- ☕ Java Core — 8 items
- 🌱 Spring Boot — 8 items
- 🏗️ Microservices — 7 items
- 🍃 MongoDB — 6 items
- 🗄️ Oracle/SQL — 6 items
- 🧪 JUnit — 5 items
- 🌐 REST APIs — 4 items
- 📐 System Design + 🧩 DSA — 8 items

---

## 📁 Repository Structure

```
java-interview-prep/
│
├── README.md                          # This file
├── java-backend-interview-prep-v2.html  # Main interactive guide (open in browser)
│
├── snippets/                          # Standalone code snippets (optional)
│   ├── java/
│   │   ├── LRUCache.java
│   │   ├── BFSTemplate.java
│   │   └── StreamExamples.java
│   ├── spring/
│   │   ├── JwtFilter.java
│   │   ├── GlobalExceptionHandler.java
│   │   └── CircuitBreakerExample.java
│   ├── mongodb/
│   │   └── AggregationPipeline.js
│   └── sql/
│       └── WindowFunctions.sql
│
└── LICENSE
```

---

## 🤝 Contributing

Contributions are welcome — especially:

- Additional Q&A for any topic
- More code snippets with explanations
- New system design walkthroughs
- Corrections or updated best practices

**How to contribute:**

```bash
# 1. Fork the repo
# 2. Create a feature branch
git checkout -b feature/add-kafka-questions

# 3. Make your changes
# 4. Commit with a clear message
git commit -m "Add 5 Kafka consumer group Q&As with code examples"

# 5. Push and open a Pull Request
git push origin feature/add-kafka-questions
```

**Contribution guidelines:**
- Every Q&A must include a complete answer (not just a pointer)
- Code snippets must be runnable / syntactically correct Java
- Keep difficulty labels consistent: Easy / Medium / Hard
- New resources should be free and directly relevant to the tech stack

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to use, copy, modify, and distribute this guide for personal or commercial use with attribution.

---

## ⭐ If this helped you land the job, star the repo!

```
"The more you sweat in practice, the less you bleed in battle."
```

Good luck with your interview. 🚀
