# Code challenge validar el código postal

## Dado un json que contiene lo siguiente:
```
{
	“codigoPostal” : “45110”,
	“Impuestos”: {
		“tasa”: 0.08,
		“tipo”: “traslado”
    }
}
```

## Business Rules: 

1.- El valor de codigoPostal debe existir en el catálogo de códigos postales.
2.- El valor de Impuestos.tasa es permitido de acuerdo al catálogo de  códigos postales.

catálogo códigos postales:
```
[
    {
        “codigoPostal” : “45110”,
        “impuestosPermitidos” : [
            {
                “tasa” : 0.16,
                “tipo” : “traslado”
            }  
        ]
    },
    {
        “codigoPostal” : “45058”,
        “impuestosPermitidos” : [
            {
                “tasa” : 0.08,
                “tipo” : “traslado”
            }  
        ]
    },
    {
        “codigoPostal” : “45058”,
        “impuestosPermitidos” : [
            {
                “tasa” : 0.16,
                “tipo” : “traslado”
            }  
        ]
    }
]
```
