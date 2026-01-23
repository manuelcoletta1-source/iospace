# IOSPACE
## Infrastruttura di Operatività e Spazio di Interazione

**IOSPACE** è un modulo infrastrutturale dell’ecosistema **Hermeticum B.C.E.**
progettato per gestire **spazi operativi coerenti e governati** in cui
operatori, processi e sistemi interagiscono con **IPR**, **policy** e
componenti di scambio/interop.

IOSPACE non è un servizio applicativo finale.
È un’infrastruttura di **contesto operativo verificabile**:
definisce come, quando e in quali spazi si possono svolgere operazioni
associabili a un Identity Primary Record (IPR), rispettando
policy, livelli di conformità e vincoli tecnici.

---

## Funzione

IOSPACE serve a:

- definire **spazi operativi governati**
- integrare IPR con ambienti di esecuzione
- garantire **tracciabilità contestuale**
- abilitare audit dell’ambiente di esecuzione
- assicurare applicazione coerente di
  policy, conformità e vincoli UNEBDO

IOSPACE non introduce nuove regole:
**interpreta e applica** quelle esistenti in un contesto operativo strutturato.

---

## Cosa fa / Cosa non fa

**Fa**
- definisce spazi operativi strutturati
- integra policy UNEBDO nei workflow
- supporta contesto IPR-native di esecuzione
- rende opponibile la relazione tra operatore e spazio
- abilita interoperabilità tecnica tra moduli

**Non fa**
- definizione identità (→ IPR-CORE)
- custodia documenti (→ IPR-VAULT)
- definizione policy (→ OPC)
- decisione ex-ante (→ IPR-GATE)
- valutazione normativa (→ IPR-COMPLY)
- orchestrazione C2 (→ GitJoker-C2)

---

## Posizione nello stack Hermeticum B.C.E.
OPC (Policy) ↓ UNEBDO (Layer 0) ↓ IPR ↓ CORE · VAULT · TRACE · GATE · COMPLY · EXCHANGE ↓ IOSPACE ↓ GitJoker-C2 / IPR-AIJOKER-C2
IOSPACE opera **solo** se:
- l’IPR è valido
- la conformità è sufficiente
- le policy UNEBDO permettono l’integrazione

In caso contrario,
**lo spazio non è attivabile**.

---

## Principi operativi

- **Contesto governato**
- **Conformità prima dell’operazione**
- **Tracciabilità del contesto**
- **Audit-by-design**
- **Fail-closed**

Se lo spazio non è verificabile,
**non si può operare**.

---

## Ambito UE

IOSPACE è progettato considerando:

- AI Act UE (governance tecnica e logging)
- NIS2 / CER (responsabilità e auditabilità)
- eIDAS / ETSI (continuità e interoperabilità)
- Horizon Europe (metodologia e maturità tecnica)

---

## Destinatari

- architetti di ecosistemi operativi
- sistemi enterprise e istituzionali
- sviluppatori di sistemi ad alto rischio
- auditor e organismi di controllo

---

## Autore

**Manuel Coletta**

---

## Sigillo editoriale

**Esoterologia Edizioni**

---

## Stato

🟢 **ATTIVO — Infrastruttura di Operatività**
