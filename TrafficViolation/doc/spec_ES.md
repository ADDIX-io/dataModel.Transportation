<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
Entidad: TrafficViolation  
=========================<!-- /10-Header -->  
<!-- 15-License -->  
[Licencia abierta](https://github.com/smart-data-models//dataModel.Transportation/blob/master/TrafficViolation/LICENSE.md)  
[documento generado automáticamente](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
Descripción global: **Modelo de datos para las infracciones de tráfico registradas y los E-Challans generados en las ciudades.**  
versión: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## Lista de propiedades  

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>  
- `address[object]`: La dirección postal  . Model: [https://schema.org/address](https://schema.org/address)- `alternateName[string]`: Un nombre alternativo para este artículo  - `amountCollected[number]`: Importe recaudado por el servicio correspondiente a esta observación.  . Model: [https://schema.org/Number](https://schema.org/Number)- `areaServed[string]`: La zona geográfica en la que se presta un servicio o se ofrece un artículo  . Model: [https://schema.org/Text](https://schema.org/Text)- `dataProvider[string]`: Una secuencia de caracteres que identifica al proveedor de la entidad de datos armonizada.  - `dateCreated[string]`: Marca de tiempo de creación de la entidad. Suele ser asignada por la plataforma de almacenamiento.  - `dateModified[string]`: Marca de tiempo de la última modificación de la entidad. Normalmente será asignada por la plataforma de almacenamiento.  - `description[string]`: Una descripción de este artículo  - `equipmentId[string]`: Id. único del equipo correspondiente a esta observación.  . Model: [https://schema.org/Text](https://schema.org/Text)- `equipmentType[string]`: Tipo de equipo o el nombre del equipo correspondiente a esta observación.  . Model: [https://schema.org/Text](https://schema.org/Text)- `id[*]`: Identificador único de la entidad  - `location[*]`: Referencia Geojson al elemento. Puede ser Point, LineString, Polygon, MultiPoint, MultiLineString o MultiPolygon  - `mediaURL[string]`: URL que proporciona más información de cualquier imagen o medio de comunicación de la denuncia o el lugar.  . Model: [https://schema.org/URL](https://schema.org/URL)- `name[string]`: El nombre de este artículo.  - `observationDateTime[string]`: Última hora de observación comunicada.  . Model: [https://schema.org/Text](https://schema.org/Text)- `owner[array]`: Una lista que contiene una secuencia de caracteres codificada en JSON que hace referencia a los identificadores únicos de los propietarios  - `paymentStatus[string]`:  El estado de pago de la multa o de la infracción o de la impugnación correspondiente a esta observación. Enum:'Pagado, No pagado'.  . Model: [https://schema.org/Text](https://schema.org/Text)- `reportId[string]`: Id. único asignado a la incidencia o informe o retroalimentación o transacción correspondiente a esta observación.  . Model: [https://schema.org/Text](https://schema.org/Text)- `seeAlso[*]`: lista de uri que apuntan a recursos adicionales sobre el artículo  - `source[string]`: Una secuencia de caracteres que indica la fuente original de los datos de la entidad en forma de URL. Se recomienda que sea el nombre de dominio completo del proveedor de origen, o la URL del objeto de origen.  - `titleCode[string]`: El código asignado al título correspondiente a esta observación.  . Model: [https://schema.org/Text](https://schema.org/Text)- `type[string]`: Tipo de entidad NGSI. Tiene que ser TrafficViolation.  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
Propiedades requeridas  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## Descripción del modelo de datos de las propiedades  
Ordenados alfabéticamente (haga clic para ver los detalles)  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
TrafficViolation:    
  description: 'A Data Model for Traffic Violations registered and E-Challans generated in Cities.'    
  properties:    
    address:    
      description: 'The mailing address'    
      properties:    
        addressCountry:    
          description: 'Property. The country. For example, Spain. Model:''https://schema.org/addressCountry'''    
          type: string    
        addressLocality:    
          description: 'Property. The locality in which the street address is, and which is in the region. Model:''https://schema.org/addressLocality'''    
          type: string    
        addressRegion:    
          description: 'Property. The region in which the locality is, and which is in the country. Model:''https://schema.org/addressRegion'''    
          type: string    
        postOfficeBoxNumber:    
          description: 'Property. The post office box number for PO box addresses. For example, 03578. Model:''https://schema.org/postOfficeBoxNumber'''    
          type: string    
        postalCode:    
          description: 'Property. The postal code. For example, 24004. Model:''https://schema.org/https://schema.org/postalCode'''    
          type: string    
        streetAddress:    
          description: 'Property. The street address. Model:''https://schema.org/streetAddress'''    
          type: string    
      type: object    
      x-ngsi:    
        model: https://schema.org/address    
        type: Property    
    alternateName:    
      description: 'An alternative name for this item'    
      type: string    
      x-ngsi:    
        type: Property    
    amountCollected:    
      description: 'Amount collected towards the service corresponding to this observation.'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    areaServed:    
      description: 'The geographic area where a service or offered item is provided'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    dataProvider:    
      description: 'A sequence of characters identifying the provider of the harmonised data entity.'    
      type: string    
      x-ngsi:    
        type: Property    
    dateCreated:    
      description: 'Entity creation timestamp. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    dateModified:    
      description: 'Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    description:    
      description: 'A description of this item'    
      type: string    
      x-ngsi:    
        type: Property    
    equipmentId:    
      description: 'Unique Id of the equipment corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    equipmentType:    
      description: 'Type of equipment or the name of the equipment corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    id:    
      anyOf: &trafficviolation_-_properties_-_owner_-_items_-_anyof    
        - description: 'Property. Identifier format of any NGSI entity'    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
        - description: 'Property. Identifier format of any NGSI entity'    
          format: uri    
          type: string    
      description: 'Unique identifier of the entity'    
      x-ngsi:    
        type: Property    
    location:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
      oneOf:    
        - description: 'Geoproperty. Geojson reference to the item. Point'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                type: number    
              minItems: 2    
              type: array    
            type:    
              enum:    
                - Point    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON Point'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. LineString'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              minItems: 2    
              type: array    
            type:    
              enum:    
                - LineString    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON LineString'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. Polygon'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 4    
                type: array    
              type: array    
            type:    
              enum:    
                - Polygon    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON Polygon'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. MultiPoint'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiPoint    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiPoint'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. MultiLineString'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 2    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiLineString    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiLineString'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. MultiLineString'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    items:    
                      type: number    
                    minItems: 2    
                    type: array    
                  minItems: 4    
                  type: array    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiPolygon    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiPolygon'    
          type: object    
      x-ngsi:    
        type: Geoproperty    
    mediaURL:    
      description: 'URL providing further information of any image(s) or media of the complaint or place.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/URL    
        type: Property    
    name:    
      description: 'The name of this item.'    
      type: string    
      x-ngsi:    
        type: Property    
    observationDateTime:    
      description: 'Last reported time of observation.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    owner:    
      description: 'A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)'    
      items:    
        anyOf: *trafficviolation_-_properties_-_owner_-_items_-_anyof    
        description: 'Property. Unique identifier of the entity'    
      type: array    
      x-ngsi:    
        type: Property    
    paymentStatus:    
      description: ' The payment status of the fine or violation or challan corresponding to this observation. Enum:''Paid, Unpaid''.'    
      enum:    
        - Paid    
        - Unpaid    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    reportId:    
      description: 'Unique Id assigned for the issue or report or feedback or transaction corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    seeAlso:    
      description: 'list of uri pointing to additional resources about the item'    
      oneOf:    
        - items:    
            format: uri    
            type: string    
          minItems: 1    
          type: array    
        - format: uri    
          type: string    
      x-ngsi:    
        type: Property    
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: string    
      x-ngsi:    
        type: Property    
    titleCode:    
      description: 'The code assigned to the title corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    type:    
      description: 'NGSI entity type. It has to be TrafficViolation.'    
      enum:    
        - TrafficViolation    
      type: string    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2021 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.Transportation/blob/master/TrafficViolation/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.Transportation/TrafficViolations/schema.json    
  x-model-tags: IUDX    
  x-version: 0.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## Ejemplo de carga útil  
#### TrafficViolation NGSI-v2 key-values Ejemplo  
Aquí hay un ejemplo de una TrafficViolation en formato JSON-LD como valores-clave. Esto es compatible con NGSI-v2 cuando se utiliza `options=keyValues` y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "ngsi-ld:Trafficviolation:234R:0212",  
  "type": "TrafficViolation",  
  "amountCollected": 10500,  
  "mediaURL": "https://www.google.com/",  
  "equipmentId": "4",  
  "equipmentType": "Camera",  
  "titleCode": "11",  
  "reportId": "182",  
  "observationDateTime": "2021-03-11T15:51:02+05:30",  
  "paymentStatus": "Paid"  
}  
```  
</details>  
#### TrafficViolation NGSI-v2 normalizado Ejemplo  
He aquí un ejemplo de una TrafficViolation en formato JSON-LD normalizado. Esto es compatible con NGSI-v2 cuando no se utilizan opciones y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "ngsi-ld:Trafficviolation:234R:0212",  
  "type": "TrafficViolation",  
  "amountCollected": {  
    "type": "number",  
    "value": 10500  
  },  
  "mediaURL": {  
    "type": "Text",  
    "value": "https://www.google.com/"  
  },  
  "equipmentId": {  
    "type": "Text",  
    "value": "4"  
  },  
  "equipmentType": {  
    "type": "Text",  
    "value": "Camera"  
  },  
  "titleCode": {  
    "type": "Text",  
    "value": "11"  
  },  
  "reportId": {  
    "type": "Text",  
    "value": "182"  
  },  
  "observationDateTime": {  
    "type": "DateTime",  
    "value": "2021-03-11T15:51:02+05:30"  
  },  
  "paymentStatus": {  
    "type": "Text",  
    "value": "Paid"  
  },  
  "@context": [  
    "https://smartdatamodels.org/context.jsonld"  
  ]  
}  
```  
</details>  
#### TrafficViolation NGSI-LD key-values Ejemplo  
Aquí hay un ejemplo de una TrafficViolation en formato JSON-LD como valores-clave. Esto es compatible con NGSI-LD cuando se utiliza `options=keyValues` y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "ngsi-ld:Trafficviolation:234R:0212",  
    "type": "TrafficViolation",  
    "amountCollected": 10500,  
    "equipmentId": "4",  
    "equipmentType": "Camera",  
    "mediaURL": "https://www.google.com/",  
    "observationDateTime": "2021-03-11T15:51:02+05:30",  
    "paymentStatus": "Paid",  
    "reportId": "182",  
    "titleCode": "11",  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.Transportation/master/context.jsonld"  
    ]  
}  
```  
</details>  
#### Violación del tráfico NGSI-LD normalizado Ejemplo  
Este es un ejemplo de una TrafficViolation en formato JSON-LD normalizado. Esto es compatible con NGSI-LD cuando no se utilizan opciones y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "ngsi-ld:Trafficviolation:234R:0212",  
    "type": "TrafficViolation",  
    "amountCollected": {  
        "type": "Property",  
        "value": 10500  
    },  
    "equipmentId": {  
        "type": "Property",  
        "value": "4"  
    },  
    "equipmentType": {  
        "type": "Property",  
        "value": "Camera"  
    },  
    "mediaURL": {  
        "type": "Property",  
        "value": "https://www.google.com/"  
    },  
    "observationDateTime": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-03-11T15:51:02+05:30"  
        }  
    },  
    "paymentStatus": {  
        "type": "Property",  
        "value": "Paid"  
    },  
    "reportId": {  
        "type": "Property",  
        "value": "182"  
    },  
    "titleCode": {  
        "type": "Property",  
        "value": "11"  
    },  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.Transportation/master/context.jsonld"  
    ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
Consulte [FAQ 10](https://smartdatamodels.org/index.php/faqs/) para obtener una respuesta sobre cómo tratar las unidades de magnitud  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
