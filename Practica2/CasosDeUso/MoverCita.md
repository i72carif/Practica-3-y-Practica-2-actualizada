### **Mover cita**
**ID:** 011 **Descripción:** Se modifica la fecha en la que es fijada la cita con un paciente.

**Actores principales:** Secretaría

**Precondiciones:**
>* El paciente debe estar registrado.
>* El paciente debe tener al menos una cita

**Flujo principal:**
>1. El Secretario quiere modificar una cita.
>2. El Secretario introduce el nombre y apellidos del paciente al que quiere modificar la cita.
>3. El sistema comprueba la existencia del paciente.
>4. El secretario modifica los datos de la cita que pide el sistema.

**Postcondiciones:**
>* Se guardan los datos de la modificación en la lista de citas.

**Flujos alternativos:**
>3.a. Si existe el paciente, se muestra un mensaje de que ya existe.
>3.b. Si el paciente no tiene cita, se mostrará un mensaje indicando que dicho paciente no tiene citas.

>4.a. Si no rellena los campos obligatorios, se muestra un mensaje de que no ha añadido.
>4.b. No puede existir mas de una cita en una misma fecha y hora, y en dicho caso el sistema mostrará un mensaje de error
