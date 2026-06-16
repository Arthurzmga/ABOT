# ABOT — Site Informativo

Site informativo do projeto **ABOT (Algorithm Bot)**, desenvolvido como entrega da disciplina de Engenharia de Software na UniCesumar (2026).

---

## 🔗 Acesso

**Página publicada:** `https://Arthurzmga.github.io/ABOT/`

---

## 📖 Sobre o projeto

O **ABOT** é uma proposta de automação baseada em bots inteligentes que verificariam, dentro das próprias plataformas digitais (Instagram, TikTok, YouTube, Facebook Ads, entre outras), se um conteúdo ou anúncio está realmente visível ao público — e organizariam esses dados em relatórios simples, sem exigir conhecimento técnico do usuário.

Este site **não é um serviço em operação**. Ele foi construído para apresentar o conceito, a arquitetura técnica proposta e as integrações planejadas com APIs reais de cada plataforma, de forma visual e interativa.

O projeto parte do Modelo de Negócio Canvas desenvolvido na disciplina de Mentalidade Criativa e Empreendedora e aprofunda a proposta sob a perspectiva de Engenharia de Software — descrevendo como a solução seria arquitetada, quais APIs seriam consumidas e como os dados seriam coletados, normalizados e apresentados.

---

## 📁 Estrutura do repositório

```
.
├── index.html                           # Site informativo (HTML + CSS + JS, arquivo único)
├── docs/
│   └── Arquitetura_Site_Documento.docx  # Documentação técnica: código comentado e decisões
└── README.md
```

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 semântico | Estrutura da página (`<header>`, `<main>`, `<section>`, `<footer>`) |
| CSS3 com custom properties | Sistema de tema via variáveis em `:root`, layout em grid, responsividade |
| JavaScript ES6+ | Interatividade: diagrama clicável, sistema de abas, suporte a teclado |
| Google Fonts (CDN) | Tipografia: Unbounded (títulos), Sora (corpo), JetBrains Mono (dados/código) |
| GitHub Pages | Hospedagem estática gratuita, deploy automático via push |

---

## 💻 Como rodar localmente

Não há dependências nem etapa de build. Basta clonar e abrir:

```bash
git clone https://github.com/Arthurzmga/ABOT.git
cd ABOT
```

Então abra o arquivo `index.html` diretamente no navegador, **ou** sirva com um servidor local:

```bash
# Python 3
python3 -m http.server 8000
# acesse: http://localhost:8000
```

---

## 🌐 Como publicar no GitHub Pages

1. Acesse o repositório no GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, selecione o branch `main` e a pasta `/ (root)`
4. Clique em **Save**
5. Aguarde alguns minutos — a URL pública será gerada automaticamente

---

## 👥 Equipe

| Nome | Instituição |
|---|---|
| Arthur Ferreira dos Santos | UniCesumar — Engenharia de Software, 2026 |
| Nickolay A J Dias | UniCesumar — Engenharia de Software, 2026 |
| Gianlucca Barraco Pimentel | UniCesumar — Engenharia de Software, 2026 |
| Vinicyus Eduardo Vicentini Faria | UniCesumar — Engenharia de Software, 2026 |

**Disciplina:** FRONT END  
**Professor:** Dacio Fernando Machado Francisco