# **Protocolo anti-formatação para Linux**



![](https://zdnet1.cbsistatic.com/hub/i/r/2019/11/25/6595d828-e97b-486e-94b5-38aa1ac49fbc/resize/1200xauto/43509da90ee6c8baae390264d9f6e195/2019-11-25-at-4-03-50-pm.jpg)



**Sou usuário de Linux exclusivo, por uns quinze anos ou mais. A minha distribuição favorita é a Linux Mint. Depois de muitas mancadas e muitos sufocos, criei alguns protocolos de sobrevivência que são verdadeiras "mão na roda" e compartilho um deles aqui com vocês. No caso deste em específico, é mais ou menos como a famosa declaração de casamento: "Tenha o seu Linux sempre com você, até que a morte os separe!"**

Então, siga os passos:

- Tenha sempre à mão uma Live USB persistente com o Boot Repair instalado. Levando em conta a minha experiência pessoal, considero que a melhor ferramenta para gravar Live USB persistente é o MKUSB. Confira esse [tutorial para saber como usá-lo](https://www.youtube.com/watch?v=GlFK2-kfFeg).
- Sempre tenha uma instalação secundária de Linux em dual boot, onde a partir dela, seja possível acessar a pasta Home da instalação principal, já que pode ocorrer do Live USB não estar por perto quando mais precisar dele.
- Depois de muito apanhar, deixei de fazer instalação com a Home criptografada, justamente para poder facilitar o acesso aos arquivos a partir da Live USB ou da instalação secundária. Mas, se sua Home está criptografada, somente [seguindo este tutoria](https://www.howtogeek.com/116179/how-to-disable-home-folder-encryption-after-installing-ubuntu/)l é que consegui remover a criptografia.
- Faça uso e abuso constante do TimeShift, um recuperador de pontos de restauração do sistema que pode ser executado até pelo terminal na inicialização em modo de recuperação.
- Instale mais de uma interface gráfica no seu Linux principal, porque pode acontecer de sua interface favorita dar "crash" na inicialização, aí nesse caso, pode-se acionar uma outra para poder corrigir a situação da que deu problema.
- Mantenha sempre uma sincronização com a nuvem para os arquivos pessoais mais sensíveis.
- Regularmente use o BleachBit e o Stacer para fazer limpeza do sistema
- Mantenha sempre o Grub organizado, porque já ocorreu comigo, a bizarrice de precisar acessar o modo de segurança e essa opção não estar listada no Grub, porque eu mesmo tinha "bagunçado" antes com o Grub Customizer
- Faça um esforço de investimento para ter um HD externo de mesmo tamanho do seu interno e de tempos em tempos (uma ou duas vezes por mês), fazer clonagem do HD. Lembrando sempre que HD's podem pifar e notebooks podem ser perdidos ou roubados. Eu mesmo já tive notebook roubado à mão armada.
