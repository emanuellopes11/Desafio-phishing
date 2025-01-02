# Desafio-phishing

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- URL para clone: http://www.facebook.com


### Download do código fonte
-> Na pagina inicial, salve a página com o nome ```index.html```

![Desafio_de_codigo_04](https://github.com/user-attachments/assets/6ba93f28-b200-40c9-8f5c-154441ce8e8a)

### Editar código fonte

-> Edite o arquivo ```index.html``` e apague a linha do script onde o ```button ID`` está sendo chamado.

![Desafio_de_codigo_06](https://github.com/user-attachments/assets/f561f842-c95a-44e3-96d6-564146de43ac)

### Clonar a página do facebook

-> No ```setoolkit``` utilizaremos a opção de ```Custom Import``` e apontar para o arquivo ```index.html``` que editado.
-> Insira a URL ```http://facebook.com```

![Desafio_de_codigo_02](https://github.com/user-attachments/assets/c5257d33-177e-46a3-b40a-e3b900d8613e)

-> No navegador de uma outra estação, insira o IP do Kali Linux e a página do facebook será aberta.

![Desafio_de_codigo_03](https://github.com/user-attachments/assets/c6de3d0c-caeb-43a8-badc-5b4a615b53ba)


### Resutado

![Alt text](./password.jpg "Optional title")



