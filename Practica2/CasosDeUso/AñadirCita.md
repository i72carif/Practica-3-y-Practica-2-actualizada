### **Añadir cita**
**ID:** 008 **Descripción:** Se añade una cita con el paciente.

**Actores principales:** Secretaría

**Precondiciones:**
>* El paciente debe estar registrado.

**Flujo principal:**
>1. El Secretario quiere añadir una cita.
>2. El Secretario introduce el nombre y apellidos del paciente al que quiere añadir una cita.
>3. El sistema comprueba la existencia del paciente.
>4. Introduce los datos requeridos de la cita.

**Postcondiciones:**
>* Se guardan los datos de la nueva cita en la lista de citas.

**Flujos alternativos:**
>3.a. Si existe el paciente, se muestra un mensaje de que ya existe.

>4.a. Si no rellena los campos obligatorios, se muestra un mensaje de que no ha añadido.
>4.b. No puede existir mas de una cita en una misma fecha y hora, y en dicho caso el sistema mostrará un mensaje de error
