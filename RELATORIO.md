# Relatório de aprendizagem

**Disciplina:** Desenvolvimento Web I  
**Trabalho:** Trabalho Avaliativo 01 – GitHub Pages  
**Aluno:** Lázaro Fornari  
**Turma:** 1G  
**Projeto:** Do zero ao primeiro site

## Ideia e planejamento

Escolhi fazer uma página introdutória sobre a criação de um site porque o assunto combina com o que estamos estudando em Desenvolvimento Web I. É um projeto novo, separado do Projeto Integrador. A proposta foi explicar o processo de modo fácil para alguém que também está começando: estruturar com HTML, estilizar com CSS, registrar versões com Git e publicar com GitHub Pages.

Antes de escrever o código, dividi a página em quatro partes: uma apresentação, o caminho até a publicação, um exemplo de arquivos e um glossário. Essa divisão facilitou a escolha dos títulos e evitou colocar todo o conteúdo em um bloco só.

## Como a página foi construída

1. Criei `index.html` como página inicial. Dentro dele, usei `header`, `nav`, `main`, `section`, `article` e `footer` para organizar o conteúdo. Os links do menu apontam para identificadores das seções na mesma página.
2. Criei `styles.css` separado do HTML e conectei os arquivos com `<link rel="stylesheet" href="styles.css">`. O caminho relativo permite que a folha de estilo seja encontrada tanto ao abrir o arquivo localmente quanto no endereço do projeto no GitHub Pages.
3. Defini uma paleta pequena de cores e construí o layout com Flexbox e Grid. O desenho de uma janela de navegador no início foi feito com elementos HTML e CSS, sem imagem pronta.
4. Adicionei regras `@media` para reorganizar as colunas em telas menores. A navegação continua acessível sem depender de JavaScript. Também incluí títulos em ordem, um link para pular ao conteúdo e indicação visual para navegação pelo teclado.
5. Organizei os arquivos com `README.md` para apresentar o projeto e este `RELATORIO.md` para registrar o processo. Revisei os textos, os caminhos dos arquivos e o comportamento da página em larguras diferentes.

## Git e publicação

O repositório é público e guarda o histórico do projeto. Separei os commits por finalidade: primeiro a estrutura HTML, depois o CSS e, por fim, a documentação. Assim, as mensagens de commit explicam a evolução do trabalho, em vez de reunir tudo em uma mudança sem contexto.

Para publicar, a origem do GitHub Pages foi configurada para a branch principal, a partir da raiz do repositório. O serviço procura `index.html` nessa pasta e publica os arquivos estáticos. Depois da configuração, conferi o endereço público e se o estilo carregava corretamente. O link do site pode ser encontrado nas informações do repositório e na área **Settings → Pages**.

## Ferramentas e por que usei cada uma

| Ferramenta | Utilidade no projeto |
| --- | --- |
| HTML | Dar estrutura e significado ao conteúdo. |
| CSS | Criar o visual e adaptar a página para diferentes tamanhos de tela. |
| Git | Registrar alterações em etapas por meio de commits. |
| GitHub | Guardar o repositório e disponibilizar o código publicamente. |
| GitHub Pages | Publicar o site estático sem precisar de um servidor próprio. |
| Navegador | Conferir o resultado, os links e a versão para celular. |

## Conceitos que ficaram mais claros

O **HTML** descreve a função de cada elemento. Um título não é apenas um texto grande: ele ajuda a organizar a leitura da página. O **CSS** controla apresentação e disposição, sem substituir o conteúdo. Separar os dois arquivos facilita fazer mudanças no visual.

Um **repositório** contém os arquivos e o histórico do projeto. Um **commit** é um registro identificável de alterações, com uma mensagem que ajuda a entender aquela etapa. O **GitHub Pages** transforma os arquivos estáticos desse repositório em um site público. Também aprendi por que um **caminho relativo** é importante: ele funciona dentro da pasta do projeto, mesmo quando o endereço do site inclui o nome do repositório.

Optei por escrever HTML e CSS diretamente, sem gerador de sites, para praticar os fundamentos pedidos no trabalho. O mais interessante neste processo foi perceber que uma página simples já permite trabalhar conteúdo, visual, organização de arquivos, versionamento e publicação de forma completa.

## Referências

- [MDN Web Docs — HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [MDN Web Docs — CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [Documentação do GitHub Pages](https://docs.github.com/pt/pages)
- [Documentação do GitHub — Sobre o Git](https://docs.github.com/pt/get-started/using-git/about-git)
