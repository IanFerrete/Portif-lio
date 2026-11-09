# Portfólio Profissional — Ian Ferrete Azevedo

## Identificação
* **Nome do Aluno:** Ian Ferrete Azevedo
* **Link do Site Publicado (GitHub Pages):** [https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/](https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/)

## Descrição do Portfólio
Este projeto consiste na evolução do portfólio pessoal desenvolvido para a disciplina de implementação de páginas web. O site foi estruturado para apresentar de forma limpa, responsiva e profissional a minha trajetória acadêmica na UFABC (Engenharia Aeroespacial e Ciência e Tecnologia), projetos de robótica e automação, e competências técnicas.

## Tecnologias Utilizadas
* **HTML5 e CSS3** (Estruturação e estilização customizada)
* **Bootstrap 5.3** (Grid system, componentes responsivos e utilitários)
* **Bootstrap Icons** (Biblioteca de ícones vetoriais)
* **JavaScript (Vanilla)** (Manipulação de DOM e lógica interativa)
* **Git e GitHub Pages** (Controle de versão e hospedagem contínua)

## Explicação do Funcionamento do Projeto
O site possui uma arquitetura de página única (*Single Page Application*) com navegação fluida por âncoras no menu superior fixo (`navbar`). Ele é composto por:
1. **Seção de Perfil (Hero):** Apresentação pessoal e chamada para ação principal.
2. **Seção de Formação:** Destaca o histórico acadêmico superior e técnico.
3. **Seção de Projetos:** Cards interativos detalhando trabalhos práticos (Órtese Gamificada, Robô Aquático e Espectrofotometria).
4. **Seção de Habilidades:** Grid organizado com as principais tecnologias dominadas (Rust, C++, Arduino, Python).
5. **Seção de Contato:** Canais diretos de comunicação e redes.

## Descrição do Recurso Novo Adicionado
Como recurso adicional além da base vista em aula, foi implementado um **Modo Escuro / Claro Dinâmico (Dark/Light Mode)** interativo integrado nativamente com os atributos de tema do Bootstrap 5, acompanhado de efeitos de animação em `hover` nos cards de projetos e emblemas de habilidades (`transform: translateY` e transições suaves).

## Explicação de Como o Recurso Foi Implementado
O recurso de alternância de tema foi construído utilizando:
1. O atributo `data-bs-theme="dark"` na tag `<html>` raiz.
2. Um botão interativo na barra de navegação equipado com um listener de eventos em **JavaScript (`addEventListener`)**.
3. Ao clicar no botão, o script verifica o estado atual do atributo e o alterna entre `"dark"` e `"light"`, atualizando dinamicamente o ícone do botão (lua/sol) e invertendo a paleta de cores de todo o framework Bootstrap de forma instantânea.
