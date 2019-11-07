### **Añadir paciente**
**ID:** 001 **Descripción:** Se añaden los datos de un nuevo paciente.

**Actores principales:** Secretaría

**Precondiciones:**
>* El paciente no debe estar registrado.

**Flujo principal:**
>1. El Secretario quiere agregar un nuevo paciente.
>2. El Secretario introduce el nombre y apellidos del paciente en el sistema.
>3. El sistema comprueba la existencia del paciente.
>4. Introduce los datos basicos del paciente pedidos por el sistema.

**Postcondiciones:**
>* Se guardan los datos del nuevo paciente y se crea un historial vacío.

**Flujos alternativos:**
>3.a. Si existe el paciente, se muestra un mensaje de que ya existe.

>4.a. Si no rellena los campos obligatorios, se muestra un mensaje de que no ha añadido.
