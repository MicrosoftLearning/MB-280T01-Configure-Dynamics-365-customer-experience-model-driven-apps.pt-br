---
lab:
  title: 'Laboratório 1.1: Criar e gerenciar tabelas e colunas'
---

# Laboratório 1.1: Criar e gerenciar tabelas e colunas

## Cenário
O Bellows College é uma organização educacional com vários campi e programas. Muitos instrutores e administradores do Bellows College precisam participar de eventos e comprar itens. Historicamente, o controle dessas despesas tem sido um desafio.
A administração do campus gostaria de modernizar o sistema de relatórios de despesas fornecendo aos funcionários uma forma de relatar despesas digitalmente.
Idealmente, eles querem que seus usuários preencham um Relatório de despesas após cada evento ou compra. Para cada Relatório de despesas, eles querem poder adicionar itens de linha de despesas individuais. Eles já começaram a trabalhar nesta solução. A tabela Relatório de despesas foi criada. Você foi convidado a assumir o projeto e concluí-lo.

## Macroetapas do laboratório
Após a conclusão bem-sucedida deste laboratório, você poderá:
- Importar uma solução para o seu ambiente que inclua a tabela de Relatório de despesas.
- Criar tabela de Itens de linha de despesas
- Adicionar as colunas necessárias à tabela de Itens de linha de despesa
- Adicionar alguns dados de amostra.

## Pré-requisitos
- Conclusão do Módulo 1 Laboratório 0 – Validação do ambiente de laboratório

## Considerações antes de começar
- Convenções de nomenclatura – insira os nomes com cuidado.

## Exercício 1: Importar a solução de Relatório de despesas para seu ambiente
**Objetivo:** neste exercício, você importará a solução Relatório de despesas que inclui a tabela Relatório de despesas.

### Tarefa 1: Importar a solução
A tabela Relatório de despesas conterá informações sobre o relatório de despesas que o indivíduo enviará.
1. Se você ainda não estiver conectado, entre em `make.powerapps.com` usando suas credenciais de ambiente.
2. No menu Ambiente no canto superior direito, verifique se você está no ambiente para o qual deseja importar a solução.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Na barra de comandos na parte superior, selecione **Importar solução.**
5. Selecione o botão **Procurar**.
6. Localize e selecione o arquivo de solução `ExpenseReport_1_0_0_1` localizado nos materiais do curso.
7. Selecione o botão **Importar**.

*Observação: pode levar vários minutos para que a solução seja importada para o seu ambiente.*

## Exercício 2: Criar tabelas e colunas
**Objetivo:** neste exercício, você importará a solução Relatório de despesas que inclui a tabela Relatório de despesas.

### Tarefa 1: Criar tabela de linha de despesa
1. Se necessário, navegue até o portal do Power Apps Maker.
2. Certifique-se de estar trabalhando no ambiente para o qual importou a solução `ExpenseReport_1_0_0_1` durante o último exercício.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Localize e selecione a solução Relatórios de Despesas.
5. Selecione o botão **Novo**.
6. No menu que aparece, vá para **Tabela.** Em seguida, selecione **Tabela (propriedades avançadas).**
7. Configure sua nova tabela da seguinte maneira:
   - Nome de exibição`Expense Line`
   - Nome no plural: `Expense Lines`
   - Ativar anexos (incluindo notas e arquivos): Selecionado
8. Selecione a guia Coluna principal e altere o Nome de exibição para Título de despesa.
9. Selecione o botão Salvar.

*Observação: pode levar um ou dois minutos para a tabela ser criada.*

### Tarefa 2: Adicionar as colunas necessárias à tabela Linha de despesa
1. Com a tabela Linha de Despesa aberta, selecione Colunas no grupo Esquema.
2. Selecione **+ Nova coluna**.
3. Insira **`Expense Type`** para Nome de exibição.
4. Selecione **Escolha > Escolha** para Tipo de dados.
5. Em Obrigatório, selecione **Opcional**.
6. Defina Sincronizar com a Escolha para global como **Sim (recomendado)**.
7. Em Sincronizar esta opção com campo, selecione **+Nova escolha.**
8. No campo Nome de exibição, digite *`Expense Type`*.
9. No campo Rótulo da primeira escolha, insira *`Meals`*.
10. Selecione **+ Nova escolha**.
11. No campo Rótulos, insira *`Lodging`*.
12. Repita as etapas 10 e 11 para adicionar as seguintes opções:
    - `Travel`
    - `Entertainment`
    - `Supplies / Equipment`
    - `Other`
13. Selecione o botão **Salvar**.
14. No campo Sincronizar esta escolha com campo, selecione a escolha **Tipo de Despesa** que acabou de criar.
15. Defina o campo Escolha padrão como **Nenhuma**.
16. Selecione **Salvar**.

### Tarefa 3: Criar a coluna Valor da despesa
1. Selecione + Nova coluna.
2. Insira `Expense Amount` no Nome de exibição.
3. Selecione Moeda no tipo de dados.
4. Selecione Salvar.

### Tarefa 4: Criar a coluna Descrição do item
1. Selecione **+ Nova coluna**.
2. Insira *`Item Description`* no Nome de exibição.
3. Selecione **Várias Linhas de texto > Texto Simples** para Tipo de Dados.
4. Selecione **Salvar**.

### Tarefa 5: Criar a coluna Data da despesa
1. Selecione **+ Nova coluna**.
2. Insira *`Expense Date`* no Nome de exibição.
3. Selecione **Somente data** no grupo Data e hora no campo Tipo de dados.
4. Expanda **Opções avançadas**.
5. Defina o campo ajuste de Fuso horário como **Local do usuário.**
6. Selecione **Salvar**.

### Tarefa 6: Criar um Relatório de despesas
1. Selecione **+ Nova coluna**.
2. Insira *`Expense Report`* no Nome de exibição.
3. Selecione **Pesquisa** no grupo Pesquisa no campo Tipo de dados.
4. No campo Tabela relacionada, selecione **Relatório de despesas.**
5. Selecione **Salvar**.

## Exercício 3: Editar tabela
**Objetivo:** neste exercício, você modificará manualmente uma tabela.

### Tarefa 1: Modificar as colunas exibidas
1. Se necessário, navegue até o portal do Power Apps Maker.
2. Verifique se você está trabalhando no ambiente para o qual importou a solução **ExpenseReport_1_0_0_1** durante o último exercício.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Localize e selecione a solução **Relatórios de Despesas**.
5. Na navegação à esquerda, selecione **Tabelas**.
6. Abra a tabela Linha de despesa criada no exercício anterior.
7. iAo lado da coluna Sequência de Importação, selecione **+[X] mais**. (O número mostrado aqui dependerá do tamanho do seu navegador).
8. No menu que aparecerá, selecione as seguintes colunas:
   - Valor da despesa (base)
   - Data da despesa (se ainda não estiver selecionada)
   - Relatório de Despesas
   - Tipo de Despesa
   - Valor da Despesa
   - Descrição do Item
9. Selecione o botão **Salvar**.
10. Localize a coluna **Criado por** e selecione-a.
11. No menu exibido, selecione **Ocultar.**
12. Repita as etapas 10 e 11 para remover as seguintes colunas:
    - Criadas por
    - Linha de Despesa
    - Sequência de importação
