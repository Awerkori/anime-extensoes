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

## ⚖️ Licença e Copyright

Este catálogo de distribuição e os pacotes binários compilados são disponibilizados sob os termos da **GNU Affero General Public License versão 3.0** (`AGPL-3.0-only`). Consulte o arquivo [LICENSE](LICENSE) para obter o texto integral inalterado da licença e o arquivo [NOTICE](NOTICE) para o inventário de autoria e termos legais.

```
Copyright (C) Felipe GFA
Copyright (C) Yūzōnō Contributors & Aniyomi Contributors
Copyright (C) 2026 Project Nox Contributors & Awerkori
```

### 📦 Código-Fonte Correspondente e Rastreabilidade (AGPLv3 Seção 6)
Em cumprimento à Seção 6 da GNU AGPLv3, o código-fonte correspondente a todos os APKs de anime distribuídos neste repositório está publicamente disponível em:  
➡️ [**Project Nox · Código-fonte das Extensões de Anime**](https://github.com/Awerkori/anime-fonte-extensoes)

- **Instruções e Receitas de Compilação:** Os scripts Gradle, configurações de build e pipelines de automação estão mantidos de forma auditável e transparente no repositório de desenvolvimento irmão.
- **Rastreabilidade e Integridade:** Cada pacote possui identificador único (`pkg`), versão (`version`), código de versão (`code`) e mapeamento no catálogo serializado `index.min.json`, com os binários compilados `.apk` correspondentes preservados no diretório [`apk/`](apk/).
- **Ressalva de Proveniência Forense:** Extensões mantidas ativamente pelo Project Nox contam com rastreabilidade completa entre código-fonte, scripts e binários. Para os pacotes históricos incorporados do ecossistema upstream Yūzōnō / Aniyomi, a rastreabilidade é assegurada por pacote, versão e árvore de código upstream, não se declarando rastreabilidade universal a commits individuais para binários pré-existentes sem evidência histórica direta.
- **Componentes de Terceiros e Apache 2.0:** O catálogo preserva integralmente o regime de licenciamento da Apache License 2.0 dos componentes upstream derivados, sendo as contribuições originais do Project Nox licenciadas sob a GNU AGPL versão 3.0.

### 🌐 Política Oficial de Distribuição
- **Gratuidade Oficial:** O Project Nox distribui oficialmente todos os seus APKs e catálogos de streaming de forma 100% gratuita para a comunidade.
- **Redistribuição Comunitária:** Incentivamos o compartilhamento comunitário e o espelhamento livre dos pacotes, sempre respeitando os créditos de autoria e os termos das licenças.
- **Liberdades sob a AGPL 3.0:** Em estrita conformidade com a GNU AGPLv3 (e Apache 2.0), não é imposta nenhuma cláusula proibindo redistribuição comercial por terceiros. A gratuidade oficial é prática direta do Project Nox, preservando integralmente os direitos legais de redistribuição garantidos pela licença.

### 📌 Interação Remota de Rede (GNU AGPLv3 Seção 13)
O Project Nox adota oficialmente a licença **GNU AGPL versão 3.0**. Nos termos da Seção 13 da AGPLv3, serviços ou catálogos executados em rede com interação remota de usuários devem disponibilizar o Código-Fonte Correspondente da aplicação em execução sem cobrança.

### 🛡️ Proteção de Identidade e Marca (AGPLv3 Seção 7(e))
A concessão da licença de software livre refere-se estritamente ao código e aos binários. Ela **não concede** autorização ou licença de uso da marca, do nome "Project Nox" ou de logotipos oficiais para insinuar endosso, homologação ou representação oficial do projeto sem consentimento prévio por escrito.

### ⚖️ Isenção de Responsabilidade
O **Project Nox** desenvolve e disponibiliza ferramentas de software livre exclusivamente para fins de interoperabilidade técnica. Não hospedamos, gerenciamos, modificamos nem retransmitimos arquivos audiovisuais em servidores próprios. Todo o conteúdo acessado via extensões provém diretamente de portais públicos externos.
