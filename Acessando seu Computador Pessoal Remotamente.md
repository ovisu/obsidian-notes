---
cssclasses:
  - hr
---


### 1. Acessando e Ligando seu Computador com AnyDesk

Se você utiliza **AnyDesk** e seu computador está conectado por cabo, você pode acessar e até mesmo ligar seu PC remotamente usando seu celular.

**O que você precisa:**

* **AnyDesk** instalado tanto no seu PC quanto no seu celular.
* Seu PC conectado à internet via **cabo Ethernet**.
* A função **Wake-on-LAN (WoL)** configurada corretamente no seu PC.

**Passo a passo:**

1.  **Configure o Wake-on-LAN (WoL) no seu PC:**
    * **Na BIOS/UEFI:** Reinicie seu computador e entre na BIOS/UEFI (geralmente pressionando a tecla `Del`, `F2` ou `F10` durante a inicialização). Encontre a seção de energia ou gerenciamento de energia e ative a opção **"Wake-on-LAN"**. Salve e saia.
    * **No Windows:** Vá ao **Gerenciador de Dispositivos**, encontre sua placa de rede, clique com o botão direito, vá em **Propriedades** e na aba **Gerenciamento de Energia**, marque a caixa **"Permitir que este dispositivo acorde o computador"**.
2.  **Configure o AnyDesk:**
    * No AnyDesk do seu computador, vá em **Configurações > Despertar por LAN** e ative a opção. Anote o endereço do seu computador na rede.
3.  **Acesse pelo Celular:**
    * Abra o aplicativo **AnyDesk** no seu celular.
    * Na lista de endereços recentes, encontre o seu PC. Ele aparecerá como "offline".
    * Toque no endereço para tentar se conectar. O aplicativo irá detectar que o PC está offline e oferecerá a opção de **"Ligar"** ou **"Despertar"**.
    * O AnyDesk enviará o "pacote mágico" para a sua rede, fazendo com que o computador ligue.
4.  **Operação Remota:**
    * Assim que o PC ligar e o AnyDesk iniciar, a conexão será estabelecida e você terá controle total sobre seu computador através do celular.

---

### 2. Métodos Alternativos de Acesso Remoto

Embora o AnyDesk seja uma ótima opção, existem outras formas de acessar seu computador remotamente.

* **Chrome Remote Desktop:** Uma opção gratuita e simples do Google. Basta instalar a extensão no Chrome e seguir as instruções para configurar o acesso. É ideal para quem já utiliza o ecossistema do Google.
* **TeamViewer:** Um software completo com recursos avançados de segurança e transferência de arquivos, muito utilizado em ambientes profissionais.
* **Conexão de Área de Trabalho Remota (RDP):** Solução nativa do Windows. É mais segura se utilizada em uma rede local ou combinada com uma VPN, mas pode ser complexa para configurar o acesso pela internet.