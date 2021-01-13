# Estratégia de Transformação Digital e Governo Aberto na SME

Como um governo pode atuar para garantir o bem comum de todos? Na SME, acreditamos que um dos meios para isso seja garantir transparência e prestação de contas e constante relação entre governo e sociedade para o desenvolvimento e implementação de políticas públicas. 

A Portaria SME nº 8.008, de 12 de novembro de 2018 oficializou a estratégia da Secretaria Municipal de Educação de SP para que nossas ações sejam pautadas nos princípios de Governo Aberto e para usarmos os valores e benefícios do mundo digital para melhorarmos nossos processos e serviços para os cidadãos. Com isso, pretendemos: 

- aumentar os níveis de transparência ativa e de abertura de dados, garantindo a proteção de dados pessoais; 
- instituir metodologias ágeis e colaborativas como parte do processo de desenvolvimento e de evolução de sistemas administrativos e de serviços digitais; 
- fortalecer o controle das políticas educacionais e da aplicação de recursos por parte da gestão e da sociedade; 
- promover espaços e metodologias de colaboração entre governo, academia, sociedade civil e setor privado. 

O [Ateliê do Software](http://forum.govit.prefeitura.sp.gov.br/uploads/default/original/1X/c88a4715eb3f9fc3ceb882c1f6afe9e308805a17.pdf) é uma das ferramentas para operacionalização. Baseado em um modelo de contratação inspirado pelos movimentos ágil e de Software Craftsmanship, trabalhamos com equipes multidisciplinares para o desenvolvimento de produtos que beneficiam toda a comunidade escolar (técnicos da SME e DREs, gestores, professores, alunos e famílias) e concretizam os objetivos da Estratégia de Transformação Digital e Governo Aberto “Pátio Digital”.

# Conteúdo
1. [Sobre o Produto](#sobre-o-produto) 
2. [Como Surgiu](#como-surgiu)  
3. [Links Úteis](#links-úteis)  
4. [Comunicação](#comunicação)  
5. [Como Contribuir](#como-contribuir)  
6. [Repositórios](#repositórios)  
7. [Instalação e Configuração](#instalação-e-configuração)

# Sobre o Produto

## Visão do Produto

Para a **qualquer cidadã(o) interessada(o) que queira consultar de forma intuitiva e obter em linguagem simples os dados da Rede Municipal de Educação (RME) de São Paulo**

O **Escola Aberta** 

É uma **aplicação web responsiva** 

Que **permite a busca pelas escolas municipais a partir de seu nome ou de um dado endereço e apresenta de forma didática e atraente suas principais estatísticas (como séries, períodos, quantidade de turmas e de estudantes, vagas oferecidas e atendidas, quantos e quais profissionais trabalham lá, que ambientes a escola possui e como está a avaliação dela no Índice de Desenvolvimento da Educação), além de apresentar os dados gerais agregados da RME, com algumas opções de recorte (como por Diretoria Regional de Educação)**

Ao contrário do **Portal de Dados Abertos ou do EOL Gerenciamento,**

O Escola Aberta **não exige um conhecimento prévio aprofundado em bases de dados ou na estruturação da RME.**

## Objetivos de negócio

Oferecer mecanismo de busca amigável para consulta aos dados da Rede Municipal de Educação já disponíveis no Portal Dados Abertos, com retorno das informações em linguagem simples (incluindo gráficos e mapas interativos).

## Personas

**Quem:** cidadã(o) em geral
**Características principais e necessidades:** qualquer pessoa interessada em consultar de forma rápida e simples as escolas municipais mais próximas de sua casa ou de um dado endereço e ter acesso em linguagem simples às estatísticas não apenas dessas unidades, mas de toda a Rede Municipal de Ensino de São Paulo.

**Quem:** estudantes e famílias
**Características principais e necessidades:** público já engajado na Rede Municipal de Ensino, que busca o Escola Aberta para ter dados gerais de sua escola e, também, uma visão mais ampla da Rede Municipal de Ensino – e, assim, conseguir participar mais ativamente de sua gestão democrática.

**Quem:** servidores
**Características principais e necessidades:** buscam informações e dados gerenciais apresentados de forma simples e atraente a respeito  da  Rede  Municipal  de  Ensino  de  São  Paulo,  para  subsidiar  seus  trabalhos  de  análise  e  planejamento  da  política  educacional  nas  diferentes  áreas  e  escalas  (como  Educação  de  Jovens  e  Adultos  –  EJA  ou  determinada  Diretoria  Regional  de  Educação  -  DRE).

**Quem:** jornalistas e demais comunicadores
**Características principais e necessidades:** consomem informações e dados sobre a Rede Municipal de Educação, para levantar pautas e subsidiar suas matérias.

**Quem:** pesquisadores 
**Características principais e necessidades:** consomem informações e dados sobre a Rede Municipal de Educação, como subsídio para os estudos e análise da política educacional da Prefeitura de São Paulo, que contribuem com o seu constante aprimoramento.

## Funcionalidades

- Busca pelas escolas municipais mais próximas de um dado endereço (logradouro).
    
- Apresentação dos resultados da busca por endereço em mapa interativo, com georreferenciamento e dados de contato (endereço e telefone).
    
- Apresentação (em tabelas e gráficos) dos principais números de cada escola municipal, como as séries ofertadas, períodos, quantidade de turmas e de estudantes, vagas oferecidas e atendidas, quantos e quais profissionais trabalham lá, que ambientes a escola possui e como está a avaliação dela no Índice de Desenvolvimento da Educação (IDEP).
    
- Busca pelos dados agregados da Rede Municipal de Ensino, a partir dos seguintes filtros, que podem ser combinados: Distrito, Subprefeitura, Diretoria Regional de Ensino e tipo de unidade escolar.
    
- Apresentação (em tabelas) das principais estatísticas da Rede Municipal de Ensino, divididas em quatro grandes categorias temáticas (escolas, Profissionais, Vagas e Matrículas e Ambientes).
    
## Jornadas

- O(a) usuário(a) acessa a homepage do Escola Aberta e digita o endereço para o qual quer buscar as escolas municipais mais próximas ou o nome da unidade específica que procura. Ele(a) então terá o retorno da busca em mapa interativo, que informa também o endereço exato e dados de contato de cada unidade. A partir daí, ao clicar em estatísticas, ao lado do nome de uma determinada escola, ele(a) terá acesso à página na qual é possível consultar (em tabelas e gráficos) os principais números da escola, divididos em quatro áreas: séries e estudantes, vagas e matrículas, ambientes e Idep (quando couber).

- O(a) usuário(a) acessa a homepage do Escola Aberta e seleciona no menu superior o item “Busca por Filtro”. Ele(a) então seleciona o Distrito e/ou Subprefeitura e/ou Diretoria Regional de Ensino e/ou tipo de unidade escolar que deseja consultar. Ele(a) então terá o retorno da busca em mapa interativo, que informa também o endereço exato e dados de contato de cada unidade. A partir daí, ao clicar em estatísticas, ao lado do nome de uma determinada escola, ele(a) terá acesso à página na qual é possível consultar (em tabelas e gráficos) os principais números da escola, divididos em quatro áreas: séries e estudantes, vagas e matrículas, ambientes e Idep (quando couber).

- O(a) usuário(a) acessa a homepage do Escola Aberta e seleciona no menu superior o item “Conheça a Rede”. Ele(a) então terá acesso à página na qual é possível consultar as principais estatísticas da Rede Municipal de Ensino, divididas em quatro grandes categorias temáticas (escolas, Profissionais, Vagas e Matrículas e Ambientes).

## Roadmap

**Release 1**

Homepage com mecanismo de busca por endereço ou nome de unidade

**Release 2**

Busca por filtro e retorno da busca (principal e por filtro) em mapa interativo

**Release 3**

Números de cada escola apresentados em tabelas e gráficos, divididas em quatro categorias: séries e estudantes, vagas e matrículas, ambientes e Idep (quando couber).

**Release 4**

Estatísticas agregadas da Rede Municipal de Ensino apresentadas em gráficos e divididas em quatro categorias: escolas, Profissionais, Vagas e Matrículas e Ambientes.

# Como surgiu

**Diagnóstico:** os dados da Rede Municipal de Ensino estavam disponíveis com busca pouco amigável e apresentação de difícil compreensão no EOL gerenciamento: [http://eolgerenciamento.prefeitura.sp.gov.br/frmgerencial/NumerosCoordenadoria.aspx?Cod=000000 (http://eolgerenciamento.prefeitura.sp.gov.br/frmgerencial/NumerosCoordenadoria.aspx?Cod=000000)

**Benchmark:**[https://www.qedu.org.br/escola/192016-emef-luiz-david-sobrinho-prof/sobre](https://www.qedu.org.br/escola/192016-emef-luiz-david-sobrinho-prof/sobre)

## Protótipos:

**Home page:** [https://www.figma.com/file/Pxhwd1fPmKEgZM692v7xHjV1/Escola-Aberta_MPV1?node-id=357%3A0](https://www.figma.com/file/Pxhwd1fPmKEgZM692v7xHjV1/Escola-Aberta_MPV1?node-id=357%3A0)

**Resultado da busca:** [https://www.figma.com/file/Pxhwd1fPmKEgZM692v7xHjV1/Escola-Aberta_MPV1?node-id=458%3A2](https://www.figma.com/file/Pxhwd1fPmKEgZM692v7xHjV1/Escola-Aberta_MPV1?node-id=458%3A2)

**Estatísticas:** [https://www.figma.com/file/Pxhwd1fPmKEgZM692v7xHjV1/Escola-Aberta_MPV1?node-id=652%3A1071](https://www.figma.com/file/Pxhwd1fPmKEgZM692v7xHjV1/Escola-Aberta_MPV1?node-id=652%3A1071)

# Links Úteis

**Homologação:**

[https://hom-escolaaberta.sme.prefeitura.sp.gov.br/escolaaberta/](https://hom-escolaaberta.sme.prefeitura.sp.gov.br/escolaaberta/)

**Produção:**

[http://educacao.sme.prefeitura.sp.gov.br/escolaaberta](http://educacao.sme.prefeitura.sp.gov.br/escolaaberta)

# Comunicação

| Canal de comunicação | Objetivos |
|----------------------|-----------|
| [Issues do Github](https://github.com/prefeiturasp/SME-PTRF/issues) | - Sugestão de novas funcionalidades<br> - Reportar bugs<br> - Discussões técnicas |

# Como contribuir

Contribuições são **super bem vindas**! Se você tem vontade de construir o Escola Aberta  conosco, veja o nosso [guia de contribuição](./CONTRIBUTING.md) onde explicamos detalhadamente como trabalhamos e de que formas você pode nos ajudar a alcançar nossos objetivos. Lembrando que todos devem seguir nosso [código de conduta](./CODEOFCONDUCT.md).

## Repositórios

[SME-EscolaAberta]
[https://github.com/prefeiturasp/SME-EscolaAberta](https://github.com/prefeiturasp/SME-EscolaAberta)

[SME-EscolaAberta-API}
[https://github.com/prefeiturasp/SME-EscolaAberta-API](https://github.com/prefeiturasp/SME-EscolaAberta-API)

[SME-EscolaAberta-Front]
[https://github.com/prefeiturasp/SME-EscolaAberta-Front](https://github.com/prefeiturasp/SME-EscolaAberta-Front)

## Instalação e Configuração

## Requisitos

Para contribuir com o desenvolvimento da Plataforma:

## API:
- Docker e Docker Compose

## Front:
- NPM

## Clonar os repositórios
`git clone --recurse-submodules -j8 https://github.com/prefeiturasp/SME-EscolaAberta.git`
`cd SME-EscolaAberta`

## Criação da pasta e arquivo com variaveis de ambiente
`mkdir .env`
`vim .env/database`

## Inserir as seguintes variaveis
`POSTGRES_HOST=db`
`POSTGRES_PORT=5432`
`POSTGRES_DB=escola_aberta`
`POSTGRES_USER=postgres`
`POSTGRES_PASSWORD=postgres`
`DEBUG=True`

## Build
`docker-compose build` or `make build`.

## Migrar o banco de dados
`make migrate`.

## Executar o projeto
`docker-compose up`.
