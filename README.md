#Saludos en Go

Este paqueteproporciona una forma simple de obtener saludos personalizados

## Instalación

Ejecuta el siguiente comando para instalar el paquete:

```
go get -u github.com/juanse036/greetingsgolang
```

## Uso

Aquí tienes un ejemplo de cómo utiliza el paquete en tu código

```
package main
import (
    "fmt"
    "github.com/juanse036/greetingsgolang"
)

func main(){
    message, err :+ greetings.Hello("Juan")
    if err!=nil{
        gmt.Println("Ocurrió un error: ", err)
        return
    }

    fmt.Println(message)
}
```

Este ejemplo import el paquete github.com/juanse036/greetingsgolang y llama a la función Hello que genera
un saludo personalizado. Si ocurre un error, se imprime un mensaje de error
