<!DOCTYPE html><!--Esta tag é uma instrução utilizada no início de um documento HTML para indicar ao navegador da web qual é a versão do HTML que está sendo utilizada no documento.
Ela é uma abreviação de "Document Type Declaration" (Declaração do Tipo de Documento) e sua função é ajudar o navegador a renderizar corretamente o conteúdo do documento HTML.
Além disso, o uso correto desta tag também é importante para garantir que o documento seja válido e siga as especificações do W3C (World Wide Web Consortium).
Vale ressaltar que essa tag não é uma tag HTML propriamente dita, mas sim uma declaração que informa ao navegador qual a versão do HTML está sendo utilizada e como o conteúdo deve ser interpretado.-->

<html><!--esta tag é uma das tags fundamentais da linguagem HTML, sendo a raiz de todo documento HTML. Ela delimita o início e o fim do código HTML e define que todo o conteúdo do documento está dentro dela. Todos os outros elementos HTML devem ser filhos diretos ou indiretos da tag.-->

<head><!--Esta tag é utilizada no HTML para definir a seção do cabeçalho do documento, que contém informações sobre o documento, tais como o título, metadados e links para arquivos externos. Ela não é exibida na página, mas é fundamental para que os navegadores e mecanismos de busca possam entender e processar corretamente o conteúdo do documento. Todos os elementos dentro da tag head não são visíveis na página, apenas no código fonte.-->

	<title>Eletrolip</title><!--A tag <title> é utilizada para definir o título da página HTML, que aparece na aba do navegador e nos resultados de busca. Ele deve ser breve e descritivo, incluindo palavras-chave relevantes para o conteúdo da página.-->



	<link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Mynerve&display=swap" rel="stylesheet"><!--A primeira tag <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet"> está importando um conjunto de ícones do Material Design do Google. O atributo "href" aponta para a URL onde os ícones estão armazenados e o atributo "rel" indica que é uma folha de estilo.As outras três tags estão relacionadas à importação de fontes do Google Fonts. A tag <link rel="preconnect" href="https://fonts.googleapis.com"> pré-conecta o navegador com o servidor do Google Fonts para que o processo de carregamento das fontes seja mais rápido. A tag <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> faz a mesma coisa, mas para o servidor que armazena os arquivos de fonte. O atributo "crossorigin" é necessário para indicar que a fonte será utilizada em um domínio diferente do que a hospeda.A última tag <link href="https://fonts.googleapis.com/css2?family=Mynerve&display=swap" rel="stylesheet"> está importando uma folha de estilo de uma fonte chamada "Mynerve" do Google Fonts. O atributo "href" aponta para a URL da folha de estilo e o atributo "rel" indica que é uma folha de estilo.Essas tags são muito comuns em páginas web que utilizam fontes e ícones personalizados, e o Google Fonts é uma das fontes mais populares para se fazer isso.-->

	<link href="estilo/style.css" rel="stylesheet"/><!--Essa é uma tag que ajuda a página da web a parecer legal e organizada. Ela se conecta a um arquivo chamado "style.css" que contém as instruções de estilo para o visual da página. É como se fosse um uniforme para a página da web.-->

	<meta charset="utf-8"><!--A tag meta charset="utf-8" é utilizada para especificar o conjunto de caracteres (charset) utilizado no documento HTML. O valor "utf-8" é o conjunto de caracteres mais comum atualmente e suporta a maioria dos caracteres de todos os idiomas, incluindo caracteres especiais e acentos. A tag meta charset="utf-8" deve ser incluída dentro da tag head>do documento HTML para garantir que o navegador interprete corretamente o texto e os caracteres especiais.-->

	<meta name="viewport" content="width=device-width, initial-scale=1"><!--A tag meta name="viewport" content="width=device-width, initial-scale=1" é utilizada para definir a forma como a página será exibida em dispositivos móveis. Ela especifica que a largura da página deve ser igual à largura do dispositivo e que a escala inicial deve ser 1. Isso garante que o conteúdo da página seja exibido de forma responsiva e adaptável a diferentes tamanhos de tela.-->

	<meta name="description" content=""><!--A tag meta name="description" content= é utilizada para fornecer uma descrição do conteúdo da página HTML para os mecanismos de busca. O valor do atributo "content" contém uma breve descrição do conteúdo da página, que aparecerá nos resultados de pesquisa do Google e de outros mecanismos de busca. Isso pode ajudar os usuários a entenderem do que se trata a página antes de clicar no link para acessá-la. É recomendado que a descrição contenha até 160 caracteres e seja clara e objetiva.-->

	<meta name= "keywords" content=""><!--A tag <meta name="keywords" content=""> é utilizada para especificar uma lista de palavras-chave que descrevem o conteúdo da página HTML. O atributo "content" deve conter as palavras-chave separadas por vírgulas, sem espaços. As palavras-chave não são exibidas na página, mas são lidas pelos mecanismos de busca para ajudar a classificar e indexar o conteúdo da página.-->

</head>

<body><!--A tag body é utilizada para definir o conteúdo principal do documento HTML que será exibido no navegador. Ela delimita o início e o fim do corpo do documento, onde é inserido o conteúdo visível da página, como textos, imagens, links, entre outros. Todos os elementos HTML devem ser filhos diretos ou indiretos da tag body.-->

<header><!--Esse é um trecho de código para a cabeça de uma página. A parte que começa com <header> é onde fica o topo da página. Ali tem uma logomarca e dois menus: um para o computador e outro para o celular. Cada menu tem um monte de coisas para clicar e ir para outras páginas.-->
		<div class="center">
		<div class="logo left">ELETROLIP</div><!--Logomarca do meu site-->
		<nav class="desktop right">
			<ul>
				<li><a href="">Home</a></li>
				<li><a href="">Sobre</a></li>
				<li><a href="">Serviços<a/></li>
				<li><a href="">Contato</a></li>
			</ul>
		</nav>
		<nav class="mobile right">
			<div class="botao-menu-mobile">
				<i class= <span class="material-icons>
menu
</span>"/i></div>
			<ul>
				<li><a href="">Home</a></li>
				<li><a href="">Sobre</a></li>
				<li><a href="">Serviços<a></li>
				<li><a href="">Contato</a></li>
			</ul>
		</nav>
	<div class="clear"></div>
	</div><!--center-->
	</header>

<section class="banner-principal"><!--Esse código HTML define uma seção de banner principal contendo um formulário de e-mail. O formulário possui um cabeçalho <h2> que solicita o endereço de e-mail do usuário e dois elementos <input> para entrada de dados e envio do formulário. O primeiro elemento <input> é definido com o atributo type como "e-mail" para garantir que o usuário insira um endereço de e-mail válido e o segundo elemento <input> é definido com o atributo type como "submit" para permitir que o usuário envie o formulário para algum lugar. O atributo required é utilizado no primeiro elemento <input> para garantir que o campo de e-mail seja preenchido antes do envio do formulário.-->
	<div class="overlay"></div>
		<div class="center">
		<form>
			<h2>Seu e-mail</h2>
			<input type="e-mail" name="e-mail" required/>
			<input type="submit" name="acao" value="Cadastrar">
		</form>
	</div><!--center-->
	</section><!--banner-->

<section class="descricao"><!--Esse código HTML cria uma seção que contém informações sobre a empresa. A seção é dividida em duas colunas, a primeira contendo um título e um parágrafo com a descrição dos serviços elétricos oferecidos pela empresa, a segunda coluna contém uma imagem ilustrativa da empresa. A seção utiliza classes CSS "w50" para definir o layout em duas colunas de largura igual.-->
        
        <div class="center">
	    <div class="w50 left">
	        <h2>
			E L E T R O LIP!!!
		    </h2>
		    <p>A Eletrolip é especializada em fornecer serviços elétricos confiáveis e de alta qualidade para clientes residenciais e comerciais em nossa comunidade local. Com anos de experiência no setor, nossa equipe de técnicos qualificados é capaz de oferecer soluções personalizadas para atender às necessidades individuais de cada cliente. Estamos comprometidos em oferecer serviços seguros e eficientes, seguindo as normas de segurança e regulamentos governamentais, para garantir a satisfação e a segurança dos nossos clientes. Nós valorizamos a honestidade, a transparência e o atendimento ao cliente em todos os aspectos do nosso negócio.</p>
		</div><!--w50-->
		<div class="w50 left">
			<img class="right" src="imagens/Eletrolip.jpg" height="200">
		</div><!--w50-->   
		<div class="clear"></div>
	</div><!--center-->
	</section><!--descrição da empresa-->

	
<section class="especialidades"><!--Este trecho descreve uma seção chamada "Especialidades". Essa seção inclui três caixas diferentes, cada uma delas com um título, um ícone e uma breve descrição do serviço oferecido. As caixas estão organizadas em uma estrutura de grade usando classes CSS para alinhamento e estilo visual. A seção também possui um título principal "Especialidades" com a classe "title".-->
	<div class="center">
	<h2 class="title">ESPECIALIDADES</h2>
		<div class="w33 left box-especialidades">
			<h3>
				<span class="material-icons">
				blender</span>
             </h3>
			<h3>Eletrodomésticos</h3>
			<p>Nossa equipe de técnicos é especializada em reparar e manter aparelhos elétricos e eletrônicos, incluindo geladeiras, máquinas de lavar roupa, secadoras, fornos, fogões, entre outros. Estamos equipados com as ferramentas e conhecimentos necessários para solucionar problemas e manter seus eletrodomésticos funcionando perfeitamente.</p>
		</div><!--box-especialidade-->
		<div class="w33 left box-especialidades">
			<h3>
				<span class="material-icons">
                power</span>
            </h3>
			<h3>Instalações residenciais</h3>
			<p>Oferecemos serviços de instalação elétrica residencial, incluindo a instalação de novos sistemas elétricos, tomadas, interruptores, iluminação, quadros de distribuição e mais. Nossa equipe é altamente treinada para garantir a segurança e a eficiência em todas as nossas instalações.</p>
		</div><!--box-especialidade-->
		<div class="w33 left box-especialidades">
			<h3><span class="material-icons">
            wb_sunny
            </span>
            </h3>
			<h3>Energia renovável</h3>
			<p>Estamos comprometidos em ajudar nossos clientes a adotarem soluções de energia renovável, incluindo a instalação de painéis solares, turbinas eólicas, sistemas de aquecimento solar e muito mais. Nós acreditamos que a energia renovável é o futuro e estamos prontos para ajudar nossos clientes a fazerem a transição para fontes de energia mais limpas e sustentáveis.</p>
		</div><!--box-especialidade-->
</div><!--center-->
</section><!--especialidades-->


<section class="exrtas"><!--Aqui, temos uma seção criada usando a tag "section" com a classe "extras". Dentro desta seção, há um div com a classe "w50" que contém o título "DEPOIMENTOS" escrito em um cabeçalho de segundo nível "h2" com a classe "title".
Em seguida, temos três "divs" com a classe "depoimento-single", cada um contendo um cabeçalho de terceiro nível "h3" com o nome do cliente que deu o depoimento e um parágrafo "p" com o depoimento em si.
Por fim, temos um rodapé (footer) com um div com a classe "center" que contém um parágrafo "p" com a mensagem "Todos os direitos reservados".-->
	<div class="w50 left">
		<h2 class="title">DEPOIMENTOS</h2>
		<div class="depoimento-single">
			<h3>João</h3>
			<p>
				Contratei a Eletrolip para fazer a instalação elétrica da minha casa e fiquei muito satisfeito com o trabalho realizado. A equipe foi muito profissional, atenciosa e eficiente. Eles responderam a todas as minhas perguntas e me forneceram uma estimativa precisa do custo e do tempo necessário para concluir o trabalho. A qualidade do trabalho realizado superou minhas expectativas e agora tenho total confiança no sistema elétrico da minha casa. Recomendo fortemente os serviços da Eletrolip.
			</p>
		</div><!--dep-single-->
		<div class="depoimento-single">
			<h3>Alex</h3>
			<p>
				Recentemente, contratei a Eletrolipe para fazer a manutenção elétrica da minha empresa e fiquei muito feliz com o resultado. A equipe foi muito pontual, profissional e respeitosa em relação ao meu espaço de trabalho. Eles fizeram uma avaliação minuciosa do sistema elétrico e encontraram alguns problemas que eu nem sabia que existiam. Fiquei muito grato por terem resolvido esses problemas e me fornecerem soluções para evitar futuros problemas. A Eletrolipe é altamente recomendada para empresas que buscam serviços elétricos de qualidade.
			</p>
		</div><!--dep-single-->
		<div class="depoimento-single">
			<h3>Sandra</h3>
			<p>
				Eu tive um problema elétrico em casa e não sabia o que fazer. Foi então que um amigo me indicou a Eletrolipe. Entrei em contato com a empresa e fiquei impressionado com a rapidez e eficiência com que eles lidaram com a minha situação. A equipe foi muito atenciosa e me explicou tudo o que precisava ser feito. Eles resolveram o problema em um piscar de olhos e ainda me deram algumas dicas úteis para evitar futuros problemas elétricos. Eu recomendo fortemente os serviços da Eletrolipe para quem precisar de serviços elétricos confiáveis e eficientes.
			</p>
		</div><!--dep-single-->
	</div><!--w50-->
	<div class="w50 left">
		<h2 class="title">SERVIÇOS</h2>
		<div class="serviços">
		<ul>
			<li>Instalação elétrica em residências, comércios e indústrias</li>
			<li>Manutenção preventiva e corretiva em sistemas elétricos</li>
			<li>Projetos elétricos para construções novas e reformas</li>
			<li>Instalação de sistemas de energia solar</li>
			<li>Consultoria em eficiência energética</li>
		</ul>
		
	</div><!--w50-->
    </div><!--servicos-->
	<div class="clear"></div>

</section><!--extras-->


<footer>
	<div class="center">
		<p>Todos os direitos rervados</p>
	</div><!--center-->
</footer>




	

</body>
</html>
