# Política de privacidade do sCollect

Atualizado em: 2026-11-16

## Resumo

O sCollect **não** coleta, não armazena e não transmite dados pessoais. O app trabalha
exclusivamente no seu Mac ou PC com Windows. Não há contas, não há conexão com a nuvem, não há serviços de
análise e não há publicidade.

## Quais dados o app processa

O sCollect lê e grava os arquivos de mídia nas pastas que você entregou a ele
expressamente — escolhendo-as na janela de abertura ou arrastando-as para a janela. São
lidos o nome do arquivo, o tamanho do arquivo, a data e os metadados do arquivo; são
gravadas as informações que você digita no editor.

Sem a sua escolha o app não acessa arquivo algum. O macOS impõe isso pelo sandbox do app.

## O que o app guarda no seu Mac

- **A própria biblioteca** na pasta que você escolheu para ela: os dados do catálogo, as
  capas e um registro das sincronizações ainda não executadas.
- **Configurações e posições das janelas** na pasta protegida do app.
- **A permissão do macOS para reabrir as suas pastas na próxima inicialização.** São
  armazenados os caminhos das pastas, não o conteúdo dos arquivos. Só assim o app não
  precisa perguntar de novo a cada inicialização.
- **Um registro de diagnóstico** com horários e contagens de operações. Ele fica no seu
  Mac; você pode salvá-lo e repassá-lo quando relatar um erro.

Tudo isso é removido quando você apaga o app e a sua biblioteca.

## Duas permissões que podem levantar perguntas

**Acesso à rede.** O app a solicita porque, sem essa permissão, o macOS mostra vazia a
janela de ajuda integrada — a ajuda é exibida por um componente do sistema que precisa
dela, mesmo que carregue apenas arquivos do próprio programa. Por conta própria, o
sCollect **não chama nenhum endereço na internet**, não baixa nada e não relata nada.

Bibliotecas em unidades de rede (SMB, NFS) o app alcança pelo sistema de arquivos do seu
Mac, não por uma conexão própria.

**Controle do Apple Music.** Ao exportar uma playlist, o sCollect abre o Apple Music com o
arquivo gerado. Para isso o macOS pede o seu consentimento, e ele é solicitado na primeira
vez. O app não controla outros programas.

## Os seus arquivos

O sCollect altera os metadados exatamente nos arquivos que pertencem à sua biblioteca e os
move, ao organizá-los, dentro das pastas que você liberou.

**Os objetos vinculados ficam intactos** — eles estão fora da biblioteca, e o app não
grava nada lá.

Arquivos apagados vão primeiro para um lixo próprio dentro da biblioteca e podem ser
trazidos de volta de lá. Só são removidos definitivamente quando você o esvazia.

## No Windows

As seções acima descrevem o Mac. No Windows, o sCollect guarda o seguinte exclusivamente de forma local:

Na pasta de dados do app (`%LOCALAPPDATA%\Packages\<pacote>\LocalState` e `Settings`):

- **Configurações, posição da janela e visualização** — as bibliotecas abertas recentemente, a seleção na barra lateral, as
  últimas faixas reproduzidas, as colunas e a ordenação.
- **A correspondência entre as pastas Mac de uma biblioteca e pastas do seu PC** (apenas caminhos de pastas).
- **Sugestões de preenchimento** — valores que você já usou em campos como gênero ou idioma, oferecidos como sugestões.
- **Um identificador aleatório deste PC.** Ele distingue os seus computadores nas cópias de uma biblioteca e não contém nada
  sobre você.
- **Um registro de diagnóstico** com horários, operações e os caminhos dos arquivos envolvidos, e um **registro de erros**
  (`fehler.log`, sete dias). Ambos ficam no seu PC; você pode repassá-los quando relatar um erro.

Na pasta da biblioteca que você escolheu: os dados do catálogo, as capas, o lixo da biblioteca e — se ela tiver cópias — os
locais delas e as sincronizações ainda não executadas. Enquanto o sCollect tem uma biblioteca aberta, ele mantém ali também um
**arquivo de bloqueio** com o **nome do seu PC**, para que dois computadores não gravem ao mesmo tempo na mesma biblioteca. Se a
biblioteca estiver em uma unidade de rede, outros usuários dessa unidade podem ver o nome.

O que está na pasta de dados do app é removido quando você desinstala o app; a biblioteca permanece até que você mesmo a apague.

O sCollect só lê e grava arquivos de mídia nas pastas que você entrega a ele. O app não faz conexões de rede próprias, não usa
serviços de análise e não exibe publicidade. Arquivos que o Windows não reproduz sozinho são passados ao programa padrão para
esse tipo de arquivo, que você escolhe no Windows. Para converter e recortar áudio e vídeo, ele usa o FFmpeg incluído, também
apenas no seu PC.

Se você enviar uma playlist ao iTunes, o sCollect abre o iTunes para Windows com essa playlist; o app não controla outros
programas. Se você exportar uma playlist para o VLC ou um dispositivo, o app copia os arquivos dela para a pasta que você
escolher.

## Microsoft Store

No Windows, a compra, o download e as atualizações são feitos pela Microsoft Store; para isso vale a declaração de privacidade
da Microsoft.

## Sem repasse, sem análise

Não há publicidade, não há serviços de análise, não há relatórios de falha para terceiros
e não há contas.

## Contato

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
