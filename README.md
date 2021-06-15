def joana(n):
    if n > 0:
        print('Positivo')
    elif n == 0:
        print('Nulo')
    else:
        print('Negativo')

print('POSITIVO OU NEGATIVO')
n = int(input('Digite um número: '))
print('Este número é', end=' ')
joana(n)
