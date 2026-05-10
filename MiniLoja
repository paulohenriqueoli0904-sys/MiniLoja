
# Entrada de boas vindas com nome e sobrenome
print("Olá, seja bem-vindo(a) a loja do Paulo Henrique Minervino de Oliveira")
valor = float(input("Entre com o valor do produto: "))  # Solicita ao usuário o valor do produto. Transformado em float
quantidade = int(input("Entre a quantidade do produto: ")) # Solicita ao usuário a quantidades a serem compradas do produto anterior.
total = valor * quantidade # Calcula o valor total da compra, sem contar com o desconto

# Verifica se o total é maior ou igual a R$2500 e menor que R$6000. Para aplicar o desconto de 4%.
if total >= 2500 and total < 6000:
    result1 = total *4/100 #Calcula 4% de desconto
    result2 = round(total - result1, 2)
    print(f"O Valor SEM desconto é: R${total}")
    print(f"O Valor COM os 4% de desconto é: R${result2}")

# Verifica se o total é maior ou igual a R$6000 e menor que R$10000. Para aplicar o desconto de 7%.
elif total >= 6000 and total < 10000:
    result1 = total *7/100 #Calcula 7% de desconto
    result2 = round(total - result1, 2)
    print(f"O valor SEM desconto é: R${total}")
    print(f"O valor COM os 7% de desconto é: R${result2}")

# Verifica se o total é maior ou igual a R$10000. Para aplicar o desconto de 11%.
elif total >= 10000:
    desconto = total * 11/100 #Calcula 11% de desconto
    valor_desconto = round(total - desconto, 2)
    print(f"O valor SEM desconto é: R${total}")
    print(f"O valor COM os 11% de desconto é: R${valor_desconto}")

# Verifica se o valor total for menor que R$2500, para que nenhum desconto seja aplicado
else:
    print(f" O Valor total é {total}")
