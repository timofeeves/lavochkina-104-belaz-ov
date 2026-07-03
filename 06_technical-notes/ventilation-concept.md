# Ventilation Concept Draft

## Principle

Ventilation shall be organized as a combination of:

1. general supply and exhaust ventilation for sanitary air quality and background dilution;
2. local exhaust or technological aspiration at equipment with dust, aerosols, vapors, or heat emissions;
3. direct technological exhaust gas removal from the engine test bench if the engine operates indoors;
4. compensating supply air for all exhaust systems operating in the room;
5. Teplovey T-170iH air heater used as heating/recirculation equipment, coordinated with the air balance.

## Teplovey Coordination

Known data:

- heat output: 170 kW;
- heater air flow: 17,000 m3/h;
- maximum outlet air temperature: 95 deg C;
- maximum inlet air temperature: 40 deg C.

Design position:

The Teplovey fan air flow shall not be counted as fresh air supply by default. It is circulation/heating air unless the final installation explicitly includes outside air intake and the unit is permitted to operate in that mode.

## Air Balance

Every local exhaust, aspiration system, or technological discharge that removes room air shall be compensated by supply air.

Preliminary heat estimate:

`Q = 0.335 * L * DeltaT`

where:

- `Q` is heat demand, kW;
- `L` is outdoor air flow, m3/h;
- `DeltaT` is temperature rise, deg C.

Example:

For 5,000 m3/h outdoor air and 40 deg C temperature rise:

`Q = 0.335 * 5000 * 40 = 67 kW`

This demand must be coordinated with the available 170 kW Teplovey heat output and building heat losses.

## Working Distinction

| System Type | Responsibility | Example |
|---|---|---|
| Technological exhaust | Usually technologist/equipment supplier | Engine exhaust gas pipe from test bench |
| Technological aspiration | Usually technologist/equipment supplier, coordinated with OV | Blowing chamber with filter/fan |
| Local exhaust ventilation | OV, based on technological emissions | Hood, enclosure, side suction, suction from machine guard |
| General ventilation | OV | Supply/exhaust for room air quality and compensation |
| Air heating | OV/heating | Teplovey T-170iH |
