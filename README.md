# After Lapsus

Landing page institucional responsiva para o estúdio indie de jogos **After Lapsus**, com foco visual em terror, RPG e sobrevivência.

Site publicado via GitHub Pages:

https://devmarcosalexandreti-tech.github.io/Projeto-Site-After-Lapsus/

## Descrição

O projeto apresenta uma página institucional estática para divulgar o estúdio After Lapsus, seus jogos, canais sociais e formas de contato.

O site resolve a necessidade de ter uma presença pública simples, visualmente consistente e acessível pelo navegador, sem exigir backend ou processo de build.

Principais funcionalidades identificadas:

- Hero section com slider automático de imagens.
- Header com logo e links para redes/plataformas.
- Seção de projeto em destaque com thumbnail e link externo para vídeo no YouTube.
- Seção institucional sobre o estúdio.
- Portfólio com cards de jogos e efeito de revelação de informações no hover/focus.
- Links externos para páginas dos jogos e redes sociais.
- Formulário visual de contato preparado para integração futura.
- Footer responsivo com logo, redes sociais e copyright.
- Layout responsivo para desktop e mobile.

## Tecnologias

Tecnologias identificadas no código-fonte:

- HTML5
- CSS3
- JavaScript puro
- Markdown
- GitHub Pages
- Google Fonts
- Git

Não foram identificados:

- Flutter
- Dart
- Node.js
- React
- Vue
- Angular
- Firebase
- REST API própria
- Banco de dados
- Gerenciador de estado
- Gerenciador de pacotes

## Arquitetura

O projeto segue uma arquitetura simples de **site estático**, organizada por responsabilidade de arquivo:

- `index.html`: estrutura semântica da página.
- `css/style.css`: estilos globais, componentes visuais, responsividade e animações CSS.
- `js/script.js`: estrutura inicial para futuras interações.
- `assets/`: imagens e ícones usados na interface.

Não há arquitetura MVC, MVVM, Clean Architecture ou feature-first identificada, pois o projeto não é uma aplicação com camadas de domínio, dados e apresentação. A organização atual é adequada para uma landing page estática.

## Estrutura do Projeto

```text
.
├── .nojekyll
├── README.md
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── assets/
    ├── icons/
    │   ├── bluesky.svg
    │   ├── discord.svg
    │   ├── instagram.svg
    │   ├── steam.svg
    │   ├── tiktok.svg
    │   ├── twitter-x.svg
    │   ├── youtube.svg
    │   └── Youtube.png
    └── images/
        ├── after-lapsus-em-breve.png
        ├── image1.jpg
        ├── image2.jpg
        ├── image3.jpg
        ├── logoafterlapsus.png
        ├── thumbnailmedo.jpg
        └── thumbnailzozo.jpg
```

Finalidade das principais pastas:

- `css/`: contém a folha de estilos principal do site.
- `js/`: contém o JavaScript inicial, preparado para interações futuras.
- `assets/images/`: contém logotipo, imagens da hero section e thumbnails dos cards.
- `assets/icons/`: contém ícones das redes sociais e plataformas.

## Requisitos

Para executar localmente:

- Navegador moderno.
- A definir: versão mínima de navegador suportada.

Opcional para servir o projeto localmente:

- Python 3, caso utilize `python -m http.server`.

Não foram encontrados requisitos para:

- Flutter SDK
- Dart SDK
- Android Studio
- Java
- Node.js
- npm
- Gradle

## Como Executar

### 1. Clonar o repositório

```bash
git clone https://github.com/devmarcosalexandreti-tech/Projeto-Site-After-Lapsus.git
```

```bash
cd Projeto-Site-After-Lapsus
```

### 2. Instalar dependências

Não há dependências para instalar. O projeto não possui `package.json`, `pubspec.yaml`, `build.gradle` ou arquivo equivalente de gerenciamento de pacotes.

### 3. Executar localmente

Opção 1: abrir o arquivo diretamente no navegador:

```text
index.html
```

Opção 2: servir com Python:

```bash
python -m http.server 5500
```

Depois acesse:

```text
http://localhost:5500
```

Para testar em outro dispositivo na mesma rede, use o IP local da máquina:

```text
http://SEU_IP_LOCAL:5500
```

### 4. Gerar APK

Não aplicável. Este projeto é um site estático, não um aplicativo Android.

### 5. Gerar AppBundle

Não aplicável. Este projeto é um site estático, não um aplicativo Android.

## Configuração

Configurações identificadas:

- `.nojekyll`: instrui o GitHub Pages a publicar o projeto como site estático sem processamento via Jekyll.
- Google Fonts: a fonte Montserrat é carregada no `index.html`.
- GitHub Pages: o projeto está preparado para publicação direta pela branch configurada no GitHub Pages.
- Formulário de contato: configurado com `mailto:contato@afterlapsus.com.br`, abrindo o cliente de e-mail do usuário.

Não foram identificados:

- Variáveis de ambiente.
- Arquivos `.env`.
- Flavors.
- Configuração Firebase.
- Chaves de API.
- Backend próprio.
- Configuração de autenticação.

## Dependências Principais

O projeto não possui dependências instaláveis via gerenciador de pacotes.

Recursos externos usados:

- Google Fonts: carregamento da família tipográfica Montserrat.
- GitHub Pages: hospedagem estática.
- Links externos para Steam, YouTube, Discord, Instagram, X/Twitter, Bluesky e TikTok.

## Funcionalidades

Funcionalidades identificadas no site:

- Header com logo da After Lapsus.
- Links sociais no header e footer:
  - Steam
  - Discord
  - YouTube
  - Instagram
  - X/Twitter
  - Bluesky
  - TikTok
- Hero section com imagens em loop automático.
- Overlay escuro para legibilidade da hero section.
- Seção de destaque para `Medo Desconhecido`.
- Thumbnail com botão para assistir vídeo no YouTube.
- Seção `Sobre a After Lapsus`.
- Seção `Nossos Jogos` com cards:
  - Medo Desconhecido
  - O Show do Zozo
  - Futuros Projetos
- Cards com efeito de revelação de descrição e botão no hover/focus.
- Botões `Saiba Mais` com links externos:
  - Medo Desconhecido: Steam
  - O Show do Zozo: Steam
  - Futuros Projetos: TikTok
- Formulário de contato via `mailto:` para `contato@afterlapsus.com.br`, com campos:
  - Nome
  - E-mail
  - Mensagem
- Footer com copyright, logo e redes sociais.
- Responsividade para desktop e mobile.

## Fluxo do Site

Fluxo principal de navegação:

1. O usuário acessa a página pela URL pública ou localmente.
2. A hero section apresenta a marca After Lapsus e imagens de fundo em loop.
3. O usuário pode acessar redes sociais e plataformas pelo header.
4. A página apresenta o jogo em destaque, com link para vídeo no YouTube.
5. A seção institucional apresenta informações sobre o estúdio.
6. O usuário visualiza os cards de jogos e acessa links externos pelos botões `Saiba Mais`.
7. O usuário encontra um formulário de contato que abre o cliente de e-mail configurado no dispositivo.
8. O footer reforça o logo, redes sociais e direitos reservados.

## Gerenciamento de Estado

Não há gerenciamento de estado identificado.

O arquivo `js/script.js` contém apenas uma estrutura inicial para futuras interações, sem lógica ativa de estado.

## Comunicação com APIs

Não há comunicação com APIs identificada.

Não foram encontrados:

- Cliente HTTP.
- Autenticação.
- Interceptors.
- Tratamento de erros de API.
- Integração com backend.

O formulário de contato utiliza `mailto:contato@afterlapsus.com.br`, com método `post` e `enctype="text/plain"`. Essa abordagem abre o cliente de e-mail do usuário. Envio direto e silencioso pelo site ainda exige futura integração backend ou serviço externo de formulários.

## Persistência Local

Não há persistência local identificada.

Não foram encontrados:

- LocalStorage
- SessionStorage
- IndexedDB
- Cookies
- SQLite
- Hive
- SharedPreferences
- Banco de dados

## Testes

Não foram encontrados testes automatizados.

Não há comandos identificados para:

- Testes unitários.
- Testes de integração.
- Testes end-to-end.
- Testes de interface.

Como o projeto é estático, a validação atual deve ser feita manualmente no navegador em desktop e mobile.

## Boas Práticas Utilizadas

Boas práticas identificadas no projeto:

- Uso de HTML semântico com `header`, `main`, `section`, `article`, `nav` e `footer`.
- Separação de responsabilidades entre HTML, CSS e JavaScript.
- CSS organizado por seções com comentários.
- Uso de variáveis CSS em `:root` para cores, dimensões e transições.
- Layout responsivo com Grid, Flexbox e media queries.
- Uso de `aria-label` em navegações e links com ícones.
- Uso de `target="_blank"` com `rel="noopener noreferrer"` em links externos.
- Imagens decorativas da hero com `alt=""` e `aria-hidden`.
- Preparação explícita para futuras animações, parallax e integração backend.
- Arquivo `.nojekyll` para publicação estática no GitHub Pages.

## Melhorias Futuras

Melhorias futuras identificáveis a partir do próprio código:

- Implementar lógica do menu mobile no `script.js`, caso o menu seja reintroduzido.
- Implementar integração backend para o formulário de contato.
- Implementar validação de formulário no front-end.
- Implementar futura animação/parallax indicada pelos comentários do código.
- Revisar textos finais da seção institucional, atualmente com conteúdo provisório.
- Definir política de licença.
- Adicionar testes automatizados ou checklist de QA visual.
- Adicionar metadados sociais, como Open Graph e Twitter Cards.
- Adicionar favicon.

## Contribuição

Fluxo sugerido para contribuição:

1. Faça um fork do repositório.
2. Crie uma branch para sua alteração:

```bash
git checkout -b minha-alteracao
```

3. Faça as alterações necessárias.
4. Teste localmente no navegador.
5. Faça commit:

```bash
git commit -m "Descreve a alteração"
```

6. Envie para o repositório remoto:

```bash
git push origin minha-alteracao
```

7. Abra um Pull Request.

Padrões de contribuição formais: A definir.

## Licença

A definir.

Não foi encontrado arquivo de licença no projeto.


