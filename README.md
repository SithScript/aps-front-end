📚 APS - Desenvolvimento Web (HTML Puro)
3ºP - Engenharia de Software - UniSenai-PR 

📌 Sobre o Projeto

Este projeto é uma **Atividade Prática Supervisionada (APS)** desenvolvida para a disciplina de Desenvolvimento Web. Consiste em um mini site com 5 páginas HTML interligadas, demonstrando os fundamentos da linguagem HTML sem utilização de CSS ou JavaScript.

🎯 Objetivos da Atividade

- Aplicar os conceitos fundamentais de HTML
- Criar navegação entre múltiplas páginas
- Estruturar conteúdo com diferentes tags semânticas
- Desenvolver formulários para coleta de dados
- Construir tabelas para exibição de informações organizadas

🛠️ Tecnologias utilizadas

| Tecnologia | Finalidade |
|------------|------------|
| HTML5 | Estruturação completa do conteúdo |

Observação: Atividade exclusivamente HTML, sem recursos de estilização (CSS) ou interatividade (JavaScript), conforme solicitado pelo professor.

aps/
- index.html # Menu principal / Página inicial
- curriculo.html # Currículo profissional fictício
- cursos.html # Tabela de cursos do SENAI
- mural.html # Mural de cães desaparecidos
- formulario-de-cliente.html # Formulário de cadastro

img/ # Pasta de imagens
- beagle.png
- bullterrier.png
- collie.png


📄 Descrição das páginas

1. `index.html` - Menu Principal
Página central que conecta todas as outras páginas do projeto.

*Tags utilizadas:*
- `<h1>` - Título principal
- `<ul>` e `<li>` - Lista não ordenada para menu
- `<a>` - Links de navegação

2. `curriculo.html` - Currículo Profissional
Currículo fictício do profissional "Geniclésio Almirante Cosmos".

*Tags utilizadas:*
- `<h1>`, `<h2>` - Hierarquia de títulos
- `<ul>`, `<ol>`, `<dl>`, `<dt>`, `<dd>` - Diferentes tipos de listas
- `<hr>` - Linhas horizontais para separação de seções
- `<label>` - Rótulos para informações

*Seções do currículo:*
- Contato
- Objetivo
- Habilidades e Competências
- Experiência profissional
- Educação
- Comunicação
- Referências

3. `cursos.html` - Tabela de Cursos
Exibe uma tabela com cursos do SENAI para informática.

*Tags utilizadas:*
- `<table>`, `<thead>`, `<tbody>` - Estrutura da tabela
- `<tr>` - Linhas
- `<td>` - Células com atributo `rowspan` para mesclagem vertical

*Cursos listados:*
| Curso | Carga Horária | Valor |
|-------|---------------|-------|
| Excel Básico | 24h | R$ 390,00 |
| Excel Avançado | 39h | R$ 723,00 |
| Informática para Maturidade | 36h | R$ 622,00 |
| Operador de Computador | 160h | R$ 1.757,00 |
| PowerPoint | 20h | R$ 216,00 |
| Project | 20h | R$ 570,00 |
| Word | 24h | R$ 250,00 |

4. `formulario-de-cliente.html` - Formulário de Cadastro
Formulário para coleta de dados pessoais do cliente.

*Tags utilizadas:*
- `<form>` - Estrutura do formulário
- `<fieldset>` e `<legend>` - Agrupamento de campos
- `<input>` com diferentes tipos (`text`, `number`)
- `placeholder`, `size`, `maxlength` - Atributos de validação básica

*Campos do formulário:*
- Nome
- Idade
- Endereço
- Cidade
- Estado (UF)
- CEP
- Telefone residencial
- Telefone celular
- E-mail

5. `mural.html` - Mural de Cães Desaparecidos
Página com anúncios de cães perdidos e encontrados.

*Tags utilizadas:*
- `<h1>`, `<h2>` - Hierarquia de títulos
- `<img>` - Inserção de imagens
- `<br>` - Quebras de linha

🔍 Como visualizar

Método 1 - Local
1. Baixe todos os arquivos mantendo a estrutura de pastas
2. Abra o arquivo `index.html` no seu navegador
3. Navegue pelos links para as demais páginas

Método 2 - GitHub Pages

```bash```
Após fazer o upload para o GitHub
Ative o GitHub Pages nas configurações do repositório

📚 Conceitos praticados

Conceito e aplicação no projeto

Links relativos	- Navegação entre páginas com <a href="pagina.html">
Hierarquia de títulos -	<h1> ao <h2> para organização semântica
Listas aninhadas - ul, ol, dl com seus respectivos itens
Tabelas com mesclagem -	rowspan para células que ocupam múltiplas linhas
Formulários -	fieldset, diferentes tipos de input
Atributos de input - placeholder, size, maxlength
Imagens locais - ``Caminho relativo ../img/nome.png``



Este README destaca:
- **Aspectos técnicos** que você aprendeu (tags, atributos, estruturas)
- **Organização do projeto** (mostra que você sabe estruturar pastas)
- **Contexto acadêmico** (APS, 3º período, Engenharia de Software)
- **Transparência** (deixa claro que foi propositalmente sem CSS)

Quer que eu ajuste algo? Ou pode mandar o próximo código!
