# Trabalho-final-do-Laravel- 
Após criar um novo projeto Laravel, segui os seguintes passos:

Criei uma Migration, para criar a estrutura da tabela tasks no banco de dados e também definir os campos pedidos: ID, titulo, descrição, status, que variam entre Concluída e Não concluída, e por fim os timestamps.
O segundo passo foi, seguindo a Base Model do Laravel, determinar o modelo da task e determinar também, quais colunas na tabela seriam 'fillable', preenchíveis.
Em seguida o TaskController, que lida com quaisquer requisições feitas às tarefas - como listar as tarefas disponíveis, atualizar alguma tarefa expecífica, etc. São utilizadas rotas determinadas na api.
