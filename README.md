# Project Nox · Extensões de Anime

Repositório oficial de distribuição e catálogo compilado de extensões de anime e streaming do **Project Nox** para **Aniyomi e forks**.

---

## 🎯 Para quem é este repositório?

Este repositório é voltado para **usuários e espectadores** que desejam assistir animes, animações, filmes e séries diretamente em seus dispositivos Android através do ecossistema **Aniyomi e forks**.

> [!NOTE]
> Se você procura o **código-fonte em Kotlin**, extractors de vídeo ou deseja contribuir tecnicamente com correções e novos parsers, acesse o repositório de desenvolvimento:  
> ➡️ [**Project Nox · Código-fonte das Extensões de Anime**](https://github.com/Awerkori/anime-fonte-extensoes)

---

## 📲 Como Adicionar ao Aniyomi e forks

### Método 1: Instalação Automática (Recomendado)
Toque no link abaixo a partir do navegador do seu celular Android para registrar o catálogo diretamente no aplicativo:

👉 [**Adicionar Repositório Automaticamente**](aniyomi://add-repo?url=https%3A%2F%2Fraw.githubusercontent.com%2FAwerkori%2Fanime-extensoes%2Frepo%2Findex.min.json)

---

### Método 2: Instalação Manual

1. No seu aplicativo (**Aniyomi e forks**), acesse **Configurações** → **Navegar** → **Repositórios de extensões de anime**.
2. Toque no botão de adicionar (`+`).
3. Cole a URL do catálogo oficial:

```
https://raw.githubusercontent.com/Awerkori/anime-extensoes/repo/index.min.json
```

---

### Método 3: Download Direto de APKs
Caso deseje instalar manualmente um APK de extensão de anime:
- Navegue pela pasta [`apk/`](apk/) nesta branch ou verifique a lista de releases para transferir e instalar o pacote diretamente no dispositivo.

---

## ⚙️ Como Funciona este Repositório

- **Distribuição de Binários Assinados:** Cada APK nesta branch é compilado e assinado digitalmente a partir do repositório [`anime-fonte-extensoes`](https://github.com/Awerkori/anime-fonte-extensoes).
- **Índice Dinâmico (`index.min.json`):** Mantém metadados de versões, ícones, hashes e URLs de download consumidos pelo gerenciador de extensões de **Aniyomi e forks**.
- **Extractors Atualizados:** As extensões contam com extractors embutidos para contornar players instáveis, proteger streams HLS/M3U8 e fornecer resoluções selecionáveis (720p, 1080p, etc.).

---

## 🛠️ Suporte e Pedidos de Extensões

Encontrou uma extensão de anime fora do ar, player que parou de reproduzir ou deseja sugerir uma nova fonte?

- 🎫 **Abrir solicitação oficial:** [Project Nox · Central de Pedidos](https://github.com/Awerkori/project-nox-requests)
- 📊 **Acompanhar status em tempo real:** [Project Nox · Tracker](https://awerkori.github.io/project-nox-tracker/)

---

## 🔗 Projetos Relacionados

- 🎬 [**Project Nox · Código-fonte das Extensões de Anime**](https://github.com/Awerkori/anime-fonte-extensoes) — Código-fonte e extractors de vídeo.
- 📦 [**Project Nox · Extensões de Mangá**](https://github.com/Awerkori/manga-extensoes) — Catálogo de extensões de mangá para Mihon e forks.
- 💻 [**Project Nox · Código-fonte das Extensões de Mangá**](https://github.com/Awerkori/manga-fonte-extensoes) — Código-fonte das extensões de leitura.
- 🌐 [**Project Nox · Plataforma Web de Mangá**](https://github.com/Awerkori/project-nox-manga) — Plataforma web oficial de leitura.

---

## 🌟 Créditos e Reconhecimento

- **Felipe GFA** ([@FelipeGFA](https://github.com/FelipeGFA)): Pela migração estrutural, suporte de fontes essenciais em língua portuguesa e arquitetura do pipeline de extensões de anime.
- **Yūzōnō** ([@yuzono](https://github.com/yuzono)) e equipe **Aniyomi** ([@aniyomiorg](https://github.com/aniyomiorg)): Pela concepção da API de vídeo e base upstream do ecossistema de streaming.
- Comunidade de desenvolvedores e colaboradores independentes.

---

## ⚖️ Isenção de Responsabilidade

O **Project Nox** desenvolve e disponibiliza ferramentas de software livre para interoperabilidade técnica. Não hospedamos, gerenciamos, modificamos nem retransmitimos arquivos de vídeo em servidores próprios. Todo o conteúdo audiovisual acessado via extensões provém de servidores e portais públicos de terceiros.
