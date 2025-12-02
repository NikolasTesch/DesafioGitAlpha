#  👾`Desafio #1 - Introdução ao Git e Markdown`
<div align="center">
<img src= "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqZXkQhssgoRiImJED-PkKGsoSgSYgQaoGbQ&s" alt="Logo do Alpha" width="500" height="300">
</div>

# 📗Trilha 1.  Introdução às Redes e à Internet
  
# 📘Conceitos fundamentais de redes de computadores
## 🌐Introdução às Redes de Computadores
 **Importância das Redes**
- Eficiência
- Conveniência
- Escalabilidade
- Redundância
- Uma rede é um **sistema de comunicação** que permite troca de dados entre dispositivos. 

 **Topologias de Rede**
- Representam o “**mapa**” da rede, indicando como dispositivos estão interligados.

 **Principais Topologias**
- **⭐ Estrela**
- **📏 Barramento**
- **🔄 Anel**
- **🕸️ Malha**

## 🗣️Comunicação em Rede
 **Princípios Fundamentais**
-   **Emissor e Receptor** -**Dados** - **Meio de Comunicação**- **Protocolos:** 
 
## 🪜Escalabilidade em Redes
 **Princípios de Escalabilidade**
-   **Arquitetura adequada:** topologia, equipamentos e protocolos corretos.
-   **Redundância:** caminhos alternativos para evitar interrupções.
-   **Balanceamento de carga:** distribuição equilibrada do tráfego.
-   **Virtualização:** criação de redes virtuais otimizadas.

## 📚História e Evolução da Internet
-   Criada nos anos 1960 pelo Departamento de Defesa dos EUA.
-   Na década de 1980, o **TCP/IP** torna-se padrão.
-   Internet Comercial (Anos 1990)
-   Popularização da **World Wide Web (WWW)**.
-   Surgimento de ISPs, comércio eletrônico e acesso massivo.

##  📤Web 2.0
-   Páginas dinâmicas e colaborativas.
-   Uso de **AJAX**, design mais leve e intuitivo.
-   Fortalecimento da navegação móvel

##  📤Web 3.0
-   Também chamada de **Web Semântica**.
-   Busca fazer a web “**entender**” o significado dos dados.
-   Uso de **metadados**, **ontologias** e padrões semânticos.
-   **Inteligência Artificial (IA)**.
-   **Blockchain**.
-   **IoT – Internet das Coisas**.

# 📘 Introdução aos Protocolos de Comunicação
##  Importância dos Protocolos
-   Possibilitam que diferentes sistemas **comuniquem-se independentemente** de suas tecnologias.
-   Evitam colisões, perda de dados e falhas de comunicação.
-   Fornecem **padronização global**, permitindo interoperabilidade entre redes e serviços.

##  📄Protocolos de Transporte
**Gerenciam a comunicação ponto a ponto entre dispositivos finais.**
- **TCP – Transmission Control Protocol**
- **UDP – User Datagram Protocol**

## 📄RFC – Request for Comments
-   **Padronização:** garante compatibilidade global.
-   **Inovação:** registra novas tecnologias e evoluções.
-   **Solução de problemas:** explica abordagens técnicas a desafios da Internet.

##  🗣️Estrutura de um Protocolo de Comunicação
 **Cabeçalhos:** Contêm informações essenciais para o processamento:
  **Mensagens:** Parte principal da comunicação.  Contêm os dados transmitidos entre dispositivos.
 **Campos de Dados:** Estruturas definidas dentro das mensagens.

##  🛣️Garantia de Transmissão Correta
Protocolos empregam mecanismos para assegurar **integridade e confiabilidade**:
-   **Verificação de integridade:** detecta corrupção de dados.
-   **Sequenciamento:** garante ordem correta de entrega (TCP).
-   **Confirmação e retransmissão:** reenviam pacotes perdidos.
-   **Gerenciamento de erros:** corrige ou solicita novo envio.

##  🔗Protocolos de Segurança – SSL/TLS
 **Função do SSL/TLS**
-   Proporciona **criptografia** entre cliente e servidor.
-   Protege dados contra interceptações.
-   Identifica e autentica servidores legítimos.
   
##  🔒LGPD – Lei Geral de Proteção de Dados
-   Regula a **coleta, uso, tratamento e armazenamento** de dados pessoais no Brasil.    
-   Inspirada no **GDPR** europeu.
-   Em vigor desde 2021.


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


# 📘Serviços e Aplicações na Internet
## 🕸️Introdução aos Serviços Web
-   Os **serviços web** são fundamentais na economia digital moderna.
-   Permitem **integração de sistemas**, troca de dados e criação de soluções conectadas.

## APIs e Integração de Sistemas
Conjuntos de **regras e protocolos** que possibilitam comunicação entre sistemas.
 Funcionam como **intermediárias** para troca de dados e funcionalidades.
    
## Web Services e Protocolos (SOAP e REST)
 **SOAP (Simple Object Access Protocol)**
-   Baseado em **XML**, com estrutura rígida.
-   Adequado para **ambientes corporativos** e aplicações críticas.

**REST (Representational State Transfer)**
-   Arquitetura mais **leve e flexível**.
-   Usa métodos HTTP: **GET, POST, PUT, DELETE**.
-   Amplamente utilizado em **APIs modernas**, mídias sociais e IoT.

## 🤏 Arquitetura de Microsserviços
Divide a aplicação em **serviços independentes**, cada um com função específica.
**Principais características**
-   **Desacoplamento** total entre serviços.
-   **Independência tecnológica** (linguagens distintas).
-   **Escalabilidade** por serviço, não do sistema inteiro.
-   **Manutenção simplificada** e implantação contínua.
-   **Resiliência**: falhas isoladas não derrubam todo o sistema.
   
# 📘DNS (Domain Name System)
## 🛜Conceitos Básicos de DNS
-   Sistema distribuído que funciona como um _diretório_ de nomes da internet.
-   Converte **nomes de domínio** em **endereços IP**.
-   Facilita a navegação, permitindo o uso de nomes memoráveis em vez de números.
-   O DNS é responsável por localizar o IP de um domínio digitado no navegador.
    
## 🛜Servidores DNS
 **Servidores de Resolução (Recursivos)**
-   Recebem as consultas dos clientes.
-   Procuram respostas em cache ou consultam outros servidores.

 **Servidores Autoritativos**
-   Possuem registros oficiais de um domínio.
-   Respondem com informações definitivas sobre IPs e serviços.
    
 **Servidores Raiz**
-   Nível mais alto de resolução.
-   Direcionam consultas para os servidores dos TLDs.

## 📶Consultas e Respostas DNS
-   O navegador envia uma consulta ao servidor recursivo.
-   A consulta contém nome solicitado, tipo de registro e outros dados.
-   Servidor recursivo busca respostas nos servidores autoritativos.

##  📤Tipos de Registros DNS
- **Registro A:** Mapeia nome de domínio → **endereço IPv4**.
- **Registro AAAA:** Mapeia nome de domínio → **endereço IPv6**.
- **Registro MX:** Define servidores responsáveis por receber e-mails de um domínio.
- **Registro CNAME:** Cria _alias_ apontando para um nome canônico.
- **Registro TXT:** Armazena informações de texto, como: **SPF**; **DKIM**; **DMARC**
- **Registro NS:** Especifica os servidores de nomes autoritativos do domínio.
- **Registro SOA:** Contém informações essenciais da zona, como número serial e políticas de atualização.
- **Registro SRV:** Indica servidores que fornecem serviços específicos (VoIP, mensagens etc.).
- **Registros ALIAS:** Usados para apontar nomes para recursos em nuvem ou CDNs.

## ⛓️‍💥Zoneamento e Zonas DNS
 **Tipos de Zonas**
-   **Diretas (Forward Lookup)**: nome → IP.
-   **Reversas (Reverse Lookup)**: IP → nome.
    
# 📘Arquitetura da Internet
## 🕸️Arquitetura da Internet
 **Características Gerais**
-   A Internet é uma **rede de redes**, composta por milhões de dispositivos interconectados.
-   ISPs, backbones e IXPs cooperam para manter a conectividade global.
    
## 🏠Backbones da Internet
 **Função dos Backbones**
-   Representam a **espinha dorsal da Internet**.
-   Compostos por **cabos de fibra óptica**, **roteadores de alto desempenho** e infraestrutura robusta.
-   Transportam grandes volumes de tráfego entre regiões.

## 💣Problemas e Soluções em Backbones
 **Principais Problemas**
-   **Congestionamento:** excesso de tráfego reduz desempenho.
-   **Falhas de hardware:** problemas em roteadores ou cabos afetam a conectividade.
-   **Ataques cibernéticos:** DDoS, invasões e malware.
-   **Monitoramento insuficiente:** dificulta resposta rápida a falhas.
 
 **Soluções Comuns**
-   Aumento de capacidade e infraestrutura.
-   Redundância de equipamentos e rotas.
-   Sistemas avançados de segurança.

## 📔Pontos de Troca de Tráfego (IXPs)
 **Função dos IXPs**
-   Locais onde redes diferentes trocam tráfego diretamente.
-   Reduzem **latência** e melhoram a **eficiência** do roteamento.
    
## 🔒Desafios de Segurança na Internet
 **Principais Ameaças**
-   **Malware** (vírus, worms, trojans, spyware, adware).
-   **Ransomware:** criptografa dados e exige resgate.
-   **Phishing:** tentativa de roubo de informações por engano.
-   **DDoS:** sobrecarrega servidores e serviços.
-   **BGP Hijacking:** redirecionamento malicioso de rotas.
-   **Vulnerabilidades em IoT.**
-  **Engenharia social:** Ataques baseados na manipulação humana.
    
# 📘Redes de Computadores
## Introdução às Redes de Computadores
-   As redes são classificadas pela **abrangência geográfica** e pelas **aplicações**.

## 🏙️Classificação das Redes por Abrangência Geográfica**
**LAN – Local Area Network**
-   Rede de **pequena escala**: casas, escritórios, campi.
	
**WAN – Wide Area Network**
-   Rede de **larga escala**, conectando LANs em diferentes cidades, países ou continentes.
	
 **MAN – Metropolitan Area Network**
-   Abrange **cidades ou regiões metropolitanas**.
	
**PAN – Personal Area Network**
-   Rede de **curto alcance**, alguns metros.

## ⚡Dispositivos de Rede
 **Principais Equipamentos**
-**Switches**
-**Roteadores**
-**Hubs**
-**Access Points (APs)**
 -**Firewalls**
-**Servidores**

## 🏠Arquiteturas de LAN

**Ethernet**
-   A mais utilizada no mundo.
-   Topologias: **barramento** ou **estrela**.
-   Métodos de acesso: **CSMA/CD** (tradicional) e **CSMA/CA** (modernas).
-   Velocidades: **10 Mbps** até **100 Gbps**.

**Token Ring** ~~abençoai vosso token ring~~
-   Topologia em **anel**.
-   Acesso controlado por **token**.
-   Sem colisões, mas sujeito a atrasos.

## 🛜Tecnologias de Interconexão em WAN
	
-   **Linhas Alugadas** – circuitos dedicados (ex.: T1, T3).
-   **VPN** – tunelamento seguro via Internet.
-   **MPLS** – caminhos virtuais escaláveis.
-   **Redes Privadas Dedicadas** – máxima segurança e controle.

## 🛜Wi-Fi 
**Segurança Wi-Fi**
-   **WPA / WPA2 / WPA3** – protocolos de segurança.
-   **Criptografia AES**, autenticação forte e atualizações constantes.
    

## 📱Redes Celulares
 **Rede 3G**
-   Aumento na velocidade e suporte a videochamadas e Internet móvel.   
	
 **Rede 4G (LTE)**
-   Baseada em **comutação por pacotes**.
-   Suporta streaming em HD, jogos online e alta velocidade.
	
**Rede 5G**
-   **Velocidades ultrarrápidas**.
-  	 **Baixa latência** para aplicações críticas.
-   **Alta capacidade** para dispositivos IoT.
-   **Network slicing** para diferentes perfis de uso.
    
# 📘Segurança de Redes
A segurança em redes é essencial diante das ameaças digitais crescentes. Seu objetivo é garantir **integridade, confidencialidade e disponibilidade** das informações.
    
## 💣Principais Ameaças à Segurança de Redes
 - **Malware**
 - **Ataques de Phishing**
 - **Ataques DoS (Negação de Serviço)**
 - **Engenharia Social**
 - **Vulnerabilidades de Software**
 - **Interceptação de Dados**
- **Roubo de Identidade**
 - **Backdoors e Exploits**
- **Injeção de Código**
- **Ameaças Internas (Insider Threats)**

## 🔥Firewalls – Medidas de Segurança Essenciais
- **Firewall de Pacotes (Stateless)**
-  **Firewall de Estado (Stateful)**
- **Firewall de Aplicação (Proxy)**
- **Firewalls de Próxima Geração (NGFW)**

## 🛜Redes Privadas Virtuais (VPNs)
-   **Acesso Remoto**: acesso de usuários externos.
-   **Site-to-Site**: conecta redes corporativas.
-   **L2VPN e L3VPN**: camadas 2 e 3 da rede.
    
 **Formas de Implementação**
-   **Software VPN**: ideal para usuários e pequenas empresas.
-   **Hardware VPN**: usada em larga escala.
-   **Serviços de VPN na nuvem**: escaláveis e flexíveis.
    
# 📘Segurança na Web
## 🗣️Mecanismos de Comunicação Segura
**Criptografia**
-   Uso de protocolos **SSL/TLS** para cifrar informações.
-   Mesmo que os dados sejam interceptados, permanecem **ilegíveis**.
    
**Certificados Digitais**
-   Emitidos por **Autoridades Certificadoras (CAs)** confiáveis.
-   Validam a identidade do servidor.
-   Indicam que o site é **autêntico e seguro**.
    
**Garantias do HTTPS**
-   **Integridade:** uso de MACs para detectar alterações.
-   **Confidencialidade:** protege logins, dados pessoais e financeiros.
-   **Proteção contra MitM:** dificulta interceptação e modificação dos dados.
    
## 🔓SSL/TLS
 **Handshake SSL/TLS**
-   **Início da comunicação:** cliente solicita conexão segura.
-   **Servidor envia certificado.**
-   **Cliente valida o certificado.**
-   **Acordo de chave de sessão.**
-   **Criptografia da sessão:** comunicação segura estabelecida.
    

## 📔 Autoridades Certificadoras (CAs)
 **Processo de Emissão**
-   Escolha da CA (ex.: _Let’s Encrypt_, _DigiCert_).
-   Solicitação e geração das chaves.
-   Verificação de identidade do proprietário do domínio.
-   Emissão do certificado assinado.
	
 **Consequências da Expiração**
-   Interrupção de serviços.
-   Riscos de segurança.
-   Perda de confiança do usuário.
-   Danos à reputação da organização.
    

## 📔 Criptografia Simétrica vs. Assimétrica
**Simétrica**
-   Usa **uma única chave**.
-   Muito eficiente.
-   Problema: **distribuição segura da chave**.

**Assimétrica**
-   Usa **par de chaves** (pública + privada).
-   Resolve o problema da distribuição de chaves. -   Mais lenta e usada em pequenas porções (ex.: troca de chaves).

## 📔 Criptografia de Ponta a Ponta (E2EE)
**Características**
-   Apenas remetente e destinatário conseguem decifrar os dados.
-   Mesmo o provedor do serviço não tem acesso.
    
**Limitações**
-   Gestão segura de chaves.
-   Alto custo computacional.
-   Dificuldades de recuperação em caso de perda da chave.
-   Pode impactar a experiência do usuário.
    

## 📔Certificação
**DV – Domain Validation**
-   Valida apenas o domínio.
-   Processo simples e automatizado.
-   Confiança básica.

**OV – Organization Validation**
-   Valida domínio e organização.
-   Fornece nível intermediário de confiança.
    
**EV – Extended Validation**
-  Validação rigorosa da empresa.
-   Exibe nome da organização na barra de endereço.
-   Maior credibilidade.

# 📘 Tendências e Desafios nas Redes Modernas
# 🖥️Internet das Coisas (IoT)
Conecta **objetos físicos** à internet para coleta e troca de dados. Utiliza sensores, software e tecnologias de rede.
  
**Exemplos de Dispositivos**
-   Termostatos inteligentes
-   Dispositivos vestíveis
-   Sensores agrícolas
-   Veículos conectados
-   Sistemas urbanos inteligentes
    
**Protocolos Comuns**
-   **MQTT** – leve e eficiente
-   **CoAP** – para dispositivos restritos
-   **HTTP/HTTPS** – integração com sistemas web
-   **LoRaWAN** – comunicação de longo alcance

## 🤖Machine Learning e Inteligência Artificial
Sistemas capazes de **aprender com dados**.
    
**Tipos de Aprendizado**
-   **Supervisionado**
-   **Não supervisionado**
-   **Por reforço**
    
 **Aplicações**
-   Reconhecimento de padrões
-   Tomada de decisões automatizada
-   **Processamento de Linguagem Natural**
-   **Detecção de anomalias** e ameaças
    
## 🔒Autenticação Multifatorial e Biometria
-   **MFA**: múltiplas etapas de verificação (senhas, tokens, códigos).
-   **Biometria**: características únicas (digital, rosto, íris).
-   **Biometria comportamental**: padrões de digitação e interação.
    
## 🕴️Ataques Cibernéticos Sofisticados
**Principais Ameaças**
-   **Engenharia social avançada**
-   **Malware avançado** e **APTs**
-   **Ransomware** com extorsão
-   **Vulnerabilidades zero-day**
-   **Infraestruturas C2 robustas**
    
## 📶CDNs e Segurança nas Redes
**Benefícios das CDNs**
-   **Distribuição global** de conteúdo
-   **Mitigação de ataques DDoS**
-   **Web Application Firewall (WAF)**
-   **SSL/TLS termination**
-   Redução de exposição dos servidores de origem
-   Atualizações rápidas
-   Proteção contra força bruta
    
## ☁️Abordagens “On-Premise” e “Nuvem”
**On-Premise**
-   **Controle direto** da infraestrutura
-   Maior controle por **conformidade**
-   Melhor para baixa latência
-   Custo elevado e manutenção contínua
-   Menor escalabilidade
-   Necessidade de estratégias de **disaster recovery**

**Em Nuvem**
-   Alta **escalabilidade**
-   Acesso remoto e flexível
-   **Atualizações automáticas**
-   Menor custo de hardware
-   Resiliência e redundância
-   Acesso facilitado a tecnologias avançadas (IA, ML)
-   Segurança gerenciada por especialistas
    

#  🔗Trilha 2. Controle de Versão
# 👾Controle de Versão com Git
## 🗂️ Conceitos Fundamentais
**O que é Git?**
-   É um **Sistema de Controle de Versão distribuído**.
-   Projetado para projetos de **qualquer tamanho**, com **alta performance**.
-   Mantém o **histórico completo** de todas as revisões.
    
**Repositório**
-   Pasta que contém o projeto e **todos os registros de histórico**.
-   Pode ser local ou sincronizado com serviços remotos (ex.: GitHub).
    
**Commit**
-   “Ponto de salvamento” do projeto.
-   Registra o estado de todos os arquivos **no momento do commit**.
-   Mantém um **histórico permanente**, permitindo retorno a versões anteriores.

##  Configuração Inicial do Git

 **🗒️Nome e Email**
`git config --global user.name "Seu Nome" ` 
`git config --global user.email "email@exemplo.com"` 

**📝Editor de texto**
-   Linux/macOS/WSL: `nano`
-   Windows: `notepad`
   
**⚙️Tipos de configuração**
-   **Global**: vale para todos os projetos.
-   **Local**: vale somente no repositório atual.
    
	
## 🔄Fluxo de Trabalho Básico com Git

 **⚙️Criação do projeto**
-   Criar pasta: `mkdir nome`
-   Acessar pasta: `cd nome`
    
**Iniciar repositório**
-   `git init` cria a pasta **.git**
-   Essa pasta **não deve ser modificada**.

 **Working Tree x Index (Staging Area)**
-   **Working Tree**: arquivos reais do projeto.
-   **Index**: área onde ficam as mudanças preparadas para commit.

**Comandos essenciais**
-   **Visualizar status**: `git status`
-   **Adicionar ao Index**: `git add arquivo`
-   **Criar commit**: `git commit -m "mensagem"`
	
 **Estados de um arquivo**
-   **Untracked**: novo, não rastreado.
-   **Changes not staged**: modificado, mas não adicionado ao Index.
-   **Changes to be committed**: pronto para commit.
-   **Unmodified**: sem mudanças. 

**Git log**
-   Mostra histórico: `git log`
-   Versão compacta: `git log --oneline`
   
# 👾Branches e merge
**O que é uma _branch_**
-   Uma branch é um **marcador apontando para um commit específico**.
-   Diferente de tags, as branches **avançam** conforme novos commits são feitos.
    
## 🪢Criando e Manipulando Branches
**Comandos essenciais**
-   Criar branch:`git branch <nome>` 
-   Criar branch e já trocar para ela:`git checkout -b <nome>` 
-   Trocar de branch:`git checkout <nome>` 

 **git checkout**
-   Faz duas operações:
    -   Move a **HEAD** para outra branch.
    -   Atualiza a **Working Tree** para refletir o commit de destino.
-   **Modificações locais não são perdidas** (exceto em situações especiais com conflito de diretório).

## 🪢Merge (Fusão de Branches)
**Tipos de merge**
**Fast-forward**
-   Ocorre quando existe **linha reta** entre a branch atual e a outra.
-   O Git simplesmente **avança a branch atual** até o commit da outra.
-   Não cria novo commit.
    
**Three-way merge**
-   Ocorre quando a branch atual e a outra **divergiram** em commits diferentes.
-   O Git cria um novo **commit de merge**.
-   Involui três pontos:
    -   _HEAD_ (branch atual)
    -   _Branch a ser mergeada_
    -   _Último commit comum_ (base)
        
