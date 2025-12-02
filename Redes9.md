|[Main Page](./README.md)|
|[Trial 1 Acess](./TRilha1.md)|
|[Trial 2 Acess](./Trilha2.md)|
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

