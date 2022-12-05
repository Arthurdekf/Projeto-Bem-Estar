# UNIVERSIDADE DE RIBEIRÃO PRETO ENGENHARIA DE SOFTWARE

### Arthur Fedeli – RA:837032 
### João Victor – RA:837396 
### Yuri Martins – RA:837354

## EVENTO: BEM ESTAR NO SHOPPING

RIBEIRÃO PRETO, 2022.

Trabalho entregue para obtenção de parte da nota da Disciplina de **Programação para Web II** do curso de Engenharia de software, turma 3º etapa.

Docente: Prof. Fabiano Goncalves dos Santos. Dedicamos também como atividade avaliativa para obtenção de parte da nota da Disciplina de **Gestão de Projetos**. Docente: Prof. Alexandre da Silva Mello.

**SUMÁRIO**

1. [DISCIPLINAS RELACIONADAS A CONSTRUÇÃO DO PROJETO	4](#_bookmark0)
2. [EQUIPAMENTOS E SOFTWARES USADOS	5](#_TOC_250006)
3. [DESCRIÇÃO DO SITE PROPOSTO	6](#_TOC_250005)
4. ESTRTURA DO SITE[	6](#_TOC_250004)
5. MAPA DO SITE[	6](#_TOC_250003)
6. CONCLUSÃO[	6](#_TOC_250002)

**SUMÁRIO DE ILUSTRAÇÕES**


Figura 1 Quadro do Trello

[Figura 2 Chamada no Discord	](#_bookmark0)5

Figura 3 Grupo no WhatsApp	6

Figura 4 Tabela de usuário	6

Figura 5 Relacionamento das tabelas no DB	7

Figura 6 View do form para usuário	7

Figura 7 Conexão com o DB	8

Figura 8 Drive do Google	8

Figura 9 Tela inicial do projeto	10

Figura 10 Tela do cadastro de usuário	10

Figura 11 Tela de login do usuário	11

Figura 12 Tela de busca dos pacientes	11

Figura 13 Tela de cadastro do paciente	12

Figura 14 Mapa do site	13










#
#
# **1    DISCIPLINAS RELACIONADAS A CONSTRUÇÃO DO PROJETO**

Este documento tem como finalidade apresentar os procedimentos realizados durante a criação do projeto Bem Estar no Shopping, fazendo-se o uso de metodologias ágeis aprendidas na disciplina de **Gestão de Projetos** e que devido estes registros, é possível ter o controle e a facilitação de visualização do processo de gestão/desenvolvimento, permitindo futuramente a fácil manutenção e entendimento do mesmo.

Já na disciplina de **Programação para Web II**, o grupo teve pouca dificuldade em relacionar a mesma com as disciplinas de **POO** e **Banco de Dados**. Tendo em vista essas disciplinas, foi possível criar um sistema completo com o Back-end e banco de dados para o evento Bem Estar no Shopping.



2. **EQUIPAMENTOS E SOFTWARES USADOS**

Utilizamos algumas ferramentas de gerenciamentos ágeis, pois, enxergamos a necessidade de gerir o projeto e garantir o controle do desenvolvimento para conseguirmos concluir com a proposta final da aplicação.

O grupo teve o intuito de usar um sistema ágil, de fácil acesso e de acordo com o que foi passado nas aulas de gestão de projetos, e com isso usamos o Kanban, que faz o uso de cartões para o ajudar na interação do grupo com o projeto. Assim, fizemos o uso do Trello, o mesmo software usado em sala de aula, além disso também usamos o próprio Trello para compartilhar alguns arquivos com o grupo usando os anexos nos cartões.

Além do mais, outras plataformas foram usadas tanto nas sprints quanto na confecção de nosso EAP, entre elas o Discord, WhatsApp Web e Draw.io. Por último, o grupo usou o google Drive para guardar os dados mais importantes do projeto, como o código-fonte. As ferramentas utilizadas foram:


<https://trello.com/b/ZhWL4jw5/projeto-integrado>

Figura 1. (Quadro do Trello: Projeto em desenvolvimento).






Figura 2. (Chamada no Discord: Organizando partes do projeto).






Figura 3. (Grupo no WhatsApp: Organizando partes do projeto).


No desenvolvimento da estrutura do site, ultilizamos o MySQL pois usamos em sala de aula na disciplina de Programação para WEB II:


Figura 4. (MySQL: Tabela de usuário).




Figura 5. (MySQL: Relacionamento das tabelas no DB).

Para o desenvolvimento tanto do backend quanto o design do projeto, utilizamos o Visual Studio Code:

Figura 6. (Visual Studio Code: View do form para usuário).







Figura 7. (Visual Studio Code: Conexção com o DB usando Post).






Figura 8. (Drive do Google: Pasta compartilhada).








2. **DESCRIÇÃO DO SITE PROPOSTO**

**	O projeto Bem Estar, tem como viés de auxiliar no cadastro dos pacientes que irão realizar os exames no evento do shopping, em uma única plataforma , no qual deverá ser baseada no banco de dados de cada exame de cada paciente, consequentemente, permitindo realizar fazer login pelo usuário do evento que possuirá um ID, que irá visualizar dados a respeito de cada paciente cadastrado, os exames serão guardados e podendo ser adicionados, excluídos e atuaizados.

`	`Durante a etapa de elicitação de requisitos, utilizamos como metodologia, sprints com o grupo completo para podermos colocar as ideias em prática. A escolha do leiaute foi feita com a mesma metodologia e voltada diretamente no tema “Bem Estar”, usando paleta de cores claras, design minimalista, focando na coleta de dados dos exames realizados durante o evento.






2. **ESTRUTURA DO SITE**

O site tem função de permitir o cadastro de um usuário, que ao se cadastrar poderá visualizar os pacientes cadastrados no sistema, permitindo a interação com os exames de cada paciente cadastrado, editando, excluindo e adicionando novos exames.

Para a realização desta aplicação, as telas foram divididas e, Login, Cadastro, dentro da tela de pacientes, Busca de paciente um menu para o Cadastre o paciente,  Exames e Usuário, voltando para o menu do usuário. Segue as imagens das telas:



Figura 9. (Projeto: Tela inicial)





Figura 10. (Projeto: Tela de cadastro do usuário)

#
#
#
#
#
#
# Figura 11. (Projeto: Tela de login do usuário)
#
#
#
#
#
#
#
# Figura 12. (Projeto: Tela de busca dos pacientes)
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
# Figura 13. (Projeto: Tela de cadastro do paciente)
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
2. # **MAPA DO SITE**
#
#
#
#
#
# Figura 14. (Mapa do site: Fluxo do sistema)
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
2. # **CONCLUSÃO**
#
# `			`Nesta primeira etapa, foram desenvolvidas toda parte de gestão e do protótipo do front-end, tendo início e preparo para etapas futuras do desenvolvimento do back-end. Por tanto, concluindo a parte do front-end completa (HTML, CCS, JavaScript com Bootstrap), fizemos também o backlog do produto e toda administração do tempo e recursos, implementações que serão utilizadas na próxima etapa na parte de Programação Orientada a Objeto e do banco de dados, duas disciplinas quais tivemos dificuldade de aplicar no projeto e o grupo teve que disponibilizar mais tempo durante o decorrer do projeto para estudar antes de desenvolver a aplicação do site.
# `			`O orçamento do projeto completo incluindo o banco de dados, páginas web e configurações tem o valor de R$ 1600,00. O tempo gasto com pesquisas e estudos para a realização do projeto não foi levado em consideração para o orçamento final do projeto.
