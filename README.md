# Home Work for Mobile Robots Programming discipline

- [x] Módulo 1 (Check Point)
- [ ] Módulo 2 (Improvement of Check Point)

### Descrição

O algoritmo foi implementado utilizando uma máquina finita de estados, onde cada estado realiza uma tarefa específica. O robô faz uso de um sensor a laser, sonares, e uma bússola.

#### Notas
- Dados os ponto iniciais dos 3 mapas, o robô consegue alcançar o seu destino com sucesso.
- Ao se ter todos os sonares em 0 (não há possibilidade de colisão no momento), o robô sempre acertará a direção.
- Se o robô entrar em determinados "quartos", ele ficará preso nele. Por exemplo, no Mapa 1, se manter o ponto do destino inalterado e, posicionar o robô em outra coordenada inicialmente, ele, provavelmente, chegará a entrar em um "quarto", e não conseguirá sair.