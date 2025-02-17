# bo-presupuestos
Presupuestos del estado boliviano

* Fuente: [Sigma](https://portal.sigep.gob.bo/index.php/2016/05/09/ley-financial/); [Sigep](https://sigep.gob.bo/sigep_publico/faces/SFprRepPub?gestion=2020)
* Tipo Reporte: Detalle Institucional > Presupuesto institucional por categoria programatica
* Dump: [Reportes en PDF](https://drive.google.com/drive/folders/1JOL-Rh20rYxtqp79tYARwulLGAFbWZhh?usp=sharing)

Correcciones:
* Totales de programas difieren de la suma de los items que los componen (en los dumps del Sigma), para corregir esto se agrego un identificador de proyecto especial (-1) que agrega la diferencia.

TODO:
* Agregar archivos con metadatos
* Procesar presupuestos de otras entidades (ministerios; empresas publicas; ...)
* Procesar presupuestos de anhos anteriores (el dump de sigma va desde el 2004)
