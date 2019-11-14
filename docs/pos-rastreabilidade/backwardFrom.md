# Backward-From

## Objetivo

O objetivo deste artefato é fazer a pós-rastreabilidade dos requisitos, verificando e documentando a fonte original de cada requisito levantado para o sistema. Para isso será usado uma Matriz de Rastreabilidade

| Requisito | Descrição | NFR |Product Backlog | Esp. Casos de Uso | Cenário | Léxico | MoSCoW | First Things First | Instrospecção | Análise de Protocolo/Observação | Questionário | Rich Picture | Brainstorming |
| :-------- | :-------: | :-: | :-------------: | :---------------: | :-----: | :----: | :----: | :----------------: | :-----------: | :---------------------: | :----------: | :----------: | :-----------: |
| RQ01 | Cadastro de Usuário |  [NFR de Segurança](../modelagem/NFR#NFR-de-Segurança) | [RF01](../modelagem/backlog#Product-Backlog) | [Histórico de Músicas](../modelagem/especificacao_dcu#Histórico-de-músicas) | [C2](../modelagem/cenarios#C2) | [Login](../modelagem/lexicos) | [RF01](../modelagem/backlog) | - | - | - | - | - | - |
| RQ02 | Conectar com aplicativos de _streaming_ de terceiros | - | [RF02](../modelagem/backlog#Product-Backlog) | - | [C9](../modelagem/cenarios#C9) | [Compartilhar](../modelagem/lexicos) | [RF02](../modelagem/backlog) | [Compartilhamento de músicas](../priorizacao/firstThingFirst) | [US05](../elicitacao/introspeccao) |  [RF04 Observação](../elicitacao/observacao#Requisitos-Funcionais) | - | [Rich Pictures](../pre-rastreabilidade/rich-pictures/index) | [RF12](../elicitacao/brainstorming#Requisitos-Funcionais) |
| RQ03 | Ter acesso a uma lista de amigos | - | [RF03](../modelagem/backlog#Product-Backlog) | - | - | - | [RF03](../modelagem/backlog) | - | - |  - | - | - | - |
| RQ05 | Utilizar a aplicação de forma intuitiva.	| [Usabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#NFR%20de%20Usabilidade) | [RF08](../modelagem/backlog#Product-Backlog) | - | - | - | [RF08](../modelagem/backlog) | - | - | - | - | - | - |
| RQ05 | Não necessitar de um conhecimento grande sobre o mundo da música. | [Usabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#NFR%20de%20Usabilidade) | [RF09](../modelagem/backlog#Product-Backlog) | - | - | - | [RF09](../modelagem/backlog) | - | - | - | - | - | - |
| RQ05 | Não gastar todo meu plano de internet.	| [Desempenho](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#NFR%20de%20Desempenho) | [RF10](../modelagem/backlog#Product-Backlog) | - | - | - | [RF12](../modelagem/backlog) | - | - | - | - | - |  -|
| RQ05 | Conhecer novas músicas e pessoas. | - | [RF11](../modelagem/backlog#Product-Backlog) | [Descobir novas músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/##Descobrir%20novas%20músicas) | - | [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos/#Léxicos) | [RF12](../modelagem/backlog) | - | [US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#User%20Stories) | - | - | - | [RF11](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/##Requisitos%20Funcionais) |
| RQ05 | Dissipar meu conhecimento musical.	| - | [RF12](../modelagem/backlog#Product-Backlog) | - | [C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios/#C9) | [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos/#Léxicos) | [RF12](../modelagem/backlog) | - | [US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#User%20Stories) | - | - | [V1](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/##Versão1) | [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/##Requisitos%20Funcionais) |
| RQ05 | Não precisar entrar no app para escanear uma música. | - | [RF13](../modelagem/backlog#Product-Backlog) | - | - | - | [RF13](../modelagem/backlog) | - | - |  - | - | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#Requisitos%20Funcionais) |
| RQ05 | Não precisar entrar no app para escanear uma música.	| - | [RF13](../modelagem/backlog#Product-Backlog) | - | - | - | [RF13](../modelagem/backlog) | - | - | - | - | - | - |
| RQ05 | Saber a letra de uma música que está tocando em um vídeo. | - | [RF14](../modelagem/backlog#Product-Backlog) | - | - | - | [RF14](../modelagem/backlog) | - | - | - | - | - | - |
| RQ05 | Poder identificar qualquer música ao redor sem entrar no app com a opção auto Shazam ativada. | - | [RF15](../modelagem/backlog#Product-Backlog) | - | - | - | [RF15](../modelagem/backlog) | - | - |  - | - | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#Requisitos%20Funcionais) |
| RQ05 | Poder escolher um tema claro ou escuro para o app.	| - | [RF16](../modelagem/backlog#Product-Backlog) | - | - | - | [RF16](../modelagem/backlog) | - | - |  - | - | - | - |
| RQ04 | Reconhecer mídia através da voz do usuário	| - | [RF17](../modelagem/backlog#Product-Backlog) | - | - | - | [RF17](../modelagem/backlog) | - | - |  - | - | - | - |

## Controle de versão

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 13/11/2019 | 1.0 | Criação do documento e primeira versão da Matriz de Rastreabilidade | Ernando | 
