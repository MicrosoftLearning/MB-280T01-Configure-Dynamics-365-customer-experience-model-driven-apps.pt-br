---
lab:
  title: 'Laboratório 4.3: Criar um painel'
---

# Laboratório 4.3: Criar um painel 

## Cenário
O Bellows College é uma organização educacional com vários campi e programas. Muitos instrutores e administradores do Bellows College precisam participar de eventos e comprar itens. Historicamente, o controle dessas despesas tem sido um desafio.
A administração do campus gostaria de modernizar o sistema de relatórios de despesas fornecendo aos funcionários uma forma de relatar despesas digitalmente.
Ao longo deste curso, você criará aplicativos e executará a automação para permitir que os funcionários do Bellows College gerenciem as despesas.

## Macroetapas do laboratório
Após a conclusão bem-sucedida deste laboratório, você poderá:
- Criar um novo aplicativo baseado em modelo
- Criar um painel pessoal que exiba informações do Relatório de despesas
- Adicionar suas exibições e painéis ao seu aplicativo baseado em modelo

## Pré-requisitos
- Conclusão do Módulo 1 Laboratório 0 – Validação do ambiente de laboratório

## Exercício 1: Criar um painel pessoal

### Tarefa 1: Criar um aplicativo baseado em modelo.
1. Se você ainda não tiver entrado, entre em `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Na barra de comandos, selecione o botão **+ Novo**.
6. No menu exibido, vá para **Aplicativo > Aplicativo baseado em modelo.**
7. Insira *`Employee Expense Management`* no Nome e selecione **Criar**.

### Tarefa 2: Criar uma nova visualização chamada Meus relatórios de despesas ativas
1. Se você ainda não tiver entrado, entre em `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Localize e abra a tabela Relatórios de Despesas.
6. Em Experiências com dados, selecione **Exibições**.
7. Abra a exibição **Relatórios de Despesas Ativas**.
8. Selecione o botão **Salvar como**.
9. Altere o nome para *`My Active Expense Reports`*.
10. Selecione o botão **Salvar**.
11. Na seção Filtrar por, selecione **Editar filtros.**
12. Selecione o botão **Adicionar**. No menu exibido, selecione **Adicionar linha**.
13. Selecione a seta de menu suspenso na primeira linha em branco. No menu que aparecerá, selecione a coluna **Proprietário**.
14. Altere o campo **Igual a** para Igual ao usuário atual.
15. Selecione o botão **OK**.
16. Selecione o botão **Salvar e Fechar**.

### Tarefa 3: Adicionar uma seção Painéis ao aplicativo Gerenciamento de despesas do funcionário
1. Se você ainda não tiver entrado, entre em https://make.powerapps.com.
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Selecione **Aplicativos**.
6. Localize o aplicativo Gerenciamento de despesas do funcionário.
7. Selecione as **reticências verticais** e, no menu exibido, selecione **Editar**.
8. Selecione o botão **Adicionar página **.
9. Selecione **Painel**.
10. Explore os painéis do sistema que estão disponíveis por padrão. Quando estiver pronto, selecione um dos painéis que você gostaria de adicionar ao seu aplicativo.
11. Selecione **Adicionar**.
12. Com Novo grupo selecionado, altere o Título para **Painéis.**
13. Selecione o botão **Salvar**.
14. Depois de Salvar, clique no botão **Salvar e Publicar**.

### Tarefa 4: Adicionar um painel pessoal ao aplicativo de gerenciamento de despesas do funcionário
1. Se você ainda não tiver entrado, entre em `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Selecione **Aplicativos**.
6. Localize o aplicativo baseado em modelo de Gerenciamento de despesas do funcionário.
7. Selecione as **reticências verticais**. No menu exibido, selecione **Executar**.
8. No grupo Painéis, selecione o painel do sistema adicionado na Tarefa 3.
9. Selecione o botão **Novo**.
10. No menu exibido, selecione **Painel do Dynamics 365.**
11. Escolha **Painel regular de 2 colunas.**
12. Selecione o botão **Criar**.
13. Alterar o nome do painel para *`Expense Report Dashboard`*.
14. Na seção superior esquerda, selecione o **ícone Lista.**
15. Configure a lista da seguinte maneira:
    - Tipo de registro: Relatórios de despesas
    - Exibição: Relatórios de despesas com conclusão hoje.
16. Selecione o botão **Adicionar**.
17. Selecione o **ícone Lista** na seção superior direita.
18. Configure a lista da seguinte maneira:
    - Tipo de registro: Relatórios de despesas
    - Exibição: Meus relatórios de despesas ativas.
19. Selecione o botão **Adicionar**.
20. Na seção inferior esquerda, selecione o **ícone Lista.**
21. Configure a lista da seguinte maneira:
    - Tipo de registro: Linhas de despesa
    - Exibição: Minhas linhas de despesas ativas.
22. Selecione o botão **Adicionar**.
23. Na seção inferior direita, selecione o **ícone Lista.**
24. Configure a lista da seguinte maneira:
    - Tipo de registro: Contatos
    - Exibição: Meus contatos ativos
25. Selecione o botão **Adicionar**.
26. Selecione o botão **Salvaar** no canto superior esquerdo.
27. Depois que o painel for salvo, selecione o botão **Fechar**.
28. Você deve ser levado para o Painel do Relatório de Despesas.
29. Na barra de comandos no topo da tela, selecione **Definir como padrão**.
