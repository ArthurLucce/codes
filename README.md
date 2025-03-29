peso = float(input("Digite o peso: "))
altura = float(input("Digite a altura: "))
idade = int(input("Digite a idade: "))
sexo = input("Digite o sexo (M/F): ").upper()

imc = peso / (altura ** 2)
print(f"IMC: {imc:.2f}")
print(f"Idade: {idade} anos")
print(f"Sexo: {sexo}")


if imc < 18.5:
    print("Abaixo do peso")
elif 18.5 <= imc < 24.9:
    print("Peso normal")
elif 25 <= imc < 29.9:
    print("Sobrepeso")
elif 30 <= imc < 34.9:
    print("Obesidade grau 1")
elif 35 <= imc < 39.9:
    print("Obesidade grau 2")
elif imc >= 40:
    print("THAIS CARLA")
elif imc >= 50:
    print("THAIS CARLA 2")
else:
    print("IMC inválido")
