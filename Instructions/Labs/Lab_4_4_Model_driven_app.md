---
lab:
  title: 'Laboratório 4.4: Criar um aplicativo baseado em modelo'
---

# Laboratório 4.4: Criar um aplicativo baseado em modelo

## Cenário
O Bellows College é uma organização educacional com vários campi e programas.

Muitos instrutores e administradores do Bellows College precisam participar de eventos e comprar itens. Historicamente, o controle dessas despesas tem sido um desafio.
A administração do campus gostaria de modernizar o sistema de relatórios de despesas fornecendo aos funcionários uma forma de relatar despesas digitalmente.

Ao longo deste curso, você criará aplicativos e executará a automação para permitir que os funcionários do Bellows College gerenciem as despesas.

## Macroetapas do laboratório
Como parte da configuração do aplicativo baseado em modelo, você fará o seguinte:
- Configurar seu novo aplicativo baseado em modelo chamado Gerenciamento de despesas do funcionário

Vamos trabalhar com os seguintes componentes:
- Exibições: As exibições permitem que o usuário exiba os dados atuais na tabela do formulário.
- Formulários: É onde o usuário cria/atualiza novas linhas nas tabelas.
Ambos serão integrados ao aplicativo baseado em modelo para oferecer uma melhor experiência do usuário.

## Pré-requisitos
- Conclusão do Módulo 1 Laboratório 0 – Validação do ambiente de laboratório

## Exercício 1: Criar aplicativo baseado em modelo
**Objetivo:** neste exercício, você usará o aplicativo baseado em modelo configurado no Laboratório 4.3. Em seguida, você personalizará o mapa do site e testará o aplicativo.
Para simplificar e ganhar tempo, não abordaremos todas as colunas do Relatório de Despesas neste laboratório.

## Tarefa 1: Configurar o mapa do site
1. Se você ainda não tiver entrado, entre em `https://make.powerapps.com`
2. Selecione o ambiente para o qual você importou a solução Relatório de despesas no canto superior direito, se ele ainda não estiver selecionado.
3. Usando a navegação à esquerda, selecione **Soluções.**
4. Abra a solução Relatório de despesas.
5. Localize o aplicativo *`Employee Expense Management`* que você criou no último exercício.
6. Selecione **Editar** para abrir o designer de aplicativo moderno.
7. Na barra de comandos, selecione **+ Adicionar página**.
8. A tela **Adicionar página** abrirá.
9. Escolha **Tabela do Dataverse.**
10. Escolha as seguintes tabelas:
    - Relatório de Despesas
    - Linha de Despesa
11. certifique-se que Exibir na navegação está selecionado.
12. Depois de selecionar as duas tabelas, selecione **Adicionar**.
13. Em Navegação, selecione o formulário **Relatórios de despesas**.
14. Vá para a seção Neste aplicativo no lado direito da tela.
15. Selecione **Mostrar mais**.
16. Selecione as **reticências** ao lado de formulário de visualização rápida de informações.
17. No menu exibido, selecione **Remover**.
18. Selecione as **reticências** ao lado de formulário de cartão de informações.
19. No menu exibido, selecione **Remover**.
20. Em Navegação, selecione o **formulário Linhas de despesa**.
21. Vá para a seção Neste aplicativo no lado direito da tela.
22. Selecione **Mostrar mais**.
23. Selecione as **reticências** ao lado de formulário de visualização rápida de informações.
24. No menu exibido, selecione **Remover**.
25. Selecione as **reticências** ao lado de formulário de cartão de informações.
26. No menu exibido, selecione **Remover**.
27. Selecione **Salvar** espere as alterações serem salvas.
28. Depois de Salvar, selecione o botão **Publicar** para publicar as alterações. Aguarde a conclusão da publicação.

### Tarefa nº 2: Testar app
**Iniciar o aplicativo**
1. Selecione o botão Reproduzir, e o novo aplicativo baseado em modelo será carregado em uma nova guia.

**Criar um novo Relatório de Despesas**
1. Selecione **Relatórios de despesas** na navegação à esquerda (também conhecida como mapa do site).
2. Selecione **+ Novo**.
3. Insira os campos da seguinte maneira:
    - Nome do relatório: **`New Test Report`**
    - Finalidade do relatório: selecione **`Conference`**
    - Data de conclusão do relatório: selecione **`Today's date`**
4. Selecione **Salvar e Fechar**. Isso criará o novo Relatório de Teste e você poderá vê-lo na exibição Relatórios de Despesas Ativas .
5. Altere o modo de exibição para **Relatórios de despesas com conclusão hoje** usando o menu suspenso ao lado de Relatórios de despesas ativas.
6. Você poderá adicionar mais alguns registros de teste.

O aplicativo baseado em modelo em execução será parecido com o seguinte:

![Captura de tela de um aplicativo baseado em modelo.](./Media/Model_driven_apps.png)

Parabéns! Você criou e configurou seu primeiro aplicativo controlado por modelos.
