### Borrar paciente
**ID:** 003
**Descripción:** El secretario borra un paciente del sistema.   

**Actores principales:** Secretaría.   

**Precondiciones:**
>+  El paciente debe existir en el sistema.

**Flujo principal:**
>1. El caso de uso comienza cuando el secretario quiere borrar un paciente del sistema.
>2. El Secretario introduce el nombre y apellidos del paciente en el sistema
>3. El sistema hace una búsqueda del paciente.
>4. El secretario confirma que quiere borrar el paciente buscado.
>5. El sistema borra todos los datos del paciente buscado.

**Postcondiciones:**
>+ El sistema borra todos los datos del paciente
>+ El sistema pide una confirmación extra de seguridad cuando se intente borrar los datos del paciente
**Flujos alternativos:**
>3.a. Si el paciente buscado no existe, salta un mensaje de error donde explica que el paciente buscado ya no existe.   
