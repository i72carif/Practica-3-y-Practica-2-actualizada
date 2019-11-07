### **Modificar datos del paciente**
**ID:** 006 **Descripción:** Se modifican los datos del paciente.

**Actores principales:** Secretaría

**Precondiciones:**
>* El paciente debe estar registrado.

**Flujo principal:**
>1. El Secretario quiere cambiar los datos del paciente.
>2. El Secretario introduce el nombre y apellidos.
>3. El sistema comprueba la existencia del paciente.
>4. El secretario confirma que desea modificar los datos del paciente.
>5. Cambia los datos del paciente guardados en el sistema, algunos campos son obligatorios.

**Postcondiciones:**
>* Se guardan los nuevos datos del paciente.

**Flujos alternativos:**
>3.a. Si no existe el paciente, se muestra un mensaje de que no existe.

>5.a. Si no rellena los campos obligatorios, se muestra un mensaje de que no ha añadido.
