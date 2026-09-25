# Ajuda do sCollect

## O que a aplicação faz

O sCollect gere coleções de suportes — música, filmes, vídeos caseiros, audiolivros,
podcasts, e-books — e peças de coleção que não são ficheiros multimédia, como moedas ou
selos. Os nomes das categorias define-os a seu gosto em **Definições → Rótulos de
categorias**.

Aquilo que introduz no editor, a aplicação **volta a escrevê-lo no ficheiro**, e não
apenas no seu próprio catálogo.

## Primeiros passos

1. No primeiro arranque, escolha uma pasta para a biblioteca. É aí que ficarão depois os
   dados do catálogo e, se assim o quiser, também os ficheiros multimédia.
2. Traga ficheiros ou pastas através de **Ficheiro → Importar ficheiros** (⌘O) ou
   **Ficheiro → Importar pasta** (⇧⌘O), ou arraste-os para a janela.
3. Ao importar, decide em cada passagem se os ficheiros são **copiados para a biblioteca**
   ou apenas **vinculados**.

## Gerido ou vinculado?

| | |
|---|---|
| **Gerido** | O ficheiro fica na biblioteca. O sCollect arruma-o, muda-lhe o nome segundo o seu esquema e escreve as tags. |
| **Vinculado** | O ficheiro fica onde está. O sCollect guarda a localização e **não toca no ficheiro**. |

A coluna «Vinculado» na lista mostra qual dos casos se aplica.

## Perguntas frequentes

**Uma entrada tem um triângulo de aviso cor de laranja.**
O ficheiro dela não foi encontrado na última passagem de **Ficheiro → Biblioteca → Assinalar
elementos em falta**. A entrada não pode então ser editada — não há nada onde escrever. No menu de
contexto a aplicação oferece **Procurar ficheiro…**; o ficheiro encontrado é trazido de
volta para a biblioteca.

**No menu de contexto aparece «Unidade não ligada», esbatido.**
Nesse caso não é o ficheiro que desapareceu, é o disco. O sCollect distingue expressamente
os dois casos: o que não está ligado também não o pode verificar — e por isso também não o
assinala como em falta. Ligue o disco e volte a correr a passagem.

**Um tipo de multimédia está cinzento e não se deixa alterar.**
A pasta dele não está acessível de momento. O sCollect bloqueia esses tipos em vez de
guardar os ficheiros noutro sítio sem o dizer. Assim que o disco voltar, o bloqueio
termina.

**O editor mostra «Um campo difere do ficheiro».**
O ficheiro traz num campo algo diferente do que está na biblioteca — em regra porque outro
programa o editou entretanto. A faixa por cima dos campos mostra quais estão afetados, e é
o utilizador que decide, campo a campo, se o valor do ficheiro é assumido.

**Não encontro um campo de que preciso.**
Para as peças de coleção há três campos de nome livre. Como se devem chamar define-se por
categoria em **Definições → Rótulos de campos**.

**Posso trazer a minha coleção do iTunes ou da Música?**
Sim. O sCollect lê o XML do iTunes com avaliações e playlists. As faixas são associadas
através dos seus caminhos de ficheiro; as avaliações já existentes não são sobrescritas.

**Como volto a tirar a minha coleção para fora?**
Através do **sCollect-XML** — é sem perdas e serve ao mesmo tempo de cópia de segurança. A
par disso existe a exportação como iTunes-XML e como playlist para o Apple Music.

**O que faz a sincronização com as cópias?**
Uma biblioteca pode registar outras bibliotecas como cópias. As alterações no acervo
principal são levadas para lá, ficheiros e tags incluídos. Se uma cópia estiver offline
nesse momento, a alteração fica pendente e é feita mais tarde.

⚠️ **Isto não é um backup.** Um ficheiro apagado é apagado também nas cópias — é esse o
propósito de uma sincronização. Para o caso de algo correr mal, precisa adicionalmente de
uma verdadeira cópia de segurança.

**O meu ficheiro perde qualidade quando as tags são escritas?**
Não. Os dados de áudio e de imagem são assumidos sem alteração; nada é recodificado. Onde
é possível, o sCollect altera apenas os poucos bytes da tag, em vez de voltar a escrever o
ficheiro.

**Preciso de uma cópia de segurança?**
Sim. O sCollect grava nos seus ficheiros, não numa cópia deles. Faça uma cópia de segurança antes de grandes alterações em muitas entradas de uma só vez; o Time Machine basta.

**Posso desfazer uma alteração?**
As entradas apagadas ⌘Z traz de volta. As alterações aos metadados não — por isso, antes
de uma grande passagem em lote, faça uma cópia de segurança.

## Alguma coisa corre mal?

O sCollect escreve um registo na pasta da sua biblioteca — regista o que a aplicação fez e
quando. Envie-o juntamente com a descrição do erro.

## Contacto

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
