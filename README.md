<h1 align="center">
    <a>🔗 Projeto E-commerce modelagem</a>
</h1> 

<h4 align="center"> 
	🚧 Em andamento 🛠️ 🚧
</h4>

<h5 align="center">Disciplina de Engenharia de Software ||| </h5>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 

    
---


## 🏷️ Tópicos da Modelagem 

- [Visão do Projeto](#visão-do-projeto)
- [Domínio de Negócio](#domínio-de-negócio)
- [Stakeholders](#stakeholders)
- [Requisitos Funcionais](#requisitos-funcionais)
- [Requisitos Não Funcionais](#requisitos-não-funcionais)
- [Diagrama de Caso de Uso](#diagrama-de-caso-de-uso)
- [Casos de usos estendidos](#Casos-de-usos-estendidos)
- [DER](#DER)
- [Banco de Dados físico](#banco-de-dados-físico)
- [Diagrama de Classe](#diagrama-de-classe)
- [Diagrama de máquina de estado](#diagrama-de-máquina-de-estado)
- [Diagrama de sequência](#diagrama-de-sequência)
- [Interface](#interface)
- [Tecnologias](#tecnologias)
- [Autores](#Autores)


---

## 💻Visão do Projeto

<p align="left"> :octocat: O projeto consiste em desenvolver um <strong>sistema de comércio eletrônico (E-commerce) </strong>
  cujo objetivo é <strong>vendas de quadros artísticos e pinturas</strong>. Esse sistema será desenvolvido para atender 
  às necessidades de vários artistas ou empresas que querem divulgar suas obras e por consequência vendê-las online. 
 </p>

<p align="left"> O artista (sendo o usuário vendedor) poderá cadastrar suas próprias artes ou 
  quadros de outros artistas. O e-commerce permite o cadastro de várias empresas ou microempreendedores a qual queiram vender suas artes por meio de uma plataforma digital.</p>

<p align="left">Além disso, será aberto para variados tipos de pinturas, desde pintura óleo, acrílica, giz etc. O e-commerce disponibiliza categorias distintas, tamanhos diversos agregando todo tipo de pinturas em quadros.</p>


---

## 🎲Domínio de Negócio
  
**E-commerce:** sistemas de software que dão suporte a compras online, gerenciamento de
  estoque e processamento de pedidos.

---

## 👨‍👨‍👦‍👦Stakeholders

 - **Usuários**: Os usuários são os indivíduos que usarão o sistema web uma vez desenvolvido.
Eles fornecerão informações valiosas sobre a usabilidade e funcionalidade do sistema além de ajudarem a
garantir que os requisitos sejam práticos e atendam às suas necessidades.

- **Vendedores:** Os vendedores são responsáveis por vender os produtos no sistema.

- **Desenvolvedores:** Os desenvolvedores são responsáveis por implementar os requisitos e construir
o sistema de software.


---

## 🔎Requisitos Funcionais

Eles definem as ações específicas que o sistema deve
executar e como deve responder a várias entradas e eventos.


##### Exemplos de alguns RF do sistema:
| Código | Identificação | Ator | Descrição |
| --- | --- | --- | --- |
| RF001 | Histórico de Pedidos | Usuário | Os usuários poderão visualizar o histórico de pedidos anteriores também rastreiem remessas e gerenciar devoluções ou trocas. |	
| RF002 | Verificar lista de pedidos recebido | Vendedor | Verificar a lista de pedidos recebidos  e providenciar o envio do produto. |
|RF003 | Número de rastreio do pedido | Transportadora |A transportadora deve disponibilizar um número de rastreamento que permita que os clientes acompanhem o progresso de suas encomendas em tempo real.|


## Requisitos Não Funcionais

São as qualidades ou atributos que o sistema deve possuir, mas que não estão
diretamente relacionados à sua funcionalidade específica. Como deve funcionar, não
necessariamente o que deve fazer.

👉Para visualizar a **lista completa** dos Requisitos Funcionais e Não Funcionais do e-commerce acesse: [requisitosFuncionais.pdf](https://github.com/franpl-pr/E-commerce-quadros-art-sticos/files/12665596/requisitosFuncionais.pdf)


---

## 🔷Diagrama de Caso de Uso

O caso de uso descreve uma sequência de ações que os
atores realizarão para alcançar um objetivo específico no sistema.
Ele mostra como o sistema responde a essas ações e quais
resultados são esperados.

O objetivo do diagrama de caso de uso,
em **UML (Unified Modeling Language - Linguagem de Modelagem Unificada)**, 
é demonstrar as diferentes maneiras que o usuário pode
interagir com o sistema.

**Visualização do Caso de Uso**
![casoUso drawio](https://github.com/franpl-pr/E-commerce-quadros-art-sticos/assets/99376161/cf87acf2-0c04-4324-8633-db0aad43405d)

👉Para visualizar melhor o caso de uso [clique aqui](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=e-commerceQuadros.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1NGqZem0uXzkIqzyiEnzuh2M5aoUQ8IQ2%26export%3Ddownload) 

## Casos de usos estendidos

 Já os casos de usos estendidos servem para cenários mais detalhados 
 ou específicos que estão relacionados a um caso de uso principal. 
 
 O objetivo é visualizar as funcionalidades adicionais ou variações do comportamento principal 
 do sistema, sem a necessidade de sobrecarregar o caso de uso principal com muitos detalhes.

 👉Para visualizar a **lista completa** dos Casos de usos estendidos acesse: [casosUsosEstendidos (1).pdf](https://github.com/franpl-pr/E-commerce-quadros-art-sticos/files/12665816/casosUsosEstendidos.1.pdf)
 
---


## 🎲DER

O Diagrama Entidade Relacionamento (DER) é um tipo de fluxograma que ilustra como as “entidades”, se relacionam entre si 
dentro do sistema. Diagramas ER são mais utilizados para projetar ou depurar o Bancos de dados relacionais.

 👉O diagrama foi desenvolvido na ferramenta 'BrModelo' e está disponível para baixá-lo, [clique aqui](https://github.com/franpl-pr/E-commerce-quadros-art-sticos/blob/main/derQuadros.brM3).

---


## 🗂️Banco de Dados físico

 👉Para baixar o Banco de Dados SQL completo clique aqui: [BancoDadosEcommerceQuadros.zip](https://github.com/franpl-pr/E-commerce-quadros-art-sticos/files/12666163/BancoDadosEcommerceQuadros.zip)

Desenvolvido no phpMyAdmin SQL Dump - version 5.2.1

---

## ♦️Diagrama de Classe

 O diagrama de classes é composto por caixas retangulares que
representam as classes, linhas que indicam os relacionamentos entre as
classes e os símbolos que representam os atributos e métodos das
classes.


As classes são as entidades principais do diagrama e representam
objetos do mundo real ou conceitos abstratos presentes no sistema.
Cada classe possui atributos, que são características ou propriedades
dos objetos daquela classe, e métodos, que são as ações ou operações
que os objetos da classe podem realizar.

**Visualização do diagrama de classes**

![diagramaClasseEcommerce drawio](https://github.com/franpl-pr/E-commerce-quadros-art-sticos/assets/52611643/8314fc25-1280-48bb-a53a-e22c152d9b19)


👉Para visualizar melhor [clique aqui](https://viewer.diagrams.net/tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=diagramaClasseEcommerce.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1_hEOJTQuIZHO7xF10SwxGJycDgFrBUH1%26export%3Ddownload)

---

## 🚦Diagrama de máquina de estado

Ele representa o comportamento dinâmico de um objeto, componente ou sistema em resposta
a diferentes eventos à medida que ele passa por diversos estados. Ou seja,
são úteis para modelar comportamentos entre estados diferentes.

Veja a visulização para o **Estado Pagamento**:

![diagramaMaquinaEstadoPagamento drawio](https://github.com/franpl-pr/E-commerce-quadros-art-sticos/assets/99376161/a67b7cec-56f2-4502-8712-f3a2ccc2fdc6)

👉Caso, queira visualizar melhor [clique aqui](https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1zIDFE4g0lxG-eA_HsV97CrqtDOERCzvR) 

---

## 🔶Diagrama de sequência

Serve para descrever a ordem e o fluxo de mensagens (ou chamadas de método)
entre os objetos ao longo do tempo. 

São usados para projetar a lógica de funcionamento de um sistema, 
ajudando os desenvolvedores a entender como as classes e objetos se
relacionam e como os métodos são chamados.

**Visualização do Diagrama de sequência**

![DiagramaSequenciaE-commerce-Quadros drawio](https://github.com/franpl-pr/E-commerce-quadros-art-sticos/assets/52611643/f1d86c5a-c466-4dce-ae18-e3476b63db02)

👉Para visualizar melhor [clique aqui](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=DiagramaSequenciaE-commerce-Quadros.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1mPO8-T0YoXEwSSqTQQ5HdvPZI6wn1DKL%26export%3Ddownload)

---

## 🎲Interface




## ⚒️Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

-   Draw.io - Diagrama de Classes
-   BrModelo - Diagrama Entidade e Relacionamento (DER)
-   Banco de Dados: MySQL PhPMyAdmin
-   Figma - Interface

---

## 📝Autores

Este projeto está sobre a licença [MIT](./LICENSE).

O projeto foi desenvolvido por meio da disciplina de Engenharia de Software ||| - 4°
Semestre, professor Anderson Barbosa na Fatec de Campinas.

Feito com ❤️ por 
- Cassia Xavier
- Franciele Procopio
- Letícia
- Maria Clara


Entre em contato! 👋🏽👋🏽

---


