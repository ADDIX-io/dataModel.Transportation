<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
エンティティBikeHireDockingStation  
============================<!-- /10-Header -->  
<!-- 15-License -->  
[オープンライセンス](https://github.com/smart-data-models//dataModel.Transportation/blob/master/BikeHireDockingStation/LICENSE.md)  
[ドキュメント自動生成](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
グローバルな説明**自転車レンタル用ドッキングステーション  
バージョン: 0.1.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## プロパティ一覧  

<sup><sub>[*] 属性にタイプがない場合、複数のタイプまたは異なるフォーマット/パターンを持つ可能性があるためです</sub></sup>。  
- `address[object]`: 郵送先住所  . Model: [https://schema.org/address](https://schema.org/address)- `agency_fare_url[string]`: 運賃の詳細が記載され、その代理店のチケットをオンラインで購入することができるウェブページのURL。と同じです。GTFS Static Field Definition - agency.txt (https://developers.google.com/transit/gtfs/reference#agencytxt) にある 'agency_fare_url' フィールド。  - `agency_name[string]`: agency_name フィールドには、交通機関のフルネームが含まれる。SameAs。GTFS Static Field Definition - agency.txt (https://developers.google.com/transit/gtfs/reference#agencytxt) にある 'agency_name' フィールド。  . Model: [https://schema.org/Text](https://schema.org/Text)- `agency_url[string]`: agency_url フィールドには、交通機関の URL が含まれます。同上。GTFS Static Field Definition - agency.txt (https://developers.google.com/transit/gtfs/reference#agencytxt) にある 'agency_url' フィールド。  . Model: [https://schema.org/Text](https://schema.org/Text)- `alternateName[string]`: この項目の別称  - `areaServed[string]`: サービスまたは提供品が提供される地理的な地域  . Model: [https://schema.org/Text](https://schema.org/Text)- `availableBikeNumber[integer]`: 利用者がレンタルできる自転車ドッキングステーションにある自転車の台数  . Model: [https://schema.org/Number.](https://schema.org/Number.)- `contactPoint[object]`: 商品に関するお問い合わせ先です。  . Model: [https://schema.org/ContactPoint](https://schema.org/ContactPoint)- `dataProvider[string]`: 調和されたデータエンティティの提供者を識別する一連の文字。  - `dateCreated[string]`: エンティティの作成タイムスタンプ。これは通常、ストレージプラットフォームによって割り当てられる。  - `dateModified[string]`: エンティティの最終更新のタイムスタンプ。これは通常、ストレージプラットフォームによって割り当てられる。  - `description[string]`: このアイテムの説明  - `freeSlotNumber[integer]`: 自転車を返却・駐輪するために利用できるスロットの数。totalSlotNumber`以下でなければならない。  . Model: [https://schema.org/Number.](https://schema.org/Number.)- `id[*]`: エンティティの一意な識別子  - `location[*]`: アイテムへの Geojson リファレンス。Point, LineString, Polygon, MultiPoint, MultiLineString, MultiPolygonのいずれかを指定することができる。  - `mediaURL[string]`: 苦情や場所に関する画像やメディアなどの詳細情報を提供するURL。  . Model: [https://schema.org/Text](https://schema.org/Text)- `name[string]`: このアイテムの名称です。  - `observationDateTime[string]`: 最後に報告された観測時刻。  . Model: [https://schema.org/Text](https://schema.org/Text)- `openingHours[string]`: ドッキングステーションの営業時間  . Model: [http://schema.org/openingHours.](http://schema.org/openingHours.)- `outOfServiceSlotNumber[integer]`: 自転車のレンタルや駐輪に使用できない、故障中のスロット数です。totalSlotNumber`以下でなければなりません。  . Model: [https://schema.org/Number.](https://schema.org/Number.)- `owner[array]`: 所有者の一意のIDを参照するJSONエンコードされた文字列を含むリスト  - `provider[string]`: 自転車レンタルサービス事業者  . Model: [https://schema.org/provider.](https://schema.org/provider.)- `seeAlso[*]`: 項目に関する追加リソースを指すURIのリスト。  - `source[string]`: エンティティデータの元のソースをURLで示す一連の文字。ソースプロバイダの完全修飾ドメイン名、またはソースオブジェクトのURLであることが推奨されます。  - `stationCode[string]`: 観測に対応するレンタサイクルのドッキングステーションのステーション番号またはステーションコード。  . Model: [https://schema.org/Text](https://schema.org/Text)- `stationName[string]`: この観測に対応するレンタサイクルのドッキングステーションの名前。  . Model: [https://schema.org/Text](https://schema.org/Text)- `status[string]`: レンタサイクルのドッキングステーションの状態。Enum:'working, outOfService, withIncidence, full, almostFull, empty, almostEmpty'（稼働中、outOfService、withIncidence、満杯、almostFull、空っぽ）。または、その他のアプリケーション固有のもの。  . Model: [https://schema.org/Number](https://schema.org/Number)- `totalSlotNumber[integer]`: この自転車ドッキングステーションが提供する総スロット数  . Model: [https://schema.org/Number.](https://schema.org/Number.)- `type[string]`: NGSI Entity タイプ。BikeHireDockingStationでなければならない。  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
必要なプロパティ  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
多くの都市では、市民のために自転車のレンタルシステムを提供しています。多くの都市が市民向けに自転車レンタルシステムを提供しており、様々な契約形態で自転車を借りることができる。レンタサイクルのドッキングステーションでは、契約したユーザーが自転車を借りたり、返したりすることができます。その主な機能と自転車や無料スロットの可用性に関するデータを提供します。  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## プロパティのデータモデル記述  
アルファベット順に並びます（クリックで詳細へ）  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
BikeHireDockingStation:    
  description: 'Bike Hire Docking Station'    
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
    agency_fare_url:    
      description: "URL of a web page that contains the details of the fares and also could allow to purchase tickets for that agency online. SameAs: 'agency_fare_url' field from GTFS Static Field Definition - agency.txt (https://developers.google.com/transit/gtfs/reference#agencytxt) "    
      type: string    
      x-ngsi:    
        type: Property    
    agency_name:    
      description: "The agency_name field contains the full name of the transit agency. SameAs: 'agency_name' field from GTFS Static Field Definition - agency.txt (https://developers.google.com/transit/gtfs/reference#agencytxt)"    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    agency_url:    
      description: "The agency_url field contains the URL of the transit agency. SameAs: 'agency_url' field from GTFS Static Field Definition - agency.txt (https://developers.google.com/transit/gtfs/reference#agencytxt)"    
      format: uri    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    alternateName:    
      description: 'An alternative name for this item'    
      type: string    
      x-ngsi:    
        type: Property    
    areaServed:    
      description: 'The geographic area where a service or offered item is provided'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    availableBikeNumber:    
      description: 'The number of bikes available in the bike hire docking station to be hired by users'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number.    
        type: Property    
    contactPoint:    
      description: 'The details to contact with the item.'    
      properties:    
        contactType:    
          description: 'Property. Contact type of this item.'    
          type: string    
        email:    
          description: 'Property. Email address of owner.'    
          format: idn-email    
          type: string    
        name:    
          description: 'Property. The name of this item.'    
          type: string    
        telephone:    
          description: 'Property. Telephone of this contact.'    
          type: string    
        url:    
          description: 'Property. URL which provides a description or further information about this item.'    
          format: uri    
          type: string    
      type: object    
      x-ngsi:    
        model: https://schema.org/ContactPoint    
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
    freeSlotNumber:    
      description: 'The number of slots available for returning and parking bikes. It must lower or equal than `totalSlotNumber`'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number.    
        type: Property    
    id:    
      anyOf: &bikehiredockingstation_-_properties_-_owner_-_items_-_anyof    
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
      format: uri    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
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
    openingHours:    
      description: 'Opening hours of the docking station'    
      type: string    
      x-ngsi:    
        model: http://schema.org/openingHours.    
        type: Property    
    outOfServiceSlotNumber:    
      description: 'The number of slots that are out of order and cannot be used to hire or park a bike. It must lower or equal than `totalSlotNumber`'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number.    
        type: Property    
    owner:    
      description: 'A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)'    
      items:    
        anyOf: *bikehiredockingstation_-_properties_-_owner_-_items_-_anyof    
        description: 'Property. Unique identifier of the entity'    
      type: array    
      x-ngsi:    
        type: Property    
    provider:    
      description: 'Bike hire service provider'    
      type: string    
      x-ngsi:    
        model: https://schema.org/provider.    
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
    stationCode:    
      description: 'The station number or station code of the bike hire docking station corresponding to the observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    stationName:    
      description: 'The name of the bike hire docking station corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    status:    
      description: 'Status of the bike hire docking station. Enum:''working, outOfService, withIncidence, full, almostFull, empty, almostEmpty''. Or any other application specific.'    
      enum:    
        - almostEmpty    
        - almostFull    
        - empty    
        - full    
        - outOfService    
        - withIncidence    
        - working    
      type: string    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    totalSlotNumber:    
      description: 'The total number of slots offered by this bike docking station'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number.    
        type: Property    
    type:    
      description: 'NGSI Entity type. It has to be BikeHireDockingStation'    
      enum:    
        - BikeHireDockingStation    
      type: string    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2021 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.Transportation/blob/master/BikeHireDockingStation/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.Transportation/BikeHireDockingStation/schema.json    
  x-model-tags: ""    
  x-version: 0.1.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## ペイロードの例  
#### BikeHireDockingStation NGSI-v2 key-value の例。  
BikeHireDockingStationをJSON-LD形式でkey-valuesにした例です。これは、`options=keyValues`を使用した場合にNGSI-v2と互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:Bcn-BikeHireDockingStation-1",  
    "type": "BikeHireDockingStation",  
    "status": "working",  
    "provider": "University of Mumbay",  
    "contactPoint": {  
        "url": "uri:ngsi:www.lignesdazur.com"  
    },  
    "availableBikeNumber": 20,  
    "freeSlotNumber": 10,  
    "openingHours": "Mo-Fr 10:00-19:00, Sa 10:00-22:00, Su 10:00-21:00",  
    "location": {  
        "type": "Point",  
        "coordinates": [  
            2.180042,  
            41.397952  
        ]  
    },  
    "address": {  
        "addressCountry": "ES",  
        "addressLocality": "Barcelona",  
        "streetAddress": "Gran Via Corts Catalanes,760"  
    },  
    "totalSlotNumber": 100,  
    "outOfServiceSlotNumber": 21,  
    "stationName": "Pune",  
    "mediaURL": "http://pedalsaddle.in/",  
    "agency_url": "http://pedalsaddle.in/",  
    "agency_name": "PedalSaddle",  
    "stationCode": "2",  
    "observationDate": "2021-03-11T15:51:02+05:30",  
    "agency_fare_url": ""  
}  
```  
</details>  
#### BikeHireDockingStation NGSI-v2 正規化例  
以下は、BikeHireDockingStation を JSON-LD 形式で正規化した例である。これは、オプションを使用しない場合、NGSI-v2と互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:Bcn-BikeHireDockingStation-1",  
  "type": "BikeHireDockingStation",  
  "status": {  
    "type": "Text",  
    "value": "working"  
  },  
  "provider": {  
    "type": "Text",  
    "value": "University of Mumbay"  
  },  
  "contactPoint": {  
    "type": "StructuredValue",  
    "value": {  
      "url": "uri:ngsi:www.lignesdazur.com"  
    }  
  },  
  "availableBikeNumber": {  
    "type": "Number",  
    "value": 20  
  },  
  "freeSlotNumber": {  
    "type": "Number",  
    "value": 10  
  },  
  "openingHours": {  
    "type": "Text",  
    "value": "Mo-Fr 10:00-19:00, Sa 10:00-22:00, Su 10:00-21:00"  
  },  
  "location": {  
    "type": "geo:json",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        2.180042,  
        41.397952  
      ]  
    }  
  },  
  "address": {  
    "type": "PostalAddress",  
    "value": {  
      "addressCountry": "ES",  
      "addressLocality": "Barcelona",  
      "streetAddress": "Gran Via Corts Catalanes,760"  
    }  
  },  
  "totalSlotNumber": {  
    "type": "Number",  
    "value": 100  
  },  
  "outOfServiceSlotNumber": {  
    "type": "Number",  
    "value": 21  
  },  
  "stationName": {  
    "type": "Text",  
    "value": "Pune"  
  },  
  "mediaURL": {  
    "type": "Text",  
    "value": "http://pedalsaddle.in/"  
  },  
  "agency_url": {  
    "type": "Text",  
    "value": "http://pedalsaddle.in/"  
  },  
  "agency_name": {  
    "type": "Text",  
    "value": "PedalSaddle"  
  },  
  "stationCode": {  
    "type": "Number",  
    "value": "2"  
  },  
  "observationDate": {  
    "type": "DateTime",  
    "value": "2021-03-11T15:51:02+05:30"  
  },  
  "agency_fare_url": {  
    "type": "Text",  
    "value": ""  
  }  
}  
```  
</details>  
#### BikeHireDockingStation NGSI-LD key-value 例  
BikeHireDockingStationをJSON-LD形式でkey-valuesにした例です。これは `options=keyValues` を使用した場合に NGSI-LD と互換性があり、個々のエンティティのコンテキストデータが返される。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:Bcn-BikeHireDockingStation-1",  
    "type": "BikeHireDockingStation",  
    "address": {  
        "addressCountry": "ES",  
        "addressLocality": "Barcelona",  
        "streetAddress": "Gran Via Corts Catalanes,760"  
    },  
    "agency_fare_url": "",  
    "agency_name": "PedalSaddle",  
    "agency_url": "http://pedalsaddle.in/",  
    "availableBikeNumber": 20,  
    "contactPoint": {  
        "url": "uri:ngsi:www.lignesdazur.com"  
    },  
    "freeSlotNumber": 10,  
    "location": {  
        "type": "Point",  
        "coordinates": [  
            2.180042,  
            41.397952  
        ]  
    },  
    "mediaURL": "http://pedalsaddle.in/",  
    "observationDate": "2021-03-11T15:51:02+05:30",  
    "openingHours": "Mo-Fr 10:00-19:00, Sa 10:00-22:00, Su 10:00-21:00",  
    "outOfServiceSlotNumber": 21,  
    "provider": "University of Mumbay",  
    "stationCode": "2",  
    "stationName": "Pune",  
    "status": "working",  
    "totalSlotNumber": 100,  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.Transportation/master/context.jsonld"  
    ]  
}  
```  
</details>  
#### BikeHireDockingStation NGSI-LD 正規化例  
BikeHireDockingStation を JSON-LD 形式で正規化した例です。これはオプションを使用しない場合、NGSI-LDと互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:Bcn-BikeHireDockingStation-1",  
    "type": "BikeHireDockingStation",  
    "address": {  
        "type": "Property",  
        "value": {  
            "addressCountry": "ES",  
            "addressLocality": "Barcelona",  
            "streetAddress": "Gran Via Corts Catalanes,760"  
        }  
    },  
    "agency_fare_url": {  
        "type": "Property",  
        "value": ""  
    },  
    "agency_name": {  
        "type": "Property",  
        "value": "PedalSaddle"  
    },  
    "agency_url": {  
        "type": "Property",  
        "value": "http://pedalsaddle.in/"  
    },  
    "availableBikeNumber": {  
        "type": "Property",  
        "value": 20  
    },  
    "contactPoint": {  
        "type": "Property",  
        "value": {  
            "url": "uri:ngsi:www.lignesdazur.com"  
        }  
    },  
    "freeSlotNumber": {  
        "type": "Property",  
        "value": 10  
    },  
    "location": {  
        "type": "Geoproperty",  
        "value": {  
            "type": "Point",  
            "coordinates": [  
                2.180042,  
                41.397952  
            ]  
        }  
    },  
    "mediaURL": {  
        "type": "Property",  
        "value": "http://pedalsaddle.in/"  
    },  
    "observationDate": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-03-11T15:51:02+05:30"  
        }  
    },  
    "openingHours": {  
        "type": "Property",  
        "value": "Mo-Fr 10:00-19:00, Sa 10:00-22:00, Su 10:00-21:00"  
    },  
    "outOfServiceSlotNumber": {  
        "type": "Property",  
        "value": 21  
    },  
    "provider": {  
        "type": "Property",  
        "value": "University of Mumbay"  
    },  
    "stationCode": {  
        "type": "Property",  
        "value": "2"  
    },  
    "stationName": {  
        "type": "Property",  
        "value": "Pune"  
    },  
    "status": {  
        "type": "Property",  
        "value": "working"  
    },  
    "totalSlotNumber": {  
        "type": "Property",  
        "value": 100  
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
マグニチュード単位の扱いについては、[FAQ 10](https://smartdatamodels.org/index.php/faqs/)を参照してください。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
