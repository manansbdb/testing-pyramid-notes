<p align="center">
  <img src="docs/banner.svg" alt="Testing Pyramid Notes banner" width="100%" />
</p>

<h1 align="center">testing-pyramid-notes</h1>

<p align="center">
  <strong>EN</strong> Testing pyramid guide + practical tips<br/>
  <strong>PT</strong> Guia da pirâmide de testes + dicas práticas
</p>

<p align="center">
  <a href="https://github.com/manansbdb/testing-pyramid-notes/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-testing-22c55e?style=for-the-badge" alt="testing" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| A clear **testing pyramid** overview and practical tips for balancing unit / integration / E2E. | Uma visão clara da **pirâmide de testes** e dicas para equilibrar unit / integração / E2E. |
| Share with teams when deciding where to invest automation. | Partilha com a equipa ao decidir onde investir em automação. |

```mermaid
flowchart TB
  E["🔺 E2E few"] --> I["🔷 Integration"]
  I --> U["🟩 Unit many"]
  style E fill:#ef4444,stroke:#b91c1c,color:#fff
  style I fill:#f59e0b,stroke:#b45309,color:#fff
  style U fill:#16a34a,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/testing-pyramid-notes.git
cd testing-pyramid-notes
```

### 2) Copy / Copia

```bash
mkdir -p docs/testing
cp pyramid.md docs/testing/
cp practical-tips.md docs/testing/
```

### Requirements / Requisitos

- `git`
- No runtime dependencies

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/testing-pyramid-notes.git
# open pyramid.md + practical-tips.md in your next test-strategy meeting
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `pyramid.md` | Pyramid overview |
| `practical-tips.md` | Day-to-day tips |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
testing-pyramid-notes/
├── docs/banner.svg
├── pyramid.md
├── practical-tips.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
