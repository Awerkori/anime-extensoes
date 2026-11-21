<p align="center">
  <img src="https://raw.githubusercontent.com/ProjectNox-org/.github/main/assets/brand/nox-emblem.webp" alt="Emblema oficial do Project Nox" width="96" />
</p>

<h1 align="center">Project Nox · Extensões de Anime</h1>

<p align="center">
  Catálogo oficial de extensões de anime para <strong>Aniyomi, Anikku e aplicativos compatíveis</strong>.
</p>

<p align="center">
  <strong>Distribuição oficial 100% gratuita</strong> · Não pague por instalações ou atualizações oferecidas como serviço oficial do projeto.
</p>

## Como instalar

### Opção 1: Instalação automática (Android)

O GitHub bloqueia links que abrem aplicativos diretamente a partir do README. Para adicionar o catálogo com um toque pelo navegador do seu celular Android, acesse a página oficial de instalação:

[**Adicionar catálogo ao Aniyomi pelo portal oficial**](https://projectnox-org.github.io/extensoes/#aniyomi)

Se o aplicativo não abrir automaticamente ou o seu fork não reconhecer o link, use a instalação manual abaixo.

### Opção 2: Instalação manual (copiar e colar)

1. Abra o **Aniyomi** (ou fork compatível, como **Anikku**) e vá em **Mais** → **Configurações** → **Navegar** → **Repositórios de extensões de anime** *(em alguns forks, a opção aparece como **Repositórios de extensões**)*.
2. Toque em **Adicionar** (`+`).
3. Copie e cole o endereço abaixo:

```text
https://raw.githubusercontent.com/ProjectNox-org/anime-extensoes/repo/index.pb
```

4. Confirme e volte à aba **Navegar** → **Extensões de anime** para instalar as fontes desejadas.

<details>
<summary>Meu aplicativo deu erro ao importar <code>index.pb</code> (formatos JSON para clientes antigos ou forks)</summary>

O arquivo `index.pb` (Protobuf) é o padrão atual. Caso seu aplicativo seja antigo ou exija JSON, use uma das URLs abaixo (mantidas sincronizadas automaticamente):

- **JSON compacto** *(também usado no link automático `aniyomi://`)*:
  ```text
  https://raw.githubusercontent.com/ProjectNox-org/anime-extensoes/repo/index.min.json
  ```
- **JSON completo**:
  ```text
  https://raw.githubusercontent.com/ProjectNox-org/anime-extensoes/repo/index.json
  ```

</details>

<details>
<summary>Alternativa: baixar o APK de uma extensão individual</summary>

Um `.apk` de extensão adiciona apenas uma fonte específica sem precisar registrar o catálogo inteiro. Para utilizá-lo, já é necessário ter o **Aniyomi**, **Anikku** ou fork compatível instalado no Android — instalar apenas a extensão não cria um aplicativo de vídeo independente.

- Navegue diretamente pelos pacotes oficiais na pasta [`apk/`](apk/) desta branch (`repo`).

</details>

## O que são as extensões?

- **O catálogo é apenas a lista de fontes:** adicionar o repositório permite que o aplicativo encontre as extensões do Project Nox, mas não instala nenhuma fonte automaticamente.
- **Você escolhe o que instalar:** após adicionar o catálogo, abra a aba **Extensões de anime** no aplicativo, procure os sites desejados e toque em instalar.
- **Reprodução de vídeo:** as extensões conectam o aplicativo a sites públicos externos e incluem extractors atualizados para lidar com players e streams HLS/M3U8.

## Atualizações e migração

Novas versões das extensões e adições ao catálogo aparecem diretamente na aba de extensões do aplicativo sempre que você atualizar a lista.

<details>
<summary>Já utilizava o repositório antigo (<code>Awerkori</code>)?</summary>

Os endereços antigos sob `Awerkori/anime-extensoes` continuam ativos via redirecionamento do GitHub e as assinaturas dos APKs não foram alteradas.

Para migrar para a URL oficial da organização no Aniyomi:

1. **Adicione o repositório `ProjectNox-org` antes de remover o antigo.**
2. Caso alguma extensão apareça como *Obsoleta*, reinicie o aplicativo: o Aniyomi marca extensões como obsoletas quando ficam temporariamente ausentes da lista e limpa esse estado ao recarregar na inicialização — não se trata de erro de assinatura nem exige reinstalação.

</details>

## Suporte

Encontrou uma extensão fora do ar, erro no player ou quer sugerir uma nova fonte?

- **Central de Pedidos ([`project-nox-requests`](https://github.com/ProjectNox-org/project-nox-requests)):** abrir pedidos de novas extensões e relatar problemas.
- **Tracker ([Project Nox Tracker](https://projectnox-org.github.io/project-nox-tracker/)):** consultar e acompanhar o status das solicitações.

## Informações técnicas

- **Código-fonte e compilação:** cada APK na pasta [`apk/`](apk/) desta branch (`repo`) é compilado e assinado digitalmente com chaves consistentes a partir de [`anime-fonte-extensoes`](https://github.com/ProjectNox-org/anime-fonte-extensoes).
- **Catálogos e metadados:** [`index.pb`](https://raw.githubusercontent.com/ProjectNox-org/anime-extensoes/repo/index.pb) segue o esquema Protobuf v2 oficial do Aniyomi (incluindo `isTorrent` e `sources`), com [`index.json`](https://raw.githubusercontent.com/ProjectNox-org/anime-extensoes/repo/index.json) e [`index.min.json`](https://raw.githubusercontent.com/ProjectNox-org/anime-extensoes/repo/index.min.json) mantidos sincronizados para clientes legados. [`repo.json`](https://raw.githubusercontent.com/ProjectNox-org/anime-extensoes/repo/repo.json) armazena identidade, chave de assinatura e aponta para `index.pb` via `index_v2`.

## Projetos relacionados

- [**Project Nox · Código-fonte das Extensões de Anime**](https://github.com/ProjectNox-org/anime-fonte-extensoes) — Código-fonte, extractors de vídeo e automação de build.
- [**Project Nox · Extensões de Mangá**](https://github.com/ProjectNox-org/manga-extensoes) — Catálogo oficial de extensões de mangá para Mihon e forks.
- [**Project Nox · Código-fonte das Extensões de Mangá**](https://github.com/ProjectNox-org/manga-fonte-extensoes) — Código-fonte das extensões de mangá.

## Créditos

- **Felipe GFA** ([@FelipeGFA](https://github.com/FelipeGFA)): migração estrutural, suporte a fontes essenciais em português e arquitetura do pipeline de extensões de anime.
- **Alex** ([@Alex17273747576777](https://github.com/Alex17273747576777)): proposta inicial do catálogo Protobuf de anime, adaptada para usar o esquema oficial do Aniyomi.
- **Yūzōnō** ([@yuzono](https://github.com/yuzono)) e **Aniyomi** ([@aniyomiorg](https://github.com/aniyomiorg)): concepção da API de vídeo, infraestrutura e base upstream do ecossistema.
- **Tachiyomi / Keiyoushi / Javier Tomás** e demais colaboradores históricos do ecossistema open-source e do Project Nox.

## Licenciamento e informações legais

- **Código-fonte correspondente (AGPLv3, Seção 6):** o código-fonte, receitas Gradle e workflows dos APKs distribuídos aqui estão disponíveis em [`ProjectNox-org/anime-fonte-extensoes`](https://github.com/ProjectNox-org/anime-fonte-extensoes). Extensões mantidas ativamente pelo Project Nox possuem rastreabilidade entre código, scripts e binários em [`apk/`](apk/); pacotes históricos incorporados de Yūzōnō / Aniyomi mantêm rastreabilidade por pacote, versão e árvore upstream, sem declarar rastreabilidade universal a commits individuais para binários legados sem evidência direta.
- **Licença dos pacotes e do catálogo:** contribuições originais do Project Nox e a organização do catálogo combinado seguem a **GNU Affero General Public License v3.0** (`AGPL-3.0-only`, [`LICENSE`](LICENSE)). Componentes herdados de Yūzōnō, Aniyomi, Tachiyomi, Felipe GFA e demais autores mantêm integralmente seus copyrights e licenças originais (notadamente **Apache License 2.0**), sem reivindicação de exclusividade pelo Project Nox sobre código de terceiros. O regime jurídico de cada APK observa os componentes efetivamente incorporados.
- **Gratuidade e redistribuição:** o Project Nox distribui oficialmente seus catálogos e APKs de forma gratuita, preservando as liberdades de redistribuição previstas na GNU AGPLv3 e na Apache 2.0.
- **Rede, marca e isenção de responsabilidade:** nos termos da Seção 13 da AGPLv3, quem operar versão modificada com interação remota de rede deve disponibilizar o Código-Fonte Correspondente; conforme a Seção 7(e) da AGPLv3, a licença de software não autoriza usar os nomes ou marcas "Project Nox", "Awerkori" ou de terceiros para sugerir endosso oficial. O Project Nox fornece apenas software livre de integração e não hospeda nem retransmite conteúdos audiovisuais de terceiros.

Consulte [`LICENSE`](LICENSE) e [`NOTICE`](NOTICE) para o texto integral da licença e o inventário completo de atribuições.

```text
Copyright (C) Felipe GFA
Copyright (C) Yūzōnō Contributors & Aniyomi Contributors
Copyright (C) 2026 Project Nox Contributors & Awerkori
```
