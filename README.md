# Primeiro Servidor Web na AWS com EC2

##  Descrição
Projeto prático de criação e publicação de um servidor web utilizando uma instância Amazon EC2, acessível via HTTP.

## Tecnologias utilizadas
- AWS EC2
- Linux
- HTTP
- DNS
- Security Groups

##  Acesso à aplicação
A aplicação foi disponibilizada através do DNS público da instância EC2:

http://ec2-13-219-103-92.compute-1.amazonaws.com/

O DNS público é responsável por traduzir o nome de domínio para o endereço IP público da instância, permitindo que o navegador se conecte ao servidor correto.

## Segurança
O Security Group da instância foi configurado para permitir tráfego HTTP (porta 80) a partir da internet, possibilitando o acesso público à aplicação.

## Contexto do projeto
Este projeto foi desenvolvido como parte de um laboratório prático do **AWS Skill Builder (Cloud Quest)**, com foco na aplicação dos fundamentos de Cloud Computing.

## Evidências do funcionamento

### Página web rodando na instância EC2
![Página web EC2](https://github.com/user-attachments/assets/40532ccb-4b73-46ab-a69f-2abb185925ec)

### Instância EC2 em execução no console AWS
![EC2 no console](https://github.com/user-attachments/assets/e6cca0a1-58ef-4537-8235-6b1621a1d68f)

## Resultado
A instância EC2 foi configurada com sucesso e está respondendo a requisições HTTP via navegador, validando a configuração de rede, segurança e servidor web.
