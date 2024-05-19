def calculadora(num1, num2, operacao):
    if operacao == 1:
        return num1 + num2
    elif operacao == 2:
        return num1 - num2
    elif operacao == 3:
        return num1 * num2
    elif operacao == 4:
        if num2 != 0:  # Verifica se o segundo número não é zero para evitar divisão por zero
            return num1 / num2
        else:
            print("Erro: Divisão por zero!")
            return 0
    else:
        print("Operação inválida!")
        return 0
