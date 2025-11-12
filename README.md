Minha primeira calculadora no curso da EBAC (módulo 1 ) 


print ('Bem-Vindo a calculadora EBAC')

while True:
    primeiro_numero = float(input('digite o primeiro numero: '))
    segundo_numero = float(input('digite o segundo numero: '))
    operacao = str(input('digite o nome da operacao, mas como sou iniciante digite apenas: menos, mais, vezes e dividir: '))

    match operacao:
        case 'menos':
            print(f'{primeiro_numero - segundo_numero}')
        case 'mais':
            print(f'{primeiro_numero + segundo_numero}')
        case 'vezes':
            print(f'{primeiro_numero * segundo_numero}')
        case 'dividir':
            print(f'{primeiro_numero / segundo_numero}')
        case '_':
            print('opção invalida')

    continuar = input('fazer outra operacao?: ')

    if continuar != 'sim':
        print('vlw...')
        break






