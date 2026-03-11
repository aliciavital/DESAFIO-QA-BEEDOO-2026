# Relatório de Bugs

## Bug 1 — Cadastro com campo obrigatório vazio

Passos:
1. Acessar criação de curso
2. Deixar campo obrigatório vazio
3. Clicar em criar curso

Resultado atual:
Sistema permite cadastrar curso sem preencher o campo.

Resultado esperado:
Sistema deveria impedir cadastro com campo obrigatório vazio.

Severidade: Alta


## Bug 2 — Layout quebra com nome de curso muito longo

Passos:
1. Inserir nome de curso muito longo
2. Criar curso

Resultado atual:
Curso é salvo e o layout da lista fica desproporcional.

Resultado esperado:
Sistema deveria limitar caracteres ou manter layout estável.

Severidade: Média


## Bug 3 — Sistema permite cursos duplicados

Passos:
1. Cadastrar um curso
2. Cadastrar novamente o mesmo curso

Resultado atual:
Sistema permite cursos duplicados.

Resultado esperado:
Sistema deveria impedir duplicação.

Severidade: Média


## Bug 4 — Sistema permite cadastro com número de vagas inválido

Passos:
1. Inserir número de vagas negativo
2. Criar curso

Resultado atual:
Curso é cadastrado normalmente.

Resultado esperado:
Sistema deveria validar e impedir número inválido.

Severidade: Média


## Bug 5 — Sistema permite datas inválidas

Passos:
1. Inserir data final anterior à inicial
2. Criar curso

Resultado atual:
Curso é cadastrado mesmo com datas inválidas.

Resultado esperado:
Sistema deveria impedir cadastro com datas inválidas.

Severidade: Média


## Bug 6 — Exclusão de curso não funciona

Passos:
1. Cadastrar um curso
2. Clicar em excluir

Resultado atual:
Curso permanece na lista.

Resultado esperado:
Curso deveria ser removido da lista.

Severidade: Alta


## Bug 7 — Informações do curso não são exibidas

Passos:
1. Cadastrar curso preenchendo todos os campos
2. Visualizar lista de cursos

Resultado atual:
Endereço, nome do instrutor e link do curso não aparecem. Não existe opção de visualizar detalhes ou editar.

Resultado esperado:
Sistema deveria exibir todas as informações ou permitir visualizar/editar o curso.

Severidade: Média
