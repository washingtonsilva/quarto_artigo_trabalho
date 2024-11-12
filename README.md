# Template para Working Paper em Quarto

Template em Quarto para elaboração de versões de trabalho de 
artigos científicos (*working papers*) seguindo as normas 
atuais ABNT.

## Estrutura do Projeto

O template contém os seguintes arquivos essenciais:

- `artigo.qmd`: Arquivo principal do Quarto contendo a 
estrutura do artigo.

- `referencias.bibtex`: Arquivo para gerenciamento das 
referências bibliográficas.

- `associacao-brasileira-de-normas-tecnicas-ipea.csl`: Arquivo 
de estilo ABNT 2023 do IPEA.

## Como Usar

### Pré-requisitos

- Quarto (versão mais recente)
- Editor de texto (RStudio/VS Code/Positron)
- Sistema TeX instalado (`tinytex`, recomendado)

### Utilizando o Template

1. Clique no botão "Use this template" no topo da página
2. Clone o novo repositório criado
3. Edite o arquivo `artigo.qmd` com seu conteúdo
4. Adicione suas referências no arquivo `referencias.bibtex`

### Gerando o PDF

No RStudio clique em `Render`.

Nos demais editores, e também no RStudio, podemos 
usar o terminal:

```bash
quarto render artigo.qmd
```

## Estrutura do Documento

O template gera um artigo PDF com:

- Título e Subtítulo
- Autor
- Resumo e Palavras-chave
- Seções numeradas
- Citações no padrão ABNT
- Suporte a figuras e tabelas
- Referências bibliográficas

## Exemplos de Uso

### Citações

```markdown
@autor2023titulo cita normalmente
[@autor2023titulo] cita entre parênteses
```

### Figuras/Imagens Externas

```markdown
![Título da figura](caminho/figura.jpg){#fig-1 fig-align="center" width="80%"}
```

### Referências Cruzadas

```markdown
Como mostrado na @fig-1
```

## Licença

Este template está sob a licença MIT.

## Suporte

Em caso de dúvidas ou problemas, abra uma issue no repositório.


