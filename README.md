# Projeto Latex para Elaboração de Trabalhos Textuais

Este repositório contém um projeto em Latex voltado para a elaboração de trabalhos textuais no curso de Engenharia Elétrica do Instituto Federal de Goiás - Campus Jataí. O objetivo principal é fornecer uma estrutura pronta e personalizável para a criação de documentos acadêmicos como relatórios, artigos e projetos de pesquisa.

## Estrutura do Projeto

O projeto possui a seguinte estrutura de diretórios:

- `figuras/`: Pasta destinada a armazenar todas as figuras utilizadas no documento.
- `capitulos/`: Pasta contendo os arquivos de cada capitulo do trabalho.
- `referencias.bib`: Arquivo no formato BibTeX para gerenciamento das referências bibliográficas.
- `main.tex`: Arquivo principal do projeto que contém a estrutura geral do documento e faz a inclusão das seções.

## Requisitos

Para utilizar esse projeto, você precisa ter instalado em sua máquina o software LaTeX. Recomendamos a utilização do [TeX Live](https://www.tug.org/texlive/) ou [MikTeX](https://miktex.org/), que são distribuições LaTeX amplamente utilizadas.

## Como Utilizar

Siga as etapas abaixo para utilizar o projeto:

1. Faça um clone deste repositório para o seu ambiente local: 
  ```git clone git@github.com:vitorsubhi/IFG_Modelo.git```
2. Abra o arquivo `main.tex` em um editor de texto ou IDE LaTeX de sua preferência.
3. Personalize o cabeçalho do documento com o título do trabalho, nome do autor, data, etc.
4. Crie ou edite os arquivos dentro do diretório `capitulos/` de acordo com as seções do seu trabalho.
5. Adicione as referências bibliográficas no arquivo `referencias.bib` utilizando o formato BibTeX.
6. No arquivo `main.tex`, inclua as seções do seu trabalho utilizando o comando `\input{secoes/nome-do-arquivo.tex}`.
7. Adicione as figuras do seu trabalho no diretório `figuras/` e utilize o comando `\includegraphics` para inseri-las nas seções.
8. Compile o arquivo `main.tex` para gerar o documento final. Dependendo da sua configuração LaTeX, você pode utilizar comandos como `pdflatex`, ou outro de sua preferência.
9. O documento final será gerado como um arquivo PDF no mesmo diretório.

## Contribuição

Sinta-se à vontade para contribuir com melhorias neste projeto. Caso encontre algum problema ou tenha sugestões, abra uma nova *issue* ou envie um *pull request*.
