# Política de privacidade do sCollect

Atualizado a: 2026-09-16

## Em resumo

O sCollect **não** recolhe, não guarda e não transmite dados pessoais. A aplicação
trabalha exclusivamente no seu Mac. Não há contas, não há ligação à nuvem, não há serviços
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

## Sem transmissão, sem análise

Não há publicidade, não há serviços de análise, não há relatórios de falha para terceiros
e não há contas.

## Contacto

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
