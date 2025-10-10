# Jak skonfigurować AI_MENTOR w ChatGPT/Claude/Gemini

## 📂 Pliki które musisz dodać

Z tego folderu (`02_pliki_projektu`):

1. **`MAIN_MENU.md`** ⭐ - Główny kontroler, menu systemu
2. **`mentor_learner.md`** 🟢 - Tryb systematycznej nauki (curriculum wbudowany)
3. **`mentor_creator.md`** 🔵 - Tryb rapid building i portfolio
4. **`PROFIL.md`** - Twój profil (stworzyłeś w kroku 1)

Plus:
5. **`INSTRUKCJA_DO_PROJEKTU.md`** - Instrukcje dla AI (wklejasz jako project instructions)

---

## 🎯 DWA TRYBY PRACY

AI_MENTOR ma dwa tryby które możesz przełączać w zależności od potrzeby:

### LEARNER MODE 🟢
- Systematyczna nauka AI od podstaw
- Curriculum z 4 poziomów (Foundation → Builder → Architect → Master)
- 60+ lekcji z metoda sokratejską
- Checkpointy (kontrolujesz tempo)
- Capstone challenges (projekty integracyjne)
- Tracking postępów w nauce

**Dla kogo:** Osoby uczące się AI systematycznie, budujące fundamenty

### CREATOR MODE 🔵
- TOOL SCOUT - 30-minutowe rapid testing narzędzi
- Portfolio projects - projekty w 3h gotowe do pokazania
- Content generation - 1 projekt → 12 pieces of content
- Case studies - zamiana kodu w posty/tutoriale
- ROI focus - zawsze mierz wartość

**Dla kogo:** Twórcy content, budujący produkty AI, educators, consultants

**WAŻNE:** Nie jesteś "learnerem" LUB "creatorem" - używasz trybu który pasuje do aktualnego celu. Możesz przełączać się między nimi w dowolnym momencie!

---

## Opcja A: ChatGPT Plus

### Krok 1: Stwórz projekt
1. Kliknij **"Projects"** (lewy panel)
2. **"Create project"** → nazwa **"AI Mentor"**

### Krok 2: Dodaj pliki
Przeciągnij lub dodaj 4 pliki:
- `MAIN_MENU.md`
- `mentor_learner.md`
- `mentor_creator.md`
- `PROFIL.md` (twój profil z kroku 1)

### Krok 3: Dodaj instrukcje
1. W projekcie kliknij **"Project settings"** lub **"Instructions"**
2. Otwórz plik `INSTRUKCJA_DO_PROJEKTU.md`
3. Skopiuj całą zawartość
4. Wklej do pola **"Project instructions"**
5. Zapisz

### Krok 4: Start!
Rozpocznij nowy czat w projekcie i napisz:
```
Cześć, zacznijmy naukę AI
```

---

## Opcja B: Claude Pro

### Krok 1: Stwórz projekt
1. **"Create a project"** → nazwa **"AI Mentor"**

### Krok 2: Dodaj pliki
1. Kliknij **"Add content"**
2. Dla każdego pliku:
   - Otwórz plik na komputerze
   - Skopiuj całą zawartość (Ctrl+A, Ctrl+C)
   - Wklej do projektu

Dodaj:
- `MAIN_MENU.md`
- `mentor_learner.md`
- `mentor_creator.md`
- `PROFIL.md` (twój profil z kroku 1)

### Krok 3: Dodaj instrukcje
1. W projekcie znajdź **"Custom instructions"** lub **"Project instructions"**
2. Otwórz `INSTRUKCJA_DO_PROJEKTU.md`
3. Skopiuj całą zawartość
4. Wklej do instrukcji projektu
5. Zapisz

### Krok 4: Start!
Kliknij **"Start new chat"** i napisz:
```
Cześć, zacznijmy naukę AI
```

---

## Opcja C: Gemini (Gem)

### Krok 1: Stwórz Gem
1. **"Create a new Gem"** → nazwa **"AI Mentor"**

### Krok 2: Dodaj instrukcje
1. W sekcji **"Instructions"** wklej treść z `INSTRUKCJA_DO_PROJEKTU.md`
2. Zapisz

### Krok 3: Dodaj pliki do Knowledge
1. W sekcji **"Knowledge"** kliknij **"Add files"**
2. Kliknij 📎 i dodaj pliki (lub skopiuj treść każdego):
   - `MAIN_MENU.md`
   - `mentor_learner.md`
   - `mentor_creator.md`
   - `PROFIL.md` (twój profil z kroku 1)

### Krok 4: Start!
Rozpocznij czat z Gem i napisz:
```
Cześć, zacznijmy naukę AI
```

---

## Opcja D: Darmowe AI (fallback)

Jeśli nie masz dostępu do Projects/Gems:

1. Otwórz `MAIN_MENU.md`
2. Skopiuj całą zawartość
3. Wklej do nowego czatu
4. Dodaj swój `PROFIL.md` na końcu
5. Napisz: "Cześć, zacznijmy"

**Ograniczenia:** Musisz ręcznie kopiować pliki `mentor_learner.md` lub `mentor_creator.md` gdy wybierzesz tryb.

---

## Co zobaczysz po starcie?

AI pokaże główne menu:

```
🎓 AI_MENTOR - Cześć [Twoje Imię]!

[L] LEARNER MODE - Systematyczna nauka AI
    └─ Curriculum, lekcje, projekty edukacyjne
    └─ 4 poziomy: Foundation → Builder → Architect → Master

[C] CREATOR MODE - Research, build, portfolio
    └─ Tool scouting, projekty portfolio, content generation
    └─ Quick wins, mierzalny ROI

────────────────────────────────────

[P] PROFIL - Zaktualizuj swój profil
[R] ROADMAP - Zobacz obie ścieżki (Learner + Creator)
[S] STATUS - Gdzie jesteś? (progress obu trybów)

────────────────────────────────────

Wybierz literę lub opisz co chcesz zrobić.
```

**Wybierz:**
- `[L]` - Jeśli chcesz uczyć się systematycznie
- `[C]` - Jeśli chcesz budować/testować/tworzyć content

---

## LEARNER MODE - Co zobaczysz?

Po wybraniu `[L]` dostaniesz menu:

```
🎓 LEARNER MODE - [Imię]

[1] START - Quick test + pierwsza lekcja
[2] LEKCJA - Następny temat z curriculum
[3] PROJEKT - Budujemy coś realnego
[4] ROADMAP - Twój plan nauki (tylko Learning track)
[5] CHECK - Na jakim jesteś poziomie?
[6] SPRINT - Intensywny tydzień
[7] CASE - Przykład z twojej branży

[M] MAIN MENU - Wróć do menu głównego
```

**Struktura nauki:**
- 4 poziomy: Foundation → Builder → Architect → Master
- 12 modułów tematycznych
- 60+ lekcji z metodą sokratejską
- Checkpointy po każdej koncepcji ("Gotowy przejść dalej?")
- Capstone challenges - projekty integracyjne łączące wiele koncepcji

---

## CREATOR MODE - Co zobaczysz?

Po wybraniu `[C]` dostaniesz menu:

```
🎨 CREATOR MODE - [Imię]

[1] TOOL SCOUT - Quick recon narzędzia (30 min)
    "Czy to tool dla mnie? Use or skip?"

[2] BUILD - Portfolio project (3h)
    "Zbuduj coś konkretnego z narzędziem"

[3] DOCUMENT - Projekt → Case study
    "Zamień kod w case study/tutorial"

[4] CONTENT - Generate post
    "Wygeneruj content z projektu"

[5] PORTFOLIO - Zarządzaj projektami
    "Zobacz co masz, improve/document existing"

[6] COMPARE - Tool A vs Tool B
    "Decision framework: który wybrać?"

[7] ROADMAP - Strategy (content/product)
    "Plan na następne 3 miesiące"

[M] MAIN MENU - Wróć do menu głównego
```

**Quick wins:**
- Tool Scout - poznaj nowe narzędzie w 30 minut i zadecyduj: deep dive or skip
- Portfolio project - zbuduj coś w 3h (mierzalny ROI)
- Content leverage - jeden projekt = 5+ pieces of content

---

## Jak aktualizować PROFIL.md?

### Podczas sesji:
Na końcu każdej sesji AI wygeneruje update do skopiowania:

**Learner mode:**
```markdown
📊 UPDATE DO PROFIL.MD (LEARNING TRACK):

## LEARNING TRACK - PROGRESS
ostatnia_sesja: 2025-01-15
ostatnia_lekcja: "RAG basics"
streak: 7 dni

### Ukończone moduły
- ☑ AI BASICS (100%)
- ☐ RAG & KNOWLEDGE (40%)

Skopiuj do PROFIL.md!
```

**Creator mode:**
```markdown
📊 UPDATE DO PROFIL.MD (CREATOR TRACK):

## CREATOR TRACK - PROGRESS
ostatnia_sesja: 2025-01-15
ostatni_research: "Claude Code"

### Portfolio Projects
3. ☑ AI News Aggregator - completed 2025-01-15

Skopiuj do PROFIL.md!
```

### Pełna aktualizacja:
Możesz w każdej chwili napisać `[P]` lub `[M]` → `[P]` i wybrać:
- `[1]` Wszystko - pełny zaktualizowany profil
- `[2]` Tylko progress (learning + creator)
- `[3]` Cele i roadmapa
- `[4]` Narzędzia i stack

AI wygeneruje gotowy fragment do skopiowania.

---

## 🆕 NOWE NARZĘDZIA W KURSIE (2025)

### AGENTY KODUJĄCE (delegacja, nie augmentacja!)
- **Claude Code** - refaktoryzacja całego repo w 3h
- **GPT-5-Codex** - autonomiczna praca przez godziny
- **Cursor / Aider** - terminal coding tools

### VIBE CODING (dla non-tech)
- **Lovable / Bolt** - opisz aplikację, dostaniesz kod
- Bez programowania tworzysz działające aplikacje
- Hybrid workflow: generate → GitHub → debug

### GROK ECOSYSTEM
- **Grok 4 Fast** - real-time X/Twitter data
- **Grok Tasks** - automatyczne raporty co rano
- Przykład: "Znajdź 3 trendy AI z 24h i wyślij na Slack o 7:00"

### AUTOMATION
- **n8n** - workflow automation (znasz kroki)
- **Manus** - goal-driven agent (znasz cel)
- ROI przykład: 2h dziennie × $50 = $25k/rok saved

### CREATIVE
- **Higgsfield** - fotorealistyczne obrazy
- **Veo3** - generowanie video
- **Gamma** - prezentacje AI

---

## QUICK WINS - Od czego zacząć?

**Learner:**
1. Problem-first thinking (lekcja bez AI!)
2. Vibe coding app (Lovable - 2h vs $5k)
3. Grok Tasks setup (5 min → 30 min/day saved)

**Creator:**
1. Tool scout Manus (30 min → decision)
2. Portfolio project (3h → GitHub + content)
3. Document existing project (code → case study)

---

## ❌ NAJCZĘSTSZE BŁĘDY - Nie rób tego!

1. **"Chcę nauczyć się AI"**
   ✅ Zamiast: "Chcę zaoszczędzić 5h tygodniowo na raportach"

2. **"Który model jest najlepszy?"**
   ✅ Zamiast: "Który model da mi 80% wartości za 20% ceny?"

3. **"Zbudujmy chatbota"**
   ✅ Zamiast: "Co zabiera mi najwięcej czasu i jak to zautomatyzować?"

4. **Uczenie się wszystkich narzędzi**
   ✅ Zamiast: Wybierz 2-3 które rozwiążą twoje problemy

5. **Czekanie na "idealny moment"**
   ✅ Zamiast: Start z Grok Tasks (5 min) i zobacz wartość

---

## 📈 MIERZ SUKCES

Po każdym tygodniu odpowiedz:
- Ile godzin zaoszczędziłem dzięki AI?
- Jaki problem rozwiązałem?
- Jaki jest ROI? (czas × stawka)

Jeśli nie możesz odpowiedzieć → zmień podejście.

---

## Problem?

**AI nie widzi plików?**
→ Napisz: "Przeczytaj MAIN_MENU.md"

**Za długie odpowiedzi?**
→ Napisz: "Pisz krócej, max 3 akapity"

**Nie personalizuje?**
→ Napisz: "Jestem [stanowisko] z PROFIL.md"

**Zaczyna od narzędzi?**
→ Napisz: "Zacznij od mojego problemu biznesowego"

**Nie działa przełączanie trybów?**
→ Napisz: "[M]" dla menu, potem "[L]" lub "[C]"

---

## 🔄 Przełączanie między trybami

W dowolnym momencie możesz:

```
Ty: "[C]" lub "Creator mode"
AI: [pokazuje Creator menu]

Ty: "[L]" lub "Learner"
AI: [pokazuje Learner menu]

Ty: "[M]" lub "Menu"
AI: [pokazuje główne menu]
```

AI pamięta gdzie byłeś (która lekcja, który projekt) i wraca do tego miejsca.

---

## Przykłady użycia

### Typowy Learner (90% nauki):
```
Sesja 1-10: [L] Systematyczna nauka
Sesja 11: [C] "Chcę case study do CV"
Sesja 12-20: [L] Powrót do nauki
```

### Creator building product (50/50):
```
Poniedziałek: [C] Tool scout (30 min)
Wtorek: [L] Deep dive learning (2h)
Środa: [C] Build projekt (3h)
Czwartek: [L] Continue learning
Piątek: [C] Document + content
```

### Flexible (najlepsze!):
```
User: "[C] Scout Manus"
AI: [30 min test]

User: "Menu → [L]"
AI: "Multi-agent deep dive?"

User: [learns for 2h]

User: "[C] Build"
AI: "Projekt z Manus + multi-agent?"
```

---

**Gotowy? Dodaj pliki do projektu i napisz: "Cześć, zacznijmy naukę AI"**
