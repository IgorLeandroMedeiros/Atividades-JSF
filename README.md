# 🚀 Portfólio: Desenvolvimento Back-End

Bem-vindo ao meu portfólio da disciplina de **Desenvolvimento Back-End**! 🎉

Este repositório contém os projetos desenvolvidos ao longo da disciplina, demonstrando a aplicação prática dos conhecimentos adquiridos em tecnologias front-end e back-end.

**Autor:** Igor Leandro Dantas Medeiros
**Curso:** Tecnologia em Sistemas para Internet
**Instituição:** Unopar
**Período:** 2025

---

## 📖 Sobre Este Portfólio

Este portfólio documenta minha jornada de aprendizado na disciplina de Desenvolvimento Back-End. O objetivo principal é apresentar de forma clara e organizada os projetos desenvolvidos, as metodologias empregadas, as tecnologias utilizadas, os aprendizados obtidos e os desafios superados em cada etapa.

As atividades abrangem desde a criação de interfaces web estáticas com **HTML5** e **CSS3**, passando pela implementação de funcionalidades dinâmicas com **JavaServer Faces (JSF)** e **CDI Beans**, até o versionamento de código utilizando **Git** e **GitHub**.

🔗 **Repositório Principal:** [https://github.com/IgorLeandroMedeiros/Atividades-JSF](https://github.com/IgorLeandroMedeiros/Atividades-JSF)

---

## 📂 Estrutura do Repositório e Atividades Desenvolvidas

Abaixo, um resumo de cada atividade presente neste portfólio:

### 📝 Atividade 1: Currículo Web com HTML e CSS
* **Objetivo:** Desenvolver uma página web estática para apresentar um currículo profissional, utilizando HTML para estruturação semântica e CSS para estilização visual.
* **Principais Tecnologias:** HTML5, CSS3 (com variáveis, Grid Layout), Font Awesome.
* **Resultado:** Uma página de currículo online de duas colunas, organizada, com seções como dados pessoais, formação, experiências, habilidades (com barras de progresso) e projetos.
* **➡️ Código:** [Ver Atividade 1](./Atividade1/)

### 🖥️ Atividade 2: Formulário com JSF
* **Objetivo:** Implementar um formulário web interativo para coleta de dados de contato (nome, sobrenome, telefone e e-mail) utilizando o framework JavaServer Faces (JSF).
* **Principais Tecnologias:** JSF 2.3, XHTML, CSS3, Font Awesome.
* **Resultado:** Um formulário de contato funcional com campos validados como obrigatórios, estilização CSS e ícones para melhor experiência do usuário.
* **➡️ Código:** [Ver Atividade 2](./Atividade2/)

### 🧑‍💻 Atividade 3: Cadastro de Usuários com Bean e ArrayList
* **Objetivo:** Desenvolver uma aplicação web que permita o cadastro de nomes de usuários, armazenando-os em um `ArrayList` gerenciado por um Bean CDI (`@Named`, `@SessionScoped`) e exibindo a lista dinamicamente com JSF e AJAX.
* **Principais Tecnologias:** JSF 2.3 (com `<f:ajax>`, `<h:dataTable>`), XHTML, Java, CDI Beans (`@Named`, `@SessionScoped`), `ArrayList`.
* **Resultado:** Uma aplicação interativa que permite adicionar nomes a uma lista e limpar a lista, com atualizações da interface via AJAX, demonstrando o gerenciamento de estado na sessão.
* **➡️ Código:** [Ver Atividade 3](./CadastroUsuarios/) 

### 🛠️ Atividade 4: Versionamento de Código com GitHub
* **Objetivo:** Aplicar o processo de versionamento de código utilizando Git e GitHub, incluindo a integração do Eclipse IDE para clonar, realizar `commits` e `push` das atividades anteriores.
* **Principais Tecnologias/Ferramentas:** Git, GitHub, Eclipse IDE (com plugin EGit).
* **Resultado:** Os projetos das atividades 1, 2 e 3 foram versionados e hospedados neste repositório no GitHub, com o histórico de alterações gerenciado pelo Git. Demonstra o fluxo básico de trabalho com controle de versão.
* **➡️ Evidência:** A própria estrutura deste repositório e seu histórico de commits. Veja o relatório completo para screenshots e detalhes do processo.

---

## ✨ Tecnologias Gerais Utilizadas
Ao longo destas atividades, as principais tecnologias e ferramentas que utilizei foram:

* **Front-End:** HTML5, CSS3, XHTML
* **Back-End:** Java, JavaServer Faces (JSF 2.3), CDI Beans (`@Named`)
* **Servidor de Aplicação:** WildFly
* **IDE:** Eclipse IDE
* **Controle de Versão:** Git, GitHub
* **Outras:** Font Awesome, Google Fonts

---

## 🚀 Como Visualizar/Executar os Projetos JSF (Atividades 2 e 3)

1.  **Pré-requisitos:**
    * Java Development Kit (JDK) 8 ou superior.
    * Um servidor de aplicação compatível com JSF 2.3 (ex: WildFly, Tomcat com bibliotecas JSF).
    * Apache Maven (opcional, dependendo de como os projetos foram configurados para build, mas não explicitamente detalhado nos roteiros como dependência de build).
    * Eclipse IDE for Enterprise Java and Web Developers (ou similar).
2.  **Passos:**
    * Clone este repositório: `git clone https://github.com/IgorLeandroMedeiros/Atividades-JSF.git`
    * Importe os projetos `Atividade2` e `CadastroUsuarios`  no seu Eclipse IDE.
    * Configure o servidor WildFly (ou similar) no Eclipse.
    * Adicione os projetos ao servidor.
    * Inicie o servidor e acesse as respectivas URLs (ex: `http://localhost:8080/NomeDoProjeto/`).

**Nota:** A Atividade 1 (Currículo HTML/CSS) pode ser visualizada diretamente abrindo o arquivo `index.html` em um navegador.

---

Obrigado por visitar meu portfólio! Sinta-se à vontade para explorar os códigos e o relatório completo para mais detalhes.
