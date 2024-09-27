#leer tres valores y almacenarlos en las variables: A, B y C respectivamente
A = int(input("ingresa un primer numero A: ")) #muestra el valor de A
B = int(input("ingresa el segundo numero B: ")) #muestra el valor de B
C = int(input("ingresa el tercer numero C: ")) #muestra valor de c

#revisar si los valores son distintos
if A == B and A == C and B == C:
    print("Altera: los valores introducidos deben ser diferentes.")#presenta una alerta en caso de que los valores sean iguales
else:
#verificar cual valor es mayor y menor
    mayor = max(A, B, C) #aqui presentara cual valor es mayor de A, B y C
    menor = min(A, B, C) #aqui presentara cual valor es menor de A, B y C

#imprimir resultados
print("El valor mayor es:", mayor) #muestra el resultado del valor mayor
print("El valor menor es:", menor) #muestra el resultado del valor menor
![image](https://github.com/user-attachments/assets/07bfe213-c311-44dc-a1ba-0f2a814fcfc6)
![image](https://github.com/user-attachments/assets/70be807f-23f7-4408-b719-3bcf52151f89)
