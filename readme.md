## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

#### steps

+ Grid name

+ Columns 

+ Indices

##### Grid 

**Grid name:** *Cars*

##### Columns 

**car_id:** *id* | PRIMARY_KEY NOT_NULL UNIQUE AUTO_INCREMENT

**car_brand:** *brand* | NOT_NULL VARCHAR(40)

**car_year:** *immatricolation year* | NOT_NULL YEAR

**car_km:** *chilometers* | NOT_NULL MEDIUMINT

**car_owners:** *number of owners* | DEFAULT(1) TINYINT

**car_fuel:** *fuel* | NOT_NULL VARCHAR(15)

**car_maintenance:** *regular basis checks* | NULL TINYINT(0/1)

**car_description** *description* | NULL TEXT

**car_value_new:** *value if new car* | NULL FLOAT(8,2)

**car_value_second_hand:** *value second hand* | NOT_NULL FLOAT(8,2)
