# DIO-cibersecurity-desafio-phishing
## Desafio do Bootcamp Santander Cybersecurity sobre PHISHING

No desafio de projeto proposto pelo porfessor Cassiano da DIO, foi proposto o desenvolvimento de um PHISHING onde deveriamos clonar o acesso de uma rede social e obter as credenciais do usuario.

Esse procedimento deveria ser realizado atraves do SO Kali Linux, usando a ferramenta do SETOOLKIT.

A seguir demonstratei o passo a passo usado para o desenvolvimento do desafio!

## **1º PASSO:**

Acessar o Terminal do Linux e digita o comando "sudo su".

Ao usar sudo su, você primeiro usa o sudo para obter permissão administrativa e, em seguida, executa o su para alternar para o usuário root.
Na prática, isso significa que você se torna o usuário root sem precisar digitar diretamente a senha do root (se o seu sistema estiver configurado para usar sudo).

![passo 1](https://github.com/user-attachments/assets/7943d0c0-9ae1-42ba-b77e-97763f4ff7c2)

____________________________________________________________________________________________________________________________________________________

## **2º PASSO:**

Após logar no seu usuario, digite o comando "setoolkit".

O comando setoolkit é usado para iniciar o Social-Engineer Toolkit (SET), uma ferramenta poderosa e amplamente usada para testes de penetração focados em engenharia social. Ela está pré-instalada no Kali Linux e foi criada para ajudar especialistas em segurança a simular ataques de engenharia social e testar a resiliência de sistemas e pessoas contra esses tipos de ameaças.

![passo 2](https://github.com/user-attachments/assets/dba2f158-cb7a-41e6-b0ab-bf6ba20707b8)

____________________________________________________________________________________________________________________________________________________

## **3º PASSO:**

Agora iremos acessar o menu de opções do SETOOLKIT.

Nesse menu temos uma variedade de ferramentas, no entanto para esse desafio iremos usar a opção 1 "Social-Engineerring Attacks".

![passo 3](https://github.com/user-attachments/assets/9016afb7-5a53-4bbf-a02a-7d18c9a68c50)

____________________________________________________________________________________________________________________________________________________

## **4º PASSO:**

Usaremos a opção 2 "Website Attack Vectors" para dar sequencia na atividade.

Essa opção permite configurar ataques baseados na criação de páginas web maliciosas. Ideal para criar cenários de phishing que envolvem clonar sites ou hospedar páginas falsas para capturar credenciais de usuários.

![passo 4](https://github.com/user-attachments/assets/29027c6a-522e-4867-ba1f-57274efc13ac)

____________________________________________________________________________________________________________________________________________________

## **5º e 6º PASSOS:**

Escolheremos agora a opção 3 "Credential Harvester Attack Method".

Em seguida escolha a opção 2 "Site Cloner"

Isso nos possibilitara a clonar um site legítimo e configura um servidor para capturar as credenciais que a vítima insere (como nome de usuário e senha).

![passo 5](https://github.com/user-attachments/assets/ba53b109-0e5e-4280-b54f-0dd7d645883d)

____________________________________________________________________________________________________________________________________________________

## **7º PASSO:**

Assim que concluirmos os passos anteriores, daremos inicio a clonagem. Certifuque-se que onde está com um borrão amarelo na imagem, conste o IP de sua máquina. Conferindo que está correto, apenas aperte ENTER.

Em seguida, digite a URL do site a ser clonado. No meu caso, utilizei o INSTAGRAM para a atividade, com a seguinte URL: 

http://www.instagram.com

Pressione ENTER novamente e aguarde um resultado semelhante ao da caixa amarela da imagem abaixo:

![passo 6](https://github.com/user-attachments/assets/44c6fa86-a16f-4af4-bcd8-e6978f2cfe48)

____________________________________________________________________________________________________________________________________________________

# **PRONTO**

Seu site clonado esta pronto!

Utilize o IP da sua maquina para pesquisar no navegador e digite suas credenciais na página.

![pagina insta](https://github.com/user-attachments/assets/2496d9fd-b630-4054-832d-e32c2200e9b4)

____________________________________________________________________________________________________________________________________________________

# Conferindo...

Confira no seu terminal linux se apresentou as mesmas credenciais digitadas no navegador.

![senha e login](https://github.com/user-attachments/assets/178f6e65-36b0-4a00-86cd-3320f9fd305f)

____________________________________________________________________________________________________________________________________________________

# Conclusão

O desaafio apresentou uma certa complexidade para um iniciante na area de Cibersegurança que nem eu. No entanto, foi muito produtivo e satisfatório a execução do mesmo.
Pude aprender um pouco mais sobre essa tecnologia, entender um pouco mais sobre as vulnerabilidades presentes no nosso cotidiano.

Lembrando que esse desafio foi criado para fins educativos, reproduzido em um ambiente controlado.

