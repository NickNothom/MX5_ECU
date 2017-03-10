# MX5_ECU

This is the code that runs the engine in my MX5. It's a 1991 1.6L B6ZE with a MegaSquirt 2 ECU. I spent a couple months teaching myself how to tune it and this is the result of that. 

Still need to work out some issues with air intake temperature sensing, as my sensor gets heat soaked on warm days. 

See log below for details.

![alt text](https://github.com/NickNothom/MX5_ECU/raw/master/projectCfg/plot.jpg "Logo Title Text 1")

## Log:

### 20170311

Swapped injectors to 420cc RX8 Yellows.

### 20170312

Adjusted accel enrichment, warmup enrichment. Aiming to solve lean condition after startup and warmup. Disabled MAT correction during ASE. 
Autotune session to account for changes in rest of map. 

### 20170313
Re-endbled MAT correction because of issues on extreme cold starts. Reevaluate when warm. 

### 20170317
TODO: Adjust fuel map to be richer in low rpm range. Re-run autotune to compensate. Going lean on fast throttle up at low RPM.
