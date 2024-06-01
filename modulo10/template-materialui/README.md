# Lista de Modificacoes #

## ListarTafera.jsx ##

<ol>
  <li>
    Adicionado os states 'historicoTarefas' e 'mostrarHistorico' para controlar o historico de tarefas.
  </li>
  <li>
    Criacao do botao 'Mostrar Historico' para alternar a exibicao do historico de tarefas.
  </li>
  <li>
    Criacao do segundo bloco de tabela para exibir o historico de tarefas quando 'mostrarHistorico' e true.
  </li>
  <li>
    Modificacao da Logica de exclusao para mover tarefas concluidas para o historico.
  </li>
</ol>

## AlertDialog.jsx ##

<ol>
  <li>
    Novo componente 'AlertDialog' para exibir dialogo de confimacao.   
  </li>
  <li>
    Recebe as props 'open', 'handleClose', 'handleConfirm', 'title' e 'description'. 
  </li>
  <li>
    Utiliza o componente 'Dialog' do Material-UI para exibir o dialogo. 
  </li>
  <li>
    Exibe um titulo e uma descricao no corpo do dialogo.
  </li>
  <li>
    Adiciona botoes de acao para confirmar ou cancelar a operacao.
  </li>
</ol>

## Adicao do componente AlertDialog no ListarTarefa.jsx ##

<ol>
  <li>
    Adicao do componente 'AlertDialog' para mostrar um dialogo de confirmacao antes de excluir uma tarefa.
  </li>
  <li>
    Implementacao do componente 'AlertDialog' para exibir um dialogo de confirmacao ao tentar excluir uma tarefa. 
  </li>
  <li>
    Implementacao a logica para abrir e fechar o dialogo de confirmacao.
  </li>
</ol>

# Modificacao dos Estilos #
## index.js ##

<ol>
  <li>
    Adiciona classes .table-row-even e .table.row.odd para estilizar as linhas da tabela alternadamente.
  </li>
</ol>

1. Clonar o repositório
2. Localmente, entrar na pasta do projeto e instalar as dependências:
   `
   npm install
   `
3. Executar a aplicação:
   `
   npm start
   `