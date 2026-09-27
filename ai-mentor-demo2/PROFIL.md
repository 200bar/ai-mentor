# PROFIL UŻYTKOWNIKA - AI MENTOR

)

2. AKTUALIZUJ tylko wartości:
   - W nawiasach [ ]
   - Daty (ostatnia_sesja)
   - Liczby (projekty, streak, %)
   - Listy (dodawaj nowe elementy)

3. SEKCJE DO AKTUALIZACJI:

   📚 LEARNING TRACK - aktualizuj po sesji Learner:
   - ostatnia_sesja: [data dzisiejsza]
   - ostatnia_lekcja: "[nazwa lekcji]"
   - streak: [increment jeśli dzisiaj, reset jeśli przerwa]
   - ukończone moduły: [update % i zmień ☐ na ☑ gdy 100%]
   - projekty learning: [dodaj nowe lub update status]

   🎨 CREATOR TRACK - aktualizuj po sesji Creator:
   - ostatnia_sesja: [data dzisiejsza]
   - ostatni_research: "[tool name]" (jeśli był scout)
   - ostatni_build: "[project name]" (jeśli był build)
   - tools researched: [dodaj nowe z werdyktem]
   - portfolio projects: [dodaj nowe lub update status]
   - content generated: [increment liczby]

   📊 COMBINED STATS:
   - total_time: [suma learning_time + creating_time]
   - total_projects: [suma learning + portfolio]
   - streak: [najdłuższy z obu track lub combined]

4. NIE ZMIENIAJ (chyba że user EXPLICITE prosi):
   - Sekcja DANE PODSTAWOWE
   - Sekcja CELE I ROI
   - Sekcja GRANICE
   - Te instrukcje aktualizacji

5. PEŁNA AKTUALIZACJA [P] → [1]:
   - Wygeneruj kompletny PROFIL.md z wszystkimi sekcjami
   - Zachowaj te instrukcje na górze
   - Update wszystkie progress sekcje
   - Dodaj nowe projekty/tools/content

6. PROGRESS ONLY [P] → [2]:
   - Generuj tylko sekcje:
     * LEARNING TRACK - PROGRESS
     * CREATOR TRACK - PROGRESS
     * COMBINED STATS
   - User skopiuje i wklei do swojego profilu

═══════════════════════════════════════════════════════════
-->

## DANE PODSTAWOWE
imię: [Lukasz]
poziom_AI: [zaawansowany (buduje własne rozwiązania)]
poziom_tech: [wysoki (DevOps, k8s, terraform)]
czas_tygodniowo: [7]h
energia_szczyt: [przedpołudnie (9-12), wieczór (19+)]

## PRACA I KONTEKST
stanowisko: [DevOps]
branża: [bankowość]
zadania_główne:
- [Terraform]
- [Kubernetes (k8s)]
- [CI/CD]

do_automatyzacji: [Bot auto-remediujący błędy k8s na podstawie alertów Prometheus]
problem_cost: [5 godzin / tydzień]

## EXPERIENCE & TOOLS
top_10_procent: [Generowanie pomysłów (słabszy w egzekucji)]
doświadczenie_AI: [Budował własne narzędzia (alerty krypto, kurs prompt eng, hardening VPS). Wysoka krzywa uczenia się narzędzi. AI słabe w automatyzacji GUI.]
failed_ai_projects: [Brak]
zrealizowane_projekty_ai: [Alerty crypto, kurs prompt engineering dla DevOps, narzędzie do hardeningu VPS]
known_tools: [Claude Code [Tak], GPT-5-Codex [Tak], Grok [Nie], Perplexity [Tak], n8n [Tak], Manus [Nie, ale otwarty], vibe coding [Nie]. (Dodatkowo: Claude, Gemini, ChatGPT)]
workflow_preference: [terminal]
automation_style: [precyzyjne kroki (n8n), otwarty na cel (agentic)]

## CELE I ROI
problem_do_rozwiązania_3m:
- [Zbudować bota auto-remediującego błędy k8s, wyzwalany alertami Prometheus]
- [szacowany_ROI: 5h / tydzień (oszczędność 20h / miesiąc)]

wizja_rok:
- [Chief AI Officer (CAIO) w obecnej firmie]

wartość_deadline: [Codziennie ("it gives me every day")]

success_criteria: [Zbudowanie bota (X), który automatycznie naprawia błędy podów k8s (Y) na podstawie alertów Prometheus.]

## ZASOBY
budżet: [$100-200+]/msc
narzędzia_obecne: [Notion, Slack, Excel, VS Code, Lens]
ai_tools_dostępne: [ChatGPT Plus, Claude Pro, Copilot]

## PREFERENCJE NAUKI
styl: [Mix (samodzielnie, z mentorem, w grupie)]
teoria_vs_praktyka: [20-80]
format_preferowany: [Tekst, Praktyka (kod)]
preferuje_interface: [Terminal]

## GRANICE
nie_chcę: [Brak ("there is no kind of thing")]
nie_chcę_szczegóły: [Matematyka ML]
blockers: [Brak czasu]
ograniczenia: [Brak czasu]

## REKOMENDACJE SYSTEMU
poziom_startowy: [Architect]
ścieżka_sugerowana: [Agent Builder / Automation Expert]

sugerowany_tryb_główny:
- [Głównie CREATOR - rapid building]
- [Dlaczego: Lukasz ma konkretny, zaawansowany cel (bot k8s) i mało czasu. Priorytetem jest budowanie (CREATOR) z mierzalnym ROI (5h/tydz.), aby odzyskać czas. Nauka (LEARNER) powinna wspierać ten cel, a nie być celem samym w sobie.]

pierwsze_3_kroki:
1. [Deconstruct: Zmapuj ręczny proces remediacji błędów k8s. Jakie alerty z Prometheus? Jakie komendy `kubectl` są używane do naprawy?]
2. [Quick Win (Terminal): Użyj Aider / Continue (w VS Code) aby napisać szkielet skryptu Python/Go, który nasłuchuje na webhook z Alertmanagera Prometheus.]
3. [Projekt v0.1 (ROI): Zbuduj w n8n workflow, który odbiera alert, filtruje go i wysyła *powiadomienie* do Slack (zamiast remediacji) z sugerowaną komendą `kubectl`. To potwierdzi działanie pętli i da natychmiastową wartość.]

najlepsze_narzędzia_dla_mnie:
- [**Aider / Continue**: Do kodowania bota w terminalu, bezpośrednio w VS Code. Idealne dla preferencji `terminal` i `practice`.]
- [**n8n (self-hosted)**: Do orkiestracji flow (Prometheus -> Agent -> k8s API -> Slack). Znasz już to narzędzie i preferujesz `precise steps`.]
- [**Claude 3 Opus (API)**: Do logiki agenta. Potrzebujesz najlepszego modelu do rozumienia logów i decydowania o krokach remediacji, a budżet nie jest problemem.]

najlepsze_moduły:
- [**CODING AGENTS**: Kluczowe do budowy bota. Nauczą Cię używać Aider/Continue, co pomoże Ci w "egzekucji" pomysłów.]
- [**n8n ORCHESTRATION**: Jak połączyć agenta kodującego z zewnętrznymi systemami (Prometheus, k8s API). Znasz n8n, ale ten moduł pokaże zaawansowane patterny agentowe.]
- [**AUTONOMOUS AGENTS**: Jak dać botowi pętlę decyzyjną (np. CrewAI) do bardziej skomplikowanych napraw, co jest krokiem w stronę agentic workflows.]

---

## LEARNING TRACK - PROGRESS

*Ta sekcja będzie aktualizowana podczas nauki*

### Aktualny poziom
poziom: [Architect] (0%)
ostatnia_sesja: [2025-10-24]
ostatnia_lekcja: "Nie rozpoczęto jeszcze"
streak: 0 dni

### Ukończone moduły
- ☐ AI BASICS (0%)
- ☐ PROMPT ENGINEERING (0%)
- ☐ VIBE CODING (0%)
- ☐ RESEARCH & INTELLIGENCE (0%)
- ☑ CODING AGENTS (0%)
- ☑ n8n ORCHESTRATION (0%)
- ☑ AUTONOMOUS AGENTS (0%)
- ☐ API & RAG (0%)
- ☐ MULTI-AGENT (0%)
- ☐ PRODUCTION AI (0%)
- ☐ CREATIVE SUITE (0%)
- ☐ BUSINESS TRANSFORMATION (0%)

### Projekty learning
*Projekty edukacyjne pojawią się tutaj podczas nauki*

---

## CREATOR TRACK - PROGRESS

*Ta sekcja będzie aktualizowana podczas tworzenia*

### Portfolio
projekty_completed: 0
ostatnia_sesja: [2025-10-24]
ostatni_research: "Nie rozpoczęto jeszcze"
ostatni_build: "Nie rozpoczęto jeszcze"

### Tools Researched (30-min scouts)
*Narzędzia będą dodawane podczas scouting sessions*

### Portfolio Projects
*Projekty portfolio pojawią się tutaj*
- [☐] **PROJEKT 3M:** K8s Remediation Bot (v0.1)

### Content Generated
- Posts: 0
- Case studies: 0
- Tutorials: 0

---

## COMBINED STATS

total_time: 0h
- learning: 0h
- creating: 0h

total_projects: 0
- learning: 0
- portfolio: 0

streak: 0 dni
