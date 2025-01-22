# desafio-cybersecurity-dio

# Phishing para captura de senhas do Facebook

O Brasil é o país com o maior número de vítimas de phishing. Uma estratégia muito utilizada por golpistas para obter acesso a dados confidenciais como logins e senhas. Ainda que a maioria das pessoas tenha sido vítima desse tipo de ataque cibernético em contextos pessoais, 25% dos ataques ocorreram no contexto profissional. O phishing tem esse nome em referência à palavra fishing ou pescaria. Nesse tipo de ataque cibernético, os criminosos “jogam uma isca” para tentar fisgar um internauta que não percebe que está prestes a cair em uma armadilha. Essas armadilhas chegam em forma de e-mails, mensagens de WhatsApp e outras muito convincentes que acabam por direcionar a sites maliciosos. 

Neste repositório teremos a construção de um phishing para captura de senhas do Facebook como resolução de um exercício do Desafio da Plataforma de treinamentos especializados da DIO.

# Ferramentas

    Kali Linux
    setoolkit

# Configurando o Phishing no Kali Linux

    Acesso root: sudo su
    Iniciando o setoolkit: setoolkit
    Tipo de ataque: Social-Engineering Attacks
    Vetor de ataque: Web Site Attack Vectors
    Método de ataque: Credential Harvester Attack Method 
    Método de ataque: Site Cloner
    Obtendo o endereço da máquina: ifconfig
    URL para clone: http://www.facebook.com

Para resolver o desafio phishing da trilha Cybersecurity Specialist da DIO será necessário entrar com as credenciais no site fake do Facebook. Assim, você vai se deparar com a página atual do facebook com a boa prática de tentar defender os campos login e senha via scripts de codificação 64 e hashing. Ou seja não irão conseguir o mesmo sucesso que o instrutor obteve. 

# Resultado

![0f204b7a-d41a-4d79-82d3-9703a317d318](https://github.com/user-attachments/assets/46321fac-1239-4b85-a2f8-0813727df118)

Importante perceber que a opção clonar diretamente do setoolkit não vai funcionar. 
Neste caso do facebook ou de qualquer outra página com script de defesa devemos optar pela importação customiza, ou seja, um código fonte da página que desejamos clonar editado localmente.

![11821b9a-84e7-4b2d-9d44-0eaa68524e6c](https://github.com/user-attachments/assets/58fed615-e849-49ce-be96-79a4d777e2ab)

Com as devidas edições poderemos novamente ver em plain text o login e senha

![01860c95-c72f-4cf9-9492-09140ac6798a](https://github.com/user-attachments/assets/8eb2f86d-9c25-4a5f-ac0f-7edce5dc8b69)



