|[Main Page](./REDME.md)|
|[Trial 1 Acess](./Trilha1.md)|
|[Trial 2 Acess](./Trilha2.md)|
# 📘Endereçamento de IP, Sub-redes e Portas
## 📍IPv4
-   Composto por **quatro octetos decimais** (ex.: 192.168.1.1).
-   **Endereço de Rede:** define a qual rede o dispositivo pertence.
-   **Endereço de Host:** identifica o dispositivo dentro da rede.
-   **Máscara de Sub-rede:** separa **rede** e **host** por meio de 1s e 0s.
-   **Endereço de Broadcast:** último endereço da rede, usado para comunicação geral.

## 📍IPv6
-   Criado para solucionar a **escassez de endereços IPv4**.
-   Utiliza **128 bits**, permitindo espaço “virtualmente infinito”.
-   Representado em **hexadecimal**, separado por dois-pontos.
-   **Endereçamento ampliado**.
-   **Segurança aprimorada** com IPsec.
-   Melhor suporte a **QoS**.
-   Maior **eficiência e desempenho**.


## 🎭Máscaras de Sub-rede e Segmentação
**Máscara de Sub-rede**
-   Define quais bits representam a **rede** (1) e o **host** (0).
-   Fundamental para identificar se dispositivos estão na mesma sub-rede.

** ⛓️‍💥Segmentação de Rede**
-   Divide uma rede maior em **sub-redes menores**.

# **🤓Ferramentas de Análise de Redes**
 **Ping**
-   Verifica **conectividade**.
-   Mede **latência** ida e volta.

**Traceroute**
-   Exibe o **caminho** percorrido pelos pacotes.
-   Ajuda a identificar **falhas de roteamento** e **perda de pacotes**.

## 🚪Portas e Firewall
**Portas**
-   **Portas bem conhecidas:** 0–1023.
-   **Portas registradas:** 1024–49151.
-   **Portas dinâmicas/privadas:** 49152–65535.

**Firewall** 
-   **Filtragem de pacotes**.
-   **NAT** para compartilhamento de IP público.
-   **Proxy** como intermediário seguro.

    
## 🔒Bloqueio de Portas por ISPs
-   Portas podem ser bloqueadas por motivos de **segurança** e **controle de tráfego**.
-  Pode afetar serviços dependentes dessas portas.
