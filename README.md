Olá, Aqui é o Gabriel, estou a aprofundar meus estudos em python ainda mais e por conta disso começarei a postar alguns projetos de simples a complexos por aqui com suas explicações.
Segue um formulario de contato simples, sem interface pedindo nome, idade cpf e demais informações. Caso queira adicionar demais informações só seguir o exemplo.
Exemplo: nome = input ('Nome'), para mudar a variavel "nome" pra idade, por exemplo é só substituir a palavra nome e colocar idade. a função input serve como uma pergunta e da a opção do usuário responder em terminal como não temos interface.
OBS: idade como seria respondida em número seria uma variavel do tipo int (inteiro/número inteiro) e não do tipo string (texto) igual é o nome, mas no python essa conversão de string pra int e demais conversões ocorre de forma automática.
No entanto no final decidi a o invés de encurtar o código usando o + como separador e no final dar um print na variavel preferi usar o processo extenso. segue o exemplo de como ficaria da outra forma abaixo:
frase nome, 'De CPF' + str(cpf) + 'Residente No Endereço' + endereço + 'Possui o Telefone:' + str(telefone) + 'Com' + str(idade) + 'anos e' + str(altura) + 'Metros'
print (frase)
Dessa forma imprimiria as informações, o maior problema (ou talvez chatice) é ter que usar o str(Nome da variavel) pra transformar a variavel em string.

Se você leu até aqui, obrigado, isso foi uma breve explicação desse simples formulário que eu fiz.

![image](https://user-images.githubusercontent.com/52702785/149771017-41b81d50-5288-425a-a485-b80415c9d7ba.png)

Feito com Love by Gabrielan1 <3
