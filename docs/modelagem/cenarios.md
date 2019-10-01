# Cenários

## Introdução


Os cenários consistem de uma coleção de narrativas de situações no domínio que favorecem o levantamento de informações em um contexto proposto que permitem a identificação de possíveis tarefas e funcionalidades que se pode realizar em um software, como também identifica problemas e a antecipação das soluções. A técnica de elaborar cenários é uma maneira excelente de representar, para clientes e usuários, os problemas existentes em um software e as possibilidades que podem surgir. Os cenários têm como foco as atividades desempenhadas pelos usuários nas organizações em diferentes contextos possibilitando uma perspectiva mais ampla dos problemas atuais onde o sistema será inserido, explicando porque ele é necessário.

# Cenário 1

**Identificar uma música**

|Objetivo  |
 -----------   |
|Descobrir uma música       |
|**Contexto** |
|Local: Página inicial do Shazam (login não obrigatório)<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: Usuário descobre música<br> |
|**Atores**|
|Usuário que quer descobrir uma música|
|**Recursos**|
|Internet, aplicativo|
|**Episódios**|
|Usuário que quer descobrir uma música abre o aplicativo<br>Usuário clica no botão circular da tela de início<br>A música e artista são detectados pelo Shazam com sucesso<br>Se a música não foi detectada, usuário clica no botão circular e tenta novamente|
|**Restrição**|
|Aplicativo estar instalado<br>Música(s) tocando no momento|
|**Exceção**|
Internet cair<br>Conteúdo musical muito distante para ser detectado<br>Aplicativo estar indisponível<br>Muitos ruídos no ambiente|

# Cenário 2

**Realizar cadastro**

|Objetivo  |
 -----------   |
|Permitir que usuários se cadastrem    |
|**Contexto** |
|Local: Tela da esquerda do Shazam (no ícone de configurações)<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: Usuário realiza inscrição<br> |
|**Atores**|
|Usuário que deseja ter cadastro na plataforma|
|**Recursos**|
|Internet, aplicativo, conta de e-mail|
|**Episódios**|
|Usuário quer descobrir uma música abre o aplicativo<br>Usuário clica no botão circular da tela de início<br>A música e artista são detectados pelo Shazam com sucesso<br>Se a música não foi detectada, usuário clica no botão circular e tenta novamente<br>Usuário quer salvar seus Shazams, então clica na opção de configurações e em seguida realizar inscrição|
|**Restrição**|
|O usuário ter conta no Facebook<br>O usuário possuir e-mail|
|**Exceção**|
|Internet cair<br>E-mail inválido<br>Aplicativo estar indisponível<br>Senha inválida<br>E-mail ou conta do Facebook inexistente<br>E-mail ou Facebook fora do ar|

# Cenário 3

**Visualizar músicas descobertas**

|Objetivo  |
 -----------   |
|Visualizar as músicas que o usuário descobriu   |
|**Contexto** |
|Local: Tela da esquerda do Shazam (em biblioteca)<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: Usuário visualiza músicas que descobriu<br> |
|**Atores**|
|Usuário que deseja ter acesso às músicas que descobriu|
|**Recursos**|
|Internet, aplicativo, músicas identificadas|
|**Episódios**|
|Usuário quer visualizar uma música que descobriu<br>Usuário clica no ícone escrito "biblioteca" ou desliza o dedo da esquerda para a direita partindo da tela de início<br>O usuário encontra suas músicas e artistas na biblioteca|
|**Restrição**|
|O usuário ter o aplicativo<br>O usuário ter clicado no botão de identificar músicas na tela inicial do Shazam|
|**Exceção**|
|Internet cair<br>Músicas não terem sido reconhecidas<br>Aplicativo estar indisponível<br>|

# Cenário 4

**Salvar músicas descobertas**

|Objetivo  |
 -----------   |
|Salvar as músicas que foram identificadas   |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone de configurações)<br>Pré-Condição: Ter instalado o app e ter músicas descobertas na biblioteca<br>Pós-Condição: Usuário salva músicas que descobriu<br> |
|**Atores**|
|Usuário que deseja salvar às músicas reconhecidas pelo app|
|**Recursos**|
|Internet, aplicativo, músicas identificadas na biblioteca do app|
|**Episódios**|
|Usuário quer salvar as músicas que descobriu sem ter o risco de sair do aplicativo e elas sumirem da biblioteca<br>Usuário clica no ícone escrito "biblioteca" ou desliza o dedo da esquerda para a direita partindo da tela de início e depois no ícone de configurações<br>O usuário encontra a opção de inscrição que garante que suas músicas sejam salvas|
|**Restrição**|
|O usuário ter o aplicativo<br>Usuário ter músicas na biblioteca que deseja salvar<br>O usuário ter conta no Facebook<br>O usuário possuir e-mail|
|**Exceção**|
|Internet cair<br>Músicas não terem sido reconhecidas<br>E-mail inválido<br>Aplicativo estar indisponível<br>Senha inválida<br>E-mail ou conta do Facebook inexistente<br>E-mail ou Facebook fora do ar|

# Cenário 5

**Procurar músicas ou artistas no app**

|Objetivo  |
 -----------   |
|Efetuar busca por músicas ou artistas já disponíveis no app   |
|**Contexto** |
|Local: Tela da direita do Shazam (ícone de descobrir)<br>Pré-Condição: Ter o app instalado<br>Pós-Condição: Usuário encontra músicas ou artistas de seu interesse existentes no app<br> |
|**Atores**|
|Usuário que deseja explorar músicas ou artistas de seu interesse que estão disponíveis no app|
|**Recursos**|
|Internet, aplicativo|
|**Episódios**|
|Usuário quer explorar as músicas ou artistas existentes no aplicativo<br>Usuário clica no ícone escrito "Descobrir" ou desliza o dedo da direita para a esquerda partindo da tela de início e depois no ícone de "lupa" em seguida, digita algo de seu interesse<br>O usuário encontra as músicas ou artistas que deseja e visualiza as músicas mais populares de tal artista|
|**Restrição**|
|O usuário ter o aplicativo|
|**Exceção**|
|Internet cair<br>Usuário pesquisar por um artista ou música inexistente|

# Cenário 6

**Fazer login**

|Objetivo  |
 -----------   |
|Fazer login no app e salvar suas músicas |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca) e botão de "fazer login"<br>Pré-Condição: Ter o app instalado<br>Pós-Condição: Usuário faz login<br> |
|**Atores**|
|Usuário que deseja ter sua conta logada e já fez inscrição|
|**Recursos**|
|Internet, aplicativo, e-mail válido|
|**Episódios**|
|Usuário prefere ter uma conta com login<br>Usuário clica no ícone escrito "Biblioteca" ou desliza o dedo da esquerda para a direita partindo da tela de início e depois no clica no botão referente a "fazer login" em seguida, clica na opção de realizá-lo com e-mail ou facebook<br>O usuário recebe uma validação por e-mail<br>Após a confirmação o usuário estará logado|
|**Restrição**|
|O usuário ter o aplicativo<br>Usuário possuir cadastro|
|**Exceção**|
|Internet cair<br>Usuário esquecer e-mail<br>Usuário não ter confirmado a conta por e-mail|

# Cenário 7

**Sair do aplicativo Shazam**

|Objetivo  |
 -----------   |
|Fazer logout no app |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca) em seguida, ícone de configurações<br>Pré-Condição: O usuário deve estar logado<br>Pós-Condição: Usuário clica na opção de "sair" e encerra a sessão a conta<br> |
|**Atores**|
|Usuário que deseja sair da sua conta logada|
|**Recursos**|
|Internet, aplicativo, conta do usuário|
|**Episódios**|
|Usuário clica em "biblioteca" em seguida, na ferramenta de "configurações"<br>Usuário clica na opção de sair<br>Usuário visualiza a página de início do app|
|**Restrição**|
|O usuário ter o aplicativo<br>Usuário estar logado|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível|

# Cenário 8

**Excluir conta**

|Objetivo  |
 -----------   |
|Excluir conta no app |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca) em seguida, ícone de configurações e na opção "sobre"<br>Pré-Condição: O usuário deve ter conta e estar logado<br>Pós-Condição: Usuário exclui sua conta<br> |
|**Atores**|
|Usuário que não quer mais ter conta no app|
|**Recursos**|
|Internet, aplicativo, conta do usuário|
|**Episódios**|
|Usuário clica em "biblioteca", em seguida, na ferramenta de "configurações" e na opção "sobre"<br>Usuário visualiza a opção de excluir conta<br>Usuário clica em "excluir conta" e o app direciona para uma página no browser que solicita ao usuário iniciar uma sessão com e-mail ou facebook de acordo com a opção que o usuário se cadastrou |
|**Restrição**|
|O usuário ter o aplicativo<br>Usuário ter conta e estar logado|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>E-mail ou facebook inválidos|

# Cenário 9

**Compartilhar mídia identificada**

|Objetivo  |
 -----------   |
|Compartilhar mídia identificada pelo Shazam |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca) em seguida, "Shazams recentes" e menu contido na música que o usuário escolheu<br>Pré-Condição: O usuário deve ter  identificado uma ou mais músicas<br>Pós-Condição: Usuário compartilha mídia<br> |
|**Atores**|
|Usuário que deseja compartilhar mídia com outros usuários|
|**Recursos**|
|Internet, aplicativo, Facebook, Gmail, Messenger, Instagram, Telegram, Whatsapp, Hangouts, etc|
|**Episódios**|
|Usuário clica em "biblioteca", em seguida, no título de "Shazams recentes" encontra suas músicas<br>Usuário escolhe a opção que deseja compartilhar<br>Usuário clica na música, em seguida, no menu à direita no canto inferior da tela<br>Usuário clica na opção "compartilhar" e escolhe uma opção de compartilhamento em outras plataformas disponíveis|
|**Restrição**|
|O usuário ter o aplicativo<br>Usuário possuir conta em alguma das plataformas disponíveis na opção de "compartilhar" |
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>E-mail ou conta em alguma das plataformas de compartilhamento estar indisponível<br>O usuário não possuir e-mail ou nenhuma conta nas plataformas disponíveis|

# Cenário 10

**Abrir mídia do Shazam em plataformas de reprodução de músicas**

|Objetivo  |
 -----------   |
|Abrir músicas identificadas pelo Shazam em outros aplicativos que reproduzam mídia musical |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca) em seguida, "Shazams recentes" e menu contido na música que o usuário escolheu<br>Pré-Condição: O usuário deve ter  identificado uma ou mais músicas<br>Pós-Condição: Usuário abre a música em outro app<br> |
|**Atores**|
|Usuário que deseja ouvir mídia que identificou através de outros apps de reprodução de música|
|**Recursos**|
|Internet, aplicativo, Apple Music, Google Play Music, Spotify|
|**Episódios**|
|Usuário clica em "biblioteca", em seguida, no título de "Shazams recentes" encontra suas músicas<br>Usuário escolhe a opção que deseja compartilhar<br>Usuário clica na música, em seguida, no menu à direita no canto inferior da tela<br>Usuário clica na opção "Abrir no Apple Music" ou "Abrir no Google Play music" ou "Abrir no Spotify" e escolhe a opção de seu interesse para reproduzir a música|
|**Restrição**|
|O usuário ter o aplicativo<br>Usuário possuir conta em alguma das plataformas disponíveis na opção de "Abrir a música"|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>A conta em alguma das plataformas de compartilhamento estar indisponível<br>O usuário não possuir conta em nenhuma das plataformas disponíveis|

# Cenário 11

**Remover alguma mídia identificada da biblioteca**

|Objetivo  |
 -----------   |
|Remover alguma música descoberta da biblioteca do Shazam |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca) em seguida, "Shazams recentes" e menu contido na música que o usuário escolheu<br>Pré-Condição: O usuário deve ter identificado uma ou mais músicas<br>Pós-Condição: Usuário remove a música de sua biblioteca <br> |
|**Atores**|
|Usuário que deseja remover uma música de sua biblioteca|
|**Recursos**|
|Internet, aplicativo, músicas da biblioteca do app|
|**Episódios**|
|Usuário clica em "biblioteca", em seguida, no título de "Shazams recentes" e encontra suas músicas<br>Usuário clica em alguma música e no menu à direita dessa música escolhida encontra a opção de remover música da sua biblioteca|
|**Restrição**|
|O usuário ter o aplicativo<br>Usuário possuir uma ou mais músicas em sua biblioteca|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>Usuário não ter nenhuma música em sua biblioteca|

# Cenário 12

**Visualizar letra de alguma música identificada**

|Objetivo  |
 -----------   |
|Visualizar as letras de músicas identificadas pelo Shazam|
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca) em seguida, "Shazams recentes" e a opção "letra" na música que o usuário escolheu<br>Pré-Condição: O usuário ter identificado uma ou mais músicas<br>Pós-Condição: Usuário acessa a letra de alguma das músicas de sua biblioteca|
|**Atores**|
|Usuário que deseja ter acesso a letra de alguma música de sua biblioteca|
|**Recursos**|
|Internet, aplicativo, músicas da biblioteca do app|
|**Episódios**|
|Usuário clica em "biblioteca", em seguida, no título de "Shazams recentes" e encontra suas músicas<br>Usuário clica em alguma música e na opção "letra"|
|**Restrição**|
|O usuário ter o aplicativo<br>Usuário possuir uma ou mais músicas em sua biblioteca|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>Não existir letra da música que o usuário optou<br>Usuário não ter nenhuma música em sua biblioteca|


## Controle de versão

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 27/09/2019 | 1.0 | Criação do documento | Nathalia Lorena |
| 27/09/2019 | 2.0 | Adicionando cenários | Nathalia Lorena |
| 28/09/2019 | 2.1 | Adicionando cenários | Nathalia Lorena |
