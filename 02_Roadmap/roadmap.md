# RoadToExpert — Roadmap

## 1. Cel końcowy

Docelowy profil:

**Quality Engineer / QA Automation Engineer / SDET z szerokimi kompetencjami inżynierskimi**

Profil ma łączyć:

* test automation,
* software engineering,
* API,
* frontend,
* backend,
* CI/CD,
* cloud,
* konteneryzację,
* architekturę,
* AI-assisted engineering.

Nie zakładamy, że konkretne narzędzie będzie najważniejsze za 3–5 lat.

Budujemy fundamenty, które pozwalają szybko przyswajać nowe technologie.

---

# 2. Roadmapa wysokiego poziomu

```text
ETAP 0
Projekt + Git
       ↓
ETAP 1
Fundamenty IT
       ↓
ETAP 2
Web + HTTP + API
       ↓
ETAP 3
Programowanie + TypeScript
       ↓
ETAP 4
Playwright + automatyzacja
       ↓
ETAP 5
SQL + dane + backend
       ↓
ETAP 6
CI/CD + Azure DevOps + GitHub Actions
       ↓
ETAP 7
Linux + Docker
       ↓
ETAP 8
Cloud
       ↓
ETAP 9
Kubernetes + IaC
       ↓
ETAP 10
Architecture + Observability
       ↓
ETAP 11
AI-assisted Engineering
       ↓
PROFIL EXPERT
```

AI jest obecne na każdym etapie, a nie dopiero w ETAPIE 11.

---

# 3. TOR A — Market Value

## Priorytet P0 — absolutne fundamenty

### Git

Cel:

* rozumieć system kontroli wersji,
* swobodnie pracować z repozytorium,
* tworzyć branche,
* wykonywać merge,
* rozwiązywać konflikty,
* korzystać z pull requestów,
* rozumieć podstawowy workflow GitHub.

Status:

* [x] Git zainstalowany
* [x] repozytorium utworzone
* [x] clone
* [x] commit
* [x] push
* [ ] branch
* [ ] merge
* [ ] pull request
* [ ] conflict resolution
* [ ] .gitignore
* [ ] GitHub workflow

---

## HTTP / HTTPS

Cel:

Rozumieć, jak naprawdę działa komunikacja aplikacji webowej.

Do opanowania:

* request / response,
* metody HTTP,
* status codes,
* headers,
* cookies,
* sessions,
* authentication,
* authorization,
* HTTPS,
* podstawy TLS,
* browser → server.

---

## JSON

Cel:

Swobodne czytanie i tworzenie danych używanych przez API.

Do opanowania:

* objects,
* arrays,
* strings,
* numbers,
* booleans,
* null,
* nested structures,
* JSONPath,
* walidacja danych.

---

# 4. TOR A — API Testing

## REST API

Do opanowania:

* endpoint,
* resource,
* GET,
* POST,
* PUT,
* PATCH,
* DELETE,
* request body,
* response body,
* headers,
* authentication,
* status codes,
* negative testing,
* contract thinking.

## Postman

Cel:

Samodzielnie testować API bez korzystania z UI aplikacji.

Do wykonania:

* tworzenie requestów,
* collections,
* environments,
* variables,
* assertions,
* test scripts,
* chained requests,
* authentication,
* import OpenAPI,
* uruchamianie kolekcji.

---

# 5. TOR A — Programming

## TypeScript

Cel:

Osiągnięcie poziomu wystarczającego do samodzielnego tworzenia i utrzymywania automatyzacji.

Zakres:

* variables,
* types,
* functions,
* arrays,
* objects,
* conditions,
* loops,
* modules,
* interfaces,
* classes,
* async/await,
* promises,
* error handling,
* podstawy OOP,
* podstawy clean code.

Nie dążymy początkowo do poziomu profesjonalnego programisty TypeScript.

Dążymy do poziomu:

> „Potrafię samodzielnie czytać, pisać, debugować i rozwijać kod automatyzacji.”

---

# 6. TOR A — Playwright

## Cel

Budowa nowoczesnego warsztatu automatyzacji testów webowych.

Zakres:

* instalacja,
* konfiguracja projektu,
* locators,
* assertions,
* actions,
* waits,
* fixtures,
* test data,
* Page Object Model,
* API testing,
* authentication,
* screenshots,
* traces,
* reports,
* parallel execution,
* retries,
* tagging,
* konfiguracja środowisk.

Następnie:

* projekt frameworku,
* reusable components,
* test architecture,
* maintainability,
* CI execution.

---

# 7. TOR A — SQL

Cel:

Umiejętność samodzielnej weryfikacji danych po wykonaniu testu.

Zakres:

* SELECT,
* WHERE,
* ORDER BY,
* GROUP BY,
* JOIN,
* INSERT,
* UPDATE,
* DELETE,
* aggregate functions,
* subqueries,
* podstawy indeksów,
* relacje między tabelami.

---

# 8. TOR A — CI/CD

## Azure DevOps

Zakres:

* repositories,
* work items,
* pipelines,
* test results,
* artifacts,
* variables,
* environments,
* podstawy YAML.

## GitHub Actions

Zakres:

* workflow,
* triggers,
* jobs,
* steps,
* runners,
* artifacts,
* secrets,
* uruchamianie testów automatycznych.

---

# 9. TOR B — Expert

Po osiągnięciu podstawowej wartości rynkowej rozwijamy kompetencje infrastrukturalne.

## Linux

* filesystem,
* permissions,
* processes,
* networking,
* package management,
* logs,
* shell.

## Bash / PowerShell

Automatyzacja codziennych zadań.

## Docker

* images,
* containers,
* Dockerfile,
* volumes,
* networks,
* registries,
* Docker Compose.

## Cloud

Preferowany pierwszy kierunek:

**Microsoft Azure**

Zakres:

* compute,
* storage,
* networking,
* identity,
* monitoring,
* containers,
* podstawy security.

## Kubernetes

* pods,
* deployments,
* services,
* ingress,
* config,
* secrets,
* scaling,
* podstawy troubleshooting.

## Infrastructure as Code

Docelowo:

**Terraform**

Zakres:

* providers,
* resources,
* variables,
* state,
* modules,
* plan,
* apply,
* podstawy architektury IaC.

---

# 10. Architecture

Docelowo rozumiemy:

* frontend,
* backend,
* API,
* databases,
* queues,
* microservices,
* containers,
* cloud,
* authentication,
* networking,
* observability.

Cel:

Nie tylko testować system.

Rozumieć:

> „Jak ten system działa jako całość i gdzie mogą występować problemy?”

---

# 11. AI — kompetencja przekrojowa

AI jest używane od pierwszego dnia.

### ChatGPT

Wykorzystanie:

* nauka,
* wyjaśnianie błędów,
* analiza kodu,
* generowanie przykładów,
* tworzenie test cases,
* analiza API,
* dokumentacja,
* debugging,
* refactoring,
* przygotowanie do rozmów.

### GitHub Copilot

Docelowo:

* code completion,
* test generation,
* refactoring,
* documentation,
* code exploration.

### AI-assisted testing

Docelowo:

* generowanie testów,
* analiza logów,
* generowanie danych,
* analiza failure patterns,
* wspomaganie maintenance,
* analiza coverage,
* test optimization.

---

# 12. TOR C — Career

Równolegle rozwijamy:

* CV,
* LinkedIn,
* GitHub,
* portfolio,
* projekty demonstracyjne,
* przygotowanie do rozmów,
* analizę ofert pracy,
* analizę wynagrodzeń,
* analizę wymagań rynku.

Co pewien czas roadmapa będzie podlegała rewizji.

---

# 13. Priorytety

## P0 — natychmiast

* Git
* HTTP
* JSON
* REST API
* Postman
* TypeScript
* Playwright

## P1 — następna warstwa

* SQL
* Azure DevOps
* GitHub Actions
* Docker
* Linux

## P2 — rozwój ekspercki

* Azure
* Kubernetes
* Terraform
* architecture
* observability

## P3 — technologie zależne od rynku

Technologie, które mogą pojawić się w przyszłości:

* Python
* Java
* C#
* Cypress
* Selenium
* Pact / contract testing
* Kafka
* Grafana
* inne narzędzia.

Nie uczymy się ich z góry.

Wprowadzamy je wtedy, kiedy uzasadnia to:

1. rynek pracy,
2. projekt,
3. portfolio,
4. wymagania konkretnej ścieżki.

---

# 14. Zasada aktualizacji roadmapy

Roadmapa nie jest kontraktem.

Co około 3 miesiące wykonujemy:

## Market Review

Sprawdzamy:

* jakie technologie pojawiają się w ofertach,
* jakie kompetencje są wymagane,
* jakie wynagrodzenia są oferowane,
* które technologie tracą znaczenie,
* jakie nowe technologie pojawiają się,
* jak AI zmienia wymagania.

Następnie aktualizujemy roadmapę.

---

# 15. Definition of Done dla kompetencji

Nie uznajemy technologii za poznaną tylko dlatego, że przeczytaliśmy dokumentację.

Kompetencja jest uznana za praktycznie opanowaną, gdy potrafię:

1. wyjaśnić podstawowe koncepty,
2. samodzielnie wykonać typowe zadanie,
3. znaleźć i naprawić podstawowy błąd,
4. wykorzystać technologię w projekcie,
5. wyjaśnić swoje rozwiązanie podczas rozmowy technicznej.

---

# 16. Docelowy profil

```text
                 Quality Engineering
                         │
        ┌────────────────┼────────────────┐
        │                │                │
   Automation          API             Software
        │                │             Engineering
   Playwright         REST              TypeScript
   Tosca              Postman           Git
        │                │                │
        └────────────────┼────────────────┘
                         │
                    CI/CD + DevOps
                         │
                 Docker + Linux
                         │
                      Cloud
                         │
              Kubernetes + IaC
                         │
              Architecture + SRE
                         │
                    AI-assisted
                    Engineering
```

---

# 17. Najbliższy cel

### Sprint 1

**Git Fundamentals**

Rezultat Sprintu:

> Potrafię swobodnie pracować z repozytorium Git i GitHub oraz rozumiem, co dzieje się podczas codziennego workflow.

Dopiero po osiągnięciu tego celu przechodzimy do HTTP.
