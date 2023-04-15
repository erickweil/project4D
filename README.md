# project4D
Project 4D - Navegue em um mundo com quatro dimensões espaciais

## Gameplay
O jogo consiste em algumas fases onde que o objetivo é coletar todos os núcleos (hyper-octaedros verdes que ficam rodando), após coletar todos os núcleos deve entrar no portal (dois hyper-torus xadrez vermelho rodando).

## Controles
- W, A, S, D ou setas para se mover
- Espaço para pular
- Shift + Scroll do mouse para controlar zoom da camera
- 1, 2 e 3 para mudar o hyper-plano de corte 3D
- Scroll do mouse para rodar suavemente o hyper-plano de corte 3D atual
- J e K para trocar o eixo Y pelo W e vice-versa

# Editor
Os controles do editor são inspirados no Blender

## Camera
Os mesmos controles da Gameplay, porém:
- Segure Botão direito para orbitar a camera
- Segure Botão direito + W, A, S, D ou setas para mover
- Shift + Botão Esquerdo para mover lateralmente

## Interação com Objetos
Os submenus contém quase todas as opções e que atalhos utilizar. Mas segue uma lista do mais utilizado:

## Seleção
- Botão esquerdo para selecionar objeto
- Shift + Botão esquerdo para selecionar vários
- A seleciona todos os objetos
- C seleciona um círculo

## Transformações
Em todos os casos de mover, rotacionar ou escala o procedimento é o mesmo: Você inicia a transformação, opcionalmente especifica os eixos X, Y, Z ou W, move o mouse ou escreve o número exato, e então aperta Enter/Botão Esquerdo para confirmar, ou Esc/Botão Direito para cancelar

- G Inicia Movimentação
- S Inicia Escala
- R Inicia Rotação
  
### Eixos
Em escala e movimentação, digite X, Y, Z ou W para travar neste exio (Shift para mover em todos menos este)
Em rotação, digite XY, XZ, YZ, XW, ZW, YW para movimentar neste plano de rotação
Durante uma rotação, o padrão é rotacionar no plano visível atual, porém segure Shift para rotacionar perpendicular ao plano atual.

### Controle Preciso
Enquando está movendo, escalonando ou rotacionando é possível digitar números que irão afetar a movimentação de forma precisa. no caso da rotação os valores são em graus 0-360.

## Modos de Edição
Com um objeto selecionado:

- Tab entra no modo Mesh Edit
- U+ Tab entra no modo UV/Color Edit
- N+ Tab entra no modo Normal Edit 
- T+ Tab entra no modo Texture Edit
