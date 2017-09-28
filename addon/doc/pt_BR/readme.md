# Temas Sonoros #

*   Autores: Musharraf Omer e outros
*   baixe a [versão estável][1]
*   baixe a [versão em desenvolvimento][2]

Este complemento cria uma tela sonora virtual que toca sons ao focar ou
navegar-se por objetos (como botões, linques etc.) O áudio será tocado numa
posição que corresponde à localização do objeto na tela visual.

O complemento também possibilita ativar, instalar, remover, editar, criar e
distribuir pacotes de temas sonoros.

## Uso

Este complemento possibilita executar três tarefas distintas, incluindo
gerir os temas sonoros instalados, editar o tema sonoro atualmente ativo e
criar um novo tema sonoro.

Voce pode acessar essas funções a partir do menu do complemento, que se
encontra no menu principal do NVDA.

### Gerenciando temas sonoros

- O diálogo "Gerir temas sonoros" possibilita ativar ou desativar temas
  sonoros, além de instalá-los e removê-los.
Neste diálogo, existem mais algumas opções incluindo:
 - Tocar som em modo 3D: Quando você desmarca esta caixa, o complemento tocará os sons em modo mono (sempre no centro da tela sonora) não importando o local do objeto.
 - Falar o papel, como botão, caixa de edição, linque etc.: Quando você desmarca esta caixa, o NVDA passará a anunciar o papel ao focar objetos em vez de ignorá-lo (que é o comportamento padrão ao instalar o complemento).
 - Usar volume do sintetizador: Marcar esta caixa fará o tocador de som do complemento usar o som da voz ativa, deixando assim toda a saída audível com o mesmo volume da voz cada vez que você muda esse volume.
 - Controle deslizante de volume do tema sonoro: Como alternativa, você pode configurar o volume do complemento usando este controle. Colocando ele em 0 vai silenciar todos os sons e 100 é o volume máximo.

### Editando o tema sonoro ativo:

- Quando você clica na opção "Editar o tema sonoro ativo", abre-se um
  diálogo contendo uma lista com todos os sons contidos no tema sonoro
  atualmente ativo. Neste diálogo, você pode::
- Alterar selecionado: Ao selecionar um som da lista e clicar neste botão,
  abre-se um diálogo padrão de abrir arquivo. Selecione um arquivo de áudio
  ogg ou wave do seu sistema de arquivos para substituir o som selecionado e
  clique em OK para completar o processo.
- Remover selecionado: Isto removerá do tema o som selecionado. Clique em
  "Sim" para concluir o processo de remoção e o som selecionado será
  removido.
- Adicionar novo som: Ao clicar neste botão, um novo diálogo será mostrado. Na primeira caixa de combinação do diálogo recém-aberto, selecione o tipo de objeto ao qual deseja associar um som, por exemplo botão, linque, guia, menu e assim por diante, aí clique no botão "Navegar até um arquivo de áudio" para selecionar o som que quer associar ao tipo de objeto anteriormente selecionado. Opcionalmente, você pode clicar no botão testar para reproduzir o som e clicando finalmente no botão OK aplicará as alterações e associará o som selecionado ao tipo de objetos.
- Fechar: Sairá do diálogo sem executar qualquer ação.

### Criar um novo tema sonoro

- Caso você tenha boas habilidades em produção de áudio, pode aplicá-las
aqui e criar um tema sonoro próprio ao invés de editar um existente. Para
fazê-lo, pode seguir estes passos:  - Junte seus arquivos de áudio num só
local, eles têm que estar em formato ogg or wave, e renomeie-os para
qualquer coisa que faça sentido. Por exemplo, quando eu estava criando o
tema sonoro Default para este complemento, agrupei os sons de acordo com
padrões de interação, por exemplo, a caixa de combinação, o botão de lista e
o botão de divisão podem ter todos o mesmo som, enquanto a caixa de seleção,
o botão de alternância e o item de menu podem ter o mesmo som.  - No menu do
complemento, clique em "Criar novo tema sonoro" - Um diálogo será aberto
solicitando algumas informações sobre o novo tema, incluindo: *	Nome do
tema: O nome do tema, que será mostrado no Gestor de temas sonoros. Este
deve ser um nome válido duma pasta do Windows.  *	Seu nome: Insira seu nome
verdadeiro ou um apelido.  *	Descrição do tema: Uma breve descrição do tema
sonoro.  - Clique em OK para ir ao próximo passo.  - No próximo passo, um
diálogo similar ao "Editor de temas sonoros" será mostrado e a partir daí o
processo é semelhante ao processo de editar um tema, por isso consulte a
seção "Editar o tema sonoro atualmente ativo".

## Copyright:

Copyright (c) 2014-2016 Musharraf Omer e outros

Embora este complemento tenha sido iniciado como um projeto independente, o
mesmo evoluiu para uma versão aprimorada do complemento "não-falado", de
Austin Hicks e Bryan Smart. Grande parte do desenvolvimento deste
complemento consistiu em criar as ferramentas para gerir, editar e criar
pacotes de temas sonoros. Portanto, um muito obrigado a eles por criar um
complemento tão maravilhoso e torná-lo disponível para construirmos encima
do trabalho deles.

## Nota sobre arquivos de áudio de terceiros:

O pacote de tema sonoro **Default** usa sons de diversas origens; eis um
apanhado das mesmas: - Áudio 3d não-falado: Um complemento para NVDA -
TWBlue: Um cliente gratuito e de código aberto para Twitter - Mushy
TalkBack: Um Talkback alternativo com sons melhores.

## Licença
Licenciado sob a Licença Pública Geral GNU. Vide o arquivo **copying** para
mais detalhes.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
