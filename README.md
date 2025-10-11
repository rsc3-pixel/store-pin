# StorePin - Loja de Pins

## 📌 Descrição do Projeto

Este é o projeto da 1ª Avaliação da disciplina de Introdução à Computação, com o objetivo de criar um site estático institucional focado em HTML Semântico, CSS Organizado** e Acessibilidade Básica. Escolhemos o tema Loja de Pin's de Aço para aplicar os conhecimentos de estrutura e estilo.

## 👥 Autores e Papéis

O projeto foi desenvolvido pelo trio a seguir, seguindo a sugestão de papéis para garantir a cobertura dos requisitos:

| Nome do Aluno | Papel Principal | Contribuições |
| :--- | :--- | :--- |
| **[Luís Felipe Farias Nunes]** | **Dev 1 – Estrutura e Acessibilidade** | Estruturação de todas as páginas, uso correto de tags semânticas (`header`, `nav`, `main`, `footer`), e atributos `alt` em imagens. Elaboração do Index e Produtos|
| **[Renato Santos Chong]** | **Dev 2 – Layout e Componentes** | Implementação do Flexbox, criação do Hero, design dos cards de destaque e layout da tabela. Elaboração do Sobre e Produtos|
| **[Fernando Andrade Leandro Peixoto]** | **Dev 3 – Estilo e Documentação** | Definição e aplicação da paleta de cores via `:root`, tipografia, otimização de imagens e elaboração deste `README.md`. Elaboração do Contato e Produtos|

## 🎨 Identidade Visual e Tipografia

### Paleta de Cores (Definidas em `:root`)

| Nome da Variável | Código Hexadecimal | Uso Principal |
| :--- | :--- | :--- |
| `--cor-primaria` | **#18230F** | Destaques, Botões e Títulos |
| `--cor-secundaria` | **#27391C** | Plano de Fundo Secundário |
| `--cor-texto` | **#FFF** | Corpo de Texto |
| `--cor-fundo` | **#27391C** | Fundo Principal da Página |

### Fontes Utilizadas (Google Fonts)

* **Título Principal:** **"Quicksand", sans-serif** 

@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap');

## 💻 Como Abrir o Projeto

O projeto é 100% estático e não requer servidores. Basta seguir os passos:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/rsc3-pixel/store-pin.git
    ```
2.  **Acesse a pasta:**
    ```bash
    cd STORE-PIN
    ```
3.  **Abra o arquivo principal:**
    Localize e abra o arquivo **`index.html`** diretamente no seu navegador de preferência.

## ✅ Checklist de Entregáveis

Este checklist confirma o cumprimento dos requisitos obrigatórios da avaliação:

| Item | Status |
| :--- | :--- |
| **3 páginas mínimas** (Home/Sobre/Contato) + links funcionando. | [OK] |
| `header`, `nav`, `main`, `footer` usados com propósito. | [OK] |
| **Hero** na página principal (Título, subtítulo, botão). | [OK] |
| **Tabela simples** presente (na página Sobre/Serviços). | [OK] |
| Paleta no **`:root`** (variáveis CSS). | [OK] |
| **Google Fonts** aplicadas. | [OK] |
| Imagens otimizadas com **`alt` descritivo**. | [OK] |
| **README** com papéis, paleta, fontes e decisões. | [OK] |
| **Site no ar** (Link ativo: https://rsc3-pixel.github.io/store-pin/index.html ). | [OK] |
| **Vídeo de demonstração** (Link: [LINK DO VÍDEO AQUI]). | [OK] |

## 💡 Decisões de Design e Código (Para o Vídeo e Documentação)

*As decisões a seguir serão detalhadas no vídeo de demonstração, mas são listadas para referência:*

1.  **Semântica do Destaque:** Optamos por usar `<section>` para os destaques da Home e `<article>` dentro de cada card. Isso reforça a semântica, indicando que cada card é um conteúdo independente dentro de uma seção temática.
2.  **Gerenciamento de Cores:** Utilizamos o bloco **`:root`** para declarar as 4 cores principais. Isso permite uma gestão centralizada do tema, facilitando futuras alterações e garantindo a consistência do design em todo o site.
3.  **Layout Responsivo (Bônus):** Implementamos *Media Queries* específicas no CSS para adaptar a barra de navegação e os cards de destaque, garantindo uma melhor experiência em dispositivos móveis.
