# Pet Worlds: versões para baixar

Pet Worlds é um audiogame de cuidar de gatos e cachorros na Cidade Beramar, feito para ser jogado de ouvido, com leitor de tela (NVDA) ou com a voz do próprio jogo. Roda no Windows, no Linux e no Android.

Este repositório só tem as versões prontas, sem o código.

## Baixar a versão mais recente

**[Pet Worlds, versão mais recente](https://github.com/nic-kalenna/pet-worlds-versoes/releases/latest)**

Na página, em "Assets", escolha o arquivo do seu aparelho:

| Aparelho | Arquivo |
|---|---|
| Windows | `PetWorlds-<versão>-windows.zip` |
| Linux | `PetWorlds-<versão>-linux.zip` |
| Android | `PetWorlds-<versão>-android.apk` |

A partir da 0.9.1, o jogo se atualiza sozinho: ao abrir, ele avisa quando há versão nova e instala pelo menu **Atualização**. Seus saves continuam.

## Instalar

- **Windows**: descompacte o zip numa pasta sua (não em "Arquivos de Programas") e abra `PetWorlds.exe`. Se aparecer "O Windows protegeu o computador", escolha "Mais informações" e "Executar assim mesmo". A janela abre preta: tudo é falado.
- **Linux**: descompacte e abra `PetWorlds/PetWorlds.x86_64`.
- **Android**: abra o `.apk` e permita instalar apps desta fonte, se o Android pedir. Quem tinha a 0.9.0 ou anterior no celular precisa desinstalar antes de instalar a 0.9.1 ou mais nova, uma vez só.

O jogo é portátil: contas, saves e opções ficam na pasta `dados`, dentro da pasta do jogo. No Android, ficam na pasta do app.

## Versões antigas (beta)

Todas as versões, da 0.1.1 em diante, estão em [Releases](https://github.com/nic-kalenna/pet-worlds-versoes/releases), da mais nova para a mais antiga. As anteriores à 0.9.1 são betas de teste e não se atualizam sozinhas. O que mudou em cada uma está no [CHANGELOG](CHANGELOG.md).

## Para o jogo

O arquivo `atualizacoes.json` é a lista que o jogo lê para saber se há versão nova. Não precisa mexer nele.
