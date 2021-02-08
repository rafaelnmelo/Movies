Arquitetura do Projeto

Arquitetura utilizada: MVP

Foi utilizada esta arquitetura pois al�m de minha maior familiaridade com a mesma, ele proporciona 
uma melhor separa��o das camadas do projeto. Tendo a Model como a camada de dados, a View 
com todos os elementos gr�ficos e finalmente o Presenter, que tem por sua miss�o integrar os 
dados da Model de uma forma apresent�vel para cada View 

Bibliotecas Utilizadas

Alamofire: utilizada para facilitar o gerenciamento de requisi��es da API do TheMovieDB.

Kingfisher: utilizado para efetuar o download e utiliza��o das imagens necess�rias

Requisitos

Os requisitos principais foram todos atendidos, sendo eles:

Tela de Home com duas abas:
Filmes: Um grid exibindo os filmes melhores classificados.
Favoritos: Uma listagem dos filmes marcados como favorito. 

Loading no carregamento da listagem de filmes;

Tela de tratamento de erros (falta de internet e erro na api) na tela de Filmes;

Tela de detalhe do filme com informa��es dos g�neros;

Favoritar um filme na tela de detalhe com armazenamento local. 


Extras

Como extra foi realizado a seguinte tarefa:

A��o de remover o filme da lista de Favoritos com swipe.
Adequa��o do tema do aplicativo pra ter uma sensa��o mais agrad�vel ao 
usu�rio sendo mais parecida com uma sala de cinema
