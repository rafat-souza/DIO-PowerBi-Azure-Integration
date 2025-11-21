# DIO-PowerBi-Azure-Integration
Nesse projeto fiz a conexão de um database do MySQL no Power BI. 
- Alteração dos nomes das tabelas e colunas para facilitar a compreensão
- Valores nulos na coluna de ssn do supervisor, na tabela de colaboradores, foram renomeados para "Manager"
- Tabela employee mesclada com tabela department
- Colunas de nome, nome do meio e sobrenome mescladas para uma única coluna de nome juntando os três valores
- Mescla da tabela de departamento com a tabela dept_location, carga da tabela dept_location desabilitada
- resposta a pergunta do ponto 14 da atividade:
  <img width="1089" height="470" alt="14" src="https://github.com/user-attachments/assets/25ede097-e593-4f26-b887-ac44e1dcccf7" />
  Como o objetivo é adicionar novas colunas (como Store e Dnumber) a uma tabela existente, fazendo a correspondência através de uma coluna chave comum, a operação correta é a Mesclagem (Merge).
  A operação de Atribuir/Acrescentar não funcionaria corretamente, pois ela tentaria empilhar as linhas das tabelas, mas as tabelas não possuem as mesmas colunas, resultando em muitos valores nulos (nulls) ou uma estrutura de dados inutilizável.
