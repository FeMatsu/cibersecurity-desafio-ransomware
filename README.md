#Resultado do Desafio Ransomware

Quando o código encrypter.py e decrypter.py estavam escritos escritos, Criei um arquivo chamado "teste.txt" e adicionei um conteúdo nele. Após salvar, utilizei o comando ``` ls ``` para listar os arquivos, e o resultado foi exibido corretamente.

![Captura de tela 2024-12-29 215629](https://github.com/user-attachments/assets/0319c0bd-a620-43c5-ac48-8bfa29fd9459)

Em seguida, executei o comando: 'python encrypter.py'. Depois disso, usei novamente o comando ``` ls ```, que agora mostrava um arquivo chamado "teste.txt.ransomwaretroll".

- Imagem do resultado do comando 'ls'

![Captura de tela 2024-12-29 215710](https://github.com/user-attachments/assets/aad8bc5d-0e41-4ffd-a11a-e1ab58366396)
  
- Para verificar o conteúdo desse arquivo criptografado, utilizei o comando 'nano teste.txt.ransomwaretroll'

![Captura de tela 2024-12-29 215803](https://github.com/user-attachments/assets/b6f61915-4c76-4698-a59f-9ae5d3db4170)

  
Por fim, executei o comando 'python decrypter.py' que descriptografou o arquivo "teste.txt.ransomwaretroll", fazendo com que ele voltasse ao nome original, "teste.txt", com o mesmo conteúdo inicial.
  ![Captura de tela 2024-12-29 215856](https://github.com/user-attachments/assets/47b75c4e-1815-40bd-a20c-165cd66a1f21)




