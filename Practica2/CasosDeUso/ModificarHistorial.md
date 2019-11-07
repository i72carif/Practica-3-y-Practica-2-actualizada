### **Añadir en historial**
**ID:** 007 **Descripción:** Se añade nuevas lineas de información en el historial.

**Actores principales:** Secretaría

**Precondiciones:**
>* El paciente debe estar registrado.

**Flujo principal:**
>1. El Secretario quiere actualizar el historial del paciente.
>2. El Secretario introduce el nombre y apellidos del paciente en el sistema
>3. El sistema comprueba la existencia del paciente.
>4. Introduce la informacion actual médica del paciente y se va registrando en forma de historial cada vez que añada algo nuevo.

**Postcondiciones:**
>* Se guardan los datos del historial.

**Flujos alternativos:**
>3.a. Si existe el paciente, se muestra un mensaje de que ya existe.

>4.a. Si no rellena los campos obligatorios, se muestra un mensaje de que no ha añadido.
