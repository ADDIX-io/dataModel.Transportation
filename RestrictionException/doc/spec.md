Entity: RestrictionException  
============================  
[Open License](https://github.com/smart-data-models//dataModel.Transportation/blob/master/RestrictionException/LICENSE.md)  
Global description: **A Restriction Exception represents a particular case that specialise restriction reported in a Restricted Traffic Areas; for instance it could describe particular permissions applied to specific kind vehicles**  

## List of properties  

- `address`: The mailing address  - `allowedVehicleType`: Vehicle type(s) allowed to cross the restricted traffic area.  - `alternateName`: An alternative name for this item  - `areaServed`: The geographic area where a service or offered item is provided  - `dataProvider`: A sequence of characters identifying the provider of the harmonised data entity.  - `dateCreated`: Entity creation timestamp. This will usually be allocated by the storage platform.  - `dateModified`: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.  - `description`: A description of this item  - `exceptionValidityHours`: Days of the week and hours in which the exception is valid  - `id`: Unique identifier of the entity  - `location`:   - `name`: The name of this item.  - `owner`: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)  - `refRestrictedTrafficArea`: The Restricted Traffic Area this exception belongs.  - `refVehicleModel`: Specify characteristics of the vehicle for which the exception has been established  - `seeAlso`: list of uri pointing to additional resources about the item  - `source`: A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.  - `type`: NGSI Entity type. It has to be RestrictionException    
Required properties  
- `allowedVehicleType`  - `id`  - `refRestrictedTrafficArea`  - `type`    
Data model coming from synchronicity project  
## Data Model description of properties  
Sorted alphabetically (click for details)  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
RestrictionException:    
  description: 'A Restriction Exception represents a particular case that specialise restriction reported in a Restricted Traffic Areas; for instance it could describe particular permissions applied to specific kind vehicles'    
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
        areaServed:    
          description: 'Property. The geographic area where a service or offered item is provided. Model:''https://schema.org/areaServed'''    
          type: string    
        postOfficeBoxNumber:    
          description: 'Property. The post office box number for PO box addresses. For example, Spain. Model:''https://schema.org/postOfficeBoxNumber'''    
          type: string    
        postalCode:    
          description: 'Property. The postal code. For example, Spain. Model:''https://schema.org/https://schema.org/postalCode'''    
          type: string    
        streetAddress:    
          description: 'Property. The street address. Model:''https://schema.org/streetAddress'''    
          type: string    
      type: Property    
      x-ngsi:    
        model: https://schema.org/address    
    allowedVehicleType:    
      description: 'Vehicle type(s) allowed to cross the restricted traffic area.'    
      items:    
        enum:    
          - anyVehicle    
          - agriculturalVehicle    
          - bicycle    
          - bus    
          - car    
          - caravan    
          - carWithCaravan    
          - carWithTrailer    
          - constructionOrMaintenanceVehicle    
          - dieselCarEuro0    
          - dieselCarEuro1    
          - dieselCarEuro2    
          - dieselCarEuro3    
          - dieselCarEuro4    
          - dieselCarEuro5a    
          - dieselCarEuro5b    
          - dieselCarEuro6    
          - freightTransportVehicle    
          - lorry    
          - moped    
          - motorcycle    
          - motorcycleWithSideCar    
          - motorscooter    
          - petrolCarEuro0    
          - petrolCarEuro1    
          - petrolCarEuro2    
          - petrolCarEuro3    
          - petrolCarEuro4    
          - petrolCarEuro5    
          - petrolCarEuro6    
          - tanker    
          - trailer    
          - van    
        type: string    
      minItems: 1    
      type: Property    
      uniqueItems: true    
    alternateName:    
      description: 'An alternative name for this item'    
      type: Property    
    areaServed:    
      description: 'The geographic area where a service or offered item is provided'    
      type: Property    
      x-ngsi:    
        model: https://schema.org/Text    
    dataProvider:    
      description: 'A sequence of characters identifying the provider of the harmonised data entity.'    
      type: Property    
    dateCreated:    
      description: 'Entity creation timestamp. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: Property    
    dateModified:    
      description: 'Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: Property    
    description:    
      description: 'A description of this item'    
      type: Property    
    exceptionValidityHours:    
      description: 'Days of the week and hours in which the exception is valid'    
      type: Property    
      x-ngsi:    
        model: 'http://schema.org/openingHours '    
    id:    
      anyOf: &restrictionexception_-_properties_-_owner_-_items_-_anyof    
        - description: 'Property. Identifier format of any NGSI entity'    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
        - description: 'Property. Identifier format of any NGSI entity'    
          format: uri    
          type: string    
      description: 'Unique identifier of the entity'    
      type: Property    
    location:    
      $id: https://geojson.org/schema/Geometry.json    
      $schema: "http://json-schema.org/draft-07/schema#"    
      oneOf:    
        - properties:    
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
        - properties:    
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
        - properties:    
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
        - properties:    
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
        - properties:    
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
        - properties:    
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
      title: 'GeoJSON Geometry'    
    name:    
      description: 'The name of this item.'    
      type: Property    
    owner:    
      description: 'A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)'    
      items:    
        anyOf: *restrictionexception_-_properties_-_owner_-_items_-_anyof    
        description: 'Property. Unique identifier of the entity'    
      type: Property    
    refRestrictedTrafficArea:    
      anyOf:    
        - description: 'Property. Identifier format of any NGSI entity'    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
        - description: 'Property. Identifier format of any NGSI entity'    
          format: uri    
          type: string    
      description: 'The Restricted Traffic Area this exception belongs.'    
      type: Property    
    refVehicleModel:    
      description: 'Specify characteristics of the vehicle for which the exception has been established'    
      items:    
        anyOf: *restrictionexception_-_properties_-_owner_-_items_-_anyof    
        description: 'Property. Unique identifier of the entity'    
      type: Property    
    seeAlso:    
      description: 'list of uri pointing to additional resources about the item'    
      oneOf:    
        - items:    
            - format: uri    
              type: string    
          minItems: 1    
          type: array    
        - format: uri    
          type: string    
      type: Property    
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: Property    
    type:    
      description: 'NGSI Entity type. It has to be RestrictionException'    
      enum:    
        - RestrictionException    
      type: Property    
  required:    
    - id    
    - type    
    - allowedVehicleType    
    - refRestrictedTrafficArea    
  type: object    
```  
</details>    
## Example payloads    
#### RestrictionException NGSI V2 key-values Example    
Here is an example of a RestrictionException in JSON format as key-values. This is compatible with NGSI V2 when  using `options=keyValues` and returns the context data of an individual entity.  
```json  
{  
  "id": "urn:ngsi-ld:RestrictedTrafficArea:Milan:RestrictionException:GeoJson:ds51-1",  
  "type": "RestrictionException",  
  "name": "Corso Concordia Area",  
  "allowedVehicleType": [  
    "dieselCarEuro6",  
    "petrolCarEuro6"  
  ],  
  "exceptionValidityHours": "Tu,Th 16:00-20:00",  
  "refVehicleModel": [  
    "vehicle:VehicleModel:modelName-1"  
  ],  
  "refRestrictedTrafficArea": "urn:ngsi-ld:RestrictedTrafficArea:Milan:RestrictedTrafficAreas:GeoJson:ds51-1"  
}  
```  
#### RestrictionException NGSI V2 normalized Example    
Here is an example of a RestrictionException in JSON format as normalized. This is compatible with NGSI V2 when not using options and returns the context data of an individual entity.  
```json  
{  
  "id": "urn:ngsi-ld:RestrictedTrafficArea:Milan:RestrictionException:GeoJson:ds51-1",  
  "type": "RestrictionException",  
  "name": {  
    "type": "string",  
    "value": "Corso Concordia Area"  
  },  
  "allowedVehicleType": {  
    "type": "array",  
    "value": [  
      "dieselCarEuro6",  
      "petrolCarEuro6"  
    ]  
  },  
  "exceptionValidityHours": {  
    "type": "string",  
    "value": "Tu,Th 16:00-20:00"  
  },  
  "refVehicleModel": {  
    "type": "string",  
    "Object": "vehicle:VehicleModel:modelName-1"  
  },  
  "refRestrictedTrafficArea": {  
    "type": "string",  
    "Object": "urn:ngsi-ld:RestrictedTrafficArea:Milan:RestrictedTrafficAreas:GeoJson:ds51-1"  
  }  
}  
```  
#### RestrictionException NGSI-LD key-values Example    
Here is an example of a RestrictionException in JSON-LD format as key-values. This is compatible with NGSI-LD when  using `options=keyValues` and returns the context data of an individual entity.  
```json  
{  
  "id": "urn:ngsi-ld:RestrictedTrafficArea:Milan:RestrictionException:GeoJson:ds51-1",  
  "type": "RestrictionException",  
  "name": "Corso Concordia Area",  
  "allowedVehicleType": [  
    "dieselCarEuro6",  
    "petrolCarEuro6"  
  ],  
  "exceptionValidityHours": "Tu,Th 16:00-20:00",  
  "refVehicleModel": [  
    "vehicle:VehicleModel:modelName-1"  
  ],  
  "refRestrictedTrafficArea": "urn:ngsi-ld:RestrictedTrafficArea:Milan:RestrictedTrafficAreas:GeoJson:ds51-1",  
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/data-models/master/context.jsonld"  
  ]  
}  
```  
#### RestrictionException NGSI-LD normalized Example    
Here is an example of a RestrictionException in JSON-LD format as normalized. This is compatible with NGSI-LD when not using options and returns the context data of an individual entity.  
```json  
{  
  "id": "urn:ngsi-ld:RestrictedTrafficArea:Milan:RestrictionException:GeoJson:ds51-1",  
  "type": "RestrictionException",  
  "name": {  
    "type": "string",  
    "value": "Corso Concordia Area"  
  },  
  "allowedVehicleType": {  
    "type": "array",  
    "value": [  
      "dieselCarEuro6",  
      "petrolCarEuro6"  
    ]  
  },  
  "exceptionValidityHours": {  
    "type": "string",  
    "value": "Tu,Th 16:00-20:00"  
  },  
  "refVehicleModel": {  
    "type": "string",  
    "Object": "vehicle:VehicleModel:modelName-1"  
  },  
  "refRestrictedTrafficArea": {  
    "type": "string",  
    "Object": "urn:ngsi-ld:RestrictedTrafficArea:Milan:RestrictedTrafficAreas:GeoJson:ds51-1"  
  },  
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/data-models/master/context.jsonld"  
  ]  
}  
```  
