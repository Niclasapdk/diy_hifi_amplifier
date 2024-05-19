# Transformer considerations

My considerations for choosen a transformer for this project.
The values are chosen with a focus on making the transformer way oversized for the project because of safety margins.

## Requirements for power amplifier transformer single power amp
Primary winding 230VAC

2 Secondary windings

Power rating of over 200VA

Can sustain a current draw of 7A 

### 230VAC primary, 50VAC 2 secondary 200VA rated transformer
https://dk.rs-online.com/web/p/chassismonterede-transformere/0503916

Notes: 

Could fit the project however the rails are going to be higher than required and then the amplifier can draw more than the rated power unless a fuse is put in place or some other form of current limiting in the amplifier. Dont know about if it can tolerate the current drawn by the amplifier 

### 230VAC primary, 50VAC 2 secondary 200VA rated transformer
https://dk.farnell.com/multicomp-pro/mcp-126-200-250/chassis-mount-transformer-200va/dp/4220632

Notes: 

Cheaper than the one above and seem to have the same specs.

### 230VAC primary, 30VAC 2 secondary 200VA rated transformer
https://dk.rs-online.com/web/p/chassismonterede-transformere/0503906

Notes: 

This can deliver enough current them rails may just be too little especially after rectification.

### 230VAC primary, 20VAC 2 secondary 200VA rated transformer
https://dk.rs-online.com/web/p/chassismonterede-transformere/0503956

Notes: 

Could get two of these and wire them in series to create 40VAC, expensive solution though.

### 230VAC primary, 35VAC 2 secondary 300VA rated transformer
https://dk.rs-online.com/web/p/ringkernetransformere/1233990

### 230VAC primary, 40VAC 2 secondary 625VA rated transformer for stereo
https://dk.rs-online.com/web/p/ringkernetransformere/1233998

Notes: 

This could be the transformer for the project good price aswell. The two transformers are pretty much the same except one is rated for twice the amount of power as required by a stereo amp. Funny enough the bigger transformer is cheaper so might aswell go with it to be on the safe side of power rating.

## Requirements for microelectronics which usually run on 5V
Primary winding 230VAC

2 secondary windings

Power rating over 5VA

Secondary winding as close to 5VAC as possible.

Prefer pcb mounting

### 230VAC primary, 9VAC 2 secondary 10VA rated transformer
https://dk.rs-online.com/web/p/printmonterede-transformere/1739995

Notes:

PCB mounted, great price and not too big and fits all the criteria.