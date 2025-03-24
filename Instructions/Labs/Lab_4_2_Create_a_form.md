---
lab:
  title: 'Laboratório 4.2: Criar formulários'
---

# Laboratório 4.2: Criar formulários

## Cenário
O Bellows College é uma organização educacional com vários campi e programas. Muitos instrutores e administradores do Bellows College precisam participar de eventos e comprar itens. Historicamente, o controle dessas despesas tem sido um desafio.
A administração do campus gostaria de modernizar o sistema de relatórios de despesas fornecendo aos funcionários uma forma de relatar despesas digitalmente.
Ao longo deste curso, você criará aplicativos e executará a automação para permitir que os funcionários do Bellows College gerenciem as despesas.

## Macroetapas do laboratório
Após a conclusão bem-sucedida deste laboratório, você terá realizado o seguinte:
- Terá personaliza o formulário da tabela para melhor atender às suas necessidades.

Vamos trabalhar com os seguintes componentes:
- Formulários: É onde o usuário cria/atualiza novas linhas nas tabelas.

## Pré-requisitos
- Conclusão do Módulo 1 Laboratório 0 – Validação do ambiente de laboratório

## Exercício 1: Personalizar exibições e formulários
**Objetivo:** Neste exercício, você vai personalizar as exibições e os formulários das tabelas personalizadas que serão usadas no aplicativo baseado em modelo.

### Tarefa 1: Editar o Formulário do Relatório de Despesas
1. Se você ainda não tiver entrado, entre em `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Localize e abra a tabela Relatórios de Despesas.
6. Na seção Experiências de dados, selecione **Formulários** e abra o formulário Informações com o tipo Formulário Principal. (Importante: selecione o formulário com o tipo de formulário Principal).

**IMPORTANTE:** como, por padrão, todos os formulários são denominados Informação, verifique se o formulário selecionado tem um Tipo de formulário Principal e não outro. Por padrão, o formulário tem dois campos: Nome do relatório e Proprietário.

### Tarefa 2: Selecionar colunas para o formulário
1. No lado direito da tela no painel Propriedades, selecione o campo **Nome** e altere-o para `Report Information`.
2. Selecione **Colunas da tabela** no painel de navegação à esquerda e adicione os seguintes campos abaixo do campo Proprietário arrastando as colunas para o formulário ou simplesmente clicando nos nomes das colunas:
    - Descrição
    - Finalidade do relatório
    - Data de conclusão do relatório
    - Total do Relatório
3. Arraste a coluna **Razão do Status** e solte-a no cabeçalho do formulário. O cabeçalho é a área superior direita do formulário. Pode ser necessário recolher o painel Propriedades do lado direito da tela para ver o campo no formulário.
4. Arraste a coluna **Última data para aprovação** e solte-a no cabeçalho do formulário ao lado de razão do status.
5. Selecione o campo **Proprietário**. No painel Propriedades, altere o Rótulo para *`Requestor`*.
6. Na navegação à esquerda, selecione **Componentes.**
7. Selecione a seção de 1 coluna para adicioná-la abaixo da seção atual.
8. No painel Propriedades, altere o rótulo para **`Expense Lines`**.
9. Com a seção Linha de despesa ainda selecionada, localize e selecione o componente **Subgrade**.
10. Marque a caixa de seleção **Mostrar registros relacionados**.
11. Defina a Tabela como **Linhas de despesa (Relatório de despesa).**
12. Defina a exibição Padrão como **Linhas de despesa ativas.**
13. Selecione **Concluído**.
14. Selecione o botão **Salvar e publicar** no canto superior direito e aguarde a conclusão do salvamento e da publicação.
15. Selecione o botão voltar na parte superior da tela. Agora você deve voltar à tabela Formulários do Relatório de Despesas.

### Tarefa 3: Editar formulário de linha de despesas ativas
Nesta tarefa, modificaremos o formulário usado para adicionar itens de linha de despesa.

1. Se você ainda não tiver entrado, entre em `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione Soluções.
4. Abra a solução Relatório de despesas.
5. Localize e abra a tabela Linha de despesa.
6. Na seção Experiências de dados, selecione Formulários e abra o formulário Informações com o tipo Formulário Principal. (Importante: selecione o formulário com o tipo de formulário Principal).

**IMPORTANTE:** como, por padrão, todos os formulários são denominados Informação, verifique se o formulário selecionado tem um Tipo de formulário Principal e não outro. Por padrão, o formulário tem dois campos: Título da despesa e Proprietário.

1. No lado direito da tela no painel **Propriedades**, selecione o campo **Nome de exibição** e altere-o para `Item Details`.
2. Selecione **Colunas da tabela** no painel de navegação à esquerda e adicione os seguintes campos abaixo do campo Proprietário arrastando as colunas para o formulário ou simplesmente clicando nos nomes das colunas:
    - Tipo de Despesa
    - Descrição do Item
    - Valor da Despesa
    - Relatório de Despesas
3. Arraste a coluna **Razão do Status** e solte-a no cabeçalho do formulário. O cabeçalho é a área superior direita do formulário. Pode ser necessário recolher o painel Propriedades do lado direito da tela para ver o campo no formulário.
4. Selecione o botão **Salvar e Fechar**.
