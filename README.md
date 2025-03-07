## Importações iniciais
Importamos pyautogui para automatizar interações com a tela.

<div>Importamos time para adicionar pausas entre ações.
<div>Definimos pyautogui.PAUSE = 0.3 para dar um pequeno intervalo entre os comandos, evitando que o código execute rápido demais.
<div>Abrindo o Google Chrome
</div>
  
## Execução
<div>Automaticamente a tecla Windows abre o menu iniciar.
<div>Digita "Google Chrome" e abre o navegador.
<div>Clica se em uma posição específica (x=1011, y=492) para garantir que a janela esteja ativa.
<div>Acessando o Link de Login
<div>Digita se a URL https://dlp.hashtagtreinamentos.com/python/intensivao/login e pressionamos Enter.
<div>Usa se time.sleep(3) para esperar a página carregar.
</div>
  
## Fazendo Login
<div>Clicamos no campo de e-mail (x=828, y=376) e digitamos o email
<div>Pressionamos Tab para mudar para o campo de senha.
<div>Digitamos a senha e clicamos no botão de login (x=914, y=520).
<div>Esperamos 3 segundos para garantir que o login seja processado.
</div>


## Importando a Base de Produtos
<div>Importamos a biblioteca pandas para manipular a base de dados.
<div>Carregamos a planilha produtos.csv em um DataFrame chamado tabela.
<div>Exibimos a tabela com print(tabela).
</div>
  
##Cadastrando os Produtos
<div>Percorremos todas as linhas da tabela usando um for.
<div>Para cada produto, seguimos este processo:
<div>Clicamos no campo de código (x=719, y=257).
<div>Pegamos os valores da planilha e digitamos nos campos correspondentes, pressionando Tab para avançar.
<div>Se houver um campo de observação (obs), verificamos se está preenchido antes de digitá-lo.
<div>Pressionamos Enter para cadastrar o produto.
<div>Damos um scroll para cima para voltar ao topo da página.
<div>Repetição do Processo

<div>O código repete esse fluxo para cada produto até que todos sejam cadastrados.
