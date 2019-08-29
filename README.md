# Archive IFES - Projeto de Sistemas

### 1) Descrição do Contexto(Minimundo)
> Um sistema Web que fornece informações sobre os projetos desenvolvidos dentro do IFES - Campus Serra. Ele armazenará informações referentes a dados técnicos do projeto, pessoas que estão envolvidas, competições e eventos as quais já participou ou irá participar, além de possuir vídeos, fotos, comentários dos autores e usuários,  quando possível. Além de ter uma área dedicada a informar se o projeto está em desenvolvimento ou finalizado, caso esteja em desenvolvimento terá a possibilidade de visualizar as vagas para o mesmo.

### 2) Requisitos Não Funcionais

Identificador | Descrição | Categoria | Escopo 
:---------: | ---------- | :---------: | :---------: |
RNF01 |O sistema deve possuir uma linguagem simples e ser de facil navegabilidade        |           |           |
RNF02 |O sistema deve ser capaz de autenticar usuários                                   |Segurança de acesso |Sistema|
RNF03 |O sistema deve ser capaz de validar a permissão para editar projetos              |Segurança de acesso |Sistema|
RNF04 |O sistema deve ser capaz de futuramente possuir uma versão mobile                 |Portabilidade|Funcionalidade|
RNF05 |O sistema deve ser capaz de receber upload de videos e fotos                      |Eficiência de recursos|Sistema |
RNF06 |O sistema deve ser capaz de facilitar a comunicação entre parcerias e novos contratos     |           |           | 
RNF07 |O sistema deve ser capaz de receber mensagens e sugestões da comunidade externa           |           |           |


### 3) Táticas para tratar Atributos de qualidade

Categoria | Requisitos Não Funcionais | Condutor de Arquitetura | Tática  
:---------: | :----------: | --------- | --------- |
Facilidade de Operação |   RNF01      |           |Mensagens de auxilio ao usuário, simplificar textos e utilizar imagens autoexplicativas.             |
Segurança de Acesso | RNF02, RNF03  |           |Validação dos campos, exibir mensagens de erro/informações, histórico de edição/visualização dos projetos, autenticação por login e senha, confirmação por email.          |
   Portabilidade   |    RNF04      |           |Utilizar ferramenta que permite expansão do sistema para outra plataforma (mobile), construir um sistema responsivo.           |
 Eficiência de recursos |    RNF05      |           |Padronizar formato, tamanho e extensão dos dados de entrada no sistema. Ou disponibilizar o link do arquivo.|



          
### 4) Protótipos de Tela do Sistema

