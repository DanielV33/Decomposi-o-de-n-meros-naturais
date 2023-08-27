# Decomposi-o-de-n-meros-naturais
Código em Python que decompõe números naturais de até 4 casas decimais.
num=input("Digite o numero:")
lista=[]
for i in num:
    lista.append(i)
print("Unidade: {0}".format(lista[3]))
print("Dezena:  {0}".format(lista[2]))
print("Centena: {0}".format(lista[1]))
print("Milhar:  {0}".format(lista[0]))
