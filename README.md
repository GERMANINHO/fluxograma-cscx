# Fluxograma CS/CX — Sankhya ABC Paulista

Repositório do **hub de fluxos interativos** dos processos de CS/CX da unidade **Sankhya ABC Paulista**.  
Aqui você encontra uma página única em **HTML/CSS/JS puro** que funciona como atalho central para todos os fluxos, planilhas e materiais de apoio do time.

A aplicação foi pensada para rodar 100% em **front-end**, podendo ser publicada facilmente via **GitHub Pages** para navegação online.

---

## 🌐 O que este projeto entrega

- **Hub de Fluxos — Sankhya** com:
  - Menu lateral fixo com ícones (Ionicons);
  - Campo de **pesquisa** para localizar fluxos pelo nome;
  - Links diretos para:
    - Fluxo AE;
    - Fluxo Blitz NPS (e indicador NPS);
    - Fluxo Case (e indicador de Case);
    - Fluxo Certificação;
    - Fluxo de Usuários Temporários;
    - Fluxo Eventos (rótulo organizador);
    - Indicadores da Campanha de Consultor/Coordenador de CS;
    - Fluxo de Licenciamento de Empresas (OS/RevOps);
    - Fluxo Passagem de Bastão — Implantação > Base;
    - Fluxo Pendências (triagem, agenda, FUP).
- **Hero image** centralizada para comunicação visual (logo Sankhya e adquiridas).
- Layout responsivo com barra lateral rolável, pensado para uso diário do time de CS/CX.

---

## 🧱 Tecnologias utilizadas

- **HTML5** — estrutura da página;
- **CSS3** — layout (sidebar fixa, conteúdo centralizado, scroll customizado);
- **JavaScript vanilla** — lógica de:
  - Filtro de pesquisa no menu lateral;
  - Abertura/fechamento de submenus (por exemplo, Blitz NPS e Case);
- **Ionicons v2** — ícones no menu lateral.

Não há dependências de build (Webpack, Vite etc.): é um projeto **estático**, ideal para GitHub Pages.

---

## 📂 Estrutura básica

Os arquivos principais deste repositório são:

- `index.html`  
  Página principal do **Hub de Fluxos — Sankhya**, contendo:
  - Sidebar de navegação;
  - Campo de pesquisa;
  - Links para os fluxos externos (outros GitHub Pages e planilhas);
  - Script JS embutido para filtro e toggle dos submenus.
- `imagem-sankhya-adquiridas.png`  
  Imagem utilizada como destaque visual na área principal (hero).

> Caso você adicione novos fluxos, basta criar o link correspondente na sidebar do `index.html` e, se necessário, incluí-los também na busca.

---

## ▶️ Como rodar localmente

1. **Clone** o repositório:

   ```bash
   git clone https://github.com/<seu-usuario>/fluxograma-cscx.git
   cd fluxograma-cscx
