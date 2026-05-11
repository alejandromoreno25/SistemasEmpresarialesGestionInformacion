# Sistemas Empresariales Gestion Informacion
**Para Comenzar**
Para comenzar, nos hemos dividido las tareas de la actividad, para posteriormente realizar una puesta en común sobre cada parte.
Alejandro- es el encargado de la parte 1
Victor- es el encargado de la parte 2
Ángel- es el encargado de la parte 3

**PARTE 1**
**Justifica la elección basándote en el perfil de la empresa (25 empleados, presupuesto ajustado, necesidad de personalización en el etiquetado).**
Teniendo en cuenta las necesidades de la empresa dada, hemos decidido que la mejor opción es Zoho One, a pesar de no ser gratuito,
Zoho ofrece una relación calidad-precio inmejorable. 
Con precios muy asequibles y una interfaz 100% en la nube , la plataforma compite directamente con gigantes como Salesforce o Microsoft Dynamics, pero con una lógica más sencilla y económica. como Odoo, su TCO también es muy bajo ya que se usa mucho en empresas pequeñas.
Además, nos ofrece una alta personalización en etiquetas. pudiendo crearlas y editarlas.

**Cálculo de TCO: Realiza una estimación a 3 años. No olvidéis incluir:
Coste de licencias/suscripción.**
El precio de licencia son de unos 37€ por ello, a los 3 años si nuestra empresa son 25 empleados nos costaría: 11.100€ al año
**Coste de implantación (vuestras horas de desarrollo: estima 100h a 40€/h).**

**Coste operativo (Hosting en Google Cloud, AWS, Huawei Cloud o similar).**
 	una interfaz 100% en la nube y no hay que pagar hosting
  
**PARTE 2**

|  | Record rules | Stock/Albaranes | Facturas | Presupuestos |
| :---- | :---- | :---- | :---- | :---- |
| Administrador | ✓  | ✓  | ✓  | ✓  |
| Comercial | ✓  | ✗ | ✗ | ✓  |
| Operario de Almacén | ✗ | ✓  | ✗ | ✗ |
| Contable | ✗ | ✗ | ✓  | ✗ |


**PARTE 3**
1. Fase de planificación
  Hay que repartir los roles de cada empleado, ver qué problemas debe resolver cada uno y si la documentación será digital (por ejemplo pdf) o a mano.
2. Diseño de la información
  Buscar información sobre cuál es el problema, cómo resolverlo y elaborar una tabla de posibles errores.
3. Revisión y Pruebas
  Asegurarse de que todo está en orden, y realizar las pruebas necesarias usando el fragmento de docker-compose.yml necesario y el comando para realizar un backup de la base de datos PostgreSQL.

**PREGUNTAS FINALES**
¿Es coherente el TCO con la realidad de una PYME?

Sí, lo es, para una PYME, el TCO que hemos propuesto cumple con los requisitos de la empresa.

¿La matriz RBAC evita que el comercial vea los costes de producción?

Si, La matriz esta diseñada para que se cumplan los requisitos, entre ellos el comercial no puede ver los costes de produccion.

¿El comando de backup es sintácticamente correcto?

