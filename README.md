# cibersecurity-desafio-phishing

## Criação de um Phishing com o Kali Linux

- Site Cloner não estava disponível;
- Utilizei o Web Template, selecionei o template do Google.

# Etapas de criação do Phishing
## Antes de tudo, instalei e configurei o Kali Linux como máquina virtual através do VirtualBox.
- Através do comando "setoolkit" no terminal do sistema, acessei a tela de opções disponíveis;
- Na tela de opções disponíveis, selecionei a opção "1) Social-Engeneering Attacks" para acessar a aba de Engenharia Social da tela;
- Na aba de Engenharia Social, selecionei a opção "2) Website Attack Vectors" para acessar as ferramentas disponíveis de ataques se utilizando de websites com Engenharia Social;
- Dentre as ferramentas disponíveis, selecionei a nomeada "3) Credential Harvester Attack Method" pois com ela poderia construir a interface de website voltado ao teste de roubo de credenciais;
- Na próxima tela, selecionei a ferramenta "1) Web Templates" (a ideia inicial era utilizar a ferramenta "2) Site Cloner" mas a ferramenta está apresentando erros) e utilizei o template do site de login da Google;
- O acesso é feito através do número de IP relacionado ao sistema Kali Linux no seu navegador padrão, número esse apresentado pelo terminal;
## Após acessar esse clone de website através do seu IP, o clone estará disponível e completo. Testes podem ser feitos para saber se está funcionando mesmo, segue a imagem de um exemplo de coleta de credenciais feito por mim na imagem disponível no repositório.
