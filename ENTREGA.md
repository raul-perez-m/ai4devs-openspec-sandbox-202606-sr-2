PARTE A.

*Micro-tarea:* Validador de email
*Pilar 1 — Herramienta:* Claude Sonnet 4.6
 ¿Por qué esta y no otra?
 Porque es para realizar una tarea pequeña y acotada, pero que requiere de cierto razonamiento. 
*Pilar 2 — Contexto:* ¿Qué información estás aportando? (lenguaje, framework, restricciones, ejemplos…)
**Información**
Lenguaje: Javascript
Tipo: Función
Entrada: String
Salida: Boolean

 ¿Hay algo del contexto que has decidido omitir conscientemente?
 Que compruebe que la entrada es un string

*Pilar 3 — Prompt:* ¿Cómo lo estructuras? (estilo, formato de salida, ejemplos…)
 Pega aquí el prompt final que vas a lanzar.

Write a JavaScript function to validate emails:

Requirements: 
 return: Boolean
 Received parameter: string
 validations: 
  - Received value it's a string
  - Email it's in a valid format.
  - Emails can contain characters like "." or "+".

*Resultado:* ¿Funcionó a la primera o tuviste que iterar?

Funciono a la primera.

 Una mejora que harías si volvieras a hacerlo.

Incluir mas validaciones, por ejemplo, para que elimine espacios en blanco tanto al inicio como al final.


PARTE B

Evidencias: 

raul2@MSI MINGW64 /c/Projects/Lidr/ai4devs-openspec-sandbox-202606-sr-2 (alumno/raul-perez)
$ ls -R openspec/
openspec/:
changes/  config.yaml  specs/

openspec/changes:
archive/

openspec/changes/archive:

openspec/specs:

raul2@MSI MINGW64 /c/Projects/Lidr/ai4devs-openspec-sandbox-202606-sr-2 (alumno/raul-perez)
$ openspec --version
1.4.1


*3 Cosas que te hayan llamado la atención*

Que solo tenga 4 comandos para trabajar todo. Al final solo trabaja con new, ff, apply y archive. Parece que debería tener mas comandos.


La estructura me parece super fácil de seguir y muy "humana", lo cual parece que luego será bastante sencillo de seguir lo que va ocurriendo con las specs.

El archivo config.yaml me parece un punto de inicio super interesante y probablemente el punto mas critico dentro del uso de openSpec, porque sin este fichero debidamente configurado y especificado el resto de acciones estan abocadas al fracaso.