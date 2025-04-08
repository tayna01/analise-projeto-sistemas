    @author Luan Gabriel
    @data   08/04/2025
    @aula   05
> ### Alto-avaliação: *Dev Pleno*

---

#### 1° Etapa - Rastreabilidade

Nesta primeira etapa devemos apenas listar os requisitos, sem nos preocuparmos em categorizar ou validar as informações, aqui nós iremos praticamente transcrever as informações que obtivos com as técnicas de levantamos de requisitos, devemos entender o que o cliente QUER.

O refinamento e categorização dos requisitos é uma responsabilidade das próximas fases.

#### 2° Etapa - Levantamento de Requisitos Princípais
O segundo passo é definir quais são os requisitos principais.

    LRP001 - Desenvolver um sistema de emissão automatizada de relatórios.

#### 3° Etapa - Levantamento de Requisitos Específicos

Após isso, realizamos a especificação, nesta etapa, realizaremos a decomposição dos requisitos principais em vários requisitos específicos.
    
    LRE001 - Deve ser possível solicitar a emissão de um relatório.
    LRE002 - Deve ser possível consultar relatórios emitidos.

#### 4° Etapa - Identificar os Atores

Nesta etapa vamos analisar os requisitos e definir quem são os **atores** que irão interagir com o sistema a ser desenvolvido.

    LRE003 - Se o relatório estiver com status COMPLETO, o usuário deverá ser capaz de baixar o PDF referente a ele.

#### 5° Etapa - Complementação Funcional

Nesta etapa iremos levantar os requisitos referentes a funcionalidades que devem haver no projeto para que os requisitos principais e especificos sejam cumpridos.

Ex. Se há um requisito especifico que diz que deve ser possível listar relatórios que foram emitidos, logo, faz sentido haver um requisito funcional que diga que deva haver uma tela por onde os relatórios possam ser buscados e filtrados.

    LRE004 - Deve haver uma tela por onde relatórios emitidos anteriormentes podem ser consultados e buscados por meio vários filtros que podem ser aplicados. (Ex. Filtrar por nome, data, status e etc...).


#### 6° Etapa - Funcionalidades Fora do Escopo Inicial

Nesta etapa iremos levantar os requisitos que foram pedidos/sugeridos mas que fogem do escopo inicial do projeto, normalmente estes são requisitos que não agregam tanto valor ao sistema quanto os requisitos anteriores, mas que são interessantes de serem implementados, desde que não tragam tanto **custo** extra ao projeto.

    LRE005 - Implementar um dashboard simples onde podemos ver informações sobre os relatórios emitidos no dia, semana, mês e ano em forma de gráfico.

#### 7° Etapa - Validação e Verificação

Na última etapa, iremos analisar tudo o que obtivos nas fases anteriores, iremos validar e verificar a qualidade do que foi definido, conferir se está claro e o mais importante, se os requisitos obtidos realmente são necessários para alcançar o que o cliente PRECISA.