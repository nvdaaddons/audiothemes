# Temas de Áudio #

*   Autores: Musharraf Omer e outros
*   baixar a [versão estável][1]
*   baixar a [versão em desenvolvimento][2]

Este extra cria um ecrã áudio virtual que toca sons, quando se foca ou se
navega por objectos (como botões, linques etc.) O áudio será reproduzido
numa posição que representa a localização do objecto no ecrã visual.

O extra também possibilita activar, instalar, remover, editar, criar e
distribuir pacotes de temas de áudio.

## Utilização:

Este extra permite efectuar três tarefas distintas: gerir os temas de áudio
instalados, editar o tema áudio actualmente activo e criar um novo tema
áudio.

Pode aceder a essas funções a partir do menu do extra, que se encontra no
menu principal do NVDA.

### Gerir os seus temas de áudio

- O diálogo "Gerir temas de áudio" possibilita activar ou desativar esses
  temas, além de instalá-los e removê-los.
Neste diálogo, existem ainda outras opções: 
 - reproduzir som em modo 3D: Quando se desmarca esta caixa, o extra reproduzirá os sons em modo mono (sempre no centro do ecrã de áudio) não importando o local do posicionamento do objecto.
 - Falar o objecto, como botão, caixa de edição, linque etc.: Quando se desmarca esta caixa, o NVDA passará a anunciar o tipo ao focar objectos em vez de ignorá-lo (que é o comportamento padrão ao instalar o extra).
 - Usar volume do sintetizador: se Marcar esta caixa fará com que o reprodutor de som do extra use o volume da voz activa, deixando assim toda a saída audível com o mesmo volume da voz cada vez que muda esse volume.
 - Controle deslizante de volume do tema áudio: Como alternativa, pode configurar apenas o volume do extra usando este controlo. Se o colocar em 0 silenciará os sons do extra e colocá-los-á no máximo se posicionar o volume em 100.

### A editar o tema de áudio activo:

- Quando clica na opção "Editar o tema áudio activo", abre-se um diálogo que
  contém uma lista com todos os sons presentes no tema de áudio actualmente
  activo. Neste diálogo, pode:
- Modificar seleccionado: Ao seleccionar um som da lista e clicar neste
  botão, abre-se um diálogo padrão de abrir ficheiro. Escolha um ficheiro de
  áudio com formato ogg ou wave do seu sistema de ficheiros para substituir
  o som seleccionado e clique em OK para completar o processo.
- Remover seleccionado: Isto apagará do tema de áudio o som
  escolhido. Clique em "Sim" para concluir o processo de remoção e o som
  seleccionado será apagado.
- Adicionar novo som: Ao clicar neste botão, um novo diálogo será exibido. Na primeira caixa de combinação, escolha o tipo de objecto ao qual deseja associar um determinado som, por exemplo botão, linque, guia, menu, etc., depois, clique no botão "Navegar até um ficheiro de áudio" para seleccionar o som que quer associar ao tipo de objecto anteriormente seleccionado. Opcionalmente, pode clicar no botão testar para reproduzir o som escolhido e, se activar  no botão OK aplicará as alterações e associará o som seleccionado ao tipo de objetos.
- Fechar: Sairá do diálogo sem executar qualquer acção.

### Criar um novo tema de áudio

- Caso você tenha boas habilidades em produção de áudio, pode aplicá-las
aqui e criar um tema áudio próprio ao invés de editar um existente. Para
fazê-lo, pode seguir estes passos:  - Junte seus ficheiros de áudio num só
local, eles têm que estar em formato ogg or wave, e renomeie-os para
qualquer coisa que faça sentido. Por exemplo, quando eu estava criando o
tema áudio Default para este complemento, agrupei os sons de acordo com
padrões de interação, por exemplo, a caixa de combinação, o botão de lista e
o botão de divisão podem ter todos o mesmo som, enquanto a caixa de seleção,
o botão de alternância e o item de menu podem ter o mesmo som.  - No menu do
complemento, clique em "Criar novo tema áudio" - Um diálogo será aberto
solicitando algumas informações sobre o novo tema, incluindo: *	Nome do
tema: O nome do tema, que será mostrado no Gestor de temas de áudio. Este
deve ser um nome válido duma pasta do Windows.  *	Seu nome: Insira seu nome
verdadeiro ou um apelido.  *	Descrição do tema: Uma breve descrição do tema
áudio.  - Clique em OK para ir ao próximo passo.  - No próximo passo, um
diálogo similar ao "Editor de temas de áudio" será mostrado e a partir daí o
processo é semelhante ao processo de editar um tema, por isso consulte a
seção "Editar o tema áudio atualmente ativo".

## Copyright:

Copyright (c) 2014-2016 Musharraf Omer e outros

Embora este complemento tenha sido iniciado como um projeto independente, o
mesmo evoluiu para uma versão aprimorada do complemento "não-falado", de
Austin Hicks e Bryan Smart. Grande parte do desenvolvimento deste
complemento consistiu em criar as ferramentas para gerir, editar e criar
pacotes de temas de áudio. Portanto, um muito obrigado a eles por criar um
complemento tão maravilhoso e torná-lo disponível para construirmos encima
do trabalho deles.

## Nota sobre ficheiros de áudio de terceiros:

O pacote de tema áudio **Default** usa sons de diversas origens; eis um
apanhado das mesmas: - Áudio 3d não-falado: Um complemento para NVDA -
TWBlue: Um cliente gratuito e de código aberto para Twitter - Mushy
TalkBack: Um Talkback alternativo com sons melhores.

## Licença
Licenciado sob a Licença Pública Geral GNU. Vide o ficheiro **copying** para
mais detalhes.

[[!tag dev]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
