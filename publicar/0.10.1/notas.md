### Novo
- Modo desenvolvedor escondido, com senha:
  - abre com Shift + F12, ou com 5 toques de três dedos no celular; não aparece no F1 nem na lista de teclas;
  - a senha pode ser trocada lá dentro;
  - os testes técnicos e as salas de som saíram das opções e foram para lá, com o Ctrl + T da sala de testes;
  - com um jogo aberto: velocidade do tempo (1, 2, 5, 10 ou 30 vezes), pular 1 hora ou 1 dia, voltar o relógio e voltar à hora de verdade;
  - criar um pet escolhendo espécie, raça, sexo e jeito;
  - mudar comida, água, felicidade, confiança e saúde de cada pet, fazer adoecer ou fugir;
  - dar ou tirar moedas, e ir direto para a casa, a frente de casa, a Animais & Vida, o mercado, a padaria, a praça, a Vila das Casas ou a praia;
  - trancar ou destrancar a casa;
  - qualquer mudança marca o save como "de teste", e a lista de contas mostra isso.
- Na cidade, o jogo fala o chão quando ele muda: calçada, "no asfalto da Rua das Gaivotas", faixa de pedestre, grama, terra e areia.
- Na beira da calçada, o jogo diz onde fica a faixa de pedestre mais perto, em metros e para que lado.
- Dá para desligar a fala do chão nas opções.
- Se um carro atinge um pet pequeno, vem uma cena contada, com sons:
  - o freio, a batida e o choro do pet;
  - o motorista ajuda e leva vocês para a Animais & Vida;
  - a Dra. Helena trata o machucado;
  - a conta, de 90 moedas, vem para você (ou o que você tiver, se for menos);
  - você termina no consultório, com o pet na coleira; ele fica com medo por um tempo.
- Preparo do servidor:
  - cada casa ganha um id e um dono (o id do jogador), e pode estar aberta ou trancada;
  - a cidade ganhou a Vila das Casas, perto de casa: lotes de 14 por 22 metros, todos do mesmo tamanho, com muro e portão na calçada, para as casas da 0.11 e as dos outros jogadores.

### Mudou
- Dá para atravessar a rua em qualquer lugar de novo, como você pediu. Fora da faixa:
  - os carros buzinam e desviam de você pela outra pista, devagar, quando ela está livre;
  - se não está livre, param antes e buzinam;
  - um pet pequeno, o motorista às vezes vê tarde demais.
- A faixa continua sendo o lugar seguro, com o sinal de pedestre.
- A ajuda do F1 no mapa explica isso.

### Sons
- Novos: freio, batida, choro de cachorro e de gato, porta do carro e o carro andando, todos da sua pasta de sons. A lista está em `docs/sons/sons-0.10.1.md`.
- Estão no artefato "Sons dos meus jogos", na parte "Rua", com outros da sua pasta, para você escolher.
