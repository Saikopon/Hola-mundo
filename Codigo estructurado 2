def main():

    empleados = []

    numero_empleados = int(input("Digite el número de empleados: "))

    for i in range(numero_empleados):

        print(f"\nEmpleado {i + 1}")

        identificacion = input("Identificación del empleado: ")
        nombre = input("Nombre del empleado: ")
        cartones = int(input("Cantidad de cartones vendidos: "))

        pago_por_carton = 500

        salario = cartones * pago_por_carton

        empleado = {
            "identificacion": identificacion,
            "nombre": nombre,
            "cartones_vendidos": cartones,
            "salario": salario
        }

        empleados.append(empleado)

    total_nomina = 0

    print("\n===== RESULTADOS =====")

    for emp in empleados:

        print("\nEmpleado:", emp["nombre"])
        print("Identificación:", emp["identificacion"])
        print("Cartones vendidos:", emp["cartones_vendidos"])
        print("Salario:", emp["salario"])

        total_nomina += emp["salario"]

    print("\n======================")
    print("Nómina total:", total_nomina)


if __name__ == "__main__":
    main()
