|[Main Page](./README.md)|
|[Trial 1 Acess](./TRilha1.md)|
|[Trial 2 Acess](./Trilha2.md)|

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


