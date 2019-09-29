# Cenários

## Introdução


Os cenários consistem de uma coleção de narrativas de situações no domínio que favorecem o levantamento de informações em um contexto proposto que permitem a identificação de possíveis tarefas e funcionalidades que se pode realizar em um software, como também identifica problemas e a antecipação das soluções. A técnica de elaborar cenários é uma maneira excelente de representar, para clientes e usuários, os problemas existentes em um software e as possibilidades que podem surgir. Os cenários têm como foco as atividades desempenhadas pelos usuários nas organizações em diferentes contextos possibilitando uma perspectiva mais ampla dos problemas atuais onde o sistema será inserido, explicando porque ele é necessário.

# Cenário 1

**Identificar uma música**

|Objetivo  |
 -----------   |
|Descobrir uma música       |
|**Contexto** |
|Local: Página inicial do Shazam (login não obrigatório)<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: usuário descobre música<br> |
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
|Local: Tela da esquerda do Shazam (no ícone de configurações)<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: usuário realiza inscrição<br> |
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
|Usuário deseja visualizar as músicas que descobriu   |
|**Contexto** |
|Local: Tela da esquerda do Shazam (em biblioteca)<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: usuário visualiza músicas que descobriu<br> |
|**Atores**|
|Usuário que deseja ter acesso às músicas que descobriu|
|**Recursos**|
|Internet, aplicativo, músicas descobertas|
|**Episódios**|
|Usuário quer visualizar uma música que descobriu<br>Usuário clica no ícone escrito "biblioteca" ou desliza o dedo da esquerda para a direita partindo da tela de início<br>O usuário encontra suas músicas e artistas na biblioteca|
|**Restrição**|
|O usuário ter o aplicativo<br>O usuário ter clicado no botão de busca|
|**Exceção**|
|Internet cair<br>Músicas não terem sido reconhecidas<br>Aplicativo estar indisponível<br>|


# Cenário 4

**Salvar músicas descobertas**

|Objetivo  |
 -----------   |
|Usuário deseja salvar as músicas que descobriu   |
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
|Usuário deseja efetuar busca por músicas ou artistas já disponíveis no app   |
|**Contexto** |
|Local: Tela da direita do Shazam (ícone de descobrir)<br>Pré-Condição: Ter instalado<br>Pós-Condição: Usuário encontra músicas ou artistas de seu interesse existentes no app<br> |
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
|Usuário deseja fazer login no app pra salvar suas músicas |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca)<br>Pré-Condição: Ter o app instalado<br>Pós-Condição: Usuário clica na opção de fazer login<br> |
|**Atores**|
|Usuário que deseja ter sua conta logada e já fez inscrição|
|**Recursos**|
|Internet, aplicativo, e-mail válido|
|**Episódios**|
|Usuário prefere ter uma conta com login<br>Usuário clica no ícone escrito "Biblioteca" ou desliza o dedo da esquerda para a direita partindo da tela de início e depois no clica no botão referente a "fazer login" em seguida, clica na opção de realizá-lo com e-mail ou facebook<br>O usuário recebe uma validação por e-mail<br>Após a confirmação o usuário estará logado|
|**Restrição**|
|O usuário ter o aplicativo|
|**Exceção**|
|Internet cair<br>Usuário esquecer e-mail<br>Usuário não ter confirmado a conta por e-mail|


# Cenário 7

**Sair do aplicativo Shazam**

|Objetivo  |
 -----------   |
|Usuário deseja fazer logout no app |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da biblioteca) em seguida, ícone de configurações<br>Pré-Condição: o usuário deve estar logado<br>Pós-Condição: Usuário clica na opção de "sair" e encerra a sessão a conta<br> |
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


## Controle de versão

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 27/09/2019 | 1.0 | Criação do documento | Nathalia Lorena |
| 27/09/2019 | 2.0 | Adicionando cenários | Nathalia Lorena |
