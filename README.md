# Ransomware para criptografia

### Ferramentas

  - Kali Linux
  - Python

### Configurando o ransomware no Kali Linux

  - Criação do encriptador: ``` nano encrypter.py ```
  - Criação do descriptador: ``` nano descrypter.py ```
  - Criação do arquivo a ser criptografado: ``` teste.txt ```
  - Método de ataque: ``` Ransomware e criptografia via python ```

### Resultados

#### Arquivo de texto original

![Alt text](https://github.com/bielramalho/cybersecurity-desafio-ransomware/assets/103615988/bf3c4532-5314-4ece-a0a3-589804c29588)

#### Encriptando o arquivo

![Alt text](https://github.com/bielramalho/cybersecurity-desafio-ransomware/assets/103615988/384d91f1-cbd7-4bab-85db-eeaa74bcc6e1)

#### Arquivo de texto encriptado

![Alt text](https://github.com/bielramalho/cybersecurity-desafio-ransomware/assets/103615988/9d79615d-1577-4b33-b7f5-c6d521a8bf12)

#### Descriptando o arquivo

![Alt text](https://github.com/bielramalho/cybersecurity-desafio-ransomware/assets/103615988/8fbbdb4d-ffeb-43ca-b5b3-88d4328f3400)

# Dificuldades para fazer o exercício

  - Ao tentar realizar a encriptação do arquivo, tive problemas, aparecendo no cmd ``` no module named 'pyaes' ```. Fiquei alguns minutos quebrando a cabeça
  para saber do que realmente se tratava, apenas sabia que o erro era na biblioteca.

  - Depois de um tempo, notei que não havia baixado a biblioteca "pyaes" usada para puxar no código. Então eu tive que entrar me conectar a internet
  e baixar a biblioteca por meio do comando ``` pip install pyaes ```. Após baixado, consegui encriptar e assim, terminar o desafio.

![Alt text](https://github.com/bielramalho/cybersecurity-desafio-ransomware/assets/103615988/f7df9dbf-2806-4443-a047-4aa1173a73c9)
