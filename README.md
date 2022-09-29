# npc-godot

## NPC de uma Vigia criado com a Engine Godot

## Atividades do NPC

- Um vigia percorre um perímetro patrulhando um tesouro.
Esse perímetro deve ser definido usando um "caminho" em Godot.

- Se o usuário acionar a tecla espaço, o vigia fica desorientado:
durante 15 segundos sua caminhada fica um pouco errática.

- Se o usuário clicar em algum ponto do cenário enquanto acontece a ronda,
o vigia se dirige rapidamente a esse ponto,
circula-o 2 vezes, volta ao perímetro e prossegue sua patrulha normal.

- Se o tal clique no cenário acontecer enquanto o vigia está 'desorientado',
então ele fica parado (finge-se de morto!) durante 5 segundos.
Depois volta a patrulhar o perímetro como sempre.

- Depois de acionar 2x a tecla espaço, o vigia fica apertado.
Ao passar perto do toilette, desvia da ronda e entra nele,
lá permanecendo durante 5 segundos.
Depois disso o vigia retoma sua patrulha normal.
