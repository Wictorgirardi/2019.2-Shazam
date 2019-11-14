# Backward-From

## Objetivo

O objetivo deste artefato é fazer a pós-rastreabilidade dos requisitos, verificando e documentando a fonte original de cada requisito levantado para o sistema. Para isso será usado uma Matriz de Rastreabilidade

| Requisito | Descrição | NFR |Product Backlog | Esp. Casos de Uso | Cenário | Léxico | MoSCoW | First Things First | Instrospecção | Análise de Protocolo/Observação | Questionário | Rich Picture | Brainstorming |
| :-------- | :-------: | :-: | :-------------: | :---------------: | :-----: | :----: | :----: | :----------------: | :-----------: | :---------------------: | :----------: | :----------: | :-----------: |
| RF01 | Cadastro de Usuário |  [NFR de Segurança](../modelagem/NFR#NFR-de-Segurança) | [RF01](../modelagem/backlog#Product-Backlog) | [Histórico de Músicas](../modelagem/especificacao_dcu#Histórico-de-músicas) | [C2](../modelagem/cenarios#C2) | [L05](../modelagem/lexicos) | [RF01](../modelagem/backlog) | - | - | - | - | - | - |
| RF02 | Conectar com aplicativos de _streaming_ de terceiros | - | [RF02](../modelagem/backlog#Product-Backlog) | - | [C9](../modelagem/cenarios#C9) | [L03](../modelagem/lexicos) | [RF02](../modelagem/backlog) | [Compartilhamento de músicas](../priorizacao/firstThingFirst) | [US06](../elicitacao/introspeccao) |  [RF04](../elicitacao/observacao#Requisitos-Funcionais) | - | [Rich Pictures](../pre-rastreabilidade/rich-pictures/index) | [RF12](../elicitacao/brainstorming#Requisitos-Funcionais) |
| RF03 | Ter acesso a uma lista de amigos | - | [RF03](../modelagem/backlog#Product-Backlog) | - | - | - | [RF03](../modelagem/backlog) | - | - |  - | - | - | - |
| RF04 | Detecção de mídias ao meu redor | - | [RF04](../modelagem/backlog) | [Escanear Música](../modelagem/especificacao_dcu#Escanear-música) | [C1](../modelagem/cenarios#C1) | [L01](../modelagem/lexicos) | [RF04](../modelagem/backlog) | [Buscar mídias](../priorizacao/firstThingFirst) | [US01](../elicitacao/introspeccao) | [RF01](../elicitacao/analise_protocolo) | [Q01](../elicitacao/questionario#Requisitos-elicitados) | [Rich Pictures](../pre-rastreabilidade/rich-pictures/index) | [RF01](../elicitacao/brainstorming) | 
| RF05 | Escanear uma música que estou ouvindo no meu dispositivo | - | [RF05](../modelagem/backlog) | [Escanear Música](../modelagem/especificacao_dcu#Escanear-música) | [C1](../modelagem/cenarios#C1) | [L01](../modelagem/lexicos) | [RF04](../modelagem/backlog) | [Buscar mídias](../priorizacao/firstThingFirst) | [US01](../elicitacao/introspeccao) | [RF01](../elicitacao/analise_protocolo) | [Q01](../elicitacao/questionario#Requisitos-elicitados) | [Rich Pictures](../pre-rastreabilidade/rich-pictures/index) | [RF01](../elicitacao/brainstorming) |
| RNF01 | Acessar uma música já escaneada | [NFR de Confiabilidade](../modelagem/NFR#NFR-de-Confiabilidade) | [RNF01](../modelagem/backlog) | [Histórico de Músicas](../modelagem/especificacao_dcu#Histórico-de-músicas) | [C3](../modelagem/cenarios#C3) | [L04](../modelagem/lexicos) | [RNF01](../modelagem/backlog) | [Armazenar músicas](../priorizacao/firstThingFirst) | [US02](../elicitacao/instrospeccao) | [RF03](../elicitacao/analise_protocolo#Requisitos-Funcionais) | [Q05](../elicitacao/questionario) | -| [RF03](../elicitacao/questionario) |
| RNF02 | Acessar playlists baseadas no meu gosto | [NFR de Confiabilidade](../modelagem/NFR#NFR-de-Confiabilidade) | [RNF02](../modelagem/backlog) | [Histórico de Músicas](../modelagem/especificacao_dcu#Histórico-de-músicas) | - | [L07](../modelagem/lexicos) | [RNF02](../modelagem/backlog) | [Recomendações de músicas e playlists](../priorizacao/firstThingFirst) | [US04](../elicitacao/instrospeccao) | - | [Q04](../elicitacao/questionario) | - | [RF08](../elicitacao/brainstorming) |
| RNF03 | Ver artistas favoritos | [NFR de Confiabilidade](../modelagem/NFR#NFR-de-Confiabilidade) | [RNF03](../modelagem/backlog) | - | [C5](../modelagem/cenarios) | - | [RNF03](../modelagem/backlog) | - | - | - | -| - | - |
| RNF04 | Saber as músicas mais tocadas de um país | - | [RNF04](../modelagem/backlog) | [Descobrir novas músicas](../modelagem/especificacao_dcu#descobrir-novas-músicas) | - | [L06](../modelagem/lexicos) | [RNF04](../modelagem/backlog) | - | [US03](../elicitacao/instrospeccao) | - | - | - | - |
| RNF05 | Conhecer lançamentos no mundo da música | - | [RNF05](../modelagem/backlog) | [Descobrir novas músicas](../modelagem/especificacao_dcu#descobrir-novas-músicas) | - | [L06](../modelagem/lexicos) | [RNF06](../modelagem/backlog) | - | [US04](../elicitacao/instrospeccao) | - | - | - | - |
| RNF06 | Mostrar aos amigos o que estou escutando | - | [RNF06](../modelagem/backlog) | - | [C9](../modelagem/cenarios) | - | [RNF06](../modelagem/backlog) | - | [US06](../elicitacao/introspeccao) | - | - | [Rich Pictures](../pre-rastreabilidade/rich-pictures/index) | [RF18](../elicitacao/brainstorming) | 
| RNF07 | Adicionar novas músicas ao meu serviço de _streaming_ | - | [RNF07](../modelagem/backlog) | - | [C10](../modelagem/cenarios) | [L08](../modelagem/lexicos) | [RNF07](../modelagem/backlog) | [Compartilhar músicas em outras plataformas](../priorizacao/firstThingFirst) | [US05](../elicitacao/instrospeccao) | [RQ04](../elicitacao/observacao) | - | [Rich Pictures](../pre-rastreabilidade/rich-pictures/index) | [RF20](../elicitacao/brainstorming) | 


## Controle de versão

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 13/11/2019 | 1.0 | Criação do documento e primeira versão da Matriz de Rastreabilidade | Ernando | 


## Referências

### Exemplo de modelo de Backward From

http://www.joberth-rogers.ml/2018.2-Requisitos-Pinterest/backward_from/ Acesso em 13 de novembro de 2019.

https://github.com/gabrielziegler3/Requisitos-2018-1/wiki/Matriz-Rastreabilidade Acesso em 13 de novembro de 2019.


### Material disponibilizado pelo professor

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 24. 2º/2019. 44 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.