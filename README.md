# Hub de Fluxos CS/CX — Sankhya ABC Paulista (fluxograma-cscx)

Repositório do **Hub de Fluxos** do time de **CS/CX da unidade Sankhya ABC Paulista**.

A proposta é simples: **uma página única** (HTML/CSS/JS puro) que funciona como **atalho central** para:
- fluxos (GitHub Pages),
- indicadores (Google Sheets),
- apresentações (PDF/Slides),
- materiais internos (portais e links Sankhya).

> Projeto **100% front-end** (estático) — sem build, sem dependências de compilação. Ideal para GitHub Pages.

---

## 🌐 O que este projeto entrega

- **Menu lateral fixo** (rolável) com ícones e layout pensado para uso diário.
- **Campo de pesquisa** para filtrar fluxos pelo nome.
- **Submenus expansíveis** para agrupar itens (ex.: AE, Blitz NPS, Case, Hub Comercial).
- **Links diretos** para fluxos e materiais de apoio (internos e externos).
- **Hero image** centralizada (imagem Sankhya/adquiridas) para comunicação visual.

---

## 🔗 Conteúdos disponíveis no Hub (atalhos)

> A lista abaixo reflete o que está publicado no menu do `index.html` (pode crescer conforme novos fluxos forem adicionados).

### CS/CX (Processos e Indicadores)
- **Fluxo AE**
  - Fluxo (GitHub Pages)
  - Planilha: *AE - Agenda x Meta x Realizado*
- **Fluxo Blitz NPS**
  - Fluxo/launcher (GitHub Pages)
  - Indicador NPS por ano (Sheets)
  - Follow-ups pós plano (ancoras internas no fluxo)
- **Fluxo Case**
  - Fluxo (GitHub Pages)
  - Indicador de Case (Sheets)
- **Fluxo Certificação** (GitHub Pages)
- **Fluxo de Usuários Temporários** (GitHub Pages)
- **Fluxo Pendências** (GitHub Pages)
- **Fluxo Passagem de Bastão — Implantação → Base** (GitHub Pages)
- **Fluxo MRR x Churn** (GitHub Pages)
- **Status Report - CS** (Google Slides)

### Operação / Materiais
- **Fluxo Licenciamento de Empresas (OS/RevOps)** (GitHub Pages)
- **Gerente Online (GOL)** (GitHub Pages)

### Hub Comercial (atalhos de apoio)
- Links úteis (ex.: GMO, battlecards, cases, produtos, apresentações e materiais relacionados)
> Observação: alguns itens podem exigir login em domínio Sankhya.

---

## 🧱 Tecnologias utilizadas

- **HTML5** — estrutura do hub
- **CSS3** — layout (sidebar fixa, responsividade, scroll customizado)
- **JavaScript (vanilla)** — filtro de pesquisa e toggle de submenus
- **Ionicons v2** — ícones do menu

---

## 📂 Estrutura do repositório

- `index.html`  
  Página principal do Hub (menu, busca, submenus e links).
- `imagem-sankhya-adquiridas.png`  
  Imagem do hero (destaque visual no conteúdo).
- `*.pdf` / `*.pptx.pdf` (quando existirem)  
  Materiais locais referenciados por links do menu.

---

## ▶️ Como rodar localmente

### Opção A) Abrir direto no navegador
Você pode abrir o `index.html` com duplo clique.

> Dica: alguns navegadores podem restringir certos comportamentos com `file://`. Se notar algo estranho com arquivos locais, use um servidor local (Opção B).

### Opção B) Subir um servidor local (recomendado)
**Python (rápido):**
```bash
python -m http.server 5500
