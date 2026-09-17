🔐 Laboratório de Phishing — SEToolkit

📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático de Cibersegurança da DIO, com o objetivo de compreender, em um ambiente controlado, como ataques de phishing podem utilizar páginas falsas para induzir usuários a fornecer informações sensíveis.

A atividade utiliza o SEToolkit (Social-Engineer Toolkit) em um ambiente Kali Linux para demonstrar os conceitos envolvidos na criação de uma página de phishing.

⚠️ Aviso de segurança: este projeto possui finalidade exclusivamente educacional. A demonstração deve ser realizada somente em laboratório próprio, com autorização e utilizando dados fictícios. Não utilize páginas falsas para coletar credenciais reais ou informações de terceiros.

🎯 Objetivos

Compreender o funcionamento básico de ataques de phishing.

Conhecer o SEToolkit e seus recursos voltados à engenharia social.

Identificar os elementos utilizados em páginas fraudulentas.

Entender os riscos associados ao fornecimento de credenciais em páginas não confiáveis.


🛠️ Tecnologias e ferramentas

  Kali Linux

  SEToolkit


🔎 SEToolkit

O Social-Engineer Toolkit (SEToolkit) é um framework utilizado em testes de segurança e conscientização sobre engenharia social.

Neste laboratório, a ferramenta foi utilizada para compreender, de maneira controlada, os componentes envolvidos em uma simulação de phishing.

A atividade foi realizada sem utilização de credenciais reais ou coleta de informações de terceiros.

⚙️ Configuração do Phishing no Kali Linux

1. Acesso root

Para iniciar a configuração do ambiente com privilégios administrativos:

sudo su

2. Iniciando o SEToolkit

Após obter acesso root, o SEToolkit foi iniciado através do comando:

setoolkit

3. Configuração do ataque

Dentro do SEToolkit, foram selecionadas as seguintes opções:

Tipo de ataque: Social-Engineering Attacks
Vetor de ataque: Web Site Attack Vectors
Método de ataque: Credential Harvester Attack Method
Método de ataque: Site Cloner

4. Obtendo o endereço da máquina

Para verificar as informações de rede da máquina utilizada no laboratório:

ifconfig


O endereço IP identificado foi utilizado para acessar a demonstração dentro do ambiente de testes.

5. URL utilizada como referência

Para a demonstração do conceito de clonagem de página, foi utilizada como referência:

http://www.facebook.com



📸 Resultados

As capturas de tela utilizadas para documentar o laboratório podem ser armazenadas no diretório:



🛡️ Como se proteger contra phishing

Algumas medidas importantes para reduzir o risco incluem:

Verificar o endereço do site antes de realizar login.

Evitar clicar em links suspeitos recebidos por mensagens ou e-mail.

Utilizar autenticação multifator sempre que possível.

Utilizar gerenciadores de senhas.

Manter navegador e sistema operacional atualizados.

Nunca compartilhar códigos de autenticação.

Reportar mensagens e páginas suspeitas.

