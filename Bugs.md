# Relatório de Bugs

## Bug 1 — Cadastro permitido com campo obrigatório vazio

Passos para reproduzir
1. Acessar a página de cadastro
2. Deixar o campo obrigatório vazio
3. Clicar em salvar

Resultado atual
O curso é cadastrado mesmo sem preencher o campo.

Resultado esperado
O sistema deveria impedir o cadastro e exibir mensagem de erro.

Severidade: Alta



## Bug 2 — Layout quebra com nome de curso muito longo

Passos para reproduzir
1. Inserir um nome de curso muito longo
2. Clicar em salvar

Resultado atual
O curso é salvo e a interface da lista fica desproporcional.

Resultado esperado
O sistema deveria limitar caracteres ou manter o layout estável.

Severidade: Média



## Bug 3 — Sistema permite cadastro de cursos duplicados

Passos para reproduzir
1. Cadastrar um curso
2. Cadastrar o mesmo curso novamente

Resultado atual
O sistema permite cursos duplicados.

Resultado esperado
O sistema deveria impedir duplicação.

Severidade: Média



## Bug 4 — Sistema aceita apenas espaços em branco como nome

Passos para reproduzir
1. Inserir apenas espaços no campo
2. Clicar em salvar

Resultado atual
O curso é cadastrado mesmo sem conteúdo válido.

Resultado esperado
O sistema deveria tratar o campo como vazio e impedir cadastro.

Severidade: Alta



## Bug 5 — Sistema permite datas inválidas

Passos para reproduzir
1. Inserir data final anterior à data inicial
2. Salvar curso

Resultado atual
O curso é cadastrado mesmo com datas inválidas.

Resultado esperado
O sistema deveria impedir cadastro com datas inválidas.

Severidade: Média



## Bug 6 — Sistema permite número de vagas inválido

Passos para reproduzir
1. Inserir número negativo ou zero
2. Salvar curso

Resultado atual
Curso é cadastrado normalmente.

Resultado esperado
Sistema deveria rejeitar o valor.

Severidade: Média



## Bug 7 — Exclusão de curso não funciona

Passos para reproduzir
1. Cadastrar curso
2. Clicar em excluir
3. Atualizar página

Resultado atual
O curso permanece na lista.

Resultado esperado
O curso deveria ser removido.

Severidade: Alta



## Bug 8 — Informações do curso não são exibidas

Passos para reproduzir
1. Cadastrar curso preenchendo todos os campos
2. Visualizar lista de cursos

Resultado atual
Endereço, instrutor e link não aparecem. Não existe opção de visualizar detalhes ou editar.

Resultado esperado
Todas as informações deveriam estar visíveis ou acessíveis.

Severidade: Média
