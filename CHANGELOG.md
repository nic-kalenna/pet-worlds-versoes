# Changelog do Pet Worlds

Este arquivo lista, versão por versão, o que entrou, o que mudou e o que foi corrigido. A mais nova fica no alto. As versões antigas, com os arquivos para baixar, ficam nas releases do GitHub.

## 0.10.1: ruas livres, a calçada falada e a Vila das Casas, 17/11/2026

### Novo
- Na cidade, o jogo fala o chão quando ele muda: calçada, "no asfalto da Rua das Gaivotas", faixa de pedestre, grama, terra e areia.
- Na beira da calçada, o jogo diz onde fica a faixa de pedestre mais perto, em metros e para que lado.
- Dá para desligar a fala do chão nas opções.
- Se um carro atinge um pet pequeno, vem uma cena contada, com sons:
  - o freio, a batida e o choro do pet;
  - o motorista ajuda e leva vocês para a Animais & Vida;
  - a Dra. Helena trata o machucado;
  - a conta, de 90 moedas, vem para você (ou o que você tiver, se for menos);
  - você termina no consultório, com o pet na coleira; ele fica com medo por um tempo.
- A cidade ganhou a Vila das Casas, perto de casa: lotes do mesmo tamanho, com muro e portão na calçada. Por enquanto estão vazios; as casas chegam nas próximas versões.

### Mudou
- Dá para atravessar a rua em qualquer lugar de novo. Fora da faixa:
  - os carros buzinam e desviam de você pela outra pista, devagar, quando ela está livre;
  - se não está livre, param antes e buzinam;
  - um pet pequeno, o motorista às vezes vê tarde demais.
- A faixa continua sendo o lugar seguro, com o sinal de pedestre.
- A ajuda do F1 no mapa explica isso.
- Os testes técnicos e as salas de som saíram do menu de opções.

### Sons
- Novos: freio, batida, choro de cachorro e de gato, porta do carro e o carro andando.

## 0.10.0: mercado, padaria, trabalhos e pausa, 17/11/2026

### Novo
- Menu de pausa no Esc, dentro do jogo: continuar, salvar, opções, atualização, sair para o menu da conta e sair do jogo.
- Shift + Enter abre a lista dos seus pets: onde cada um está, como está, se está doente e o jeito dele. Setas passam, Esc fecha.
- G ficou mais esperto:
  - com um pet a menos de 5 metros, faz carinho;
  - mais longe, você assobia e chama o pet mais perto;
  - até 15 metros ele vem fácil, se confia em você e estiver com vontade;
  - mais longe é bem mais difícil, e depende do jeito dele;
  - quando chega, ganha carinho.
- Q pega no colo um pet pequeno, e põe no chão de novo. No colo, ele vai junto pelas portas. Na rua e nas lojas, só desce se estiver na coleira.
- O Mercado Aurora tem lado de dentro, com 6 corredores, cada um com o seu som:
  - laticínios, padaria, limpeza, bebidas, hortifrúti e pet;
  - Enter numa prateleira mostra os produtos, e cada produto tem o seu som;
  - Enter ou seta para a direita põe na cesta, seta para a esquerda tira;
  - no caixa, a Bia passa tudo (bip, bip) e você paga de uma vez;
  - tem comida e bebida para você e ração e petiscos de marcas mais baratas.
- Trabalho de repositor no mercado, a qualquer hora, com o Seu Antônio, o gerente:
  - se ele foi ao depósito, deixe o nome no quadro de vagas e comece;
  - parte 1, a memória de pares: uma grade de cartas, cada uma com o som de um produto;
  - formou um par, escolha o corredor certo; o errado tira 5 segundos;
  - 6 etapas, cada uma com mais cartas e mais tempo;
  - T diz o tempo que falta, e o jogo avisa com 1 minuto, 30 e 10 segundos;
  - parte 2, arrumar uma prateleira: pelas etiquetas, juntando os iguais ou pela lista do gerente (um modo por turno);
  - no fim, o gerente diz como foi e paga um salário fixo de 25 moedas e um bônus de 20 a 150.
- A Padaria Estrela tem lado de dentro, com o balcão, o Seu Jorge, a vitrine e os fornos:
  - compre pão francês, bolo e sonho para você, e biscoito para pet;
  - trabalho no balcão: o cliente pede, você acha o produto na vitrine pelo som, escolhe quantos e entrega; rápido dá gorjeta maior;
  - trabalho nos fornos: o jogo do forno da 0.8, agora lá dentro.
- Na Animais & Vida, a Marta:
  - vende rações premium para gato e para cachorro, que os pets gostam mais;
  - dá banho no pet que veio com você (25 moedas): cachorro adora, gato tolera;
  - tem um trabalho novo, o reflexo dos bichinhos: um bichinho aparece pela esquerda ou pela direita, com o som dele, e você aperta a seta do lado certo. Acertos seguidos valem mais.
- Doenças que pedem remédio:
  - o pet maltratado pode pegar resfriado, verminose ou infecção de pele;
  - a Dra. Helena diz qual é a doença, o remédio, quantas doses e de quanto em quanto tempo;
  - o remédio é pago, e você dá no menu do pet, uma dose de cada vez.
- Pessoas pela cidade: a Dona Célia, o Seu Raimundo, a Ana carteira e o Seu José pescador andam pelas calçadas perto de casa, do mercado e da padaria. Enter perto de uma pessoa conversa. Elas têm uma categoria própria no J e K (U e I).
- A Praça das Gaivotas, perto de casa, com grama, caminhos de terra, bancos, uma fonte e um jardim.
- Comida e bebida no inventário (X): Enter come ou bebe.
- O aviso de versão nova, ao abrir o jogo, agora tem três opções: Atualizar agora, Ver mudanças e Pular versão. A versão pulada não avisa mais, mas continua no menu Atualização para instalar quando quiser.

### Mudou
- O radar passou do Q para o A. Se você tinha o radar no Q, ele muda sozinho para o A; as outras teclas que você mudou ficam como estão.
- Esc no jogo não sai mais direto para o menu: abre a pausa.
- O pet que foge age conforme o jeito dele:
  - o curioso, o agitado e o brincalhão exploram as calçadas, devagar;
  - o tímido, o calmo e o carinhoso ficam num lugar só: embaixo de um banco da praça ou no jardim.
- Quando o pet foge, a confiança em você volta a zero.
- Reconquistar pede comida na mão primeiro; o carinho só funciona com calma: chegue e fique parado um pouco do lado dele. Carinho apressado assusta.
- As ruas são movimentadas: só se atravessa na faixa de pedestre. Fora da faixa, o jogo avisa e não deixa entrar no asfalto. Os pets também não andam pelo asfalto.
- O jogo da memória de bipes do caixa saiu: no lugar dele, o trabalho de repositor.
- Ração e petisco de marcas diferentes contam juntos para encher a tigela e dar na mão.

### Corrigido
- A consulta com a Dra. Helena agora diz o que o pet tem, em vez de só curar tudo.
- Enter perto de um pet que está ao lado de um banco ou sofá agora fala com o pet, em vez de sentar.

## 0.9.2: teste da atualização, 17/11/2026

Esta versão existe para testar a 0.9.1 atualizando sozinha.

### Novo
- Esta é a versão de teste da atualização automática. Se você está ouvindo isto depois de atualizar, a atualização funcionou.
- O save passa a guardar a versão do jogo que salvou por último. Os saves da 0.9.1 são convertidos sozinhos para o formato novo, e o original fica guardado em dados/perfis/copias.

## 0.9.1: atualização automática, 17/11/2026

### Novo
- O jogo agora se atualiza sozinho. Ao abrir, ele procura versão nova e, se houver, fala qual é e o que mudou.
- Menu Atualização, no menu inicial: instalar a versão nova, ouvir o que há de novo, procurar agora e voltar para a versão anterior.
- A procura ao abrir pode ser desligada em Opções ou no menu Atualização.
- No Windows e no Linux, o jogo baixa a versão nova, confere o arquivo e troca os arquivos sozinho, sem tocar na pasta dados. Seus saves, contas e opções continuam.
- Antes de trocar, o jogo guarda uma cópia da versão antiga e dos saves. Se a troca falhar, tudo volta como estava.
- No Android, o jogo baixa o APK e abre o instalador do Android.
- Quando o formato do save mudar, o save antigo é convertido sozinho, e o original fica guardado em dados/perfis/copias.

### Mudou
- O APK do Android passa a ter uma assinatura permanente. Por isso, só desta vez, é preciso desinstalar a 0.9.0 antes de instalar a 0.9.1 no celular.
- O número da versão perdeu o nome da etapa: agora é só 0.9.1.

## 0.9.0 (etapa 10): o tempo com o jogo fechado e a fuga, 07/11/2026

### Novo
- O tempo passa com o jogo fechado. Ao abrir, os pets sentiram fome, sede e saudade, e comeram e beberam do que tinha nas tigelas.
- Ao entrar no jogo, a fala conta quanto tempo você ficou fora e o que cada pet comeu e bebeu.
- Depois de 2 dias com a comida ou a água zerada, o pet foge de casa para uma calçada da cidade. Isso vale com o jogo aberto ou fechado.
- A fala avisa da fuga e diz a rua perto de onde ele está. N repete onde ele está.
- O pet fugido fica quieto, fazendo barulho de vez em quando, para você achar pelo som.
- Reconquistar:
  - com medo, ele não deixa pôr a coleira, nem fazer carinho no começo;
  - petisco e ração na mão devolvem bastante confiança;
  - quando ele confia de novo, L põe a coleira e você leva para casa.
- O lugar do pet fugido fica salvo.

### Mudou
- Saves antigos começam a contar o tempo fechado a partir desta versão.

### Corrigido
- Um pet que sai do mapa onde você está não trava mais o som dos pets.

## 0.8.0 (etapa 9): minijogos de moedas e a veterinária, 06/11/2026

### Novo
- O mercado e a padaria mais perto de casa estão abertos, cada um com um jogo que dá moedas. O nome da porta diz que está aberto.
- Mercado, jogo da memória do caixa:
  - a máquina toca uma sequência de bipes, e você repete com as setas;
  - cada rodada põe um bipe a mais;
  - as moedas crescem a cada rodada, até 80.
- Padaria, jogo do forno:
  - um forno apita à esquerda, à frente ou à direita, e você aperta a seta daquele lado;
  - fica cada vez mais rápido;
  - são 20 pães, cada um vale 2 moedas, e três erros acabam o jogo.
- A Dra. Helena, a veterinária, atende no consultório da loja. Traga o pet na coleira; a consulta custa 40 moedas.
- O telefone de casa liga para ela, que vem examinar todos os pets por 70 moedas.
- A consulta deixa a saúde cheia, e ela dá conselhos (fome, sede, tristeza, confiança).
- O pet com a saúde baixa reclama baixinho e avisa para levar à veterinária.

### Mudou
- Enter só senta quando o sofá ou o banco é a coisa mais perto. Perto do telefone, de uma tigela ou de um pet, Enter mexe neles.
- As prateleiras da loja não dizem mais "em breve dá para comprar".

### Corrigido
- O Alt com as setas ainda andava. Agora não faz nada, como você pediu.

## 0.7.0 (etapa 8): carros na cidade e passeio com coleira, 06/11/2026

### Novo
- Carros nas ruas da Cidade Beramar, cada um com o seu som de motor, que anda com ele.
- Semáforos em todos os cruzamentos. Os carros param no vermelho, antes da faixa de pedestre.
- Sinal sonoro de pedestre: virado para uma faixa, você ouve:
  - um tique grave e lento, para esperar;
  - um tique agudo e rápido, para atravessar.
- A fala avisa quando o sinal abre ou fecha.
- Os carros param para você e para o seu pet. Buzinam quando você está fora da faixa, ou na faixa com o sinal aberto para eles.
- Se um carro freia perto demais, você ouve um aviso, e o pet na coleira leva um susto.
- Coleira na tecla L: chegue perto do seu pet, e ele passa a andar logo atrás de você.
  - Ele passa pelas portas junto com você.
  - Na rua e na loja não dá para tirar a coleira; em casa dá.
  - No passeio, ele cheira a calçada, puxa a coleira, late ou mia e fica contente.
  - Passear deixa o pet mais feliz e com mais confiança em você.
  - O jogo salvo no meio do passeio abre com o pet na coleira, do seu lado.

## 0.6.0 (etapa 7): pets vivos, 06/11/2026

### Novo
- Cada pet adotado sente fome, sede, felicidade, confiança e saúde. Tudo muda com o tempo do jogo aberto e fica salvo.
- Os pets vão comer e beber sozinhos nas tigelas quando têm fome ou sede.
- As tigelas começam vazias. Enter perto de uma tigela em casa enche:
  - a de comida gasta uma porção de ração e dá 3 refeições;
  - a de água é de graça.
- J e K dizem se a tigela está vazia, com um pouco ou cheia.
- O pet reclama, miando ou latindo:
  - na tigela vazia;
  - de onde estiver, quando está com muita fome, muita sede ou triste.
- Menu do pet: Enter perto de um pet seu. Tem:
  - fazer carinho;
  - dar um petisco;
  - dar ração na mão;
  - ver como está;
  - as características.
- A tecla N diz como está o seu pet mais perto.
- A felicidade e a confiança sobem quando você fica por perto, e com carinho, petisco e brinquedos.
- O tímido chega desconfiado e só segue você quando confia bastante.
- O relatório anota em que coisa você apertou Enter.

### Mudou
- O andar ficou mais rápido: agora tem a velocidade do antigo correr.
- O carinho com G num pet seu também conta para a felicidade e a confiança dele.

### Tirado
- O correr. A tecla V e o Alt com as setas ficaram livres.

## 0.5.0 (etapa 6): moedas, compras e o kit inicial, 06/11/2026

### Novo
- Moedas. Um jogo novo começa com um valor sorteado entre 150 e 300. A tecla M diz quantas você tem.
- Compras com a Marta, a atendente da Animais & Vida: chegue perto do balcão ou dela e aperte Enter. Ela vende:
  - ração de gato e ração de cachorro (10 porções cada);
  - petiscos (5);
  - bola e mordedor, entregues em casa;
  - par de tigelas, entregue na cozinha.
- Kit inicial na primeira adoção: um pacote de ração da espécie e o brinquedo preferido dela.
- Inventário na tecla X: moedas, ração e petiscos.
- Hora do relógio na tecla T.
- Control + S salva na hora.
- Sons de comprar e de moedas.

### Mudou
- Cada pet adotado ganha o seu par de tigelas, e o nome diz de quem é ("tigela de comida da Mel").
- O teste de áudio da sala de testes passou de T para Control + T.

## 0.4.1 (etapa 5): correções depois do teste da Nicole, 06/11/2026

### Novo
- Sons de fundo, que entram e saem devagar:
  - a casa por dentro;
  - os passarinhos no quintal (e bem baixinho dentro de casa);
  - a loja;
  - a cidade na rua;
  - o mar, mais forte perto da praia.
- A Luna e o Thor ficam na loja para adoção. O nome deles já vem escrito, e dá para trocar.
- O jeito de cada pet muda a vida dele:
  - o carinhoso vem até você e segue você;
  - o tímido quase não chega perto;
  - o brincalhão brinca mais;
  - o calmo espera mais e anda devagar;
  - o curioso passeia longe e cheira tudo;
  - o agitado não para.
- Relatório automático: cada vez que o jogo abre, ele cria `dados/relatorios/relatorio-DATA_HORA.txt`, com tudo até a saída e o resumo no fim. Ficam guardados os 30 últimos.

### Mudou
- A sua casa no jogo é a casa da 0.3.2 (sala com tapete, cozinha e quintal), com a porta da rua na parede sul da sala.
- O radar só toca quando algo muda ao redor, e não a cada passo.
- O bipe-farol (B) ficou bem mais baixo.
- Os passos dos pets ficaram mais altos, para ouvir onde eles andam pela casa.

### Corrigido
- O personagem virava sozinho ao passar por uma porta. Agora ele continua virado para o mesmo lado.
- Apertar outra tecla (J, Z, Tab, Shift) enquanto segurava a seta parava o andar.
- As vozes do SAPI falavam ao abrir o jogo. Agora o teste das vozes é feito em silêncio.

## 0.4.0 (etapa 5): a loja, a adoção, a casa e a Cidade Beramar, 06/11/2026

### Novo
- No menu do jogo, "Começar" (depois "Continuar"). O jogo abre com uma introdução e começa dentro da Animais & Vida.
- A loja tem balcão, a atendente Marta, a área dos gatos, a dos cachorros e o consultório.
- 3 gatos e 3 cachorros sorteados para cada conta, com sexo, raça, cor, porte, idade, jeito e voz.
- Adoção com nome: Enter perto do animal descreve como ele é, e "Adotar" pede o nome. Dá para adotar até 6.
- A Cidade Beramar, gerada sempre igual, com 1000 por 1000 metros:
  - o mar e a praia no sul;
  - ruas e avenidas com nome, calçadas e faixas de pedestre;
  - 9 bairros e prédios com porta.
- Portas entre mapas: para passar, ande contra a porta. Os prédios fechados avisam que estão fechados.
- Z diz todas as zonas onde você está (rua e bairro).
- As portas viraram uma categoria no U e I.
- O jogo salva sozinho o lugar e os pets.
- Saída de som em Opções: fones (estéreo) ou alto-falante (mono). No mono, os sons dos lados mudam de tom.

## 0.3.2 (etapa 4): radar ativo e pets mais calmos, 06/11/2026

### Novo
- Radar ativo, como no A Hero's Call: em silêncio quando você está parada, e tocando a cada passo o que está à frente e as aberturas dos lados.
- A bola rola pelo mapa, e o Thor vai buscar.
- O mordedor da Luna, que ela morde e leva para outro canto.
- Refeições em tempo real: a cada 2 a 3 horas, cada pet come e bebe nas suas tigelas.

### Mudou
- Os pets andam mais devagar e esperam mais entre uma brincadeira e outra.

## 0.3.1 (etapa 4): pular, sentar, pets vivos e radar, 06/11/2026

### Novo
- Espaço pula, e a queda soa diferente em cada chão.
- Enter perto do sofá ou do banco senta; andar ou Enter de novo levanta.
- A Luna e o Thor andam sozinhos: passeiam, sobem no sofá, brincam com a bola, comem, bebem e vêm até você.
- Carinho com G (a gata ronrona).
- Radar sonoro com os sons do A Hero's Call (parede, porta, objeto, pet e espaço livre).
- As vozes do RHVoice Plus e outras que o System.Speech recusa são abertas pelo SAPI direto. Quando não abrem, o relatório diz por quê.

## 0.3.0 (etapa 4): movimento e orientação numa casa de teste

### Novo
- Casa de teste com sala, cozinha e quintal, a gata Luna e o cachorro Thor.
- Passos com o som de cada chão (madeira, tapete, azulejo, grama, terra).
- Esbarrar nos móveis e nos pets, ouvindo o nome do que esbarrou.
- Teclas:
  - J e K passam pelas coisas;
  - U e I trocam a categoria;
  - Tab diz a distância e a direção;
  - Home vira você para a coisa escolhida;
  - B liga o bipe-farol;
  - Z diz a zona, e Shift + Z descreve o lugar;
  - F diz a direção, e C a posição.
- Correr com V ou com Alt e as setas.

## 0.2.0 (etapa 3): menu inicial, contas, opções, idiomas e teclas

### Novo
- Menu inicial com criar conta, jogar com conta, opções, sobre e sair.
- Contas locais: criar, mudar o nome e apagar (o apagar pergunta antes).
- Opções:
  - idioma (português e inglês);
  - voz do jogo, velocidade e volume;
  - leitor de tela;
  - gráficos;
  - teclas.
- Teclas mudáveis: quando a nova tecla já é de outra ação, as duas trocam. Também dá para voltar todas ao padrão.
- O jogo é portátil: contas, opções, teclas, registro e relatórios ficam na pasta `dados`, dentro da pasta do jogo.

### Corrigido
- As vozes SAPI 5 que não abrem (como as "Online") ficam fora da lista, e um erro de voz é anotado uma vez só.
- O som do Steam Audio gasta menos processador.

## 0.1.1 (etapa 1): ajustes do teste técnico no Windows

### Novo
- Vozes SAPI 5 clássicas do Windows. A voz, a velocidade, o caminho da fala e o volume ficam guardados.
- Correr nas salas de teste.

### Corrigido
- O som falhava quando o jogo dava uma pausa. Agora a mistura do Steam Audio roda separada.
- O miado tinha ruído de fundo e foi trocado.

## 0.1.0 (etapa 1): teste técnico

### Novo
- Teste da base técnica:
  - som 3D com Steam Audio;
  - fala pelo NVDA, SAPI, Speech Dispatcher e TTS do Android;
  - tela desligada.
- Testado em Windows, Linux e Android.
