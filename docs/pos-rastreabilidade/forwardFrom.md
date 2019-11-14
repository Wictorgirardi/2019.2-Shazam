# Forward-from 

## Tabela de Requisitos Funcionais

|Requisito|Descrição|NFR|US|Épicos|Artefato de desenho|
|:--:|:----:|:-------:|:---:|:----:|:----:|
|RF01 |Detecção de mídias musicais por áudio|-|||[Tela inicial do Shazam](../imgs/RF01.shazam.android.jpg)|
|RF02 |Permite ouvir trecho da música detectada|[NFR de Desempenho](../modelagem/NFR#NFR-de-Desempenho)|||[Tela de acesso ao trecho da música](../imgs/RF02.shazam.android.jpg)|
|RF03 |Armazena músicas descobertas em uma biblioteca permitindo encontrá-las novamente em outro momento|-|||[Biblioteca de músicas detectadas](../imgs/rf03.shazam.android.jpg)|
|RF04 |Compartilhamento de músicas descobertas em outras plataformas|-|||[Tela de compartilhar mídia](../imgs/RF04.shazam.android.jpg)|
|RF05 |Detecção de alguns programas de TV|[NFR de Desempenho](../modelagem/NFR#NFR-de-Desempenho)|||-|
|RF06 |Detecção de Qr code especifícos|[NFR de Desempenho](../modelagem/NFR#NFR-de-Desempenho)|||-|
|RF07 |Opção de abrir a música descoberta em aplicativos reprodutores de músicas|-|||[Tela de abrir as músicas em outros apps](../imgs/RF07.shazam.android.jpg)|
|RF08 |Recomendações de músicas e playlists|-|||[Tela de playlists recomendadas](../imgs/RF08.shazam.android.jpg)|
|RF09 |Recomendações de músicas mais localizadas com o Shazam na última semana|-|||[Tela de top-trending](../imgs/RF09.shazam.android.jpg)|
|RF10 |Permitir a opção de ser um detector e reprodutor de música no mesmo aplicativo|-|||-|
|RF11 |Permitir que a detecção da música indique playlists relacionadas a gêneros musicais já existentes em um aplicativo de reprodução de músicas|-|||-|
|RF12 |É possível conectar-se com o Spotify, dessa forma, músicas descobertas pelo Shazam formam uma playlist no Spotify|-|||[Tela de conectar com o Spotify](../imgs/RF12.shazam.android.jpg)|
|RF13 |O aplicativo não necessita do Login para detectar músicas. O login é opcional|[NFR de Segurança](../modelagem/NFR#NFR-de-Segurança)|||-|
|RF14 |Modo auto Shazam. É uma ferramenta do smartphone que possibilita identificar músicas automaticamente sem a necessidade do aplicativo estar aberto|-|||[Tela de autorizar o Auto Shazam](../imgs/RF12.shazam.android.jpg)|
|RF15 |Locais com muitos ruídos atrapalham a detecção do aúdio musical|-|||-|
|RF16 |Caso o usuário esteja offline a busca fica salva no histórico, e quando houver conexão com internet ele efetua a pesquisa|[NFR de Desempenho](../modelagem/NFR#NFR-de-Desempenho)|||-|
|RF17 |Permitir acesso a biblioteca sem efetuar login|[NFR de Usabilidade](../modelagem/NFR#NFR-de-Usabilidade)|||-|
|RF18 |Permitir a opção de playlists compartilhadas no próprio aplicativo ao invés de ter que migrar para outro aplicativo para realizar essa ação|-|||-|
|RF19 |Permitir a opção de visualizar o vídeo clipe da música no próprio aplicativo sem a necessidade de migrar para um aplicativo reprodutor de vídeos|-|||-|
|RF20 |Permitir a integração com o Spotify, criação de um botão do Shazam no Spotify|-|||-|
|RF21 |Permitir a opção de backup de conteúdo descoberto no aplicativo caso o usuário troque de dispostivo móvel|[NFR de Desempenho](../modelagem/NFR#NFR-de-Desempenho)|||-|
|RF22 |O aplicativo disponibiliza a letra da música descoberta|-|||[Tela que disponibiliza letra da música](../imgs/RF22.shazam.android.jpg)|
|RF23 | O usuário pode escutar o conteúdo que descobriu e receber mais informações sobre o mesmo |-|||-|


## Tabela de Requisitos Não Funcionais

|Requisito|Descrição|NFR|US|Épicos|Artefato de desenho|
|:--:|:----:|:-------:|:---:|:----:|:----:|
|RNF01 |Disponibilidade de uso em tempo integral|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)||||
|RNF02 |Acesso para download em Android e IOS|[Portabilidade](../modelagem/NFR#NFR-de-Portabilidade)||||
|RNF03 |Necessidade de internet apenas para finalizar buscas|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)||||
|RNF04 |Curto tempo de busca no banco de dados|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)||||
|RNF05 |Botão intuitivo e com frases instrutivas|[Usabilidade](../modelagem/NFR#NFR-de-Usabilidade)||||
|RNF06 |O aplicativo possuir três telas|[ Desempenho](../modelagem/NFR#NFR-de-Desempenho)||||
|RNF07 |ícones instrutivos na opção  de abrir a mídia musical em um aplicativo reprodutor de músicas|[Usabilidade](../modelagem/NFR#NFR-de-Usabilidade)|||[Tela de abrir as músicas em outros apps](../imgs/RF07.shazam.android.jpg)|
|RNF08 |ícones instrutivos na opção  de compartilhar mídia musical|[Usabilidade](../modelagem/NFR#NFR-de-Usabilidade)|||[Tela de compartilhar mídia com ícones intuitivos](../imgs/RF04.shazam.android.jpg)|
|RNF09 | Atualização constante do banco de dados |[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|||| 
|RNF10 | Portabilidades (Dispositivos móveis, Web App) |[Portabilidade](../modelagem/NFR#NFR-de-Portabilidade)|||[Tela do Shazam Web](../imgs/RNF10.shazam.web.png)|
|RNF11 | Ter uma versão mais leve para abranger mais usuários |-||||
|RNF12 | Fazer conexão com outros streamings de música |-||||

# Versionamento

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
|13/11/2019|1.0|Criação do documento e adição de conteúdo|Débora Vilela|
|13/11/2019|1.1|Adicionando Artefato de desenho |Nathalia Lorena|
|13/11/2019|1.2|Adicionando NFRs ao documento|Débora Vilela|

# Referências

### Exemplo de modelo de Forward From

[Repositório Pinterest](http://www.joberth-rogers.ml/2018.2-Requisitos-Pinterest/forward_from/) Acesso em 13 de novembro de 2019.

[Repositório Twitch](https://github.com/gabrielziegler3/Requisitos-2018-1/wiki/Matriz-Rastreabilidade) Acesso em 13 de novembro de 2019.


### Material disponibilizado pelo professor

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 24. 2º/2019. 44 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

