# ES_S3_Ponderada

### Introdução

&emsp;&emsp;Este relatório tem como objetivo explorar o acesso SSH no Amazon Elastic Compute Cloud (EC2), um serviço de computação em nuvem altamente escalável oferecido pela Amazon Web Services (AWS). O SSH desempenha um papel crucial na administração e no gerenciamento seguro de instâncias EC2, permitindo que os usuários se conectem remotamente aos servidores na nuvem de forma criptografada. Esse acesso está diretamente relacionado ao projeto desenvolvido neste módulo, uma vez que utilizaremos essa tecnologia para armazenar nosso banco de dados.

### Objetivo

&emsp;&emsp;O objetivo do acesso SSH no EC2 é proporcionar aos usuários uma maneira segura e confiável de se conectar remotamente às instâncias de computação na nuvem hospedadas no serviço EC2 da AWS. O SSH é uma ferramenta essencial para administradores de sistemas e desenvolvedores, permitindo o gerenciamento remoto de servidores sem comprometer a segurança dos dados transmitidos.

### Materiais

- AWS Academy
- Instancia Ec2
- PuTTY

### Método

&emsp;&emsp;Para realizar o acesso SSH iniciamos o laboratório de aprendizagem da AWS academy.

<div align="center">
  <sub>Figura 1:</sub>
  <img src="/imagens/Ec2_1.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

&emsp;&emsp;Após, criamos uma instância Ec2 e damos um nome para ela.

<div align="center">
  <sub>Figura 2:</sub>
  <img src="/imagens/Ec2_2.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

&emsp;&emsp;Após, selecionamos uma AMI para a instância que nesse caso foi a Amazon Linux.

<div align="center">
  <sub>Figura 3:</sub>
  <img src="/imagens/Ec2_3.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

&emsp;&emsp;Após, selecionamos o tipo de instância baseado na necessidade da sua aplicação, nesse caso selecionamos t2.micro.

<div align="center">
  <sub>Figura 4:</sub>
  <img src="/imagens/Ec2_4.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

&emsp;&emsp;Após, devemos selecionar um par de chaves e para nossa aplicação criaremos um novo par de chaves.

<div align="center">
  <sub>Figura 5:</sub>
  <img src="/imagens/Ec2_5.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

<div align="center">
  <sub>Figura 6:</sub>
  <img src="/imagens/Ec2_6.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

&emsp;&emsp;Após, criamos um grupo de segurança e executamos a instância. 

<div align="center">
  <sub>Figura 7:</sub>
  <img src="/imagens/Ec2_12.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

<div align="center">
  <sub>Figura 8:</sub>
  <img src="/imagens/Ec2_9.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

&emsp;&emsp;Após, devemos abrir o PuTTY, colocar o ip da instância Ec2 criada e o par de chaves para acessar pelo SSH

<div align="center">
  <sub>Figura 8:</sub>
  <img src="/imagens/Ec2_8.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

<div align="center">
  <sub>Figura 8:</sub>
  <img src="/imagens/Ec2_10.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

<div align="center">
  <sub>Figura 8:</sub>
  <img src="/imagens/Ec2_11.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>

&emsp;&emsp;Após seguir esses passos consiguiremos o acesso SSH no EC2

<div align="center">
  <sub>Figura 8:</sub>
  <img src="/imagens/Ec2_14.png" width="100%">
  <sup>Fonte: Os autores (2024)</sup>
</div>