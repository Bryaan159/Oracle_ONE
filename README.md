## Teoria

Maquina virtual (JVM)

Código -> Ejecutable -> Java Virtual Machine(JVM)-> Sistema Operativo

```java
public class Persona{

    String nombre;
    String apellido;
    int edad;

    void defaultDatos(){
        this.nombre = "Juan";
        this.apellido = "Perez";
        this.edad = 30;
    }

}

```
* Administracion de memoria
* Multiplataforma
* Seguridad
* Optimizacion
* Librerias
---
¿Cuál es la diferencia entre archivos ejecutables de Windows (.exe) y archivos ejecutables de Java (Bytecode)?:

**Respuesta**:
1) Los ejecutables de Windows pueden correr directamente en el sistema operativo, los de Java necesitan de la máquina virtual

2) Los archivos ejecutables de Java son portátiles, los de Windows no

