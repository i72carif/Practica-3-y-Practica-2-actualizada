### **Cancelar cita**
**ID:** 012 **Descripción:** Cancelación de una cita con un paciente.

**Actores principales:** Secretaría

**Precondiciones:**
>* El paciente debe estar registrado.
>* El paciente debe tener al menos una cita

**Flujo principal:**
>1. El Secretario quiere cancelar una cita.
>2. El Secretario introduce el nombre y apellidos del paciente al que quiere cancelar una cita.
>3. El sistema comprueba la existencia del paciente.
>4. El secretario confirma la cancelación de la cita con el paciente

**Postcondiciones:**
>* La cita cancelada desaparecerá de la lista de citas.

**Flujos alternativos:**
>3.a. Si existe el paciente, se muestra un mensaje de que ya existe.
>3.b. Si el paciente no tiene cita, se mostrará un mensaje indicando que dicho paciente no tiene citas.

>4.a. Si el secretario no confirma la cancelacion la cita no será borrada de la lista de citas
