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

## ⚖️ Licenciamento e Política de Distribuição

Este catálogo de distribuição e os pacotes binários compilados são disponibilizados sob os termos da **GNU General Public License versão 3.0** (`GPL-3.0-only`). Consulte o arquivo [LICENSE](LICENSE) para obter o texto integral inalterado da licença e o arquivo [NOTICE](NOTICE) para o inventário de autoria e termos legais.

### 📦 Código-Fonte Correspondente (GPLv3 Seção 6)
Em cumprimento à Seção 6 da GNU GPLv3, o código-fonte correspondente a todos os APKs de anime distribuídos neste repositório está publicamente disponível em:  
➡️ [**Project Nox · Código-fonte das Extensões de Anime**](https://github.com/Awerkori/anime-fonte-extensoes)

As instruções de compilação, scripts de build em Gradle e extractors de vídeo estão mantidos de forma auditável e transparente no repositório de desenvolvimento irmão.

### 🌐 Política Oficial de Distribuição
- **Gratuidade Oficial:** O Project Nox distribui oficialmente todos os seus APKs e catálogos de streaming de forma 100% gratuita.
- **Redistribuição Comunitária:** Incentivamos o compartilhamento comunitário e o espelhamento livre dos pacotes, sempre respeitando os créditos de autoria e os termos das licenças.
- **Termos da GPL 3.0:** Em conformidade estrita com a GPLv3, não é incluída nenhuma cláusula contratual proibindo a cobrança pela distribuição por terceiros. A preferência comunitária por gratuidade não altera os direitos e garantias concedidos pela GNU GPLv3 e pela Apache 2.0.

### 📌 Nota sobre GPL-3.0 e AGPL-3.0
O Project Nox adota oficialmente a licença **GNU GPL versão 3.0**. Diferentemente da licença GNU AGPLv3, a GPLv3 não contém a cláusula de interação remota por rede (Seção 13 da AGPL).

### 🛡️ Autenticidade e Marca
A concessão da licença de software livre refere-se estritamente ao código e aos binários. Ela **não concede** autorização ou licença de uso da marca, do nome "Project Nox" ou de logotipos oficiais para alegar endosso ou representação oficial do projeto.

### ⚖️ Isenção de Responsabilidade
O **Project Nox** desenvolve e disponibiliza ferramentas de software livre exclusivamente para fins de interoperabilidade técnica. Não hospedamos, gerenciamos, modificamos nem retransmitimos arquivos audiovisuais em servidores próprios. Todo o conteúdo acessado via extensões provém diretamente de portais públicos externos.
