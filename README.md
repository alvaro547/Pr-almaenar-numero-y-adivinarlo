# Pr-almaenar-numero-y-adivinarlo

print(" ")
print("Alvaro Campechano practica en clase que alamcene un numero y pida al usuario adivinarlo")
print(" ")
# Programa para adivinar un número

# Almacenamos un número secreto
numero_secreto = 7  # Puedes cambiar este número a cualquier otro

print("¡Bienvenido al juego de adivinar el número!")
print("He escogido un número entre 1 y 10. Intenta adivinarlo.")

# Variable para controlar el intento del usuario
adivinado = False

# Bucle hasta que el usuario adivine el número
while not adivinado:
    try:
        # Solicitar al usuario que ingrese su intento
        intento = int(input("Ingresa tu intento: "))
        
        # Comprobar si el intento es correcto
        if intento < numero_secreto:
            print("Demasiado bajo. Intenta nuevamente.")
        elif intento > numero_secreto:
            print("Demasiado alto. Intenta nuevamente.")
        else:
            print("¡Felicidades! Has adivinado el número.")
            adivinado = True  # Cambiamos la variable a True para salir del bucle
    except ValueError:
        # Manejar el caso en que la entrada no sea un número válido
        print("Por favor, ingresa un número entero válido.")

![image](https://github.com/user-attachments/assets/e9a12223-cb4c-4eff-bcf2-0d7e76abe500)
![image](https://github.com/user-attachments/assets/7991b243-d6f1-4e5d-ad07-d61c01d05324)

