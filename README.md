# AI-ML Assignment 6: Prompt Engineering for Persona Adherence  
**Author:** Ingrid Arenas Rosas  
**Model Used:** Microsoft Copilot (powered by a large language model)



##  Task Overview  
This experiment explores how different prompt engineering techniques affect the ability of a language model to retell a story in distinct personas (Yoda and Gen Z TikTok creator). The goal was to evaluate how role, format, and reasoning structure influence output quality.

---

##  Summary Table

| Prompt Type         | Persona(s) Used     | Score (1–10) | Observation |
|---------------------|---------------------|--------------|-------------|
| Baseline            | None                | 4            | Generic retelling, no style adherence |
| Role-Based Prompt   | Yoda, Gen Z         | 7            | Captures tone but lacks structure |
| Format-Based Prompt | Proverbs, Captions  | 8            | Strong stylistic clarity, punchy delivery |
| Chain-of-Thought    | Yoda, Gen Z         | 9            | Emotional arc adds depth and coherence |
| Final Optimized     | Dual Persona + CoT  | 10           | Best balance of tone, structure, and clarity |

---

##  Key Lesson Learned

Prompt structure dramatically affects LLM output quality. Combining **persona**, **format**, and **reasoning scaffolds** (like emotional arcs) leads to the most coherent, creative, and persona-faithful results. The final prompt outperformed all others by guiding the model with clear intent and constraints.
