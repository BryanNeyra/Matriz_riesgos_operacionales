# Matriz_riesgos_operacionales
Proyecto de gestión de riesgos operacionales: matriz de 10 riesgos con escalas basadas en ISO 31000, cálculo de riesgo inherente y residual, mapa de calor y plan de acción. Herramientas: Excel.

##Contexto 
Este proyecto muestra como identifico, evalùo y priorizo riesgos operacionales en un proceso de atención de reclamos.El caso es ficticio "Financiera Andina S.A" es una entidad inventada, con datos simulados para el ejercicio.
Alcance del proceso: Desde que el cliente registra un reclamo por cualquier canal(app,call center o agencia) hasta que reciba la respuesta.

##Supuestos 
*Entidad regula por la SBS, con cartera de créditos de consumo y pyme.
*Volumen estimado: 1200 reclamos al mes
*Plazo de respuesta: 30 dias calendario, según el Reglamento de Transparencia de Información y Protección al Usuario.Verifica el plazo vigente antes de publicar.
*Los controles y calificaciones de efectividad son una evaluación propia para el ejercicio , no una auditoria real. 

##Metodología
Usé ISO 31000 como referencia general.Cada riesgo se evalúa con:
*Probabilidad(1 a 5):frecuencia anual estimada
*Impacto(1 a 5):perdida economica o regulatoria 
*Riesgo inherente = probabilidad x impacto 
*Riesgo residual= riesgo inherente ajustado por la efectividad del control existente (Efectivo reduce cerca de la mitad, Parcial reduce un 30% ineficaz y ausente no reducen).         

Clasificación:1-4 bajo,5-9 medio, 10-16 alto, 20-25 critico

Las escalas completas están en la hoja Escalas del libro

##Resultados principales 
1.R06 es el único riesgo alto residual.La revisión por muestreo del 10% no detecta suficientes errores en las respuesta.Recomiendo ampliar la revisión a un segundo nivel para todas las respuestas con monto o datos sensibles.
2.Los riesgos de capacitación y de derivación(R02 Y R03) bajan a nivel medio con el control actual, pero siguen cerca del umbral alto.Conviene reforzarlos antes de que aumente el volumen.
3.R09(dependencia de un solo analista) no tienes control formal.Es un riesgo de bajo costo de mitigar:basta documentar casos complejos y definir un suplente.

##Estructura del repositorio
matriz-riesgos-reclamos/
├── README.md
├── matriz_riesgos_reclamos.xlsx
├── outputs/
│   └── mapa_calor.png
└── docs/
    └── supuestos.md

#Como usasr el archivo 
1.Abre matriz_riesgos_reclamos.xlsx en Excel o Google Sheets
2.Revisa la hoja de Escalas para entender los criterios
3.En evaluación , cambia probabilidad, impacto o control:el nivel se recalcula solo
4.Revisa el Mapa de calor y el Plan de Acción 

#Herramientas
*Microsoft Excel (o Google Shetts)
*Formato condicional, validación de datos, BUSCARV o XLOOKUP y CONTAR.SI 

#Proximos pasos 
*Ampliar el catálogo con riesgos de tecnologia y fraude
*Vincular los riesgos con indicadores (KRI) en el proyecto 2.

*
