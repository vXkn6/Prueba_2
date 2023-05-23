aux=0.15
admin=0-10
docente=0.5

carillas_porcelana=250000
implantes_dentales=475000
ortodoncia_brackets=800000

opc=0

while opc!=3:
    print("*********El Diente de Oro*************")
    print("1.-Cotizacion\n2.-Renunciar\n3.-Salir")
    print("*"*50)
    try:
        opc=int(input("Ingrese una opcion "))
    except:
        print("ERROR Solo se aceptan digitos")
    if opc==1:
        opct=0
        cantcarpor=0
        cantimpden=0
        cantortbra=0
        subtototal=0
        total=0
        opcdes=0
        while True:
            print("\tTratamientos")
            print(f"1.-Carillas Porcelana ${carillas_porcelana}\n2.-Implantes Dentales ${implantes_dentales}\n3.-Ortodoncia Brackets ${ortodoncia_brackets}\n4.-Salir")
            try:
                opct=int(input("Ingrese la opcion del tratamiento que desa ingresar "))
            except:
                print("ERRO Solo se aceptan digitos")
            if opct==1:
                cantcarpor=int(input("Ingrese la cantidad que desea del tratamiento "))
            elif opct==2:
                cantimpden=int(input("Ingrese la cantidad que desea del tratamiento "))
            elif opct==3:
                cantortbra=int(input("Ingrese la cantidad que desea del tratamiento "))
            else:
                break
        while True:
            print("Tiene Descuento\n1.-Si\n2.-NO")
            try:
                opcdes=int(input("Ingrese una opcion "))
            except:
                print("ERROR Valor ingresado no valido")
            if opcdes==1:
                print("1.-Trabajador Auxiliar\n2.-Trabajador Administrativo\n3.-Trabajador Docente.")
                tipodes=int(input("Ingrese una opcion de descuento "))
                break
            else:
                break
        if tipodes==1:
            descuento=15  
        elif tipodes==2:
            descuento=10
        else:
            descuento=5
        descpor=0
        if tipodes==1:
            descpor=0.15  
        elif tipodes==2:
            descpor=0.10
        else:
            descpor=0.5      
        subtototal=carillas_porcelana*cantcarpor+implantes_dentales*cantimpden+ortodoncia_brackets*cantortbra
        valordes=subtototal*descpor 
        total=subtototal-valordes
        cuotas=total/12
        print("*"*50)
        print("\tCotizacion")
        print("*"*50)
        print(f"Subtotal\t""$",subtototal)
        print("*"*50)
        print(f"Descuento {descuento}%\t${valordes} ")
        print("*"*50)
        print("Total\t""$",total)
        print("*"*50)
        print("Sus 12 cuotas son de:\t$",cuotas)
        print("*"*50)
        print("Sonria Bonito")
        print("*"*50)
if opc==2:
    total=0
    subtototal=0
    cantcarpor=0
    cantimpden=0
    cantortbra=0
    tipodes=0
    opct=0
else:
    print("Muchas Gracias Vuelva pronto")


