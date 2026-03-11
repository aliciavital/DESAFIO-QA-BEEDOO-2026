# 1️⃣ Análise inicial da aplicação

A aplicação consiste em um módulo simples de cadastro e listagem de cursos. O objetivo é permitir que os usuários registrem novos cursos e visualizem os cursos cadastrados.

Funcionalidades identificadas:

- cadastro de curso
- listagem de cursos
- validação de campos do formulário
- exclusão de cursos
- atualização da lista após cadastro

# 2️⃣ Principais fluxos

Fluxos identificados:

Fluxo principal

- cadastrar curso
- salvar curso
- curso aparece na lista

Fluxos alternativos:

- cadastrar curso com campo vazio
- cadastrar curso com caracteres especiais
- cadastrar cursos duplicados
- cadastrar curso com dados inválidos

# 3️⃣ Pontos críticos para teste

Exemplo:

- validação de campos obrigatórios
- comportamento da aplicação com dados inválidos
- atualização correta da lista após cadastro
- comportamento da aplicação com múltiplos cliques no botão de salvar
- inserção de dados duplicados
- exibição correta das informações cadastradas

## Casos de teste

Os cenários de teste foram documentados em uma planilha do Google Sheets:

[Link para a planilha de testes](https://docs.google.com/spreadsheets/d/1e0xXxtMr45McYpNpT7-RM1daDcquDQ-6AT7bUaUtGdY/edit?usp=sharing)


## Relatório de bugs

Os bugs identificados durante os testes estão documentados no arquivo:

[Ver relatório de bugs](Bugs.md)


## Evidências

As evidências da execução dos testes estão disponíveis na pasta:

[Ver evidências dos testes](docs/evidencias)

Cada imagem corresponde a um caso de teste executado.

