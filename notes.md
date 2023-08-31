Upgrades:
    Extruder
    CHC

Individual notes
    Extruder
        Would need to run the cable to the mainboard through the loom
        Ideally would want to do the extruder and CHC in one go

[extruder]
#max_extrude_cross_section: 16 ; Threw an error, might delete
max_extrude_only_distance: 100
step_pin: PB3
dir_pin: !PB4
enable_pin: !PD1
microsteps:16
full_steps_per_rotation: 200 ; Orbiter
#rotation_distance: 21.36 ; BMG
rotation_distance: 4.637 ; Orbiter 2.0
pressure_advance: 0.089 ; PLA+
#gear_ratio: 50:17 ; BMG ratio
nozzle_diameter: 0.400
filament_diameter: 1.750
heater_pin: PC8
#sensor_type: EPCOS 100K B57560G104F ; old stock heater
#sensor_type: ATC Semitec 104GT-2 ; Stock V6 all-metal hotend
sensor_type: ATC Semitec 104NT-4-R025H42G ; CHC hotend
sensor_pin: PA0
min_temp: 0
max_temp: 250
min_extrude_temp: 180

[tmc2209 extruder]
uart_pin: PC11
tx_pin: PC10
uart_address: 3
run_current: 0.80 ; guide suggests 0.85 but starting lower
hold_current: 0.100 ; From guide
sense_resistor: 0.11
stealthchop_threshold: 0
driver_TBL: 0
driver_HEND: 6
driver_HSTRT: 7
driver_TOFF: 4





ORIGINAL STEPPER DEETS

[extruder]
#max_extrude_cross_section: 16 ; Threw an error, might delete
max_extrude_only_distance: 100
step_pin: PB3
dir_pin: !PB4
enable_pin: !PD1
microsteps:16
rotation_distance: 21.36
pressure_advance: 0.089 ; PLA+
gear_ratio: 50:17 ; BMG ratio
nozzle_diameter: 0.400
filament_diameter: 1.750
heater_pin: PC8
#sensor_type: EPCOS 100K B57560G104F ; old stock heater
sensor_type: ATC Semitec 104GT-2
sensor_pin: PA0
min_temp: 0
max_temp: 250
min_extrude_temp: 180

[tmc2209 extruder]
uart_pin: PC11
tx_pin: PC10
uart_address: 3
run_current: 0.580 ; for safety
hold_current: 0.25 ; 50% of run
stealthchop_threshold: 0