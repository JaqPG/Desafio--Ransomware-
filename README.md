# Desafio--Ransomware-


Este projeto tem como objetivo a criação de um Ransomware simples usando a linguagem Python no Kali Linux.

## Guia passo a passo: 

- ### Faça o clone do repositório.
 Execute o seguinte comando para clonar o repositório em sua máquina local, caso tenha interesse em contribuir no GitHub. 

#### code :

git clone https://github.com/JaqPG/Desafio--Ransomware-.git  

### 1. Crie o diretório do seu projeto no Kali Linux utilizando o comando mkdir: 

#### code:
```
mkdir nome_desejado  
```
Exemplo: 
mkdir projeto-Ransomware  

### 1.1 Dentro do diretório criado, crie três arquivos utilizando o comando touch: 

 #### code:
```
- touch teste.txt 
- touch encripter.py 
- touch decrypter.py  
```
### Breve explicação: 

#### teste.txt
 Este será o arquivo de texto a ser criptografado. 

#### encripter.py: 
Este script realizará a criptografia dos dados do arquivo teste.txt. 

#### decrypter.py:
 Este script realizará a descriptografia dos dados do arquivo teste.txt. 

### 1.2 Insira os dados nos arquivos criados.
 Execute os seguintes comandos: 

 #### code:

```
nano teste.txt 
```
Insira o texto base a ser criptografado 

Exemplo: Este texto está légivel.
```
nano encripter.py 
```
Insira o programa de criptografia 
```
nano decrypter.py 
```
Insira o programa de descriptografia 

Use CTRL+O para salvar, pressione Enter e, em seguida, CTRL+X para sair do editor 

### 2.Execute o encripter com o seguinte comando: 

#### code 

```
python encripter.py
```

Será gerado um novo arquivo criptografado chamado teste.txt.ransomwaretroll.

 Para verificar, utilize o comando:
 
#### code:
 ```
  ls
 ```
 Que listará os quatro arquivos:
 #### encripter.py, decrypter.py, teste.txt e teste.txt.ransomwaretroll.
![encrypter](https://github.com/JaqPG/Desafio--Ransomware-/assets/156304936/8ec641ac-2bb0-467d-b387-358474b71829)

 

 Execute nano teste.txt.ransomwaretroll

 O conteúdo do arquivo está codificado e ilegível. 
 
![teste txt ransomware](https://github.com/JaqPG/Desafio--Ransomware-/assets/156304936/2f56da8d-9d91-44d0-957c-01c16058eedd)

### 3.Execute o decrypter para decodificar o texto: 

#### code 
```
python decrypter.py  
```
O arquivo teste.txt.ransomwaretroll será descriptografado e removido do diretório.

 Confirme utilizando o comando:
 #### code:
 ```
 ls
 ```
Que listará apenas os três  arquivos criados inicialmente.

#### encripter.py, decrypter.py, teste.txt 
 ![decrypter](https://github.com/JaqPG/Desafio--Ransomware-/assets/156304936/30c57ae7-e840-4fa2-97bd-561274a1361e)

Utilize o comando:
 ```
 nano teste.txt
 ```
 O texto foi descriptografado, exibindo a mensagem original digitada. 
 
![texto descriptografado](https://github.com/JaqPG/Desafio--Ransomware-/assets/156304936/3d7295a5-18e0-4057-a070-d79c8ffcc077)
