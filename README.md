# Manual do usuário Kappta v.0.01
![Kappta](/Imagens/ImagemKappta.PNG)
## Autor: Adalberto Gonçalves
## Revisor: Victor Braz

Ano: 2022
=

## Índice

1. Introdução
2. Acessando o kappta
   1. Redifinição de senha 
   2. Recuperação do login
   3. Botões de ação
3. Módulos do sistema
   1. Origens comerciais
   2. Grupos
   3. Usuários
   4. Jornadas
   5. Formularios
   6. Mesa
   7. Relatórios
   8. Administração
4. Glossário

# 1.Introdução
O sistema foi construído visando lhe proporcionar fácil entendimento para utilizá-lo, para isso tivemos o cuidado para que todas as telas fossem intuitivas e que suas funções ficassem explicitas. A proposta deste documento é lhe auxiliar a interagir com o sistema Kappta v.0.01, apresentado as funcionalidades de modo prático, seguindo um modelo passo a passo, visando desta forma contribuir e facilitar sua experiência, como também contribuir com você para obter todos os recursos do sistema.  
# 2.Acessando o kappta
Na inclusão de um usuário, o sistema irá enviar um e-mail solicitando a confirmação do cadastro. Mais adiante será mostrado que para o cadastro de usuário é necessário informar um endereço de e-mail. 
![EmailConfirmacao](/Imagens/EmailConfirmacao.PNG)
Ao clicar em 'Confirmação de Cadastro', será exibido a tela para que seja indicada a senha. 
![CadastroSenha](/Imagens/PrimeiroAcesso.PNG)

A senha deve possuir entre 8 e 30 caracteres, contendo no mínimo uma letra maiúscula, uma letra minúscula e um numeral, caso a senha informada não obdeça a estes requisitos será exibida uma mensagem de erro e solicitado a digitação da senha seguindo os critérios informados. Efetuando o complemento do cadastro adequadamente, a próxima tela a ser exibida será o módulo que o usuário tem acesso.

Para acessar o kappta posteriormente o usuário deverá digitar em seu navegador de preferência, a URL disponibilizada pela equipe do kappta, que será a mesma disponibilizada no primeiro acesso. Após digitação da URL e confimação a tela abaixo será exibida em seu navegador.
![TelaLogin](/Imagens/TelaLogin.PNG)

# 2.1 Redifinição de senha
Caso seja necessário definir outra senha, na tela de login, é só clicar em 'Recuperar senha'. 

![TelaLogin](/Imagens/TelaLogin.PNG)
Será solicitado a digitação do endereço de e-mail, este deve ser o mesmo que foi informado na criação do seu usuário, pois o sistema fará esta checagem, só enviando o link para a redifinição de senha se o e-mail coincidir.

![RedefinirSenha](/Imagens/RedifinicaoSenha.PNG)
Após informar o e-mail e clicar em enviar, será enviado um e-mail para a caixa de entrada do endereço informado.
![EmailRecuperarSenha](/Imagens/EmailRecuperarSenha.PNG)

Clicando em 'Redefinir Senha' será exibida a tela solicitando que seja informada uma nova senha obdecendo os critérios de tamanho mínimo, contendo caracteres maiúsculos e minúsculos e números, confome já descrito neste material.

![TelaRedefinirSenha](/Imagens/TelaRedefinirSenha.PNG)

# 2.2 Recuperar Login
Caso não lembre qual seja o seu login para o sistema kappta, na tela inicial.
![TelaLogin](/Imagens/TelaLogin.PNG)

Selecione recuperar login, informe o endereço de e-mail e clique em enviar, o sistema irá enviar um e-mail informando qual é o seu usuário.
![RecuperarLogin](/Imagens/RecuperarLogin.PNG)

O e-mail enviado será conforme modelo abaixo.
![EmailRecuperarLogin](/Imagens/EmailRecuperarLogin.PNG)

# 2.3 Botões de ação
Toda a interação no sistema será através de botões, as descrições e imagens utilizados nos mesmos são intuitivas:
 [BotaoIncluir](/Imagens/BotaoIncluir.PNG) Inclusão de um novo item.

![BotaoPesquisar](/Imagens/BotaoPesquisar.PNG) Ativa a pesquisa de algum ou mais de um filtro que tenha sido preenchido.

![LimparFiltros](/Imagens/BotaoLimpar.PNG) Efetua a limpeza dos filtros utilizados para a consulta de uma única vez.

![BotaoAlterar](/Imagens/BotaoAlterar.PNG) De acordo com o item selecionado, será aberta uma janela com dados cadastrados para este item.

![BotaoSalvar](/Imagens/BotaoSalvar.PNG) As alterações ou inclusão só serão efetivadas após a confirmação do clique no botão.

![BotaoAtivoAcionado](/Imagens/BotaoAtivoAcionado.PNG) e ![BotaoAtivoDesabilitado](/Imagens/BotaoAtivoDesabilitado.PNG) Estes botões tanto informam como podem mudar o status dos registros para ativo ou inativo.

# 3.Módulos do sistema
A divisão em módulos visa facilitar a distribuição de responsabilidades por usuário, pois desta forma cada  usuário terá disponível após logar no sistema, acesso apenas ao que for relacionado a sua função, permitindo assim um foco maior em suas competências.
![TelaModulo](/Imagens/TelaModulos.png)

## 3.1. Origens comerciais
As origens comerciais, são também denominadas de filiais, onde a empresa pode ter uma ou diversas origens comerciais, com a inclusão individual, é possível customizar quais produtos serão diponibilizados por origem comercial.

![TelaOrigemComercial](/Imagens/ModuloOrigensComerciais.PNG)

Ao selecionar a opção origens, será exibido a lista com todas as origens comerciais já cadastrada, se esta é a primeira origem a ser cadastra a lista estará vazia.

![TelaInicialOrigemComercial](/Imagens/TelaInicialOrigemComercial.PNG)
- Para filtrar alguma filial específica ou uma lista, preecha parcialmente o campo título e clique em pesquisar, o sistema irá pesquisar parcialmente pelas iniciais indicadas.
- Para ativar ou desativar uma filial, vá em ativo e mude o status, ativo ficará na cor 'azul'.
- Caso deseje efetuar alterações clique na imagem do lápis para o item desejado, será disponibilizada a tela semelhante a de cadastro para que suas alterações sejam efetivadas.
- Para a inclusão de um novo item, clique no botão inserir, será exibido a tela com os seguintes campos a serem informados:
![TelaInclusaoOrigem](/Imagens/TelaInclusaOrigem.PNG)
- Lista dos campos e suas finalidades;
  - Nome: O nome da origem comercial.
  - Código externo: As empresas geralmente enumeram as suas filias, caso exista, esta é a informação a ser preenchida, caso contrário terá que ser criado um valor, pois o campo é obrigatório.
  - CEP: Código postal da localização da filial.
  - CNPJ: Número do cadastro nacional da pessoa jurídica.
  - Grupo: Indicar o grupo em que filial faz parte, caso exista, este grupo é uma forma de controle das filiais pela empresa, mais adiante iremos detalhar o cadastramento do mesmo.

## 3.2 Grupos
Os grupos, serão criados para organizar as origens comerciais, se o usuário assim o desejar, pois desta forma poderemos unificar algumas origens em apenas um grupo e este grupo direcionado para um coordenador. Unindo em grupos também irá proporcionar a criação de relatórios por grupo de origens comerciais.
![TelaGrupo](/Imagens/TelaGrupo.PNG)
 - Para filtrar algum grupo específico, informe o nome no título, basta as inciais, ao clicar no botão pesquisar e a lista será disponibilizada.
 - Caso deseje alterar clique no ícone do lápis no item que se deseja alterar e a tela com os campos disponíves será disponibilizada.

![TelaCadastroGrupo](/Imagens/TelaCadastroGrupo.PNG)
- Para inserir um novo grupo é só informar o título e clicar no botão salvar.

## 3.3 Usuários
Este módulo será o responsável pelo acesso e qual as funções específicas cada usuário irá executar, pois de acordo com o perfil cadastrado, o sistema irá disponibilizar apenas as funções referentes ao perfil cadastrado, proporcionando desta forma um maior foco nas atividades por usuário.

Para cada usuário, logo após o cadastro, o mesmo será inserido na lista e o campo status ficará com uma exclamação, o motivo é que o usuário não fez nenhum acesso, ao primeiro acesso a exclamação não constará mais.
![StatusAcesso](/Imagens/StatusAcesso.PNG)


### 3.3.1 Promotor
O promotor é o usuário do sistema que fica resposável em obter novas propostas comerciais, este irá se relacionar diretamente com o público, ofertando o produto.
![TelaPromotor](/Imagens/TelaPromotor.PNG)
Seguindo o padrão, todos os promotores serão listados, caso seja necessário pesquisar um específico, é necessário preencher mesmo que parcial alguns dos campos e clicar em pesquisar.
Ao solicitar a inclusão de um novo promotor será exibido a tela.
![TelaInserirPromotor](/Imagens/TelaInserirPromotor.PNG)
- Listas de campos e suas finalidades;
  - Nome: É o nome completo do promotor,
  - Login: Este será o nome do usuário que o promotor deverá digitar para acessar o sistema.
  - E-mail: Este será o endereço para onde será enviado as instruções para completar o cadastro e poder acessar o sistema, também será o endereço utilizado para a recuperação de senha e usuário.
  - Usar e-mail secundário: Caso seja ativado tudo o que foi comentado para o campo E-mail será substituido pelo campo E-mail secundário.
  - Origens comerciais: Neste será selecionado em quais origens comerciais o promotor irá atuar, pode ser de 1 a várias origens comerciais.

Ao acessar o sistema será solicitado ao promotor que selecione a origem comercial em que está atuando no dia.

![TelaInicialPromotor](/Imagens/TelaInicialPromotor.PNG)

Após a seleção da origem comercial.

![TelaPromotorPropostas](/Imagens/TelaPromotorPropostas.PNG)
Ao solicitar a inclusão de uma nova proposta é exibido os produtos.

![TelaPromotorProdutos](/Imagens/TelaPromotorProdutos.PNG)

Ao selecionar um dos produtos, será solicitado a inclusão dos dados do cliente.
![TelaPromotorInserirProposta](/Imagens/TelaPromotorInserirProposta.PNG)
- Lista de campos e suas finalidades;
  - CPF: Número do cadastro único do cliente.
  - Data Nascimento: A data de nascimento do cliente. 
  - Nome: O nome do cliente.

Após confirmar o cadastro, e solicitar a inclusão, será solicitado a confirmação do produto.
![TelaPromotorConfirmarProduto](/Imagens/TelaPromotorConfirmarProduto.PNG)
Confirmando o produto o sistema iniciará o processo de validação.
![TelaAnalisandoProposta](/Imagens/TelaAnalisandoProposta.PNG)
Após o término da análise da proposta, será exibido a tela com as propostas pendentes.
![TelaPropostaEmAndamento](/Imagens/TelaPropostasEmAndamento.PNG)

### 3.3.2 Analista
O analista é o usuário que ficará responsável em analisar as propostas que ficaram pendentes.
![TelaCadastroAnalista](/Imagens/TelaCadastroAnalista.PNG)
Para efetuar a pesquisa dos analistas cadastrados 

![TelaNovoAnalista](/Imagens/TelaNovoAnalista.PNG)
- Lista de campos e suas finalidades;
  - Nome: Nome do analista.
  - Login: Nome para acesso ao sistema.
  - E-mail: Este será o endereço para onde será enviado as instruções para completar o cadastro e poder acessar o sistema, também será o endereço utilizado para a recuperação de senha e usuário.
  - Usar e-mail secundário: Caso seja ativado tudo o que foi comentado para o campo E-mail será substituido pelo campo E-mail secundário.





# 4.Glossário
**White label** - É um conceito de mercado que descreve a terceirização do desenvolvimento de produtos e serviços, criando um molde que pode ser personalizado e redistribuído. Significa que um item ou plataforma foi desenvolvido por uma empresa, mas recebeu a marca de uma parceira que o revende a seus clientes.
