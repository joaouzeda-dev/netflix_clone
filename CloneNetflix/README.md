# Netflix Clone - 🎬

Este projeto consiste numa reprodução fiel e responsiva da tela "Quem está assistindo?" da Netflix. O objetivo principal foi aplicar conceitos avançados de Front-end e organização de diretórios, garantindo uma experiência de utilizador fluida em múltiplos dispositivos.

## 🚀 Tecnologias Utilizadas

* **HTML5**: Estruturação semântica de componentes.
* **CSS**: Implementação de **CSS Grid**, **Flexbox**, variáveis de design e tipografia fluida com `clamp()`.
* **JavaScript**: Lógica de interatividade e manipulação dinâmica de componentes.
* **Ambiente de Desenvolvimento**: Estruturado em **Eclipse IDE** com suporte a **Tomcat v10.1**.

## 🤖 Desenvolvimento Auxiliado por IA

Este repositório demonstra competências em **AI-Augmented Development**. Atuei como arquiteto e revisor do código, utilizando Inteligência Artificial para:

* **Otimização de Grid**: Ajuste fino para garantir a exibição de 2 colunas em smartphones.
* **Componentização**: Refatoração da lógica de JavaScript para separar elementos como o Carrossel e os Cards.
* **Acessibilidade**: Implementação de atributos ARIA e melhorias na navegação via teclado.

## 📂 Estrutura de Pastas (Arquitetura)

O projeto segue uma organização profissional de diretórios para facilitar a manutenção:

* **`/src/main/webapp`**: Diretório raiz da aplicação web.
* **`/assets`**: Contém os recursos estáticos, como os avatares dos perfis (`perfil-1.png`, etc.).
* **`/catalogo`**: Módulo que contém a página principal de exibição de conteúdos após o login.
    * **`/js`**: Contém a lógica modularizada, incluindo subpastas para `/components` (`Card.js`, `Carousel.js`).
    * **`catalogo.html`** e **`catalogo.css`**: Estilização específica do módulo de filmes.
* **`/WEB-INF`**: Pasta de configuração protegida para o ambiente Java Web/Tomcat.

## 🛠️ Como Executar

1.  Clone o repositório:
    ```bash
    git clone [(https://github.com/joaouzeda-dev/netflix_clone.git)]
    ```
2.  **Opção A (Simples)**: Abra o ficheiro `index.html` diretamente no seu navegador.
3.  **Opção B (Servidor)**: Importe o projeto no Eclipse e execute-o num servidor Apache Tomcat (v9 ou superior).

---
### 👨‍💻 Autor
**João Vitor Uzeda Medeiros**
*Estudante de Análise e Desenvolvimento de Sistemas (ADS)*
