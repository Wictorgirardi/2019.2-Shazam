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