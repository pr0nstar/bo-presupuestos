# bo-presupuestos
Presupuestos del estado boliviano

* Fuente: [Sigma](https://portal.sigep.gob.bo/index.php/2016/05/09/ley-financial/); [Sigep](https://sigep.gob.bo/sigep_publico/faces/SFprRepPub?gestion=2020)
* Tipo Reporte: Detalle Institucional > Presupuesto institucional por categoria programatica
* Dump: [Reportes en PDF](https://drive.google.com/drive/folders/1JOL-Rh20rYxtqp79tYARwulLGAFbWZhh?usp=sharing)

Grupos:

|   Grupo | Descripcion                                                 |
|--------:|:------------------------------------------------------------|
|       1 | Servicios Personales                                        |
|       2 | Servicios No Personales                                     |
|       3 | Materiales y Suministros                                    |
|       4 | Activos Reales                                              |
|       5 | Activos Financieros                                         |
|       6 | Servicio de la Deuda Publica y Disminucion de Otros Pasivos |
|       7 | Transferencias                                              |
|       8 | Impuestos, Regalias y Tasas                                 |
|       9 | Otros Gastos                                                |

Correcciones:
* Totales de programas difieren de la suma de los items que los componen, para corregir esto agregue dos identificadores de proyectos especiales que agregan la diferencia, `-1` para desconocido general y `-1000` para desconocido en proyectos de inversion.
* Para expandir los presupuestos de algunas instituciones (por ahora solo el TGN) sin aumentar un nivel a la estructura programatica, cree proyectos virtuales (-10 - codigo_actividad) y reemplace el codigo de actividad por el nuevo identificador (codigo de entidad), esto esta en borrador.

TODO:
* Detalle del TGN 2017
* Agregar archivos con metadatos
