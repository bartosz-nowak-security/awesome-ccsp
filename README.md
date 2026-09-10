# CCSP po 1 sierpnia 2026 r. 
## Najważniejsza zmiana

Od **1 sierpnia 2026 r.** egzamin CCSP jest oparty na nowym outline'cie ISC2. Egzamin zdany do 31 lipca 2026 r. odbywa się według dotychczasowego zakresu, natomiast egzamin w dniu 1 sierpnia lub później wykorzystuje nową wersję.

Zmiana wynika z okresowej analizy zadań zawodowych (Job Task Analysis). Jest to aktualizacja zakresu wiedzy, a nie całkowita przebudowa certyfikacji. Sześć domen i podstawowe pojęcia bezpieczeństwa chmurowego pozostają aktualne, ale większy nacisk położono na współczesne środowiska chmurowe, automatyzację oraz sztuczną inteligencję i uczenie maszynowe.

## Co pozostaje bez zmian

- nadal obowiązuje sześć domen CCSP;
- egzamin zachowuje format komputerowego testu adaptacyjnego (CAT): 100–150 pytań w ciągu 3 godzin;
- próg zaliczenia pozostaje na poziomie 700 punktów na 1000;
- nie zmieniają się wymagania doświadczenia zawodowego: łącznie 5 lat płatnego doświadczenia w IT, w tym 3 lata w bezpieczeństwie informacji i co najmniej 1 rok w domenie CCSP;
- posiadanie certyfikatu CISSP nadal zwalnia z całego wymogu doświadczenia;
- osoby bez wymaganego doświadczenia mogą przystąpić do egzaminu jako Associate of ISC2 i uzupełnić doświadczenie w ciągu 6 lat;
- utrzymanie certyfikatu nadal wymaga 90 punktów CPE w trzyletnim cyklu oraz opłaty rocznej.

## Zmiana wag domen

Zmieniają się tylko dwie wagi:

| Domena | Do 31.07.2026 | Od 01.08.2026 |
|---|---:|---:|
| 4. Cloud Application Security | 17% | 16% |
| 5. Cloud Security Operations | 16% | 17% |

Pozostałe domeny zachowują dotychczasowe wagi:

- Domain 1 — 17%;
- Domain 2: Cloud Data Security — 20%;
- Domain 3 — 17%;
- Domain 6 — 13%.

Cloud Data Security nadal jest największą domeną. Cloud Security Operations zyskuje jeden punkt procentowy, co dobrze odpowiada rosnącej roli automatyzacji, monitorowania i obsługi środowisk AI.

## Najważniejsze nowe i rozszerzone tematy

### Sztuczna inteligencja i uczenie maszynowe

AI/ML nie tworzy osobnej domeny, lecz zostaje włączone do istniejących obszarów CCSP. Należy przygotować się na pytania dotyczące:

- ochrony danych, zbiorów danych i modeli;
- prywatności danych wykorzystywanych w AI/ML;
- walidacji źródeł danych;
- wykrywania zagrożeń i wykorzystania SOAR;
- ryzyka związanego z potokami danych i modelami;
- etyki, regulacji oraz współdzielonej odpowiedzialności przy korzystaniu z zarządzanych usług AI.

### Aplikacje i podatności

Zakres wspólnych podatności został rozszerzony o:

- OWASP ASVS;
- OWASP API Top 10;
- OWASP Top 10 for LLM Applications.

### Operacje bezpieczeństwa

Dodano lub rozszerzono następujące elementy:

- secure by default;
- threat intelligence;
- penetration testing;
- frameworki kontroli operacyjnych: NIST, COBIT, CIS Controls i COSO, obok ITIL.

### Forensics i prywatność

Nowy outline wskazuje konkretne standardy informatyki śledczej: ISO/IEC 27037, 27041, 27042 i 27043. Rozszerzono także zakres regulacji prywatności o FERPA, PIPEDA, GDPR, HIPAA oraz indyjską ustawę Digital Personal Data Protection Act.

## Zmiany nazw i elementy nadal istotne

Niektóre punkty zmieniły nazwę:

- „Incident Management” zastąpiono nazwą „Incident Response (IR)”;
- „Understand privacy issues” zmieniono na „Understand privacy requirements”;
- „audit process” zmieniono na „audit processes”.

IaC strategy, zero trust network i DevSecOps nie są już wymienione jako osobne elementy outline'u. Nie oznacza to jednak, że można je całkowicie pominąć. Nadal są powszechnie stosowane i mogą być sprawdzane w kontekście szerszych zagadnień bezpieczeństwa chmurowego.

## Standardy, które warto znać

Nowa wersja egzaminu odwołuje się do nowszych wydań i standardów, w szczególności:

- NIST SP 800-61 Rev. 3, oparty na funkcjach NIST CSF 2.0;
- NIST SP 800-88 Rev. 2 oraz IEEE 2883 w zakresie sanitizacji nośników;
- NIST SP 800-63B-4, obejmujący m.in. passkeys i synchronizowalne uwierzytelniacze;
- ISO/IEC 27018:2025 i ISO/IEC 27701:2025;
- OWASP Top 10:2025 oraz OWASP Top 10 for LLM Applications:2025;
- CSA Top Threats to Cloud Computing 2024;
- PCI DSS v4.0.1;
- seria ISO/IEC 22123, która zastępuje ISO/IEC 17788 i 17789;
- standardy kryptografii postkwantowej FIPS 203, 204 i 205.

## Dodatkowe materiały do nauki

Poniższe zasoby pochodzą z pliku `materialy` i nie zastępują oficjalnych publikacji ISC2. Przed użyciem należy sprawdzić, czy ich zakres odpowiada outline'owi obowiązującemu od 1 sierpnia 2026 r., zwłaszcza w obszarach AI/ML, nowych standardów i rozszerzonych zagadnień bezpieczeństwa aplikacji.

### Materiały wideo

#### CCSP Exam Cram — Peter Zerger

Darmowy, około 11-godzinny kurs przygotowujący do CCSP. Materiał obejmuje także sesje dotyczące egzaminu w 2026 r., a poszczególne domeny są dostępne jako osobne filmy.

https://www.youtube.com/playlist?list=PL7XJSuT7Dq_X0AupQwU8YOGV3TsoPAcD0

#### ISC2 CCSP Full Course & Practice Exam (2026)

Kurs z materiałami do nauki i testem praktycznym. Według opisu jest dobrze oceniany i może służyć jako uzupełnienie głównego podręcznika.

https://naspers.udemy.com/course/isc2-ccsp-full-course-practice-exam

### Materiały tekstowe

#### Destination CCSP: The Comprehensive Guide

Kompleksowy przewodnik polecany przez społeczność przygotowującą się do CCSP. Warto porównać jego zakres z oficjalnym outline'em 2026.

https://destcert.com/ccsp/guidebook/

#### CCSP: The Last Mile

Skondensowane opracowanie przeznaczone do powtórek i przygotowania w końcowym etapie nauki. Nie powinno zastępować pełnego omówienia materiału.

https://leanpub.com/ccsplastmile

### Aplikacje i banki pytań

#### Pocket Prep

Aplikacja z pytaniami i funkcjami wspierającymi regularne powtórki. Część opcji może wymagać wersji premium.

https://www.pocketprep.com/

#### LearnZapp

Aplikacja do nauki i ćwiczenia pytań testowych. Może być używana jako dodatkowy bank pytań obok oficjalnych materiałów.

https://www.learnzapp.com/


## Wniosek

Aktualizacja CCSP od 1 sierpnia 2026 r. jest **odświeżeniem zakresu egzaminu, a nie zmianą jego podstaw**. Najważniejsze pozostają klasyczne kompetencje cloud security, ale trzeba je uzupełnić o AI/ML, nowoczesne bezpieczeństwo aplikacji, threat intelligence, penetration testing, aktualne regulacje i nowsze standardy.
