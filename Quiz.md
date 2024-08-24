## DIFERENCIA ENTRE UN IDE Y UN EDITOR DE TEXTO

lOS IDE son herramientas que contienen un bibliotecas, debugs, compiladores y mas funciones para el uso de lenguajes que se quiera usar como Netbeans, Eclipse o Intelliji. Pero los Editores de texto son herramientas que solo interpretan el codigo de un lenguaje, pero estos no tienen agregados funciones, bibliotecas o compiladores/interpretes para que el codigo del lenguajes que se esta usando se ejecute.

## TIPO DE LENGUAJES TIPADOS
- JAVA
- C#
- C++

## TIPO DE LENGUAJES NO TIPADOS

- PYTHON
- JAVASCRIPT

## TIPO DE DATOS EN JAVA
 Tipos numericos:
 - Int
 - Byte
 - short
 - Long
 - float
 - double

Tipos Cadenas:
 - String
 - Char

Tipos fechas:
 - Date
 - Calendar
 - time
 - Duration
 - period
 - Instant

## ESTRUCTURA IF EN DIFERENTES LENGUAJES

# C#:
string dia = "Lunes";

if (dia == "Sábado" || dia == "Domingo")
{
    Console.WriteLine("¡Es fin de semana!");
}
else if (dia == "Lunes")
{
    Console.WriteLine("Inicio de la semana laboral.");
}
else
{
    Console.WriteLine("Es un día laborable.");
}

# JAVA:

String clima = "lluvioso";

if (clima.equals("soleado")) {
    System.out.println("¡Vamos a la playa!");
} else if (clima.equals("lluvioso")) {
    System.out.println("Mejor lleva un paraguas.");
} else {
    System.out.println("El clima es impredecible.");
}

# PYTHON:

temperatura = 25

if temperatura > 30:
    print("Hace mucho calor.")
elif 20 <= temperatura <= 30:
    print("El clima está templado.")
else:
    print("Hace frío.")

# JAVASCRIPT:

let semaforo = "rojo";

if (semaforo === "verde") {
    console.log("Puedes avanzar.");
} else if (semaforo === "amarillo") {
    console.log("Prepárate para detenerte.");
} else if (semaforo === "rojo") {
    console.log("¡Detente!");
} else {
    console.log("Color de semáforo no válido.");
}


# PHP:

$edad = 20;

if ($edad < 13) {
    echo "Eres un niño.";
} elseif ($edad >= 13 && $edad < 18) {
    echo "Eres un adolescente.";
} else {
    echo "Eres un adulto.";
}