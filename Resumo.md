# Dicionário:

### Computação em nuvem
- Modelo *pay per use*
- Funcionalidades que os servidores locais não possuem

### *Serverless*
- Mode de serviços distribuídos em que o processamento e armazenamento não é mais somente feito em um único computador.

# Com o que se preocupar?

- Armazenamento
- Distribuição
- Limpeza
- Transformação e relacionamento
- Transporte

# Lembretes

- Os dados podem mudar com tempo, então as soluções podem ser atualizadas.
- Modelo serverless não precisa ser em nuvem.
- O comportamento e os tipos de dados são característicos de cada ambiente, então idealmente soluções não devem ser reaproveitadas.
- Sistemas que estão entrelaçados possuem uma dependência das funções entre si, e caso alguma delas apresente problemas, pode ser complicado fazer a troca da mesma no mesmo sistema, pois nunca se sabe o que pode usando-a.
- Arquiteturas distribuídas pode-se trabalhar nessa parte que houve problema com mais liberdade e versioná-la caso seja preciso.

# Funções

## Coleta
- Escolher ferramentas para coletar informações
- Ser capaz de ler todos os tipos de dados
- Encaminhar os dados para o local correto

## Transformação
- Validar os dados
- Ex.: Dados faltantes

## Armazenamento
- Centralizada ou distribuída

## Distribuição
- Disponibilizar dados de forma democrática.
- Fácil acesso aos dados para todos os profissionais

# Perfis

## Analista
- **Função:** Analisar de dados.
- **Valor:** Provisionamento em larga escala e um modelo de dados ligado diretamente ao aprendizado de máquinas.

## Construtor
- **Função:** Pensar nas situações em que haverá expansões do sistema, por exemplo, interação entre dados de equipamentos, comunicação rápida, backup e alta disponibilidade.
- **Valor:** Preparação do sistema para ter escalabilidade com novos dados e segurança.

## Desenvolvedor
- **Função:** Desenvolver soluções para questões particulares de forma otimizada, interação entre sistemas, como o local e nuvem. Necessita de conhecimento de arquitetura.
- **Valor:** Promoção de soluções específicas. 


## Generalista
- **Função:** Mix dos outros perfis.
- Sistemas locais e entender as bases de dados;
- Ferramentas necessárias para a manutenção e construção de softwares;
- Ter experiência com ambientes Linux e linguagens de programação que lidam com dados.

# Escalando o sistema

- **Tráfego de dados:** Verificar o volume de dados no decorrer do tempo.
-  **Armazenamento de dados:** Unir dados de todas as fontes.
-  **BIG DATA:** Necessita de novas ferramentas para adaptar a estrutura.

# Banco de dados

## Relacional SQL Dados 
Estruturados em tabelas relacionadas. 

**Dificuldades:**
- Relações rígidas entre dados;
- Mudanças são difíceis de lidar;
- Planejamento do uso para otimização;
- Mal planejamento leva a pesquisas complexas.

**Vantagens:**
- Possibilita operações nos dados (soma, mínimo, máximo...);
- Consistência entre tabelas e conteúdos;
- Possível migração dos dados (em planilhas);
- Economiza espaço. 

## Não relacional (NoSQL)
São orientados a objeto, ou seja, toda uma estrutura de dados será ligada a um documento ou a uma chave, por exemplo, o JSON.

- Dados dinâmicos: cada registro não precisa seguir um padrão.
- Muito utilizado para casos de escalablidade.

## Datastores

Armazenar dados de diferentes tipos, incluindo diferentes arquivos.

## Transporte de dados

- **Democratização:** Todos devem receber os dados com facilidade e de modo que atenda as suas necessidas. Precisamos ter cuidado em relação a segurança e dados confidenciais;
- **Transmissão de Streaming:** Dados gerados e analisados em tempo real;
- **Transmissão de Lote:** Mais simples e menos custoso. Processo grupos de dados por vez.

# Referências

Inglês What is a Data Engineer? - https://www.dataquest.io/blog/what-is-a-data-engineer/

O que faz um Engenheiro de Dados? - https://medium.com/data-hackers/o-que-faz-um-engenheiro-de-dados-fdcb0bca966b

Como se tornar Engenheiro de Dados em uma Top Tech: Processos Seletivos — Parte 1 (Acesso em 09/12/2019) https://medium.com/tableless/como-se-tornar-engenheiro-de-dados-em-uma-top-tech-processos-seletivos-parte-1-367d2b7a82bb

Inglês Data engineering: A quick and simple definition (Acesso em 09/12/2019) https://www.oreilly.com/ideas/data-engineering-a-quick-and-simple-definition

Inglês Data engineers vs. data scientists (Acesso em 09/12/2019) https://www.oreilly.com/ideas/data-engineers-vs-data-scientists

Inglês What is Data Science? (Acesso em 09/12/2019) https://datajobs.com/what-is-data-science
Inglês What is big data? A consensual definition and a review of key research topics by Andrea De Mauro, Marco Greco, and Michele Grimaldi (Acesso em 09/12/2019) http://big-data-fr.com/wp-content/uploads/2015/02/aip-scitation-what-is-bigdata.pdf

Inglês Beyond the hype: Big data concepts, methods, and analytics by Amir Gandomi & Murtaza Haider (Acesso em 09/12/2019) https://www.sciencedirect.com/science/article/pii/S0268401214001066

Inglês Critical analysis of Big Data challenges and analytical methods by Uthayasankar Sivarajah, Muhammad Mustafa Kamal, Zahir Irani Vishanth Weerakkody (Acesso em 09/12/2019) https://www.sciencedirect.com/science/article/pii/S014829631630488X

Inglês Undefined By Data: A Survey of Big Data Definitions by Jonathan Stuart Ward & Adam Barker (Acesso em 09/12/2019) http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.705.9909&rep=rep1&type=pdf

Inglês What is Big Data? A Consensual Definition and a Review of Key Research Topics (Acesso em 09/12/2019) https://www.researchgate.net/publication/265775800_What_is_Big_Data_A_Consensual_Definition_and_a_Review_of_Key_Research_Topics?enrichId=rgreq-a67cd38da6b35f09227d63d0a821a6a5-XXX&enrichSource=Y292ZXJQYWdlOzI2NTc3NTgwMDtBUzoxOTg2MjMyMDg5NzIyODhAMTQyNDM2Njg3MTExMA%3D%3D&el=1_x_2&_esc=publicationCoverPdf

Democratizar os dados é essencial, mas com governança e controle (Acesso em 09/12/2019) https://computerworld.com.br/2017/10/27/democratizar-os-dados-e-essencial-mas-com-governanca-e-controle/

As diferenças entre SQL e NoSQL: MySQL x MongoDB (Acesso em 09/12/2019) https://medium.com/devtranslate/diferencas-entre-sql-e-nosql-51311f9069bd

What Goes Around Comes Around, by Michael Stonebraker & Joseph M. Hellerstein (Acesso em 09/12/2019) https://people.cs.umass.edu/~yanlei/courses/CS691LL-f06/papers/SH05.pdf

Inglês Disambiguating ACID and CAP (Acesso em 09/12/2019) https://www.voltdb.com/blog/2015/10/22/disambiguating-acid-cap/

Inglês Relational SQL vs. Non-Relational NoSQL Databases (Acesso em 09/12/2019) https://dev.to/trevoirwilliams/relational-sql-vs-non-relational-nosql-databases-hi5

Inglês Big Data Battle : Batch Processing vs Stream Processing (Acesso em 09/12/2019) https://medium.com/@gowthamy/big-data-battle-batch-processing-vs-stream-processing-5d94600d8103
