# woow
calculadora teste
n1 = float(input('digite um numero: '))
n2 = float(input('digite mais um numero: '))
menu = 0
while menu != 6:
    print('escolha uma das opções:')
    menu = int(input(('''
    [1] para somar
    [2] para subtrair
    [3] para multiplicar
    [4] para dividir
    [5] para escolher outros números
    [6] para sair do programa

Digite aqui: ''')))

    if menu == 1:
        soma = n1 + n2
        print('==== {} + {} = {} ===='.format(n1, n2, soma))
    if menu == 2:
        subtrai = n1 - n2
        print('==== {} + {} = {} ===='.format(n1, n2, subtrai))
    if menu == 3:
        multi = n1 * n2
        print('==== {} * {} = {} ===='.format(n1, n2, multi))
    if menu == 4:
        divide = n1 / n2
        print('==== {} / {} = {} ===='.format(n1, n2, divide))
    if menu == 5:
        n1 = int(input('digite um novo número: '))
        n2 = int(input('digite mais um novo número: '))
    elif menu == 6:
        print('programa finalizado')
