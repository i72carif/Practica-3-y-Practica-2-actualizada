### Mostrar paciente
**ID:** 004
**Descripción:** El secretario busca un paciente del sistema.

**Actores principales:** Secretaría.   

**Precondiciones:**
>+  El paciente debe existir en el sistema.

**Flujo principal:**
>1. El caso de uso comienza cuando el secretario quiere mostrar los datos de un paciente en el sistema.
>2. El Secretario introduce el nombre y apellidos del paciente en el sistema
>3. El sistema hace una búsqueda del paciente.
>4. El sistema muestra los datos del paciente buscado como datos personales ,historial ,citas y tratamientos.

**Postcondiciones:**
>+ El sistema muestra las diferentes opciones relativas al paciente buscado.

**Flujos alternativos:**
>3.a. Si el paciente buscado no existe, salta un mensaje de error donde explica que este no existe en el sistema.
