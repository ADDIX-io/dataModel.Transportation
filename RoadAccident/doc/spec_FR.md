<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
Entité : RoadAccident  
=====================<!-- /10-Header -->  
<!-- 15-License -->  
[Licence ouverte] (https://github.com/smart-data-models//dataModel.Transportation/blob/master/RoadAccident/LICENSE.md)  
[document généré automatiquement] (https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
Description globale : **Description d'un accident de la route avec ses causes et ses conséquences. Première version développée dans le cadre du projet Synchronicité**.  
version : 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## Liste des propriétés  

<sup><sub>[*] S'il n'y a pas de type dans un attribut, c'est parce qu'il pourrait avoir plusieurs types ou différents formats/modèles</sub></sup>.  
- `accidentDate[string]`: Date de l'accident  . Model: [https://schema.org/DateTime](https://schema.org/DateTime)- `accidentDescription[array]`: La description de cet accident de la route est une combinaison de situations codifiées énumérées. 0 : Circonstance non spécifiée ; 1 : Le conducteur a procédé régulièrement sans tourner ; 2 : Le conducteur a procédé avec une conduite distraite ou indécise ; 3 : Le conducteur a procédé sans maintenir une distance de sécurité ; 4 : Le conducteur a procédé sans donner la priorité au véhicule venant de la droite ; 5 : Le conducteur a procédé sans respecter l'arrêt ; 6 : Le conducteur a procédé sans respecter le signal de priorité ; 7 : Le conducteur a procédé à contre-sens ; 8 : Le conducteur a procédé sans respecter les signaux lumineux ou d'agents ; 10 : Le conducteur a procédé sans respecter les panneaux d'interdiction de passage ou d'accès ; 11 : Le conducteur a procédé à des excès de vitesse ; 12 : Le conducteur a procédé sans respecter les limitations de vitesse ; 13 : Le conducteur a procédé à l'éblouissement des feux croisant d'autres véhicules ; 14 : Le conducteur a tourné à droite régulièrement ; 15 : Il a tourné irrégulièrement à droite ; 16 : Le conducteur a tourné à gauche régulièrement ; 17 : Il a tourné irrégulièrement à gauche ; 18 : Le conducteur a dépassé à l'intersection ; 20 : Le conducteur a procédé régulièrement ; 21 : Le conducteur a procédé à une conduite distraite ou indécise ; 22 : Le conducteur a procédé sans respecter une distance de sécurité ; 23 : Le conducteur a procédé à un excès de vitesse ; 24 : Le conducteur a procédé sans respecter les limitations de vitesse ; 25 : Il n'a pas procédé près du bord droit de la chaussée ; 26 : Le conducteur a procédé à contre-sens ; 27 : Le conducteur a procédé sans respecter les panneaux d'interdiction de passage ou d'accès ; 28 : Le conducteur a procédé avec les feux éblouissants croisant d'autres véhicules ; 29 : Le conducteur a dépassé régulièrement ; 30 : Il a dépassé irrégulièrement à droite ; 31 : Le conducteur a dépassé dans un virage, dans une côte ou avec une visibilité insuffisante ; 32 : Il a dépassé un véhicule qui en dépassait un autre ; 33 : Le conducteur a dépassé sans respecter le panneau d'interdiction approprié ; 34 : Il a manœuvré en relégation ou en conversion ; 35 : Le conducteur a manœuvré pour se placer dans le flux de circulation ; 36 : Il a manœuvré pour tourner à gauche (passage privé, distributeur) ; 37 : Le conducteur a manœuvré régulièrement pour s'arrêter ou s'immobiliser ; 38 : Le conducteur a manœuvré irrégulièrement pour s'arrêter ou s'immobiliser ; 39 : Il a été rejoint par d'autres deux-roues irréguliers ; 40 : Le conducteur a procédé régulièrement ; 41 : Le conducteur a procédé avec excès de vitesse ; 42 : Le conducteur a procédé sans respecter les limitations de vitesse ; 43 : Le conducteur a procédé contre la circulation ; 44 : Le conducteur a passé le véhicule en vitesse ; 45 : Manœuvré ; 46 : Manœuvré sans respecter les signaux des feux de circulation ou des agents ; 47 : Le conducteur est sorti de l'allée sans précaution ; 48 : Le conducteur est sorti de la voie et a heurté le pion ; 49 : Il n'a pas donné la priorité au piéton sur les passages appropriés ; 50 : Il a dépassé un véhicule arrêté pour permettre la traversée ; 51 : Le conducteur a heurté le piéton avec la charge ; 52 : Le conducteur a dépassé un tramway de façon irrégulière à l'arrêt ; 60 : Le conducteur procédait régulièrement ; 61 : Le conducteur procédait à une conduite distraite ou indécise ; 62 : Le conducteur procédait sans respecter une distance de sécurité ; 63 : Le conducteur procédait à contre-sens ; 64 : Le conducteur procédait à un excès de vitesse ; 65 : Le conducteur procédait sans respecter les limitations de vitesse ; 66 : Le conducteur procédait sans respecter les panneaux d'interdiction de transit ou d'accès ; 67 : Le conducteur dépassait un autre véhicule en vitesse ; 68 : Le conducteur a imprudemment franchi le passage à niveau ; 70 : Écoute avec déversement pour éviter le choc ; 71 : Écoute avec déversement pour distraction au volant ; 72 : Écoute avec déversement pour excès de vitesse ; 73 : Le conducteur a freiné brusquement avec conséquence pour les personnes transportées ; 74 : Chute de personne d'un véhicule pour : ouverture de porte ; 75 : Chute de personne d'un véhicule pour : descente d'un véhicule en mouvement ; 76 : Chute d'une personne d'un véhicule pour : accrochage ou mauvais placement ; 80 : Panne ou défaillance des freins ; 81 : Bris ou défaillance de la direction ; 82 : Éclatement des pneus ou usure excessive ; 83 : Absence ou insuffisance des phares ou des feux de position ; 84 : Absence ou insuffisance des feux clignotants ou des signaux lumineux d'arrêt ; 85 : Rupture des pièces d'attelage de la remorque ; 86 : Défaut de l'équipement de transport des marchandises dangereuses ; 87 : Défaut des adaptations prescrites aux véhicules des personnes handicapées physiques ; 88 : Détachement des roues ; 89 : Absence ou insuffisance des dispositifs visuels des cycles.  . Model: [https://schema.org/Text](https://schema.org/Text)- `accidentLocation[string]`: Brève description si l'accident a eu lieu dans une zone urbaine ou extra-urbaine. 0 : Régionale dans la zone urbaine 1 : Route urbaine dans la ville 2 : Route provinciale dans la ville 3 : Route nationale dans le village 4 : Route extra-urbaine 5 : Provinciale 6 : Route nationale 7 : Autoroute 8 : Autre voie 9 : Route régionale  - `accidentStatisticalDate[object]`: la date approximative de l'accident (souvent, la source originale des données sur les accidents ne rapporte que des attributs statistiques tels que la saison, le jour de la semaine et l'heure approximative).  . Model: [https://schema.org/DateTime](https://schema.org/DateTime)- `accidentType[array]`: Classification rapide de cet accident de la route. 1 : Collision frontale ; 2 : Collision frontale-latérale ; 3 : Accident latéral ; 4 : Collision ; 5 : Investissement d'un piéton ; 6 : Impact avec un véhicule arrêté ou en stationnement ; 7 : Impact avec un véhicule en stationnement ; 8 : Impact avec un obstacle ; 9 : Impact avec un train ; 10 : Déversement, glissade ; 11 : Accident dû à un freinage brusque ; 12 : Accident dû à la chute d'un véhicule ;.  - `address[object]`: L'adresse postale  . Model: [https://schema.org/address](https://schema.org/address)- `alternateName[string]`: Un nom alternatif pour cet élément  - `areaServed[string]`: La zone géographique où un service ou un article offert est fourni  . Model: [https://schema.org/Text](https://schema.org/Text)- `dataProvider[string]`: Une séquence de caractères identifiant le fournisseur de l'entité de données harmonisées.  - `dateCreated[string]`: Horodatage de la création de l'entité. Celui-ci sera généralement attribué par la plateforme de stockage.  - `dateModified[string]`: Horodatage de la dernière modification de l'entité. Il sera généralement attribué par la plateforme de stockage.  - `description[string]`: Une description de cet article  - `id[*]`: Identifiant unique de l'entité  - `localId[string]`: Identifiant unique de l'ensemble de données source  . Model: [https://schema.org/Text](https://schema.org/Text)- `location[*]`: Référence Geojson à l'élément. Il peut s'agir d'un point, d'une ligne, d'un polygone, d'un point multiple, d'une ligne multiple ou d'un polygone multiple.  - `name[string]`: Le nom de cet élément.  - `numPassengersDead[integer]`: Nombre de passagers du véhicule décédés à cause de l'accident  . Model: [https://schema.org/Number](https://schema.org/Number)- `numPassengersInjured[integer]`: Nombre de passagers du véhicule blessés lors de l'accident  . Model: [https://schema.org/Number](https://schema.org/Number)- `numPedestrianDead[integer]`: Nombre de piétons morts à cause de l'accident  . Model: [https://schema.org/Number](https://schema.org/Number)- `numPedestrianInjured[integer]`: Nombre de piétons blessés lors de l'accident  . Model: [https://schema.org/Number](https://schema.org/Number)- `owner[array]`: Une liste contenant une séquence de caractères codée en JSON référençant les identifiants uniques du ou des propriétaires.  - `pedestriansInvolved[boolean]`: Booléen pour déterminer si des piétons ont été impliqués dans les accidents.  - `roadClass[string]`:  La classification de la route où l'accident a eu lieu  . Model: [https://wiki.openstreetmap.org/wiki/Key:highway](https://wiki.openstreetmap.org/wiki/Key:highway)- `roadIntersection[string]`: Brève description du tronçon de la route où l'accident a eu lieu.   1 : Carrefour ; 2 : Rond-point ; 3 : Intersection signalée ; 4 : Intersection avec feu de circulation ; 5 : Intersection non signalée ; 6 : Passage à niveau ; 7 : Ligne droite ; 8 : Courbe ; 9 : Bosse, goulot d'étranglement ; 10 : Pente ; 11 : Galerie éclairée ; 12 : Galerie non éclairée ;  - `roadPaving[string]`: Revêtement de la route. 1 : Route pavée ; 2 : Route pavée brute ; 3 : Route non pavée ;  - `roadSign[string]`: Brève description du panneau routier où l'accident a eu lieu. 1 : Absent ; 2 : Vertical ; 3 : Horizontal ; 4 : Vertical et horizontal ; 5 : Temporaire par chantier ;  - `roadSurface[string]`: Brève description de l'état de la route au moment de l'accident. 1 : sec ; 2 : humide ; 3 : glissant ; 4 : gelé ; 5 : enneigé ;  - `roadTrunk[string]`: Brève description du type de tronçon de la route où a eu lieu l'accident. 1 : Branche de route ; 2 : Branche secondaire ; 3 : Branche secondaire ; 4 : Branche de jonction ; 5 : Jonction de routes ; 6 : Voie de gauche d'une autoroute ; 7 : Voie de droite d'une autoroute ; 8 : Entrée d'une jonction d'autoroute ; 9 : Sortie d'une jonction d'autoroute ; 10 : Tronc d'une jonction d'autoroute ; 11 : Station d'autoroute ; 12 : Autres cas ; 15 : Route extra-urbaine.  - `seeAlso[*]`: liste d'uri pointant vers des ressources supplémentaires sur l'article  - `source[string]`: Une séquence de caractères donnant la source originale des données de l'entité sous forme d'URL. Il est recommandé d'utiliser le nom de domaine entièrement qualifié du fournisseur source ou l'URL de l'objet source.  - `status[string]`: Statut de l'accident de la route. Enum : 'archived, onGoing, solved' (archivé, en cours, résolu)  . Model: [https://schema.org/Text](https://schema.org/Text)- `totalDeadPeopleWithin24Hours[integer]`: Nombre de personnes décédées directement à cause de l'accident  . Model: [https://schema.org/Number](https://schema.org/Number)- `totalDeadPeopleWithin30Days[integer]`: Nombre de personnes décédées à la suite de l'accident  . Model: [https://schema.org/Number](https://schema.org/Number)- `totalInjured[integer]`: nombre total de personnes blessées (non décédées) à cause de l'accident  . Model: [https://schema.org/Number](https://schema.org/Number)- `type[string]`: Type d'entité NGSI. Il doit s'agir de RoadAccident.  - `vehiclesInvolved[array]`: Liste des véhicules (et des piétons) impliqués dans l'accident 0 : piéton 1 : bicyclette 2 : véhicule agricole 3 : bus 4 : minibus 5 : voiture 6 : caravane 7 : tramway 8 : camion-citerne 9 : voiture avec caravane 10 : voiture avec remorque 11 : camion 12 : cyclomoteur 13 : camion-citerne 14 : moto 15 : moto avec side-car 16 : scooter 17 : remorque 18 : fourgon 19 : caravane 20 : véhicule de construction ou d'entretien 21 : chariot 22 : chariot à poubelles 23 : balayeuse 24 : chariot de nettoyage  - `weakestSubject[string]`: véhicule qui représente le sujet le plus faible impliqué dans l'accident (généralement un piéton). 0 : piéton 1 : bicyclette 2 : véhicule agricole 3 : bus 4 : minibus 5 : voiture 6 : caravane 7 : tramway 8 : camion-citerne 9 : voitureaveccaravane 10 : voitureavecremorque 11 : camion 12 : cyclomoteur 13 : camion-citerne 14 : moto 15 : motoaveccaravane 16 : scooter 17 : remorque 18 : fourgon 19 : caravane 20 : véhicule de construction ou d'entretien 21 : chariot 22 : chariot à poubelles 23 : balayeuse 24 : chariot de nettoyage  - `weatherConditions[array]`: Brève description des conditions météorologiques lors de cet accident de la route. 0 : clairNuit 1 : ensoleilléJour 2 : légèrement nuageux 3 : partiellement nuageux 4 : brume 5 : brouillard 6 : nuages élevés 7 : nuageux 8 : très nuageux 9 : couvert 10 : averse légère 11 : bruine 12 : averse légère 13 : heavyRainShower 14 : heavyRain 15 : sleetShower 16 : sleet 17 : hailShower 18 : hail 19 : shower 20 : lightSnow 21 : snow 22 : heavySnowShower 23 : heavySnow 24 : thunderShower 25 : thunder  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
Propriétés requises  
- `id`  - `status`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
Modèle de données provenant du projet Synchronicity  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## Description des propriétés du modèle de données  
Classés par ordre alphabétique (cliquez pour plus de détails)  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
RoadAccident:    
  description: 'A road accident description with causes and aftermath. First version developed in Synchronicity project'    
  properties:    
    accidentDate:    
      description: 'Datetime of the accident'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/DateTime    
        type: Property    
    accidentDescription:    
      description: 'Description about this Road Accident as a combination of codified situation enlisted. 0: Unspecified circumstance; 1: Driver proceeded regularly without turning; 2: Driver proceeded with a distracted driving or undecided course; 3: Driver proceeded without maintaining a safe distance; 4: Driver proceeded without giving priority to the vehicle coming from the right; 5: Driver proceeded without respecting the stop; 6: Driver proceeded without respecting the signal to give precedence; 7: Driver proceeded against traffic; 8: Driver proceeded without respecting the traffic light or agent signals; 10: Driver proceeded without respecting the signs of prohibition of transit or access; 11: Driver proceeded with speeding; 12: Driver proceeded without respecting the speed limits; 13: Driver proceeded with the dazzling lights crossing other vehicles; 14: Driver turned right regularly; 15: It turned irregularly to the right; 16: Driver turned left regularly; 17: It turned irregularly to the left; 18: Driver passed at the intersection; 20: Driver proceeded regularly; 21: Driver proceeded with a distracted driving or undecided course; 22: Driver proceeded without maintaining a safe distance; 23: Driver proceeded with speeding; 24: Driver proceeded without respecting the speed limits; 25: It proceeded not near the right edge of the roadway; 26: Driver proceeded against traffic; 27: Driver proceeded without respecting the signs of prohibition of transit or access; 28: Driver proceeded with the dazzling lights crossing other vehicles; 29: Driver passed regularly; 30: It passed irregularly to the right; 31: Driver overtook on a curve, on a hill or with insufficient visibility; 32: It overtook a vehicle that was overtaking another; 33: Driver passed without observing the appropriate prohibition sign; 34: Maneuvered in relegation or conversion; 35: Driver maneuvered to get into the flow of circulation; 36: Maneuvering To turn left (private passage, distributor); 37: Driver maneuvered regularly to stop or stop; 38: Driver maneuvered irregularly to stop or stop; 39: It was joined by other irregular two-wheeled vehicles; 40: Driver proceeded regularly; 41: Driver proceeded with speeding; 42: Driver proceeded without respecting the speed limits; 43: Driver proceeded against traffic; 44: Driver passed the vehicle in gear; 45: Maneuvered; 46: Maneuvered without respecting traffic light or agent signals; 47: Driver came out of the driveway without precaution; 48: Driver stepped out of the lane and hit the pawn; 49: It did not give priority to the pedestrian on the appropriate crossings; 50: It overtook a vehicle stopped to allow the crossing; 51: Driver hit the pedestrian with the load; 52: Driver was passing a tram unevenly at the stop; 60: Driver proceeded regularly; 61: Driver proceeded with a distracted driving or undecided course; 62: Driver proceeded without maintaining a safe distance; 63: Driver proceeded against traffic; 64: Driver proceeded with speeding; 65: Driver proceeded without respecting the speed limits; 66: Driver proceeded without respecting the signs of prohibition of transit or access; 67: Driver was passing another vehicle in gear; 68: Driver imprudently crossed the level crossing; 70: Spill with spillage to avoid impact; 71: Listening with spillage for distracted driving; 72: List with over-speed spill; 73: Driver suddenly braked with consequence to the transported; 74: Fall of person from vehicle for: door opening; 75: Fall of person from vehicle for: descent from vehicle in motion; 76: Fall of person from vehicle due to: clinging or improperly placed; 80: Brake failure or failure; 81: Breakage or steering failure; 82: Tire burst or excessive wear; 83: Lack or insufficiency of headlights or position lights; 84: Lack or insufficiency of flashing lights or stopping light signals; 85: Breaking of trailer coupling parts; 86: Deficiency of dangerous goods transport equipment; 87: Deficiency of the adaptations prescribed to vehicles of physically handicapped people; 88: Wheel detachment; 89: Lack or insufficiency    
        of visual devices for cycles'    
      items:    
        enum:    
          - 0    
          - 1    
          - 2    
          - 3    
          - 4    
          - 5    
          - 6    
          - 7    
          - 8    
          - 9    
          - 10    
          - 11    
          - 12    
          - 13    
          - 14    
          - 15    
          - 16    
          - 17    
          - 18    
          - 19    
          - 20    
          - 21    
          - 22    
          - 23    
          - 24    
          - 25    
          - 26    
          - 27    
          - 28    
          - 29    
          - 30    
          - 31    
          - 32    
          - 33    
          - 34    
          - 35    
          - 36    
          - 37    
          - 38    
          - 39    
          - 40    
          - 41    
          - 42    
          - 43    
          - 44    
          - 45    
          - 46    
          - 47    
          - 48    
          - 49    
          - 50    
          - 51    
          - 52    
          - 53    
          - 54    
          - 55    
          - 56    
          - 57    
          - 58    
          - 59    
          - 60    
          - 61    
          - 62    
          - 63    
          - 64    
          - 65    
          - 66    
          - 67    
          - 68    
          - 69    
          - 70    
          - 71    
          - 72    
          - 73    
          - 74    
          - 75    
          - 76    
          - 77    
          - 78    
          - 79    
          - 80    
          - 81    
          - 82    
          - 83    
          - 84    
          - 85    
          - 86    
          - 87    
          - 88    
          - 89    
        type: string    
      type: array    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    accidentLocation:    
      description: 'Brief description if the accident took place in a urban or extra-urban area. 0: Regional within the urban area 1: Urban road in the town 2: Provincial road within the town 3: State road within the village 4: Extra-urban road 5: Provincial 6: State road 7: Highway 8: Another way 9: Regional road'    
      enum:    
        - 0    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
        - 6    
        - 7    
        - 8    
        - 9    
      type: string    
      x-ngsi:    
        type: Property    
    accidentStatisticalDate:    
      description: 'approximate datetime of the accident (often original accident data source reports only statistical attributes such as season, weekday and approximate hour'    
      properties:    
        hour:    
          type: integer    
        quarter:    
          type: integer    
        weekday:    
          description: 'Week days'    
          enum:    
            - Monday    
            - Tuesday    
            - Wednesday    
            - Thursday    
            - Friday    
            - Saturday    
            - Sunday    
          type: string    
        year:    
          type: integer    
      type: object    
      x-ngsi:    
        model: https://schema.org/DateTime    
        type: Property    
    accidentType:    
      description: 'Quick classification this Road Accident. 1: Frontal collision; 2: Frontal-lateral collision; 3: Side crash; 4: Collision; 5: Pedestrian investment; 6: Impact with vehicle stopped or stopped; 7: Impact with parked vehicle; 8: Impact with obstacle; 9: Impact with train; 10: Spill, slip; 11: Accident due to sudden braking; 12: Accident due to falling from a vehicle;. '    
      items:    
        enum:    
          - 1    
          - 2    
          - 3    
          - 4    
          - 5    
          - 6    
          - 7    
          - 8    
          - 9    
          - 10    
          - 11    
          - 12    
        type: string    
      type: array    
      x-ngsi:    
        type: Property    
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
    id:    
      anyOf: &roadaccident_-_properties_-_owner_-_items_-_anyof    
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
    localId:    
      description: 'Unique identifier from the source data set'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
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
    name:    
      description: 'The name of this item.'    
      type: string    
      x-ngsi:    
        type: Property    
    numPassengersDead:    
      description: 'Number of vehicle''s passengers dead because the accident'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    numPassengersInjured:    
      description: 'Number of vehicle''s passengers injured because the accident'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    numPedestrianDead:    
      description: 'Number of pedestrians dead because the accident'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    numPedestrianInjured:    
      description: 'Number of pedestrians injured because the accident'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    owner:    
      description: 'A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)'    
      items:    
        anyOf: *roadaccident_-_properties_-_owner_-_items_-_anyof    
        description: 'Property. Unique identifier of the entity'    
      type: array    
      x-ngsi:    
        type: Property    
    pedestriansInvolved:    
      description: 'Boolean to determine if pedestrians were involved in the accidents'    
      type: boolean    
      x-ngsi:    
        type: Property    
    roadClass:    
      description: ' The classification of road where this accident took place'    
      type: string    
      x-ngsi:    
        model: https://wiki.openstreetmap.org/wiki/Key:highway    
        type: Property    
    roadIntersection:    
      description: 'Brief description of the piece of the road where the accident took place.   1: Crossroad; 2: Roundabout; 3: Reported intersection; 4: Intersection with traffic light; 5: Intersection not reported; 6: Rail crossing; 7: Straight; 8: Curve; 9: Bump, bottleneck; 10: Slope; 11: Illuminated gallery; 12: Unlit gallery;'    
      enum:    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
        - 6    
        - 7    
        - 8    
        - 9    
        - 10    
        - 11    
        - 12    
      type: string    
      x-ngsi:    
        type: Property    
    roadPaving:    
      description: 'Road paving. 1: Paved road; 2: Rough paved road; 3: Unpaved road;'    
      enum:    
        - 1    
        - 2    
        - 3    
      type: string    
      x-ngsi:    
        type: Property    
    roadSign:    
      description: 'Brief description of the road sign where the accident took place. 1: Absent; 2: Vertical; 3: Horizontal; 4: Vertical and horizontal; 5: Temporary by construction site;'    
      enum:    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
      type: string    
      x-ngsi:    
        type: Property    
    roadSurface:    
      description: 'Brief description of the condition of the road during the accident. 1: Dry; 2: Wet; 3: Slippery; 4: frozen; 5: Snowcapped;'    
      enum:    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
      type: string    
      x-ngsi:    
        type: Property    
    roadTrunk:    
      description: 'Brief description of type of trunk of the road where the accident took place. 1: Road branch; 2: Secondary branch; 3: Minor branch; 4: Junction branch; 5: Road junction; 6: Motorway left lane; 7: Highway carriageway right; 8: Motorway junction entrance; 9: Highway exit junction; 10: Highway junction trunk; 11: Highway station; 12: Other cases; 15: Extra urban road.'    
      enum:    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
        - 6    
        - 7    
        - 8    
        - 9    
        - 10    
        - 11    
        - 12    
        - 15    
      type: string    
      x-ngsi:    
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
    status:    
      description: 'Status of the Road Accident. Enum:''archived, onGoing, solved'''    
      enum:    
        - archived    
        - onGoing    
        - solved    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    totalDeadPeopleWithin24Hours:    
      description: 'Number of people dead directly because the accident'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    totalDeadPeopleWithin30Days:    
      description: 'Number of people dead because the aftermath of the accident'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    totalInjured:    
      description: 'total number of people injured (not dead) because the accident'    
      minimum: 0    
      type: integer    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    type:    
      description: 'NGSI Entity type. it has to be RoadAccident'    
      enum:    
        - RoadAccident    
      type: string    
      x-ngsi:    
        type: Property    
    vehiclesInvolved:    
      description: 'List of the vehicles (and pedestrians) involved because the accident 0 : pedestrian 1 : bicycle 2 : agriculturalVehicle 3 : bus 4 : minibus 5 : car 6 : caravan 7 : tram 8 : tanker 9 : carWithCaravan 10 : carWithTrailer 11 : lorry 12 : moped 13 : tanker 14 : motorcycle 15 : motorcycleWithSideCar 16 : motorscooter 17 : trailer 18 : van 19 : caravan 20 : constructionOrMaintenanceVehicle 21 : trolley 22 : binTrolley 23 : sweepingMachine 24 : cleaningTrolley'    
      items:    
        enum:    
          - 0    
          - 1    
          - 2    
          - 3    
          - 4    
          - 5    
          - 6    
          - 7    
          - 8    
          - 9    
          - 10    
          - 11    
          - 12    
          - 13    
          - 14    
          - 15    
          - 16    
          - 17    
          - 18    
          - 19    
          - 20    
          - 21    
          - 22    
          - 23    
          - 24    
        type: string    
      type: array    
      x-ngsi:    
        type: Property    
    weakestSubject:    
      description: 'vehicle that represent the weakest subject involved because the accident (usually pedestrian). 0 : pedestrian 1 : bicycle 2 : agriculturalVehicle 3 : bus 4 : minibus 5 : car 6 : caravan 7 : tram 8 : tanker 9 : carWithCaravan 10 : carWithTrailer 11 : lorry 12 : moped 13 : tanker 14 : motorcycle 15 : motorcycleWithSideCar 16 : motorscooter 17 : trailer 18 : van 19 : caravan 20 : constructionOrMaintenanceVehicle 21 : trolley 22 : binTrolley 23 : sweepingMachine 24 : cleaningTrolley'    
      enum:    
        - 0    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
        - 6    
        - 7    
        - 8    
        - 9    
        - 10    
        - 11    
        - 12    
        - 13    
        - 14    
        - 15    
        - 16    
        - 17    
        - 18    
        - 19    
        - 20    
        - 21    
        - 22    
        - 23    
        - 24    
      type: string    
      x-ngsi:    
        type: Property    
    weatherConditions:    
      description: 'Brief description of weather conditions during this Road Accident. 0 : clearNight 1 : sunnyDay 2 : slightlyCloudy 3 : partlyCloudy 4 : mist 5 : fog 6 : highClouds 7 : cloudy 8 : veryCloudy 9 : overcast 10 : lightRainShower 11 : drizzle 12 : lightRain 13 : heavyRainShower 14 : heavyRain 15 : sleetShower 16 : sleet 17 : hailShower 18 : hail 19 : shower 20 : lightSnow 21 : snow 22 : heavySnowShower 23 : heavySnow 24 : thunderShower 25 : thunder'    
      items:    
        enum:    
          - 0    
          - 1    
          - 2    
          - 3    
          - 4    
          - 5    
          - 6    
          - 7    
          - 8    
          - 9    
          - 10    
          - 11    
          - 12    
          - 13    
          - 14    
          - 15    
          - 16    
          - 17    
          - 18    
          - 19    
          - 20    
          - 21    
          - 22    
          - 23    
          - 24    
          - 25    
        type: string    
      type: array    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
    - status    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2021 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.Transportation/blob/master/RoadAccident/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.Transportation/RoadAccident/schema.json    
  x-model-tags: ""    
  x-version: 0.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## Exemples de charges utiles  
#### RoadAccident NGSI-v2 key-values Exemple  
Voici un exemple d'un RoadAccident au format JSON-LD sous forme de valeurs-clés. Ceci est compatible avec NGSI-v2 lorsque l'on utilise `options=keyValues` et renvoie les données contextuelles d'une entité individuelle.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:RoadAccident:id:ORHW:45620815",  
  "type": "RoadAccident",  
  "dateCreated": "2018-06-23T04:19:24Z",  
  "dateModified": "2020-10-29T08:36:40Z",  
  "source": "To be defined",  
  "name": "Name of the element of the accident.",  
  "alternateName": "Other name.",  
  "description": "Clash in the middle of a traffic light",  
  "dataProvider": "Municipality.",  
  "owner": [  
    "urn:ngsi-ld:RoadAccident:items:SUUU:18395806",  
    "urn:ngsi-ld:RoadAccident:items:GVOF:30958855"  
  ],  
  "seeAlso": [  
    "urn:ngsi-ld:RoadAccident:items:ESLS:37894243",  
    "urn:ngsi-ld:RoadAccident:items:ZNUH:87936284"  
  ],  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      -56.6404505,  
      168.370658  
    ]  
  },  
  "address": {  
    "streetAddress": "FranklinStrasse",  
    "addressLocality": "Berlin",  
    "addressRegion": "Berlin",  
    "addressCountry": "Germany",  
    "postalCode": "10387",  
    "postOfficeBoxNumber": "",  
    "areaServed": "worldwide."  
  },  
  "areaServed": "worldwide",  
  "localId": "20210312-A1.",  
  "status": "onGoing",  
  "accidentDate": "2021-03-12T13:59:36Z",  
  "accidentStatisticalDate": {  
    "year": 2021,  
    "quarter": 1,  
    "weekday": "Friday",  
    "hour": 4  
  },  
  "accidentType": [  
    "10",  
    "6"  
  ],  
  "accidentDescription": [  
    "23",  
    "46"  
  ],  
  "weatherConditions": [  
    "10",  
    "20"  
  ],  
  "roadSurface": "2",  
  "roadPaving": "2",  
  "accidentLocation": "5",  
  "roadClass": "Motorway.",  
  "roadIntersection": "8",  
  "roadTrunk": "12",  
  "roadSign": "5",  
  "pedestriansInvolved":  
    true  
  ,  
  "vehiclesInvolved": [  
    "21",  
    "6"  
  ],  
  "weakestSubject": "20",  
  "numPassengersInjured": 1,  
  "numPassengersDead": 1,  
  "numPedestrianInjured": 1,  
  "numPedestrianDead": 0,  
  "totalInjured": 2,  
  "totalDeadPeopleWithin30Days": 0,  
  "totalDeadPeopleWithin24Hours": 0  
}  
```  
</details>  
#### RoadAccident NGSI-v2 normalisé Exemple  
Voici un exemple d'un RoadAccident au format JSON-LD tel que normalisé. Ce format est compatible avec NGSI-v2 lorsqu'il n'utilise pas d'options et renvoie les données contextuelles d'une entité individuelle.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:RoadAccident:id:ORHW:45620815",  
  "dateCreated": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2018-06-23T04:19:24Z"  
    }  
  },  
  "dateModified": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2020-10-29T08:36:40Z"  
    }  
  },  
  "source": {  
    "type": "Property",  
    "value": "To be defined"  
  },  
  "name": {  
    "type": "Property",  
    "value": "Name of the element of the accident."  
  },  
  "alternateName": {  
    "type": "Property",  
    "value": "Other name."  
  },  
  "description": {  
    "type": "Property",  
    "value": "Clash in the middle of a traffic light"  
  },  
  "dataProvider": {  
    "type": "Property",  
    "value": "Municipality."  
  },  
  "owner": {  
    "type": "Property",  
    "value": [  
      "urn:ngsi-ld:RoadAccident:items:SUUU:18395806",  
      "urn:ngsi-ld:RoadAccident:items:GVOF:30958855"  
    ]  
  },  
  "seeAlso": {  
    "type": "Property",  
    "value": [  
      "urn:ngsi-ld:RoadAccident:items:ESLS:37894243",  
      "urn:ngsi-ld:RoadAccident:items:ZNUH:87936284"  
    ]  
  },  
  "location": {  
    "type": "Property",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        -56.6404505,  
        168.370658  
      ]  
    }  
  },  
  "address": {  
    "type": "Property",  
    "value": {  
      "streetAddress": "FranklinStrasse",  
      "addressLocality": "Berlin",  
      "addressRegion": "Berlin",  
      "addressCountry": "Germany",  
      "postalCode": "10387",  
      "postOfficeBoxNumber": "",  
      "areaServed": "worldwide."  
    }  
  },  
  "areaServed": {  
    "type": "Property",  
    "value": "worldwide"  
  },  
  "type": "RoadAccident",  
  "localId": {  
    "type": "Property",  
    "value": "20210312-A1."  
  },  
  "status": {  
    "type": "Property",  
    "value": "onGoing"  
  },  
  "accidentDate": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2021-03-12T13:59:36Z"  
    }  
  },  
  "accidentStatisticalDate": {  
    "type": "Property",  
    "value": {  
      "year": 2021,  
      "quarter": 1,  
      "weekday": "Friday",  
      "hour": 4  
    }  
  },  
  "accidentType": {  
    "type": "Property",  
    "value": [  
      "10",  
      "6"  
    ]  
  },  
  "accidentDescription": {  
    "type": "Property",  
    "value": [  
      "23",  
      "46"  
    ]  
  },  
  "weatherConditions": {  
    "type": "Property",  
    "value": [  
      "10",  
      "20"  
    ]  
  },  
  "roadSurface": {  
    "type": "Property",  
    "value": "2"  
  },  
  "roadPaving": {  
    "type": "Property",  
    "value": "2"  
  },  
  "accidentLocation": {  
    "type": "Property",  
    "value": "5"  
  },  
  "roadClass": {  
    "type": "Property",  
    "value": "Motorway."  
  },  
  "roadIntersection": {  
    "type": "Property",  
    "value": "8"  
  },  
  "roadTrunk": {  
    "type": "Property",  
    "value": "12"  
  },  
  "roadSign": {  
    "type": "Property",  
    "value": "5"  
  },  
  "pedestriansInvolved": {  
    "type": "Property",  
    "value": [  
      "true"  
    ]  
  },  
  "vehiclesInvolved": {  
    "type": "Property",  
    "value": [  
      "21",  
      "6"  
    ]  
  },  
  "weakestSubject": {  
    "type": "Property",  
    "value": "20"  
  },  
  "numPassengersInjured": {  
    "type": "Property",  
    "value": 1  
  },  
  "numPassengersDead": {  
    "type": "Property",  
    "value": 1  
  },  
  "numPedestrianInjured": {  
    "type": "Property",  
    "value": 1  
  },  
  "numPedestrianDead": {  
    "type": "Property",  
    "value": 0  
  },  
  "totalInjured": {  
    "type": "Property",  
    "value": 2  
  },  
  "totalDeadPeopleWithin30Days": {  
    "type": "Property",  
    "value": 0  
  },  
  "totalDeadPeopleWithin24Hours": {  
    "type": "Property",  
    "value": 0  
  }  
}  
```  
</details>  
#### Accident de la route Valeurs-clés NGSI-LD Exemple  
Voici un exemple d'un RoadAccident au format JSON-LD sous forme de valeurs-clés. Ceci est compatible avec NGSI-LD lorsque l'on utilise `options=keyValues` et renvoie les données contextuelles d'une entité individuelle.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:RoadAccident:id:ORHW:45620815",  
    "type": "RoadAccident",  
    "accidentDate": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-03-12T13:59:36Z"  
        }  
    },  
    "accidentDescription": {  
        "type": "Property",  
        "value": [  
            "23",  
            "46"  
        ]  
    },  
    "accidentLocation": {  
        "type": "Property",  
        "value": "5"  
    },  
    "accidentStatisticalDate": {  
        "type": "Property",  
        "value": {  
            "year": 2021,  
            "quarter": 1,  
            "weekday": "Friday",  
            "hour": 4  
        }  
    },  
    "accidentType": {  
        "type": "Property",  
        "value": [  
            "10",  
            "6"  
        ]  
    },  
    "address": {  
        "type": "Property",  
        "value": {  
            "streetAddress": "FranklinStrasse",  
            "addressLocality": "Berlin",  
            "addressRegion": "Berlin",  
            "addressCountry": "Germany",  
            "postalCode": "10387",  
            "postOfficeBoxNumber": "",  
            "areaServed": "worldwide."  
        }  
    },  
    "alternateName": {  
        "type": "Property",  
        "value": "Other name."  
    },  
    "areaServed": {  
        "type": "Property",  
        "value": "worldwide"  
    },  
    "dataProvider": {  
        "type": "Property",  
        "value": "Municipality."  
    },  
    "dateCreated": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2018-06-23T04:19:24Z"  
        }  
    },  
    "dateModified": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2020-10-29T08:36:40Z"  
        }  
    },  
    "description": {  
        "type": "Property",  
        "value": "Clash in the middle of a traffic light"  
    },  
    "localId": {  
        "type": "Property",  
        "value": "20210312-A1."  
    },  
    "location": {  
        "type": "Property",  
        "value": {  
            "type": "Point",  
            "coordinates": [  
                -56.6404505,  
                168.370658  
            ]  
        }  
    },  
    "name": {  
        "type": "Property",  
        "value": "Name of the element of the accident."  
    },  
    "numPassengersDead": {  
        "type": "Property",  
        "value": 1  
    },  
    "numPassengersInjured": {  
        "type": "Property",  
        "value": 1  
    },  
    "numPedestrianDead": {  
        "type": "Property",  
        "value": 0  
    },  
    "numPedestrianInjured": {  
        "type": "Property",  
        "value": 1  
    },  
    "owner": {  
        "type": "Property",  
        "value": [  
            "urn:ngsi-ld:RoadAccident:items:SUUU:18395806",  
            "urn:ngsi-ld:RoadAccident:items:GVOF:30958855"  
        ]  
    },  
    "pedestriansInvolved": {  
        "type": "Property",  
        "value": [  
            "true"  
        ]  
    },  
    "roadClass": {  
        "type": "Property",  
        "value": "Motorway."  
    },  
    "roadIntersection": {  
        "type": "Property",  
        "value": "8"  
    },  
    "roadPaving": {  
        "type": "Property",  
        "value": "2"  
    },  
    "roadSign": {  
        "type": "Property",  
        "value": "5"  
    },  
    "roadSurface": {  
        "type": "Property",  
        "value": "2"  
    },  
    "roadTrunk": {  
        "type": "Property",  
        "value": "12"  
    },  
    "seeAlso": {  
        "type": "Property",  
        "value": [  
            "urn:ngsi-ld:RoadAccident:items:ESLS:37894243",  
            "urn:ngsi-ld:RoadAccident:items:ZNUH:87936284"  
        ]  
    },  
    "source": {  
        "type": "Property",  
        "value": "To be defined"  
    },  
    "status": {  
        "type": "Property",  
        "value": "onGoing"  
    },  
    "totalDeadPeopleWithin24Hours": {  
        "type": "Property",  
        "value": 0  
    },  
    "totalDeadPeopleWithin30Days": {  
        "type": "Property",  
        "value": 0  
    },  
    "totalInjured": {  
        "type": "Property",  
        "value": 2  
    },  
    "vehiclesInvolved": {  
        "type": "Property",  
        "value": [  
            "21",  
            "6"  
        ]  
    },  
    "weakestSubject": {  
        "type": "Property",  
        "value": "20"  
    },  
    "weatherConditions": {  
        "type": "Property",  
        "value": [  
            "10",  
            "20"  
        ]  
    },  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.Transportation/master/context.jsonld"  
    ]  
}  
```  
</details>  
#### Accident de la route NGSI-LD normalisé Exemple  
Voici un exemple d'un RoadAccident au format JSON-LD tel que normalisé. Ce format est compatible avec NGSI-LD lorsqu'il n'utilise pas d'options et renvoie les données contextuelles d'une entité individuelle.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:RoadAccident:id:ORHW:45620815",  
    "type": "RoadAccident",  
    "accidentDate": "2021-03-12T13:59:36Z",  
    "accidentDescription": [  
        "23",  
        "46"  
    ],  
    "accidentLocation": "5",  
    "accidentStatisticalDate": {  
        "year": 2021,  
        "quarter": 1,  
        "weekday": "Friday",  
        "hour": 4  
    },  
    "accidentType": [  
        "10",  
        "6"  
    ],  
    "address": {  
        "streetAddress": "FranklinStrasse",  
        "addressLocality": "Berlin",  
        "addressRegion": "Berlin",  
        "addressCountry": "Germany",  
        "postalCode": "10387",  
        "postOfficeBoxNumber": "",  
        "areaServed": "worldwide."  
    },  
    "alternateName": "Other name.",  
    "areaServed": "worldwide",  
    "dataProvider": "Municipality.",  
    "dateCreated": "2018-06-23T04:19:24Z",  
    "dateModified": "2020-10-29T08:36:40Z",  
    "description": "Clash in the middle of a traffic light",  
    "localId": "20210312-A1.",  
    "location": {  
        "type": "Point",  
        "coordinates": [  
            -56.6404505,  
            168.370658  
        ]  
    },  
    "name": "Name of the element of the accident.",  
    "numPassengersDead": 1,  
    "numPassengersInjured": 1,  
    "numPedestrianDead": 0,  
    "numPedestrianInjured": 1,  
    "owner": [  
        "urn:ngsi-ld:RoadAccident:items:SUUU:18395806",  
        "urn:ngsi-ld:RoadAccident:items:GVOF:30958855"  
    ],  
    "pedestriansInvolved": [  
        "true"  
    ],  
    "roadClass": "Motorway.",  
    "roadIntersection": "8",  
    "roadPaving": "2",  
    "roadSign": "5",  
    "roadSurface": "2",  
    "roadTrunk": "12",  
    "seeAlso": [  
        "urn:ngsi-ld:RoadAccident:items:ESLS:37894243",  
        "urn:ngsi-ld:RoadAccident:items:ZNUH:87936284"  
    ],  
    "source": "To be defined",  
    "status": "onGoing",  
    "totalDeadPeopleWithin24Hours": 0,  
    "totalDeadPeopleWithin30Days": 0,  
    "totalInjured": 2,  
    "vehiclesInvolved": [  
        "21",  
        "6"  
    ],  
    "weakestSubject": "20",  
    "weatherConditions": [  
        "10",  
        "20"  
    ],  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.Transportation/master/context.jsonld"  
    ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
Voir [FAQ 10](https://smartdatamodels.org/index.php/faqs/) pour obtenir une réponse sur la façon de traiter les unités de magnitude.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
