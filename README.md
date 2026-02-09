# ai-state-cockpit


# ES/EN — AI Decision State Cockpit (Streamlit)

**Demo (Streamlit):** (pega aquí el enlace tras desplegar)  
**Repo (GitHub):** (pega aquí el enlace del repo)

---

## ES — ¿Qué es esto?
Proyecto “CV-ready” que demuestra **formulación de problemas de IA** con el marco **S, A, T, G, C, R** y su traducción a un producto en **Streamlit**.

Enfoque (lo que le importa a negocio y a recruiters):
- **Estados explícitos** (S) y acciones (A)
- **Restricciones hard vs soft** (R) y trazabilidad
- **Transición** (T) y explicación ejecutiva
- Datos sintéticos pequeños (sin PII)

### Casos
- **Caso A — Logística:** ruteo con ventanas + penalización por tardanza  
- **Caso B — Fraude:** approve/review/block con *velocity features* (Markov resúmenes)  
- **Caso C — Reposición:** pedido con MOQ/múltiplos + coste esperado  

> Nota: score/forecast son “demo” deterministas. Siguiente paso: enchufar modelos entrenados.

---

## EN — What is this?
A “CV-ready” project showcasing **AI problem formulation** using **S, A, T, G, C, R** and translating it into a **Streamlit** product.

Focus (what recruiters care about):
- **Explicit states** (S) and actions (A)
- **Hard vs soft constraints** (R) and traceability
- **Transitions** (T) and executive explanations
- Small synthetic data (no PII)

### Cases
- **Case A — Logistics:** routing with time windows + lateness penalty  
- **Case B — Fraud:** approve/review/block with *velocity features* (Markov summaries)  
- **Case C — Replenishment:** order decisions with MOQ/multiples + expected cost  

> Note: score/forecast are deterministic demo functions. Next step: plug in trained models.

---

## Quickstart (local)
```bash
pip install -r requirements.txt
streamlit run app.py
