> Versão beta antiga, guardada para quem quiser conhecer a história do jogo. Ela não se atualiza sozinha. A versão mais nova está em [Releases, mais recente](https://github.com/nic-kalenna/pet-worlds-versoes/releases/latest).

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

### Arquivos
- Windows: o `.zip` com `windows` no nome. Descompacte e abra `PetWorlds.exe`.
- Linux: o `.zip` com `linux` no nome. Descompacte e abra `PetWorlds/PetWorlds.x86_64`.
- Android: o `.apk`.
- `sha256.txt`: para conferir os arquivos.
