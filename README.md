# Overview

Sierra Marine TS26621 Temperature Sender - SignalK

# Spec
* T=100F when R=450 ohms
* T=220F when R=46 ohms

# Function

temperature = gain * resistance + temperature_offset

220 = gain * 46 + temperature_offset

100 = gain * 450 + temperature_offset

220 - temperature_offset / 46 = gain

100 - temperature_offset / 450 = gain

220 - temperature_offset / 46 = 100 - temperature_offset / 450

220 - temperature_offset = 46 * (100 - temperature_offset) / 450

450(220-temperatureoffset) = 46 * (100 - temperature_offset)

450*220 - 450*temperature_offset = 4600 - 46*temperature_offset

temperature_offset = 450*220-4600 / 404

temperature_offset = 233.66 F

gain = 220 - temperature_offset/46

gain = 220 - 233.6/46 =  -0.2970

temperature = -0.2970 * resistance + 233.66

# Temperature / Resistance Table

| Temperature |	Resistance |
| ----------- |:----------:|
|219.998      |    46      |
|215.543      | 61         |
|211.088      | 76         |
|206.633|	91|
|202.178|	106|
|197.723|	121|
|193.268|	136|
|188.813|	151|
|184.358|	166|
|179.903|	181|
|175.448|	196|
|170.993|	211|
|166.538|	226|
|162.083|	241|
|157.628|	256|
|153.173|	271|
|148.718|	286|
|144.263|	301|
|139.808|	316|
|135.353|	331|
|130.898|	346|
|126.443|	361|
|121.988|	376|
|117.533|	391|
|113.078|	406|
|108.623|	421|
|104.168|	436|
|99.713	|       451|

