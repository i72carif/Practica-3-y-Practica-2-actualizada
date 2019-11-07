### Añadir tratamiento
**ID:** 009
**Descripción:** El secretario añade un nuevo tratamiento al paciente.

**Actores principales:** Secretaría.   

**Precondiciones:**
>+  El paciente debe existir en el sistema.

**Flujo principal:**
>1. El caso de uso comienza cuando el secretario quiere añadir un nuevo tratamiento a un paciente.
>2. El Secretario introduce el nombre y apellidos del paciente en el sistema
>3. El sistema hace una búsqueda del paciente.
>4. El secretario introduce en el sistema el nuevo tratamiento del paciente rellenando todos los campos necesarios para el mismo como la fecha de comienzo y finalizacion o el tipo de tratamiento a seguir.


**Postcondiciones:**
>+ El sistema guarda el tratamiento nuevo del paciente aunque ya tenga otro.

**Flujos alternativos:**
>3.a. Si el paciente buscado no existe, salta un mensaje de error donde explica que el paciente buscado ya no existe.   
