texto = input ()
texto = texto.split()
numero = 0
resposta = ""
for x in range(len(texto)):
numero = len(texto[x])
if x == len(texto)-1
resposta += str(numero)
else:
resposta += str(numero) + "-"
print(resposta)
