# VagaLume

Protótipo navegável de um sistema de orientação para grandes estacionamentos. Totens com tela touchscreen e uma trilha de luzes guiam o motorista até a vaga onde deixou o carro, sem precisar de celular.

## Para quem é

Motoristas que usam estacionamentos grandes, como os de shoppings, hospitais e aeroportos, e não lembram onde estacionaram. A solução considera especialmente pessoas idosas, pessoas com mobilidade reduzida e pessoas surdas.

## Como funciona

1. **Identificação:** no totem, a pessoa digita a placa, fala a placa ou aproxima o ticket do estacionamento.
2. **Confirmação:** o totem mostra o carro encontrado, com placa, piso e pilar, e a pessoa confirma se é o dela.
3. **Orientação:** uma trilha de luzes de uma cor e um código próprios (por exemplo, verde A12) acende até a vaga. O mapa, as instruções em texto e o áudio ajudam no caminho.
4. **Chegada:** a luz da vaga pisca para indicar o carro.

Em todas as telas é possível chamar um atendente. Se o carro não for encontrado, dá para tentar de novo ou buscar pelo horário de entrada.

## Como testar

Abra o `index.html` em qualquer navegador. Não precisa instalar nada.

Placas de teste:

| Placa | Luz | Código | Local |
|---|---|---|---|
| ABC-1D23 | verde | A12 | Piso 2, Pilar 12 |
| XYZ-9F87 | azul | B07 | Piso 1, Pilar 8 |

Qualquer outra placa leva à mensagem de placa não encontrada.

O microfone, o leitor de ticket, a chamada do atendente e o deslocamento pelo estacionamento são simulados. Na tela da rota, os botões "Avançar", "Caminhar" e "Trecho anterior" representam a pessoa andando até a vaga.

## Telas

INT01 Página inicial · INT02 Inserção da placa · INT03 Confirmação do veículo · INT04 Mapa e instruções · INT05 Chamar atendente · INT06 Veículo não encontrado · INT07 Busca por horário · INT08 Reconhecimento por voz · INT09 Leitura do ticket · INT10 Chegada ao veículo

## Acessibilidade

- Modo acessível com letras maiores e instruções lidas em voz alta
- Instruções sonoras sempre acompanhadas de texto
- Rotas identificadas por cor, símbolo e código, para não depender só da cor
- Fonte Atkinson Hyperlegible, criada para facilitar a leitura

## Sobre o trabalho

TP1 da disciplina **Interação Humano-Computador**, com a Profa. Glívia Angélica Rodrigues Barbosa, Departamento de Computação (DECOM).

**Grupo:** Anélio Gonçalves Caldas, Emanuelle Camile de Paulo Lima, Gustavo de Assis Xavier e Lucas Alexsanderson da Fonseca.
