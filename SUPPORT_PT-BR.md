# Ajuda do sCollect

## O que o app faz

O sCollect gerencia coleções de mídia — música, filmes, vídeos caseiros, audiolivros,
podcasts, e-books — e peças de coleção que não são arquivos de mídia, como moedas ou
selos. Os nomes das categorias quem define é você, em **Configurações → Rótulos de
categorias**.

O que você digita no editor, o app **grava de volta no arquivo**, não apenas no próprio
catálogo.

## Primeiros passos

1. Na primeira inicialização, escolha uma pasta para a biblioteca. É lá que ficarão depois
   os dados do catálogo e, se você quiser assim, também os arquivos de mídia.
2. Traga arquivos ou pastas por **Arquivo → Importar arquivos** (⌘O) ou **Arquivo →
   Importar pasta** (⇧⌘O), ou arraste-os para a janela.
3. Na importação você decide a cada rodada se os arquivos são **copiados para a
   biblioteca** ou apenas **vinculados**.

## Gerenciado ou vinculado?

| | |
|---|---|
| **Gerenciado** | O arquivo fica na biblioteca. O sCollect o organiza, renomeia conforme o seu esquema e grava as tags. |
| **Vinculado** | O arquivo continua onde está. O sCollect guarda o local e **não toca no arquivo**. |

A coluna “Vinculado” na lista mostra qual é o caso.

## Perguntas frequentes

**Uma entrada tem um triângulo de aviso laranja.**
O arquivo dela não foi encontrado na última rodada de **Arquivo → Biblioteca → Marcar
itens ausentes**. A entrada não pode então ser editada — não há nada em que gravar. No menu de
contexto o app oferece **Procurar arquivo…**; o arquivo encontrado é trazido de volta para
a biblioteca.

**No menu de contexto aparece “Unidade não conectada”, esmaecido.**
Então não é o arquivo que sumiu, é o disco. O sCollect distingue expressamente os dois
casos: o que não está conectado ele também não pode verificar — e por isso também não
marca como ausente. Conecte o disco e rode a varredura de novo.

**Um tipo de mídia está cinza e não pode ser alterado.**
A pasta dele não está acessível no momento. O sCollect bloqueia esses tipos em vez de
guardar os arquivos em outro lugar sem avisar. Assim que o disco voltar, o bloqueio
termina.

**O editor mostra “Um campo difere do ficheiro”.**
O arquivo traz num campo algo diferente do que está na biblioteca — em geral porque outro
programa o editou nesse meio-tempo. A faixa acima dos campos mostra quais estão afetados,
e você decide campo a campo se o valor do arquivo é assumido.

**Não acho um campo de que preciso.**
Para peças de coleção existem três campos de nome livre. Como eles devem se chamar você
define por categoria em **Configurações → Rótulos de campos**.

**Posso trazer a minha coleção do iTunes ou do Música?**
Sim. O sCollect lê o XML do iTunes com avaliações e playlists. As faixas são associadas
pelos seus caminhos de arquivo; avaliações já existentes não são sobrescritas.

**Como tiro a minha coleção de volta para fora?**
Pelo **sCollect-XML** — ele é sem perdas e serve ao mesmo tempo como backup. Além dele
existe a exportação como iTunes-XML e como playlist para o Apple Music.

**O que a sincronização faz com as cópias?**
Uma biblioteca pode registrar outras bibliotecas como cópias. As alterações no acervo
principal são levadas para lá, arquivos e tags inclusive. Se uma cópia estiver offline no
momento, a alteração fica pendente e é feita depois.

⚠️ **Isso não é um backup.** Um arquivo apagado é apagado também nas cópias — esse é o
propósito de uma sincronização. Para o caso de algo dar errado, você precisa
adicionalmente de um backup de verdade.

**O meu arquivo perde qualidade quando as tags são gravadas?**
Não. Os dados de áudio e de imagem são assumidos sem alteração; nada é recodificado. Onde
dá, o sCollect muda apenas os poucos bytes da tag, em vez de gravar o arquivo de novo.

**Preciso de backup?**
Sim. O sCollect grava nos seus arquivos, não em uma cópia deles. Faça um backup antes de grandes alterações em muitas entradas de uma vez; o Time Machine basta.

**Posso desfazer uma alteração?**
Entradas apagadas o ⌘Z traz de volta. Alterações em metadados não — por isso, antes de uma
grande rodada em lote, faça um backup.

## Algo deu errado?

O sCollect escreve um registro na pasta da sua biblioteca — ele anota o que o app fez e
quando. Mande-o junto com a descrição do erro.

## Contato

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
