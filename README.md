# Aprendiendo Markdown

Mis primeros *pasos* en **Markdown**, que es un formato de marcado de ***archivos de texto***.

A continuacion una ___lista___:

* Item 1
* Item 2
  * Item 2.1
  * Item 2.2
* Item 3

A continuacion una __tabla__:

| Codigo | Nombre | Precio |
| :-: | - | -: |
| 1 | TV | 553.99 |
| 2 | computador | 1683.23 |
| 3 | celular | 791.51 |

A continuacion un *enlace* o _link_:

[Diario El Pais de España](https://elpais.com/america/)

A continuacion una ***imagen***:

![Logo de HALO](https://images.steamusercontent.com/ugc/37813303391570369/2CB0C6151F80990389B3FDA92FC0A32B7B51AD1D/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)

# Titulo nivel 1
## Titulo nivel 2
### Titulo nivel 3

A continuacion el **codigo de un programa**:

    import java.util.Scanner;
    public class Saludo2 {
        public static void main(String[] args) {
            Scanner sc = new Scanner(System.in);
            String nombre;
            System.out.print("Dime tu nombre: ");
            nombre = sc.nextLine();
            System.out.print("Hola " + nombre);
            System.out.println(", encantado de conocerte!");
        }
    }

Fin