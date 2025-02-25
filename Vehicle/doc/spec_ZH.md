<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
实体。车辆  
=====<!-- /10-Header -->  
<!-- 15-License -->  
[开放许可](https://github.com/smart-data-models//dataModel.Transportation/blob/master/Vehicle/LICENSE.md)  
[文件自动生成](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
全局描述。**该实体为一个特定的车辆模型建模，包括属于该模型的多个车辆实例所共有的所有属性**。  
版本：0.2.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

##属性列表  

<sup><sub>[*] 如果一个属性中没有一个类型，是因为它可能有几种类型或不同的格式/模式</sub></sup>。  
- `address[object]`: 邮寄地址  . Model: [https://schema.org/address](https://schema.org/address)- `alternateName[string]`: 这个项目的一个替代名称  - `annotations[array]`: 关于该项目的注释  . Model: [https://schema.org/Text](https://schema.org/Text)- `areaServed[string]`: 提供服务或提供项目的地理区域  . Model: [https://schema.org/Text](https://schema.org/Text)- `bearing[number]`: 提供车辆GPS的角度，以顺时针方向从真北测量。与GTFS实时信息-位置(https://developers.google.com/transit/gtfs-realtime/reference#message-position)的 "方位 "字段相同。  . Model: [https://schema.org/Number](https://schema.org/Number)- `cargoWeight[number]`: 车辆货物的当前重量  . Model: [https://schema.org/Number](https://schema.org/Number)- `category[array]`: 从外部角度看车辆类别。这与 "vehicleType "属性所代表的车辆类型（汽车、货车等）不同。枚举：'市政服务，非跟踪，私人，公共，特殊用途，跟踪'。追踪的车辆是那些由远程系统永久追踪位置的车辆。或任何其他应用所需的车辆。它们包括一个GPS接收器和一个网络连接，以定期更新报告的位置（位置、速度、方向...）。  . Model: [https://schema.org/Text](https://schema.org/Text)- `color[string]`: 产品的颜色  . Model: [https://schema.org/color](https://schema.org/color)- `currentTripCount[number]`: 与该观察点相对应的车辆在特定运行日的当前行程数。  . Model: [https://schema.org/Number](https://schema.org/Number)- `dataProvider[string]`: 一串识别统一数据实体提供者的字符。  - `dateCreated[string]`: 实体创建时间戳。这通常会由存储平台分配。  - `dateFirstUsed[string]`: 时间戳，表示车辆首次使用的时间  . Model: [https://schema.org/DateTime.](https://schema.org/DateTime.)- `dateModified[string]`: 实体最后一次修改的时间戳。这通常会由存储平台分配。  - `dateVehicleFirstRegistered[string]`: 车辆在各公共当局首次登记的日期  . Model: [https://schema.org/dateVehicleFirstRegistered.](https://schema.org/dateVehicleFirstRegistered.)- `description[string]`: 对这个项目的描述  - `deviceBatteryStatus[string]`: 给出报告设备的电池充电状态。Enum:'connected, disconnected'.  . Model: [https://schema.org/Text](https://schema.org/Text)- `deviceSimNumber[string]`: 提供车内设备的SIM卡号。  . Model: [https://schema.org/Text](https://schema.org/Text)- `emergencyVehicleType[string]`: 与此观察相对应的紧急车辆的类型。Enum:'policeCar, policeMotorcycle, policeVan, policeSWAT, fireEngine, waterTender, airAmbulance, ambulance, motorcycleAmbulance, rescueVehicle, hazardousMaterialsApparatus, towTruck  . Model: [https://schema.org/Text](https://schema.org/Text)- `feature[array]`: 车辆所具备的功能。Enum:' abs, airbag, alarm, backCamera, disabledRamp, gps, internetConnection, overspeed, proximitySensor, wifi'.或任何其他应用程序需要的。为了表示一个特征的多个实例，可以使用以下语法。`<特征>,<实例>`。例如，一辆有4个安全气囊的汽车将用`airbag,4`表示。  . Model: [https://schema.org/Text](https://schema.org/Text)- `fleetVehicleId[string]`: 该车辆在其所属车队中的标识符。  . Model: [https://schema.org/Text.](https://schema.org/Text.)- `fuelEfficiency[number]`: 每单位燃料的行驶距离，通常以每升公里数（km/L）表示。  . Model: [https://schema.org/Number](https://schema.org/Number)- `fuelFilled[number]`: 与该观察结果相对应的车辆的燃料填充量，单位为升。  . Model: [https://schema.org/Number](https://schema.org/Number)- `fuelType[string]`: 适用于与该观察结果相对应的车辆的发动机或引擎的燃料类型。  . Model: [https://schema.org/Text](https://schema.org/Text)- `heading[*]`: 表示车辆的行驶方向，以小数点后的度数指定，其中0 <= `heading` < 360，相对于真正的北方顺时针计数。如果车辆是静止的（即 "速度 "属性的值为 "0"），那么标题属性的值必须等于 "1"。  . Model: [https://schema.org/Number](https://schema.org/Number)- `id[*]`: 实体的唯一标识符  - `ignitionStatus[boolean]`: 给出车辆的点火状态。真表示已点燃  . Model: [https://schema.org/Boolean](https://schema.org/Boolean)- `image[string]`: 该物品的图像  . Model: [https://schema.org/URL](https://schema.org/URL)- `license_plate[string]`: 提供车辆的车牌号。相同的是：来自GTFS实时消息-车辆描述符（https://developers.google.com/transit/gtfs-realtime/reference#message-vehicledescriptor）的License_plate字段。  . Model: [https://schema.org/Text](https://schema.org/Text)- `location[*]`: 对该项目的Geojson引用。它可以是点、线字符串、多边形、多点、多线字符串或多多边形。  - `mileageFromOdometer[number]`: 从里程表上读取的特定车辆自最初生产以来所走过的总距离  . Model: [https://schema.org/mileageFromOdometer.](https://schema.org/mileageFromOdometer.)- `municipalityInfo[object]`: 与此观察相对应的市镇信息。  . Model: [https://schema.org/Text](https://schema.org/Text)- `name[string]`: 这个项目的名称。  - `observationDateTime[string]`: 最后报告的观察时间  . Model: [https://schema.org/DateTime](https://schema.org/DateTime)- `owner[array]`: 一个包含JSON编码的字符序列的列表，引用所有者的唯一Ids。  - `previousLocation[*]`: 对该项目的Geojson引用。它可以是点、线字符串、多边形、多点、多线字符串或多多边形。  - `purchaseDate[string]`: 该物品的日期，如车辆由当前所有者购买的日期  . Model: [https://schema.org/purchaseDate.](https://schema.org/purchaseDate.)- `refVehicleModel[*]`: 对一个车辆模型的引用  . Model: [https://schema.org/URL](https://schema.org/URL)- `reportId[string]`: 为与此观察相对应的问题、报告、反馈或交易分配的唯一标识。  . Model: [https://schema.org/Text](https://schema.org/Text)- `seeAlso[*]`: 指向有关该项目的其他资源的URI列表  - `serviceOnDuty[string]`: 与该观察结果相对应的紧急车辆所提供的服务的性质。真表示该观察值对应的紧急车辆正在处理/服务于紧急任务召唤，否则为假。  . Model: [https://schema.org/Boolean](https://schema.org/Boolean)- `serviceProvided[array]`: 车辆能够提供的服务或被分配到的服务。枚举："辅助服务，货物运输，建筑，游乐场，垃圾收集，货物销售，维护，公园和花园，道路信号，特殊运输，街道清洁，街道照明，城市交通，废物容器清洁"。或任何其他特定应用所需的值。  . Model: [https://schema.org/Text](https://schema.org/Text)- `serviceStatus[string]`: 车辆状态（从提供服务的角度来看，所以它不能适用于私人车辆）。驻扎"：车辆驻扎，目前不提供任何服务。onRoute`：车辆正在执行任务。可以添加一个逗号分隔的修饰符，以表明当前正在运送车辆的任务。例如，`onRoute,garbageCollection'可以用来表示车辆在路上，并且在进行垃圾收集任务。'broken' :车辆正在遭受临时故障。outOfService"：车辆在路上，但没有执行任何任务，可能是去了它的停车区。Enum:'break, onRoute, outOfService, parked  . Model: [https://schema.org/DateTime](https://schema.org/DateTime)- `source[string]`: 一系列的字符，以URL的形式给出实体数据的原始来源。建议为源提供者的完全合格域名，或源对象的URL。  - `speed[*]`: 表示车辆当前速度的水平分量的大小，单位是公里/小时。如果提供，速度属性的值必须是一个非负的实数。如果速度由于某种原因暂时未知，可以使用`-1`。  . Model: [https://schema.org/Number](https://schema.org/Number)- `tripNetWeightCollected[number]`: 在行程结束时，与该观测点相对应的车辆收集的净重。  . Model: [https://schema.org/Number](https://schema.org/Number)- `type[string]`: NGSI实体类型。它必须是车辆  - `vehicleAltitude[string]`: 使用GPS给出车辆的当前高度  . Model: [https://schema.org/Text](https://schema.org/Text)- `vehicleConfiguration[string]`: 表明车辆配置的简短文字，例如 "5dr hatchback ST 2.5 MT 225 hp "或 "限量版"。  . Model: [https://schema.org/vehicleConfiguration.](https://schema.org/vehicleConfiguration.)- `vehicleIdentificationNumber[string]`: 车辆识别码（VIN）是汽车行业用来识别个别机动车的唯一序列号。  . Model: [https://schema.org/vehicleIdentificationNumber.](https://schema.org/vehicleIdentificationNumber.)- `vehiclePlateIdentifier[string]`: 显示在车辆登记牌上的标识符或代码，用于官方识别目的。注册标识符是数字或字母数字，在发证机构的区域内是唯一的。规范性引用。DATEXII `车辆登记牌标识符'。  . Model: [https://schema.org/Text](https://schema.org/Text)- `vehicleRunningStatus[string]`: 给出报告设备的电池充电状态。枚举：'运行、等待、停止'。  . Model: [https://schema.org/Text](https://schema.org/Text)- `vehicleSpecialUsage[string]`: 表示车辆是否被用于特殊目的，如商业租赁、驾驶学校或作为出租车。许多国家的立法要求在提供汽车销售时透露这一信息。Enum:'救护车，消防队，军队，警察，学校交通，出租车，垃圾管理'。  . Model: [https://schema.org/vehicleSpecialUsage](https://schema.org/vehicleSpecialUsage)- `vehicleTrackerDevice[string]`: 与该观察结果相对应的安装在车辆上的GPS装置或跟踪装置的安装状态。  . Model: [https://schema.org/Text](https://schema.org/Text)- `vehicleType[string]`: 从其结构特点的角度来看，车辆的类型。这与车辆类别不同。枚举。农业车辆，任何车辆，铰接式车辆，自行车，垃圾车，公共汽车，汽车，房车，汽车或轻型车辆，带房车的汽车，带拖车的汽车，清洁车，建筑或维修车辆，四轮驱动，高边车辆，货车，小型客车，轻便摩托车，摩托车。摩托车, 摩托车, 扫地机, 油罐车, 三轮车, 拖车, 电车, 两轮车, 手推车, 货车, 无催化转换器的车辆, 有房车的车辆, 有拖车的车辆, 有相同号码的登记牌照, 有不相同号码的登记牌照, 其他'。以下是由_VehicleTypeEnum_和_VehicleTypeEnum2_定义的值，[DATEX 2 version 2.3](http://d2docs.ndwcloud.nu/_static/umlmodel/v2.3/index.htm)并为其他用途进行了扩展  . Model: [https://schema.org/Text](https://schema.org/Text)- `wardId[string]`: 与此观察相对应的实体的病房ID。  . Model: [https://schema.org/Text](https://schema.org/Text)- `wardName[string]`: 与此观察对应的实体的沃德名称。  . Model: [https://schema.org/Text](https://schema.org/Text)- `zoneName[string]`: 与此观察相对应的实体的区域名称  . Model: [https://schema.org/Text](https://schema.org/Text)<!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
所需属性  
- `category`  - `id`  - `location`  - `type`  - `vehicleType`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## 数据模型的属性描述  
按字母顺序排列（点击查看详情）。  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
Vehicle:    
  description: 'This entity models a particular vehicle model, including all properties which are common to multiple vehicle instances belonging to such model.'    
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
    annotations:    
      description: 'Annotations about the item'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    areaServed:    
      description: 'The geographic area where a service or offered item is provided'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    bearing:    
      description: "Gives the vehicle GPS angle measured in a clockwise direction from the True North. SameAs 'bearing' field from GTFS Realtime message-Position(https://developers.google.com/transit/gtfs-realtime/reference#message-position)"    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    cargoWeight:    
      description: 'Current weight of the vehicle''s cargo'    
      exclusiveMinimum: true    
      minimum: 0    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: Kilograms    
    category:    
      description: 'Vehicle category(ies) from an external point of view. This is different than the vehicle type (car, lorry, etc.) represented by the `vehicleType` property. Enum:''municipalServices, nonTracked, private, public, specialUsage, tracked''. Tracked vehicles are those vehicles which position is permanently tracked by a remote system. Or any other needed by an application They incorporate a GPS receiver together with a network connection to periodically update a reported position (location, speed, heading ...).'    
      items:    
        enum:    
          - municipalServices    
          - nonTracked    
          - private    
          - public    
          - specialUsage    
          - tracked    
        type: string    
      type: array    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    color:    
      description: 'The color of the product'    
      type: string    
      x-ngsi:    
        model: https://schema.org/color    
        type: Property    
    currentTripCount:    
      description: 'The current count of trips made by the vehicle corresponding to this observation on the given day of operation.'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
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
    dateFirstUsed:    
      description: 'Timestamp which denotes when the vehicle was first used'    
      format: date    
      type: string    
      x-ngsi:    
        model: https://schema.org/DateTime.    
        type: Property    
    dateModified:    
      description: 'Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    dateVehicleFirstRegistered:    
      description: 'The date of the first registration of the vehicle with the respective public authorities'    
      format: date    
      type: string    
      x-ngsi:    
        model: https://schema.org/dateVehicleFirstRegistered.    
        type: Property    
    description:    
      description: 'A description of this item'    
      type: string    
      x-ngsi:    
        type: Property    
    deviceBatteryStatus:    
      description: 'Gives the Battery charging status of the reporting device. Enum:''connected, disconnected''.'    
      enum:    
        - connected    
        - disconnected    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    deviceSimNumber:    
      description: 'Gives the SIM number of the device in the vehicle.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    emergencyVehicleType:    
      description: 'Type of emergency vehicle corresponding to this observation. Enum:''policeCar, policeMotorcycle, policeVan, policeSWAT, fireEngine, waterTender, airAmbulance, ambulance, motorcycleAmbulance, rescueVehicle, hazardousMaterialsApparatus, towTruck'    
      enum:    
        - policeCar    
        - policeMotorcycle    
        - policeVan    
        - policeSWAT    
        - fireEngine    
        - waterTender    
        - airAmbulance    
        - ambulance    
        - motorcycleAmbulance    
        - rescueVehicle    
        - hazardousMaterialsApparatus    
        - towTruck    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    feature:    
      description: 'Feature(s) incorporated by the vehicle. Enum:'' abs, airbag, alarm, backCamera, disabledRamp, gps, internetConnection, overspeed, proximitySensor, wifi''. Or any other needed by the application. In order to represent multiple instances of a feature it can be used the following syntax: `<feature>,<occurences>`. For example, a car with 4 airbags will be represented by `airbag,4`.'    
      items:    
        enum:    
          - abs    
          - airbag    
          - alarm    
          - backCamera    
          - disabledRamp    
          - gps    
          - internetConnection    
          - overspeed    
          - proximitySensor    
          - wifi    
        type: string    
      type: array    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    fleetVehicleId:    
      description: 'The identifier of the vehicle in the context of the fleet of vehicles to which it belongs'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text.    
        type: Property    
    fuelEfficiency:    
      description: 'The distance traveled per unit of fuel used, commonly in kilometers per liter (km/L).'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    fuelFilled:    
      description: 'Amount of fuel filled in liters to the vehicle corresponding to this observation.'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    fuelType:    
      description: 'The type of fuel suitable for the engine or engines of the vehicle corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    heading:    
      description: 'Denotes the direction of travel of the vehicle and is specified in decimal degrees, where 0 <= `heading` < 360, counting clockwise relative to the true north. If the vehicle is stationary (i.e. the value of the `speed` attribute is `0`), then the value of the heading attribute must be equal to `-1`'    
      oneOf:    
        - exclusiveMaximum: true    
          maximum: 360    
          minimum: 0    
          type: number    
        - enum:    
            - -1    
          type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: Degree    
    id:    
      anyOf: &vehicle_-_properties_-_owner_-_items_-_anyof    
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
    ignitionStatus:    
      description: 'Gives the ignition status of the vehicle. True means ignited'    
      type: boolean    
      x-ngsi:    
        model: https://schema.org/Boolean    
        type: Property    
    image:    
      description: 'An image of the item'    
      format: uri    
      type: string    
      x-ngsi:    
        model: https://schema.org/URL    
        type: Property    
    license_plate:    
      description: "Gives the License Plate number of the vehicle. SameAs: license_plate field from GTFS Realtime message-VehicleDescriptor (https://developers.google.com/transit/gtfs-realtime/reference#message-vehicledescriptor)'"    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    location:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
      oneOf: &vehicle_-_properties_-_previouslocation_-_oneof    
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
    mileageFromOdometer:    
      description: 'The total distance travelled by the particular vehicle since its initial production, as read from its odometer'    
      type: number    
      x-ngsi:    
        model: https://schema.org/mileageFromOdometer.    
        type: Property    
    municipalityInfo:    
      description: 'Municipality information corresponding to this observation.'    
      properties:    
        cityId:    
          description: 'Property. Model:''https://schema.org/Text''. City ID corresponding to this observation.'    
          type: string    
        cityName:    
          description: 'Property. Model:''https://schema.org/Text''. City name corresponding to this observation'    
          type: string    
        district:    
          description: 'Property. Model:''https://schema.org/Text''. District name corresponding to this observation.'    
          type: string    
        stateName:    
          description: 'Property. Model:''https://schema.org/Text''. Name of the state corresponding to this observation.'    
          type: string    
        ulbName:    
          description: 'Property. Model:''https://schema.org/Text''. Name of the Urban Local Body corresponding to this observation.'    
          type: string    
        wardId:    
          description: 'Property. Model:''https://schema.org/Text''. Ward ID corresponding to this observation.'    
          type: string    
        wardName:    
          description: 'Property. Model:''https://schema.org/Text''. Ward name corresponding to this observation.'    
          type: string    
        wardNum:    
          description: 'Property. Model:''https://schema.org/Number''. Ward number corresponding to this observation.'    
          type: number    
        zoneId:    
          description: 'Property. Model:''https://schema.org/Text''. Zone ID corresponding to this observation.'    
          type: string    
        zoneName:    
          description: 'Property. Model:''https://schema.org/Text''. Zone name corresponding to this observation.'    
          type: string    
      type: object    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    name:    
      description: 'The name of this item.'    
      type: string    
      x-ngsi:    
        type: Property    
    observationDateTime:    
      description: 'Last reported time of observation'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/DateTime    
        type: Property    
    owner:    
      description: 'A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)'    
      items:    
        anyOf: *vehicle_-_properties_-_owner_-_items_-_anyof    
        description: 'Property. Unique identifier of the entity'    
      type: array    
      x-ngsi:    
        type: Property    
    previousLocation:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
      oneOf: *vehicle_-_properties_-_previouslocation_-_oneof    
      x-ngsi:    
        type: Geoproperty    
    purchaseDate:    
      description: 'The date the item e.g. vehicle was purchased by the current owner'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/purchaseDate.    
        type: Property    
    refVehicleModel:    
      anyOf:    
        - description: 'Property. Identifier format of any NGSI entity'    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
        - description: 'Property. Identifier format of any NGSI entity'    
          format: uri    
          type: string    
      description: 'Reference to a VehicleModel'    
      x-ngsi:    
        model: https://schema.org/URL    
        type: Relationship    
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
    serviceOnDuty:    
      description: 'Nature of service provided by emergency vehicle corresponding to this observation. True indicates the emergency vehicle corresponding to this observation is attending to/ servicing to an emergency call of duty and is False otherwise.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Boolean    
        type: Property    
    serviceProvided:    
      description: 'Service(s) the vehicle is capable of providing or it is assigned to. Enum:''auxiliaryServices, cargoTransport, construction, fairground, garbageCollection, goodsSelling, maintenance, parksAndGardens, roadSignalling, specialTransport, streetCleaning, streetLighting, urbanTransit, wasteContainerCleaning''. Or any other value needed by an specific application.'    
      items:    
        enum:    
          - auxiliaryServices    
          - cargoTransport    
          - construction    
          - fairground    
          - garbageCollection    
          - goodsSelling    
          - maintenance    
          - parksAndGardens    
          - roadSignalling    
          - specialTransport    
          - streetCleaning    
          - streetLighting    
          - urbanTransit    
          - wasteContainerCleaning    
        type: string    
      type: array    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    serviceStatus:    
      description: 'Vehicle status (from the point of view of the service provided, so it could not apply to private vehicles). `parked` : Vehicle is parked and not providing any service at the moment. `onRoute` : Vehicle is performing a mission. A comma-separated modifier(s) can be added to indicate what mission is currently delivering the vehicle. For instance `onRoute,garbageCollection` can be used to denote that the vehicle is on route and in a garbage collection mission. ''broken'' : Vehicle is suffering a temporary breakdown. `outOfService` : Vehicle is on the road but not performing any mission, probably going to its parking area. Enum:''broken, onRoute, outOfService, parked'''    
      enum:    
        - broken    
        - onRoute    
        - outOfService    
        - parked    
      type: string    
      x-ngsi:    
        model: https://schema.org/DateTime    
        type: Property    
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: string    
      x-ngsi:    
        type: Property    
    speed:    
      description: 'Denotes the magnitude of the horizontal component of the vehicle''s current velocity and is specified in Kilometers per Hour. If provided, the value of the speed attribute must be a non-negative real number. `-1` MAY be used if speed is transiently unknown for some reason'    
      oneOf:    
        - minimum: 0    
          type: number    
        - maximum: -1    
          minimum: -1    
          type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: Km/h    
    tripNetWeightCollected:    
      description: 'The net weight collected by the vehicle corresponding to this observation at the end of the trip.'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    type:    
      description: 'NGSI Entity type. It has to be Vehicle'    
      enum:    
        - Vehicle    
      type: string    
      x-ngsi:    
        type: Property    
    vehicleAltitude:    
      description: 'Gives the current altitude of the vehicle using GPS'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    vehicleConfiguration:    
      description: 'A short text indicating the configuration of the vehicle, e.g. ''5dr hatchback ST 2.5 MT 225 hp'' or ''limited edition'''    
      type: string    
      x-ngsi:    
        model: https://schema.org/vehicleConfiguration.    
        type: Property    
    vehicleIdentificationNumber:    
      description: 'The Vehicle Identification Number (VIN) is a unique serial number used by the automotive industry to identify individual motor vehicles'    
      type: string    
      x-ngsi:    
        model: https://schema.org/vehicleIdentificationNumber.    
        type: Property    
    vehiclePlateIdentifier:    
      description: ' An identifier or code displayed on a vehicle registration plate attached to the vehicle used for official identification purposes. The registration identifier is numeric or alphanumeric and is unique within the issuing authority''s region. Normative References: DATEXII `vehicleRegistrationPlateIdentifier`'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    vehicleRunningStatus:    
      description: 'Gives the Battery charging status of the reporting device. Enum:''running, waiting, stopped''.'    
      enum:    
        - running    
        - stopped    
        - waiting    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    vehicleSpecialUsage:    
      description: 'Indicates whether the vehicle is been used for special purposes, like commercial rental, driving school, or as a taxi. The legislation in many countries requires this information to be revealed when offering a car for sale. Enum:''ambulance, fireBrigade, military, police, schoolTransportation, taxi, trashManagement'''    
      enum:    
        - ambulance    
        - fireBrigade    
        - military    
        - police    
        - schoolTransportation    
        - taxi    
        - trashManagement    
      type: string    
      x-ngsi:    
        model: https://schema.org/vehicleSpecialUsage    
        type: Property    
    vehicleTrackerDevice:    
      description: 'Installation status of the GPS device or the tracking device fitted to the vehicle corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    vehicleType:    
      description: 'Type of vehicle from the point of view of its structural characteristics. This is different than the vehicle category . Enum:''agriculturalVehicle, anyVehicle, articulatedVehicle, bicycle, binTrolley, bus, car, caravan, carOrLightVehicle, carWithCaravan, carWithTrailer, cleaningTrolley, constructionOrMaintenanceVehicle, fourWheelDrive, highSidedVehicle, lorry, minibus, moped, motorcycle, motorcycleWithSideCar, motorscooter, sweepingMachine, tanker, threeWheeledVehicle, trailer, tram, twoWheeledVehicle, trolley, van, vehicleWithoutCatalyticConverter, vehicleWithCaravan, vehicleWithTrailer, withEvenNumberedRegistrationPlates, withOddNumberedRegistrationPlates, other''. The following values defined by _VehicleTypeEnum_ and _VehicleTypeEnum2_, [DATEX 2 version 2.3](http://d2docs.ndwcloud.nu/_static/umlmodel/v2.3/index.htm) and extended for other uses'    
      enum:    
        - agriculturalVehicle    
        - ambulance    
        - anyVehicle    
        - articulatedVehicle    
        - autorickshaw    
        - bicycle    
        - binTrolley    
        - 'BRT mini bus·'    
        - 'BRT bus'    
        - bus    
        - car    
        - caravan    
        - carOrLightVehicle    
        - carWithCaravan    
        - carWithTrailer    
        - cleaningTrolley    
        - compactor    
        - constructionOrMaintenanceVehicle    
        - dumper    
        - e-moped    
        - e-scooter    
        - e-motorcycle    
        - fireTender    
        - fourWheelDrive    
        - highSidedVehicle    
        - hopper    
        - lorry    
        - minibus    
        - moped    
        - motorcycle    
        - motorcycleWithSideCar    
        - motorscooter    
        - policeVan    
        - publicMotor    
        - sweepingMachine    
        - tanker    
        - tempo    
        - threeWheeledVehicle    
        - tipper    
        - trailer    
        - tram    
        - trolley    
        - twoWheeledVehicle    
        - van    
        - vehicleWithoutCatalyticConverter    
        - vehicleWithCaravan    
        - vehicleWithTrailer    
        - withEvenNumberedRegistrationPlates    
        - withOddNumberedRegistrationPlates    
        - other    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    wardId:    
      description: 'Ward ID of the entity corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    wardName:    
      description: 'Ward name of the entity corresponding to this observation.'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    zoneName:    
      description: 'Zone name of the entity corresponding to this observation'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
  required:    
    - id    
    - type    
    - vehicleType    
    - category    
    - location    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2022 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.Transportation/blob/master/Vehicle/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.Transportation/Vehicle/schema.json    
  x-model-tags: IUDX    
  x-version: 0.2.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## ＃＃＃＃有效载荷的例子  
#### 车辆NGSI-v2关键值示例  
这里有一个JSON-LD格式的车辆作为key-values的例子。当使用`options=keyValues`时，这与NGSI-v2兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "vehicle:WasteManagement:1",  
  "type": "Vehicle",  
  "vehicleType": "lorry",  
  "category": [  
    "municipalServices"  
  ],  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      -3.164485591715449,  
      40.62785133667262  
    ]  
  },  
  "name": "C Recogida 1",  
  "speed": 50,  
  "cargoWeight": 314,  
  "serviceStatus": "onRoute",  
  "serviceProvided": [  
    "garbageCollection",  
    "wasteContainerCleaning"  
  ],  
  "areaServed": "Centro",  
  "refVehicleModel": "vehiclemodel:econic",  
  "vehiclePlateIdentifier": "3456ABC",  
  "bearing": 43,  
  "fuelEfficiency": 13,  
  "fuelType": "Petrol",  
  "fuelFilled": 6,  
  "tripNetWeightCollected": 12,  
  "vehicleTrackerDevice": "Installed",  
  "wardId": "4",  
  "license_plate": "KA052134",  
  "currentTripCount": 1,  
  "reportId": "21645",  
  "zoneName": "South Zone",  
  "vehicleAltitude": 600,  
  "deviceSimNumber": "9942142573",  
  "wardName": "Kempegowda Ward",  
  "deviceBatteryStatus": "Connected",  
  "ignitionStatus": true,  
  "vehicleRunningStatus": "running",  
  "observationDateTime": "2021-03-11T15:51:02+05:30",  
  "serviceOnDuty": false,  
  "emergencyVehicleType": "ambulance",  
  "municipalityInfo": {  
    "district": "Bangalore Urban",  
    "ulbName": "BMC",  
    "cityId": "23",  
    "wardId": "23",  
    "stateName": "Karnataka",  
    "cityName": "Bangalore",  
    "zoneName": "South",  
    "wardName": "Bangalore Urban",  
    "zoneId": "2",  
    "wardNum": 4  
  }  
}  
```  
</details>  
#### 车辆NGSI-v2规范化示例  
下面是一个以JSON-LD格式规范化的车辆的例子。当不使用选项时，这与NGSI-v2兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "vehicle:WasteManagement:1",  
  "type": "Vehicle",  
  "category": {  
    "type": "array",  
    "value": [  
      "municipalServices"  
    ]  
  },  
  "vehicleType": {  
    "type": "Text",  
    "value": "lorry"  
  },  
  "name": {  
    "type": "Text",  
    "value": "C Recogida 1"  
  },  
  "vehiclePlateIdentifier": {  
    "type": "Text",  
    "value": "3456ABC"  
  },  
  "refVehicleModel": {  
    "type": "Relationship",  
    "value": "vehiclemodel:econic"  
  },  
  "location": {  
    "type": "geo:json",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        -3.164485591715449,  
        40.62785133667262  
      ]  
    },  
    "metadata": {  
      "timestamp": {  
        "type": "DateTime",  
        "value": "2018-09-27T12:00:00"  
      }  
    }  
  },  
  "areaServed": {  
    "type": "Text",  
    "value": "Centro"  
  },  
  "serviceStatus": {  
    "type": "Text",  
    "value": "onRoute"  
  },  
  "cargoWeight": {  
    "type": "Number",  
    "value": 314  
  },  
  "speed": {  
    "type": "Number",  
    "value": 50,  
    "metadata": {  
      "timestamp": {  
        "type": "DateTime",  
        "value": "2018-09-27T12:00:00"  
      }  
    }  
  },  
  "serviceProvided": {  
    "type": "array",  
    "value": [  
      "gargabeCollection",  
      "wasteContainerCleaning"  
    ]  
  },  
  "bearing": {  
    "type": "Number",  
    "value": 43  
  },  
  "fuelEfficiency": {  
    "type": "Number",  
    "value": 13  
  },  
  "fuelType": {  
    "type": "Text",  
    "value": "Petrol"  
  },  
  "fuelFilled": {  
    "type": "Number",  
    "value": 6  
  },  
  "tripNetWeightCollected": {  
    "type": "Number",  
    "value": 12  
  },  
  "vehicleTrackerDevice": {  
    "type": "Text",  
    "value": "Installed"  
  },  
  "wardId": {  
    "type": "Text",  
    "value": "4"  
  },  
  "license_plate": {  
    "type": "Text",  
    "value": "KA052134"  
  },  
  "currentTripCount": {  
    "type": "Number",  
    "value": 1  
  },  
  "reportId": {  
    "type": "Text",  
    "value": "21645"  
  },  
  "zoneName": {  
    "type": "Text",  
    "value": "South Zone"  
  },  
  "vehicleAltitude": {  
    "type": "Number",  
    "value": 600  
  },  
  "deviceSimNumber": {  
    "type": "Text",  
    "value": "9942142573"  
  },  
  "wardName": {  
    "type": "Text",  
    "value": "Kempegowda Ward"  
  },  
  "deviceBatteryStatus": {  
    "type": "Text",  
    "value": "Connected"  
  },  
  "ignitionStatus": {  
    "type": "Boolean",  
    "value": true  
  },  
  "vehicleRunningStatus": {  
    "type": "Text",  
    "value": "running"  
  },  
  "observationDateTime": {  
    "type": "DateTime",  
    "value": "2021-03-11T15:51:02+05:30"  
  },  
  "serviceOnDuty": {  
    "type": "Boolean",  
    "value": false  
  },  
  "emergencyVehicleType": {  
    "type": "Text",  
    "value": "ambulance"  
  },  
  "municipalityInfo": {  
    "type": "StructuredValue",  
    "value": {  
      "district": "Bangalore Urban",  
      "ulbName": "BMC",  
      "cityId": "23",  
      "wardId": "23",  
      "stateName": "Karnataka",  
      "cityName": "Bangalore",  
      "zoneName": "South",  
      "wardName": "Bangalore Urban",  
      "zoneId": "2",  
      "wardNum": 4  
    }  
  }  
}  
```  
</details>  
#### 车辆NGSI-LD关键值示例  
这里有一个JSON-LD格式的车辆作为key-values的例子。当使用`options=keyValues`时，这与NGSI-LD兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:Vehicle:vehicle:WasteManagement:1",  
    "type": "Vehicle",  
    "areaServed": "Centro",  
    "bearing": 43,  
    "cargoWeight": 314,  
    "category": [  
        "municipalServices"  
    ],  
    "currentTripCount": 1,  
    "deviceBatteryStatus": "Connected",  
    "deviceSimNumber": "9942142573",  
    "emergencyVehicleType": "ambulance",  
    "fuelEfficiency": 13,  
    "fuelFilled": 6,  
    "fuelType": "Petrol",  
    "ignitionStatus": true,  
    "license_plate": "KA052134",  
    "location": {  
        "coordinates": [  
            -3.164485591715449,  
            40.62785133667262  
        ],  
        "type": "Point"  
    },  
    "municipalityInfo": {  
        "district": "Bangalore Urban",  
        "ulbName": "BMC",  
        "cityId": "23",  
        "wardId": "23",  
        "stateName": "Karnataka",  
        "cityName": "Bangalore",  
        "zoneName": "South",  
        "wardName": "Bangalore Urban",  
        "zoneId": "2",  
        "wardNum": 4  
    },  
    "name": "C Recogida 1",  
    "observationDateTime": "2021-03-11T15:51:02+05:30",  
    "refVehicleModel": "urn:ngsi-ld:VehicleModel:vehiclemodel:econic",  
    "reportId": "21645",  
    "serviceOnDuty": false,  
    "serviceProvided": [  
        "gargabeCollection",  
        "wasteContainerCleaning"  
    ],  
    "serviceStatus": "onRoute",  
    "speed": 50,  
    "tripNetWeightCollected": 12,  
    "vehicleAltitude": 600,  
    "vehiclePlateIdentifier": "3456ABC",  
    "vehicleRunningStatus": "running",  
    "vehicleTrackerDevice": "Installed",  
    "vehicleType": "lorry",  
    "wardId": "4",  
    "wardName": "Kempegowda Ward",  
    "zoneName": "South Zone",  
    "@context": [  
        "iudx:EmergencyVehicle",  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.Transportation/master/context.jsonld"  
    ]  
}  
```  
</details>  
#### 车辆NGSI-LD正常化的例子  
这里有一个JSON-LD格式的车辆的例子，是规范化的。当不使用选项时，这与NGSI-LD兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:Vehicle:vehicle:WasteManagement:1",  
    "type": "Vehicle",  
    "areaServed": {  
        "type": "Property",  
        "value": "Centro"  
    },  
    "bearing": {  
        "type": "Property",  
        "value": 43  
    },  
    "cargoWeight": {  
        "type": "Property",  
        "value": 314  
    },  
    "category": {  
        "type": "Property",  
        "value": [  
            "municipalServices"  
        ]  
    },  
    "currentTripCount": {  
        "type": "Property",  
        "value": 1  
    },  
    "deviceBatteryStatus": {  
        "type": "Property",  
        "value": "Connected"  
    },  
    "deviceSimNumber": {  
        "type": "Property",  
        "value": "9942142573"  
    },  
    "emergencyVehicleType": {  
        "type": "Property",  
        "value": "ambulance"  
    },  
    "fuelEfficiency": {  
        "type": "Property",  
        "value": 13  
    },  
    "fuelFilled": {  
        "type": "Property",  
        "value": 6  
    },  
    "fuelType": {  
        "type": "Property",  
        "value": "Petrol"  
    },  
    "ignitionStatus": {  
        "type": "Property",  
        "value": true  
    },  
    "license_plate": {  
        "type": "Property",  
        "value": "KA052134"  
    },  
    "location": {  
        "type": "GeoProperty",  
        "value": {  
            "type": "Point",  
            "coordinates": [  
                -3.164485591715449,  
                40.62785133667262  
            ]  
        },  
        "observedAt": "2018-09-27T12:00:00Z"  
    },  
    "municipalityInfo": {  
        "type": "Property",  
        "value": {  
            "district": "Bangalore Urban",  
            "ulbName": "BMC",  
            "cityId": "23",  
            "wardId": "23",  
            "stateName": "Karnataka",  
            "cityName": "Bangalore",  
            "zoneName": "South",  
            "wardName": "Bangalore Urban",  
            "zoneId": "2",  
            "wardNum": 4  
        }  
    },  
    "name": {  
        "type": "Property",  
        "value": "C Recogida 1"  
    },  
    "observationDateTime": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-03-11T15:51:02+05:30"  
        }  
    },  
    "refVehicleModel": {  
        "type": "Relationship",  
        "object": "urn:ngsi-ld:VehicleModel:vehiclemodel:econic"  
    },  
    "reportId": {  
        "type": "Property",  
        "value": "21645"  
    },  
    "serviceOnDuty": {  
        "type": "Property",  
        "value": false  
    },  
    "serviceProvided": {  
        "type": "Property",  
        "value": [  
            "gargabeCollection",  
            "wasteContainerCleaning"  
        ]  
    },  
    "serviceStatus": {  
        "type": "Property",  
        "value": "onRoute"  
    },  
    "speed": {  
        "type": "Property",  
        "value": 50,  
        "observedAt": "2018-09-27T12:00:00Z"  
    },  
    "tripNetWeightCollected": {  
        "type": "Property",  
        "value": 12  
    },  
    "vehicleAltitude": {  
        "type": "Property",  
        "value": 600  
    },  
    "vehiclePlateIdentifier": {  
        "type": "Property",  
        "value": "3456ABC"  
    },  
    "vehicleRunningStatus": {  
        "type": "Property",  
        "value": "running"  
    },  
    "vehicleTrackerDevice": {  
        "type": "Property",  
        "value": "Installed"  
    },  
    "vehicleType": {  
        "type": "Property",  
        "value": "lorry"  
    },  
    "wardId": {  
        "type": "Property",  
        "value": "4"  
    },  
    "wardName": {  
        "type": "Property",  
        "value": "Kempegowda Ward"  
    },  
    "zoneName": {  
        "type": "Property",  
        "value": "South Zone"  
    },  
    "@context": [  
        "iudx:EmergencyVehicle",  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.Transportation/master/context.jsonld"  
    ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
参见[常见问题10](https://smartdatamodels.org/index.php/faqs/)，以获得关于如何处理量级单位的答案。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
