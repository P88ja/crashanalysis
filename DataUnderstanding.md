#Metadata Understanding

This page contains metadata definition of the data used for Crash Analysis System project. 


| Attribute Name        | Alias Name            | Description  |
| ----------------------|:---------------------:| ------------:|
|animals1|Animals|Derived variable to indicate how many times an 'Animal(s)' was struck in the crash.areaUnitID|Area Unit ID|The unique identifier of an area unit.|
|Bicycle|Bicycle|Derived variable to indicate how many bicycles were involved in the crash.|
|Bridge|Bridge|Derived variable to indicate how many times a bridge, tunnel, the abutments, handrails were struck in the crash.|
|Bus|Bus|Derived variable to indicate how many buses were involved in the crash (excluding school buses which are counted in the SCHOOL_BUS field).|
|carStationWagon|Car/Station Wagon|Derived variable to indicate how many cars or station wagons were involved in the crash.|
|cliffBank|Cliff or Bank|Derived variable to indicate how many times a 'cliff' or 'bank' was struck in the crash. This includes retaining walls|
|crashDirectionDescription|Crash Direction Description|The direction (dirn) of the crash from the reference point. Values possible are 'North', 'East', 'South' or 'West'.|
|crashDistance|Crash Distance|The distance (dist) of the crash from the reference point for the crash. The reference point is often the intersection of 'crash road' and 'side road' (refer to 'cr_rd_sd_rd' variable).|
|crashFinancialYear|Crash Financial Year|The financial (fin) year in which a crash occurred, if known. This is displayed as a string field. eg 2004/2005|
|crashLocation1|Crash Location 1|Part 1 of the 'crash location' (crash_locn). May be a road name, route position (RP), landmark, or other, e.g. 'Ninety Mile Beach'. Used for location descriptions in reports etc.|
|crashLocation2|Crash Location 2|Part 2 of the 'crash location' (crash_locn). May be a side road name, landmark etc. Used for location descriptions in reports etc.|
|crashSeverity|Crash Severity|The severity of a crash. Possible values are 'F' (fatal), 'S' (serious), 'M' (minor), 'N' (non-injury). This is determined by the worst injury sustained in the crash at time of entry.|
|crashSHDescription1|Crash SH Description|Indicates where a crash is reported to have occurred on a State Highway (SH) marked ‘1’, or on another road type marked ‘2’.crashYear|Crash Year|The year in which a crash occurred, if known.|
|Debris|Debris|Derived variable to indicate how many times debris, boulders or items dropped or thrown from a vehicle(s) were struck in the crash|
|directionRoleDescription|Direction Role Description|The direction (dirn) of the principal vehicle involved in the crash. Possible values are North, South, East or West.|
|Ditch|Ditch|Derived variable to indicate how many times a 'ditch' or 'waterable drainage channel' was struck in a crash.|
|Easting|Easting|The easting coordinate of an object (usually a crash) expressed in NZMG referred to the WGS84 datum to a precision of 1m. Please note, in some instances crashes are not able to be assigned to GPS co-ordinates. These crashes have been assigned eastings and northings of ‘0,0’ in this dataset. There are two main reasons that a GPS coordinate cannot be allocated to a crash. Firstly, that the crash has been reported but the location was unknown. Secondly in a small number of instances, a crash may have occurred on a road which is not yet captured on the CAS spatial layer.|
|fatalCount|Fatal Count|A count of the number of fatal casualties associated with this crash.|
|Fence|Fence|Derived variable to indicate how many times a 'fence' was struck in the crash. This includes letterbox(es), hoardings, private roadside furniture, hedges, sight rails, etc.|
|flatHill|Flat Hill|Whether the road is flat or sloped. Possible values include 'Flat or 'Hill'.|
|Guardrail|Guard Rail|Derived variable to indicate how many times a guard or guard rail was struck in the crash. This includes 'New Jersey' barriers, 'ARMCO', sand filled barriers, wire catch fences, etc.|
|Holiday|Holiday|Indicates where a crash occurred during a 'Christmas/New Year', 'Easter', 'Queens Birthday' or 'Labour Weekend' holiday period, otherwise 'None'.|
|houseOrBuilding|House or Building|Derived variable to indicate how many times a houses, garages, sheds or other buildings(Bldg) were struck in the crash|
|intersectionMidblock|Intersection Midblock|A derived variable to indicate if a crash occured at an intersection (intsn) or not. The 'intsn_midblock' variable is calculated using the 'intersection' and 'junction_type' variables. Values are 'Intersection' (where intersection variable = 'Intersection' or {'Intersection' = 'At Landmark' and junction_type is not in ('Unknown' or 'Driveway')} OR {Intersection = 'Unknown' and crash_dist <= 10}), otherwise 'Midblock' for crashes not meeting the criteria for 'Intersection').|
|junctionType 1|Junction Type|The type of junction the crash happened at. Possible road junctions include ‘Driveway’, ‘Roundabout’, ‘Crossroads’ , 'T Junction', 'Y Junction', or 'Multileg’. The junction type may also be unknown. Note crashes that did not occur at a junction are also given a value of unknown.|
|Kerb|Kerb|Derived variable to indicate how many times a kerb was struck in the crash, that contributed directly to the crash.|
|Light|Light|The light at the time and place of the crash. Possible values: 'Bright Sun', 'Overcast', 'Twilight, 'Dark' or ' Unknown'.|
|meshblockId|Meshblock ID|The unique identifier of a meshblock.|
|minorInjuryCount|Minor Injury Count|A count of the number of minor injuries (inj) associated with this crash.|
|Moped|Moped|Derived variable to indicate how many mopeds were involved in the crash.|
|Motorcycle|Motorcycle|Derived variable to indicate how many motorcycles were involved in the crash.|
|Northing|Northing|The northing coordinate of an object (usually a crash) expressed in NZMG referred to the WGS84 datum to a precision of 1m. Please note, in some instances crashes are not able to be assigned to GPS co-ordinates. These crashes have been assigned eastings and northings of ‘0,0’ in this dataset. There are two main reasons that a GPS coordinate cannot be allocated to a crash. Firstly, that the crash has been reported but the location was unknown. Secondly in a small number of instances, a crash may have occurred on a road which is not yet captured on the CAS spatial layer.|
|NumberOfLanes|Number of Lanes|The number(num) of lanes on the crash road.|
|objectThrownOrDropped|Object thrown or dropped|Derived variable to indicate how many times objects were thrown at or dropped on vehicles in the crash.|
|outdatedLocationDescription1|Outdated Location Description|Indicates if the location for this crash is an outdated location ‘TRUE’ if relates to the current location ‘FALSE’.otherObject|Other Object|Derived variable to indicate how many times an object was struck in a crash and the object struck was not pre-defined. This variable includes stockpiled materials, rubbish bins, fallen poles, fallen trees, etc.|
|otherVehicleType|Other Vehicle Type|Derived variable to indicate how many other vehicles (not included in any other category) were involved in the crash.|
|Overbank|Over Bank|Derived variable to indicate how many times an embankment was struck or driven over during a crash. This variable includes other vertical drops driven over during a crash.|
|parkedVehicle|Parked Vehicle|Derived variable to indicate how many times a parked or unattended vehicle was struck in the crash. This variable can include trailers.|
|phoneBoxEtc|Phone Box etc.|Derived variable to indicate how many times a telephone kiosk traffic signal controllers, bus shelters or other public furniture was struck in the crash|
|Pedestrian|Pedestrian|Derived variable to indicate how many pedestrians were involved in the crash. This includes pedestrians on skateboards, scooters and wheelchairs.|
|postOrPole|Post or Pole|Derived variable to indicate how many times a post or pole was struck in the crash. This includes light, power, phone, utility poles and objects practically forming part of a pole (i.e. 'Transformer Guy' wires)|
|Region|Region|Identifies the local government (LG) region. The boundaries match territorial local authority (TLA) boundaries|
|roadCharacter1|Road Character|The general nature of the road. Possible values include 'Bridge', 'Motorway Ramp', ‘Rail crossing’  or 'Nil'.|
|roadCurvature1|Road Curvature|The curvature of the road is simplified. Possible values include ‘Curved’ or ‘Straight’.roadLane|Road Lane|The lane configuration of the road. Possible values : '1' (one way), '2' (two way), 'M' (for where a median exists), 'O' (for off-road lane configuations), ' ' ( for unknown or invalid configuarations).|
|roadMarkings|Road Markings|The road markings at the crash site. Possible values: 'Ped Crossing' (for pedestrian crossings), 'Raised Island', 'Painted Island', 'No Passing Lanes', 'Centre Line', 'No Marks' or ' Unknown'.|
|roadSurface|Road Surface|The road surface description applying at the crash site. Possible values: 'Sealed' or 'Unsealed'.|
|Roadworks|Road works|Derived variable to indicate how many times an object associated with 'roadworks' (including signs, cones, drums, barriers, but not roadwork vehicles) was struck during the crash|
|schoolBus|School Bus|Derived variable to indicate how many school buses were involved in the crash.|
|seriousInjuryCount|Serious Injury Count|A count of the number of serious injuries (inj) associated with this crash.|
|slipOrFlood|Slip or Flood|Derived variable to indicate how many times landslips, washouts or floods (excluding rivers) were objects struck in the crash|
|speedLimit|Speed Limit|The speed (spd) limit (lim) in force at the crash site at the time of the crash. May be a number, or 'LSZ' for a limited speed zone.|
|strayAnimal|Stray Animal|Derived variable to indicate how many times a stray animal(s) was struck in the crash. This variable includes wild animals such as pigs, goats, deer, straying farm animals, house pets and birds.|
|Streetlight|Street Light|The street lighting at the time of the crash. Possible values 'On', 'Off', 'None' or ' Unknown'.|
|Suv|SUV|Derived variable to indicate how many SUVs were involved in the crash.|
|Taxi|Taxi|Derived variable to indicate how many taxis were involved in the crash.|
|tlaId|TLA ID|The unique identifier for a territorial local authority (TLA). Each crash is assigned a TLA based on where the crash occurred.|
|tlaName|TLA Name|The name of the territorial local authority (TLA) the crash has been attributed.|
|temporarySpeedLimit|Temporary Speed Limit|The temporary (temp) speed (spd) limit (lim) at the crash site if one exists (e.g. for road works).|
|trafficControl|Traffic Control|The traffic control (ctrl) signals at the crash site. Possible values are 'Traffic Signals', 'Stop Sign', 'Give Way Sign', 'Pointsman', 'School Patrol', 'Nil' or ' N/A'.|
|trafficIsland|Traffic Island|Derived variable to indicate how many times a traffic island, medians (excluding barriers)was struck in the crash.|
|trafficSign|Traffic Sign|Derived variable to indicate how many times 'traffic signage' (including traffic signals, their poles, bollards or roadside delineators) was struck in the crash.|
|Train|Train|Derived variable to indicate how many times a train, rolling stock or jiggers was struck in the crash, whether stationary or moving|
|Tree|Tree|Derived variable to indicate how many times trees or other growing items were struck during the crash.|
|Truck|Truck|Derived variable to indicate how many trucks were involved in the crash.|
|unknownVehicleType|Unknown Vehicle Type|Derived variable to indicate how many vehicles were involved in the crash (where the vehicle type is unknown).|
|Urban|Urban|A derived variable using the 'spd_lim' variable. Possible values are 'Urban' (urban, spd_lim < 80) or 'Open Road' (open road, spd_lim >=80 or 'LSZ').|
|vanOrUtility|Van or Utility|Derived variable to indicate how many vans or utes were involved in the crash.|
|Vehicle|Vehicle|Derived variable to indicate how many times a stationary attended vehicle was struck in the crash. This includes broken down vehicles, workmen's vehicles, taxis, buses.|
|waterRiver|Water River|Derived variable to indicate how many times a body of water (including rivers, streams, lakes, the sea, tidal flates, canals, watercourses or swanps) was struck in the crash.|
|weatherA|Weather A|Indicates weather at the crash time/place. See wthr_b. Values that are possible are 'Fine', 'Mist', 'Light Rain', 'Heavy Rain', 'Snow', 'Unknown'.|
|Weather|Weather B|The weather at the crash time/place. See weather_a. Values 'Frost', 'Strong Wind' or 'Unknown'.|
