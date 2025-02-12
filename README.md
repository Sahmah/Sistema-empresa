Importamos pyautogui para automatizar interações com a tela.
Importamos time para adicionar pausas entre ações.
Definimos pyautogui.PAUSE = 0.3 para dar um pequeno intervalo entre os comandos, evitando que o código execute rápido demais.
Abrindo o Google Chrome

Pressionamos a tecla Windows para abrir o menu iniciar.
Digitamos "Google Chrome" e pressionamos Enter para abrir o navegador.
Clicamos em uma posição específica (x=1011, y=492) para garantir que a janela esteja ativa.
Acessando o Link de Login

Digitamos a URL https://dlp.hashtagtreinamentos.com/python/intensivao/login e pressionamos Enter.
Usamos time.sleep(3) para esperar a página carregar.
Fazendo Login

Clicamos no campo de e-mail (x=828, y=376) e digitamos "saramarialima43@gmail.com".
Pressionamos Tab para mudar para o campo de senha.
Digitamos "12345" e clicamos no botão de login (x=914, y=520).
Esperamos 3 segundos para garantir que o login seja processado.
Importando a Base de Produtos

Importamos a biblioteca pandas para manipular a base de dados.
Carregamos a planilha produtos.csv em um DataFrame chamado tabela.
Exibimos a tabela com print(tabela).
Cadastrando os Produtos

Percorremos todas as linhas da tabela usando um for.
Para cada produto, seguimos este processo:
Clicamos no campo de código (x=719, y=257).
Pegamos os valores da planilha e digitamos nos campos correspondentes, pressionando Tab para avançar.
Se houver um campo de observação (obs), verificamos se está preenchido antes de digitá-lo.
Pressionamos Enter para cadastrar o produto.
Damos um scroll para cima para voltar ao topo da página.
Repetição do Processo

O código repete esse fluxo para cada produto até que todos sejam cadastrados.
