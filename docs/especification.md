# Especificações do Projeto

## Personas

1. Meu nome é Sabrina, tenho 25 anos, estou terminando a faculdade em Administração e moro em São Paulo. Tenho muito apreço por filmes, e por isso, frequento o cinema toda semana, muitas vezes com amigos ou com meu namorado. Sempre quero assistir alguma pré-estreia no cinema, mas já me frustrei por não conseguir o ingresso a tempo. Procuro uma forma rápida e fácil de comprar ingressos, pipoca e acompanhar os lançamentos dos cinemas da região.

1. Me chamo Jorge, sou empresário e dono da rede de cinemas CineSuper.  Meus cinemas têm um ponto de vendas bem tradicional, com sistema somente na bilheteria, para marcar os assentos e gerar a contabilidade. Gostaria de poder oferecer uma maneira de vender os ingressos à distância para os meus clientes, assim, consigo me planejar para a quantidade de clientes, abrindo mais uma sala quando necessário e fornecendo uma forma mais fácil de me comunicar com os clientes e vender.

1. [Persona 3?]

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`               |PARA ... `MOTIVO/VALOR`                     |
|--------------------|--------------------------------------------------|--------------------------------------------|
|Cliente do Cinema   | Comprar ingressos com antecedência               | Garantir um lugar nos filmes disputados    |
|Cliente do Cinema   | Ter o melhor lugar possível escolhido na sala    | Me sentir mais confortável vendo o filme   |
|Cliente do Cinema   | Comprar pipoca e acompanhamentos online          | Pegar pipoca e acompanhamentos rapidamente |
|Cliente do Cinema   | Compartilhar os ingressos com os amigos          | Poder entrar na sala antes deles           |
|Cliente do Cinema   | Ver os filmes e horários de vários cinemas       | Escolher a opção mais conveniente          |
|Dono do Cinema      | Encantar o cliente com um sistema fácil de usar  | Ter clientes sempre usando o aplicativo    |
|Dono do Cinema      | Ter um relatório de vendas                       | Fazer a contabilidade no fechamento do mês |
|Dono do Cinema      | Integrar as vendas online com a bilheteria física| Ter coerência entre os dois sistemas       |
|Dono do Cinema      | Conduzir campanhas de marketing                  | Manter uma comunicação com o cliente       |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | 
|------|-----------------------------------------|----| 
|RF-001| A aplicação deve permitir que o usuário gerencie suas tarefas | ALTA |  
|RF-002| A aplicação deve permitir a emissão de um relatório de tarefas realizadas no mês   | MÉDIA | 


### Requisitos não Funcionais

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| A aplicação deve ser responsiva | MÉDIA | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|RNF-003| A aplicação deve ser capaz de suportar picos de tráfego, especialmente durante lançamentos de filmes populares e horários de pico, como finais de semana |  MÉDIA | 
|RNF-004| A aplicação deve estar em conformidade com as diretrizes de acessibilidade WCAG 2.1 para garantir que usuários com deficiência possam usar o sistema | MÉDIA | 
|RNF-005| A aplicação deve ser compatível com os principais navegadores (Chrome, Firefox, Safari, Edge) e dispositivos móveis | MÉDIA | 
|RNF-006| A aplicação deve estar em conformidade com as regulamentações de proteção de dados, como a LGPD (Lei Geral de Proteção de Dados) no Brasil, e outras leis locais relacionadas a transações financeiras e privacidade | ALTA | 
|RNF-007| Deve ter uma política de privacidade clara e acessível, informando aos usuários como seus dados serão coletados, utilizados e protegidos | MÉDIA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
