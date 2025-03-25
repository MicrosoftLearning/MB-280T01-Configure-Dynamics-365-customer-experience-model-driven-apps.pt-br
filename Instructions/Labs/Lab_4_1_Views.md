---
lab:
  title: 'Laboratório 4.1: Visualizar dados com exibições'
---

# Laboratório 4.1: Visualizar dados com exibições

## Cenário

O Bellows College é uma organização educacional com vários campi e programas. Muitos instrutores e administradores do Bellows College precisam participar de eventos e comprar itens. Historicamente, o controle dessas despesas tem sido um desafio.

A administração do campus gostaria de modernizar o sistema de relatórios de despesas fornecendo aos funcionários uma forma de relatar despesas digitalmente.

Ao longo deste curso, você criará aplicativos e executará a automação para permitir que os funcionários do Bellows College gerenciem as despesas.

## Macroetapas do laboratório

Você fará o seguinte para criar o aplicativo baseado em modelo:

Crie diferentes visões para visualizar elementos do relatório de despesas.

Vamos trabalhar com os seguintes componentes:

Exibições: As exibições permitem que o usuário exiba os dados atuais na tabela do formulário.

## Pré-requisitos

Conclusão do Módulo 1 Laboratório 0 – validação do ambiente de laboratório

## Exercício 1: Gerenciar exibições

**Objetivo:** Neste exercício, você criará uma nova exibição que pode ser usada posteriormente em aplicativos baseados em modelo.

### Tarefa 1: Editar as diferentes exibições de Linhas de despesa

1. Se você ainda não o tiver feito, entre em  `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Localize e abra a tabela Linha de despesa.
6. Em Experiências com dados, selecione **Exibições**.
7. Abra a exibição **Linhas de despesa ativas**.
8. Clique em **Exibir coluna**. Selecione **Data da despesa, Descrição do item, Tipo de despesa** e **Valor da despesa.**
9. Localize e selecione a coluna **Criado em**. No menu exibido, selecione **Remover.**
10. Sua exibição deve ter as colunas Título da despesa, Data da despesa, Descrição do item, Tipo de despesa e Valor da despesa.
11. Selecione o botão **Salvar e publicar**.
12. Selecione o botão voltar para retornar à lista de exibições.

Em seguida, repetiremos esse processo para atualizar a Exibição associada da Linha de despesa. Essa é a exibição que aparecerá quando você estiver examinando as Linhas de despesa de uma tabela principal, como o Relatório de despesas.

### Tarefa 2: Atualizar a Exibição associada da Linha de despesa 

1. Localize e abra a Exibição associada da Linha de despesa.
2. Clique em **Exibir coluna**. Selecione **Data da despesa, Descrição do item, Tipo de despesa** e **Valor da despesa.**
3. Localize e selecione a coluna **Criado em**. No menu exibido, selecione **Remover.**
4. Sua exibição deve ter as colunas Título da despesa, Data da despesa, Descrição do item, Tipo de despesa e Valor da despesa.
5. Selecione o botão **Salvar e publicar**.
6. Selecione o botão voltar para retornar à lista de exibições.

Por fim, repetiremos esse processo mais uma vez para atualizar a Exibição de Linhas de despesa ativas de localização rápida. Essa é a exibição usada sempre que um usuário usa o campo de pesquisa para procurar uma Linha de despesa específica.

### Tarefa 3: Atualizar a exibição de Localização rápida

1. Localize e abra a exibição Linhas de despesa ativas de localização rápida.
2. Clique em **Exibir coluna**. Selecione **Data da despesa, Descrição do item, Tipo de despesa** e **Valor da despesa.**
3. Localize e selecione a coluna **Criado em**. No menu exibido, selecione **Remover.**
4. Sua exibição deve ter as colunas Título da despesa, Data da despesa, Descrição do item, Tipo de despesa e Valor da despesa.
5. No lado direito da tela, na seção Localizar por seleção, selecione **Editar localizar colunas da tabela.**
6. Adicione as seguintes colunas:
    - Data da Despesa
    - Tipo de Despesa
7. Clique no botão **Aplicar**.
8. Selecione o botão **Salvar e publicar**.
9. Selecione o botão voltar para retornar à lista de exibições.

### Tarefa 4: Editar as diferentes exibições de Relatórios de despesas

1. Se você ainda não o tiver feito, entre em  `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Localize e abra a tabela Relatórios de Despesas.
6. Em Experiências com dados, selecione **Exibições**.
7. Abra a exibição **Relatórios de Despesas Ativas**.
8. Clique em **Exibir coluna**. Selecione **Finalidade do relatório, Data de conclusão do relatório, Total do relatório** e **Última data para aprovação.**
9. Localize e selecione a coluna **Criado em**. No menu exibido, selecione **Remover.**
10. Sua exibição deve ter as colunas Finalidade do relatório, Data de conclusão do relatório, Total do relatório e Última data de aprovação.
11. Selecione o botão **Salvar e publicar**.
12. Selecione o botão voltar para retornar à lista de exibições.

Em seguida, repetiremos esse processo para atualizar a exibição Relatórios de despesas inativas.

### Tarefa 5: Atualizar a exibição de Relatórios de despesas inativas

1. Localize e abra a exibição Relatórios de Despesas Inativas.
2. Clique em **Exibir coluna**. Selecione **Finalidade do relatório, Data de conclusão do relatório, Total do relatório** e **Última data para aprovação.**
3. Localize e selecione a coluna **Criado em**. No menu exibido, selecione **Remover.**
4. Sua exibição deve ter as colunas Finalidade do relatório, Data de conclusão do relatório, Total do relatório e Última data de aprovação.
5. Selecione o botão **Salvar e publicar**.
6. Selecione o botão voltar para retornar à lista de exibições.

### Tarefa 6: Atualizar a exibição Relatórios de despesas ativos de localização rápida 

Por fim, repetiremos esse processo mais uma vez para atualizar a exibição de Relatórios de despesas ativas de localização rápida. Essa é a exibição usada sempre que um usuário usa o campo de pesquisa para procurar um Relatório de despesas específico.

1. Localize e abra a exibição Relatórios de Despesas Ativas de Localização Rápida.
2. Clique em **Exibir coluna**. Selecione **Finalidade do relatório, Data de conclusão do relatório, Total do relatório** e **Última data para aprovação.**
3. Localize e selecione a coluna **Criado em**. No menu exibido, selecione **Remover.**
4. Sua exibição deve ter as colunas Finalidade do relatório, Data de conclusão do relatório, Total do relatório e Última data de aprovação.
5. No lado direito da tela, na seção Localizar por seleção, selecione **Editar localizar colunas da tabela.**
6. Adicione a coluna Finalidade do relatório.
7. Clique no botão **Aplicar**.
8. Selecione o botão **Salvar e publicar**.
9. Selecione o botão voltar para retornar à lista de exibições.

### Tarefa 7: Criar uma nova exibição chamada Relatórios de despesas com conclusão hoje

1. Se você ainda não o tiver feito, entre em  `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Localize e abra a tabela Relatórios de Despesas.
6. Em Experiências com dados, selecione **Exibições**.
7. Abra a exibição Relatórios de despesas ativas.
8. Selecione o botão **Salvar como**.
9. Altere o nome para *`Expense Reports Due Today`*.
10. Selecione o botão **Salvar**.
11. Na seção Filtrar por, selecione **Editar filtros.**
12. Selecione o botão **Adicionar**. No menu exibido, selecione **Adicionar linha**.
13. Selecione a seta de menu suspenso na primeira linha em branco. No menu exibido, selecione a coluna **Data de conclusão do relatório**.
14. Altere o campo Igual a para **Hoje.**
15. Selecione o botão **OK**.
16. Selecione o botão **Salvar e Fechar**.
