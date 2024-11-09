---
lab:
  title: 'Laboratório 2.1: Criar campos calculados e de valor acumulado'
---

# Laboratório 2.1: Criar campos calculados e de valor acumulado 

## Cenário
O Bellows College é uma organização educacional com vários campi e programas. Muitos instrutores e administradores do Bellows College precisam participar de eventos e comprar itens. Historicamente, o controle dessas despesas tem sido um desafio.
A administração do campus gostaria de modernizar o sistema de relatórios de despesas fornecendo aos funcionários uma forma de relatar despesas digitalmente.
Idealmente, eles querem que seus usuários preencham um Relatório de despesas após cada evento ou compra. Para cada Relatório de despesas, eles querem poder adicionar itens de linha de despesas individuais. Eles já começaram a trabalhar nesta solução. A tabela Relatório de despesas foi criada. Você foi convidado a assumir o projeto e concluí-lo.

## Macroetapas do laboratório
Após a conclusão bem-sucedida deste laboratório, você poderá:
- Adicionar novos campos a uma tabela existente
- Criar um campo cumulativo
- Criar um campo calculado

## Pré-requisitos
- Conclusão do Módulo 1 Laboratório 0 – validação do ambiente de laboratório e Laboratório 1.1, onde você importou a solução Relatório de despesas

## Considerações antes de começar
- Convenções de nomenclatura – insira os nomes com cuidado.

## Exercício 1: Criar campos calculados e de valor acumulado
**Objetivo:** neste exercício, crie um valor acumulado e um campo calculado na tabela do relatório de despesas.

### Tarefa 1: Adicionar um campo cumulativo à tabela Relatório de despesas
1. Se necessário, navegue até o portal do Power Apps Maker.
2. Verifique se você está trabalhando no ambiente para o qual importou a solução Relatório de despesas durante o último exercício.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Localize e selecione a solução Relatórios de Despesas.
5. Localize e abra a tabela Relatórios de Despesas.
6. Em Esquema de grupo, selecione **Colunas**.
7. Selecione **+ Nova coluna.**
8. Insira *`Report Total`* no nome de exibição.
9. Selecione **Moeda** no tipo de dados.
10. Em Obrigatório, selecione **Opcional**.
11. No campo Comportamento, selecione **Valor acumulado.**
12. Selecione o botão **Salvar**. (Você precisa salvar a coluna antes de configurá-la).
13. Depois que a coluna for salva, uma janela pop-up deve aparecer. (Se você receber uma mensagem pop-up, talvez seja necessário permitir pop-ups).
14. Em ENTIDADE RELACIONADA, selecione **+Adicionar entidade relacionada.**
15. Selecione **(Linhas de despesa) Relatório de despesa.**
16. Selecione o botão Marca de seleção para aceitar a alteração.
17. Em AGREGAÇÃO, selecione **+Adicionar agregação.**
18. Defina Função de agregação como **Soma.**
19. Defina o campo Entidade relacionada agregada como **Valor da despesa (linha de despesa).**
20. Selecione a marca de seleção verde e, em seguida, click no botão **Salvar e fechar**.

### Tarefa 2: Adicionar um campo calculado de fórmula Power FX à tabela Relatório de despesas
1. Se necessário, navegue até o portal do Power Apps Maker.
2. Verifique se você está trabalhando no ambiente para o qual importou a solução Relatório de despesas durante o último exercício.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Localize e selecione a solução Relatórios de Despesas.
5. Localize e abra a tabela Relatórios de Despesas.
6. Em Esquema de grupo, selecione **Colunas**.
7. Selecione **+ Nova coluna.**
8. Insira *`Last Date for approval`* no Nome de exibição.
9. Selecione **Fórmula** em Tipo de dados.
10. Insira a seguinte fórmula: `DateAdd('Report Due Date',2)`
11. Defina o campo Formatar como **Somente data.**
12. Selecione o botão **Salvar**. (Você precisa salvar a coluna antes de configurá-la).
