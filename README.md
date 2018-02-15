valor = float(input('Valor da compra: '))
forma_pag = input('Digite a forma de pagamento: ')

if forma_pag == '1':
    valor_final = valor * 0.9
elif forma_pag == '2':
    valor_final = valor * 0.95
elif forma_pag == '3':
    valor_final = valor
elif forma_pag == '4':
    valor_final = valor * 1.10
else:
    valor_final = 'Forma de pagamento inválida'

print(valor_final)  
