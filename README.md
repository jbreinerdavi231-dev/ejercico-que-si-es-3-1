# ejercico-que-si-es-3-1
numero = int(input("ingrese un numero: "))

while numero <= 1:
    print("el numero tiene que ser mayor que 1")
    numero = int(input("ingrese otro numero: "))

divisores = []

for i in range(1, numero + 1):
    if numero % i == 0:
        divisores.append(i)

print(f"divisores: {divisores}")
