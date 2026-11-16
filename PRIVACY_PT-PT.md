# Política de privacidade do sCollect

Atualizado a: 2026-11-16

## Em resumo

O sCollect **não** recolhe, não guarda e não transmite dados pessoais. A aplicação
trabalha exclusivamente no seu Mac ou PC com Windows. Não há contas, não há ligação à nuvem, não há serviços
de análise e não há publicidade.

## Que dados a aplicação processa

O sCollect lê e escreve os ficheiros multimédia nas pastas que lhe entregou
expressamente — escolhendo-as na janela de abertura ou arrastando-as para a janela. São
lidos o nome do ficheiro, o tamanho do ficheiro, a data e os metadados do ficheiro; são
escritas as indicações que introduz no editor.

Sem a sua escolha, a aplicação não acede a ficheiro nenhum. O macOS impõe-o através da
sandbox da aplicação.

## O que a aplicação deposita no seu Mac

- **A própria biblioteca** na pasta que escolheu para ela: os dados do catálogo, as capas
  e um registo das sincronizações ainda por executar.
- **Definições e posições das janelas** na pasta protegida da aplicação.
- **A autorização do macOS para voltar a abrir as suas pastas no arranque seguinte.** São
  guardados os caminhos das pastas, não os conteúdos dos ficheiros. Só assim a aplicação
  não tem de perguntar de novo em cada arranque.
- **Um registo de diagnóstico** com horas e contagens de operações. Fica no seu Mac; pode
  guardá-lo e enviá-lo quando comunicar um erro.

Tudo isto é removido quando apagar a aplicação e a sua biblioteca.

## Duas autorizações que podem levantar dúvidas

**Acesso à rede.** A aplicação pede-o porque, sem esta autorização, o macOS mostra vazia a
janela de ajuda integrada — a ajuda é apresentada por um componente do sistema que dela
necessita, mesmo carregando apenas ficheiros do próprio programa. Por iniciativa própria,
o sCollect **não contacta nenhum endereço na internet**, não descarrega nada e não comunica
nada.

As bibliotecas em unidades de rede (SMB, NFS) a aplicação alcança-as através do sistema de
ficheiros do seu Mac, não através de uma ligação própria.

**Controlo do Apple Music.** Ao exportar uma playlist, o sCollect abre o Apple Music com o
ficheiro gerado. Para isso o macOS pede o seu consentimento, que é solicitado da
primeira vez. A aplicação não controla outros programas.

## Os seus ficheiros

O sCollect altera os metadados exatamente nos ficheiros que pertencem à sua biblioteca e
move-os, ao arrumá-los, dentro das pastas que autorizou.

**Os objetos vinculados ficam intactos** — encontram-se fora da biblioteca, e aí a
aplicação não escreve nada.

Os ficheiros apagados vão primeiro para uma reciclagem própria dentro da biblioteca e daí
podem ser recuperados. Só são removidos definitivamente quando a esvaziar.

## No Windows

As secções acima descrevem o Mac. No Windows, o sCollect guarda o seguinte exclusivamente de forma local:

Na pasta de dados da aplicação (`%LOCALAPPDATA%\Packages\<pacote>\LocalState` e `Settings`):

- **Definições, posição da janela e vista** — as bibliotecas abertas recentemente, a seleção na barra lateral, as últimas faixas
  reproduzidas, as colunas e a ordenação.
- **A correspondência entre as pastas Mac de uma biblioteca e pastas do seu PC** (apenas caminhos de pastas).
- **Sugestões de introdução** — valores que já utilizou em campos como género ou idioma, apresentados como sugestões.
- **Um identificador aleatório deste PC.** Distingue os seus computadores nas cópias de uma biblioteca e não contém nada sobre
  si.
- **Um registo de diagnóstico** com horas, operações e os caminhos dos ficheiros envolvidos, e um **registo de erros**
  (`fehler.log`, sete dias). Ambos ficam no seu PC; pode enviá-los quando comunicar um erro.

Na pasta da biblioteca que escolheu: os dados do catálogo, as capas, a reciclagem da biblioteca e — se tiver cópias — as
respetivas localizações e as sincronizações ainda por executar. Enquanto o sCollect tiver uma biblioteca aberta, guarda aí
também um **ficheiro de bloqueio** com o **nome do seu PC**, para que dois computadores não escrevam ao mesmo tempo na mesma
biblioteca. Se a biblioteca estiver numa unidade de rede, outros utilizadores dessa unidade podem ver o nome.

O que está na pasta de dados da aplicação é removido quando desinstala a aplicação; a biblioteca mantém-se até que seja o
próprio a apagá-la.

O sCollect só lê e escreve ficheiros multimédia nas pastas que lhe entregar. A aplicação não estabelece ligações de rede
próprias, não usa serviços de análise e não apresenta publicidade. Os ficheiros que o Windows não reproduz sozinho são entregues
ao programa predefinido para esse tipo de ficheiro, que escolhe no Windows. Para converter e encurtar áudio e vídeo, utiliza o
FFmpeg incluído, também apenas no seu PC.

Se enviar uma playlist para o iTunes, o sCollect abre o iTunes para Windows com essa playlist; a aplicação não controla outros
programas. Se exportar uma playlist para o VLC ou um dispositivo, a aplicação copia os respetivos ficheiros para a pasta que
escolher.

## Microsoft Store

No Windows, a compra, a transferência e as atualizações são feitas através da Microsoft Store; aplica-se a declaração de
privacidade da Microsoft.

## Sem transmissão, sem análise

Não há publicidade, não há serviços de análise, não há relatórios de falha para terceiros
e não há contas.

## Contacto

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
