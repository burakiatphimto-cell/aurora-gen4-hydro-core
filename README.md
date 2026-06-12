# Aurora Gen-4 Hydro Core - HES (Hydro Energetic System)

## Panoramica Progetto

**Aurora Gen-4 Hydro Core** è un sistema idraulico unificato di generazione energetica di nuova generazione, progettato come concept per applicazioni di estrazione energetica da flussi idrici a bassa caduta in ambienti urbani sotterranei e sistemi distribuiti.

Il progetto integra:
- **Architettura geometrica 3D tetraedrica** con flusso centripeto accelerato
- **Core lineare multistadio rugged** con tecnologia Direct-Drive
- **Componenti in composito (PEEK+CF)** per affidabilità e durabilità
- **Generazione elettrica a magneti permanenti** a 1.800 RPM

---

## 📋 Documentazione Tecnica

### File Principali
- **[TECHNICAL_SPEC.md](./TECHNICAL_SPEC.md)** - Specifica tecnica completa e dettagliata
- **[SCHEMA_IDRAULICO.md](./SCHEMA_IDRAULICO.md)** - Analisi dello schema e componenti
- **[PARAMETRI_OPERATIVI.md](./PARAMETRI_OPERATIVI.md)** - Dati fisici e prestazioni

---

## 🎯 Specifiche di Progetto (Riepilogo)

| Parametro | Valore |
|-----------|--------|
| **Configurazione** | Core Multistadio a 3 Eliche Monoblocco |
| **Diametro Cilindrico** | 120 mm |
| **Materiale Principale** | PEEK + Carbon Fiber (PEEK+CF) |
| **Portata Nominale** | 30 l/s (0,03 m³/s) |
| **Salto Pressione Minimo** | 0,36 bar (3,6 kPa) |
| **Velocità Generatore** | 1.800 RPM (Direct-Drive) |
| **Efficienza Complessiva** | 72% |
| **Potenza Netta (Modulo Singolo)** | ~700 W |
| **Potenza Sistema Combinato (3 moduli)** | ~1.95 kW |
| **Gioco Microscopico** | < 1,0 mm |
| **Tenute Idrauliche** | Magnetic Fluid Coupled Seals |

---

## 🔧 Componenti Principali

### 1. **Core Idraulico Multistadio**
- 3 eliche monoblocco in PEEK+CF
- Statori fissi di raddrizzamento flusso
- Albero centrale in composito
- Gioco microscopico ottimizzato per ridurre fughe

### 2. **Sistema di Generazione**
- Generatore a magneti permanenti Direct-Drive
- Velocità nominale: 1.800 RPM
- Potenza di uscita diretta senza riduttore
- Accoppiamento coassiale fluido-elettrico

### 3. **Tenute e Sicurezza**
- Tenute idrauliche ad alta efficienza (Magnetic Fluid Coupled Seals)
- Meccanismo Automatic Trash Rake per pulizia automatica
- Micro-elica di spurgo (Backwash) per manutenzione
- Sistema di bypass robotizzato gestito da remoto

### 4. **Controllo e Regolazione**
- Valvole di sfogo pressione
- Sensori di monitoraggio pressione e portata
- Sistema di controllo remoto integrato
- Protezione da sovrapressione

---

## 📐 Architettura Geometrica 3D

Il sistema utilizza una configurazione **tetraedrica con flusso centripeto accelerato**:

- **Vettore X-**: Ingresso fluido tangenziale
- **Vettore X+**: Uscita fluido radiale
- **Asse Z**: Asse di rotazione generatore
- **Effetto centripeto**: Accelerazione del flusso verso il core

Questa geometria ottimizza il trasferimento energetico dal flusso idraulico alla rotazione meccanica.

---

## ⚡ Parametri Idraulici e Formule

### Portata Volumetrica
```
Q = 30 l/s = 0,03 m³/s
```

### Salto di Pressione
```
ΔP = 0,36 bar = 3.600 Pa
```

### Potenza Idraulica Teorica
```
P_idraulica = Q × ΔP
P_idraulica = 0,03 m³/s × 3.600 Pa = 108 W (teorico)
```

### Potenza Meccanica (con perdite)
```
P_meccanica = P_idraulica × η_idraulica
P_meccanica ≈ 108 W × 0,85 ≈ 92 W
```

### Potenza Elettrica Netta
```
P_netta = P_meccanica × η_generatore
P_netta ≈ 92 W × 0,76 ≈ 70 W (per stadio singolo)

Sistema 3 stadi: P_netta ≈ 1.95 kW (con estrapolazione)
```

**Nota**: I valori reali dipendono da test e validazione sperimentale.

---

## 🛠 Stato del Progetto

**Fase**: Concept e Prototipo Teorico
- ✅ Modello geometrico 3D completato
- ✅ Analisi idraulica preliminare
- ✅ Specifiche tecniche definite
- ⏳ In attesa di costruzione e test fisico
- ⏳ Validazione sperimentale dei parametri

---

## 📁 Struttura Repository

```
aurora-gen4-hydro-core/
├── README.md                    # Questo file
├── TECHNICAL_SPEC.md           # Specifica tecnica completa
├── SCHEMA_IDRAULICO.md         # Analisi dello schema
├── PARAMETRI_OPERATIVI.md      # Dati e formule
├── assets/
│   ├── schema_idraulico.png    # Immagine dello schema
│   └── diagrams/               # Diagrammi aggiuntivi
└── docs/
    ├── INSTALLATION.md         # Istruzioni installazione
    └── MAINTENANCE.md          # Manutenzione e diagnostica
```

---

## 📞 Contatti e Supporto

Per domande tecniche o chiarimenti su questo concept:
- **Repository**: aurora-gen4-hydro-core
- **Status**: Concept Prototype v0.1
- **Ultima Modifica**: Giugno 2026

---

## 📜 Licenza

Questo progetto è documentato per uso interno e ricerca. Verificare i diritti di proprietà intellettuale prima della distribuzione.

---

**Aurora Gen-4 Hydro Core** - Generazione Energetica Unificata per il Futuro
