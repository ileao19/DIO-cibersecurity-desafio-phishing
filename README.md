# DIO-cibersecurity-desafio-phishing
## Desafio do Bootcamp Santander Cybersecurity sobre PHISHING

No desafio de projeto proposto pelo professor Cassiano, da DIO, foi solicitado o desenvolvimento de um phishing, onde deveríamos clonar a página de login de uma rede social e capturar as credenciais do usuário.

Esse procedimento deveria ser realizado utilizando o sistema operacional Kali Linux e a ferramenta SETOOLKIT.

A seguir, apresento o passo a passo realizado para o desenvolvimento do desafio:

## **1º PASSO:**

Acesse o terminal do Linux e digite o comando:

sudo su

Ao usar sudo su, você utiliza o sudo para obter permissões administrativas e, em seguida, executa o su para alternar para o usuário root. Na prática, isso significa que você se torna o usuário root sem precisar digitar diretamente a senha do root (desde que o sistema esteja configurado para usar o sudo).

![passo 1](https://github.com/user-attachments/assets/7943d0c0-9ae1-42ba-b77e-97763f4ff7c2)

____________________________________________________________________________________________________________________________________________________

## **2º PASSO:**

Após acessar o usuário root, digite o comando:

setoolkit

O comando setoolkit inicia o Social-Engineer Toolkit (SET), uma ferramenta amplamente utilizada em testes de penetração voltados para engenharia social. Ela está pré-instalada no Kali Linux e foi projetada para ajudar especialistas em segurança a simular ataques de engenharia social e testar a resiliência de sistemas e pessoas contra esses tipos de ameaças.

![passo 2](https://github.com/user-attachments/assets/dba2f158-cb7a-41e6-b0ab-bf6ba20707b8)

____________________________________________________________________________________________________________________________________________________

## **3º PASSO:**

Acesse o menu de opções do SETOOLKIT.

Nesse menu, há uma variedade de ferramentas disponíveis. Para este desafio, utilizaremos a opção 1:

![passo 3](https://github.com/user-attachments/assets/9016afb7-5a53-4bbf-a02a-7d18c9a68c50)

____________________________________________________________________________________________________________________________________________________

## **4º PASSO:**

Selecione a opção 2:

Website Attack Vectors

Essa opção permite configurar ataques baseados na criação de páginas web maliciosas, sendo ideal para cenários de phishing que envolvem clonar sites ou hospedar páginas falsas para capturar as credenciais dos usuários.

![passo 4](https://github.com/user-attachments/assets/29027c6a-522e-4867-ba1f-57274efc13ac)

____________________________________________________________________________________________________________________________________________________

## **5º e 6º PASSOS:**

Escolha a opção 3:

Credential Harvester Attack Method

Em seguida, selecione a opção 2:

Site Cloner

Essa configuração permite clonar um site legítimo e configurar um servidor para capturar as credenciais que a vítima inserir (como nome de usuário e senha).

![passo 5](https://github.com/user-attachments/assets/ba53b109-0e5e-4280-b54f-0dd7d645883d)

____________________________________________________________________________________________________________________________________________________

## **7º PASSO:**

Concluídas as etapas anteriores, daremos início à clonagem. Certifique-se de que, no campo destacado em amarelo na imagem (ou saída do terminal), consta o IP da sua máquina. Caso esteja correto, pressione ENTER.

Na sequência, digite a URL do site que será clonado. No meu caso, utilizei o Instagram para esta atividade, inserindo a seguinte URL:

http://www.instagram.com

Pressione ENTER novamente e aguarde a conclusão do processo. O resultado será semelhante ao exemplo destacado em amarelo na imagem.

![passo 6](https://github.com/user-attachments/assets/44c6fa86-a16f-4af4-bcd8-e6978f2cfe48)

____________________________________________________________________________________________________________________________________________________

# **PRONTO**

Seu site clonado está pronto!

Utilize o IP da sua máquina para acessar a página no navegador. Digite credenciais fictícias na página para realizar os testes.

No terminal Linux, verifique se as credenciais inseridas aparecem conforme o esperado.

![pagina insta](https://github.com/user-attachments/assets/2496d9fd-b630-4054-832d-e32c2200e9b4)

____________________________________________________________________________________________________________________________________________________

# Conferindo...

Confira no seu terminal linux se apresentou as mesmas credenciais digitadas no navegador.

![senha e login](https://github.com/user-attachments/assets/178f6e65-36b0-4a00-86cd-3320f9fd305f)

____________________________________________________________________________________________________________________________________________________

# Conclusão

O desafio apresentou um grau de complexidade para iniciantes na área de Cibersegurança, como eu. No entanto, a execução foi muito produtiva e satisfatória. Durante o processo, aprendi mais sobre essa tecnologia e entendi melhor as vulnerabilidades presentes no nosso cotidiano.

Lembrando: Este desafio foi realizado para fins educativos e reproduzido em um ambiente controlado.


