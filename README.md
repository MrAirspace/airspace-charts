# airspace-charts
Files to host a tileserver for 'approach plate' background type of charts, using openmaptiles and docker:
- config.json
- style.json
- mbtiles with the chart data

Make sure to place the files in the correct directory/file_path as per the specs in the 'config.json' and 'style.json' files!

Aimed solely as 'approach plate' chart background for BlueSky ATM airspace simulation software. Charts depict topography/terrain and landmarks such as urbanisation as well as water - features generally included on airspace approach charts to support navigation and area recognition.

For rendering performance reasons, topographic features are plotted for upper and medium zoom levels only, though this can be changed by the user in the 'style.json' file.

For a step-by-step guide how to go from chart files provided in this repository to actually mapping it in BlueSky, please refer to 'Instructions.txt'. This has been tested on Linux, on Windows OS it might be recommended to use Windows Subsystem for Linux (WSL).

Data available under releases - given filesizes and correct grouping/versioning.

Examples of charts:

![approach_plate_example1](https://github.com/MrAirspace/airspace-charts/assets/144953682/1d8a03d2-7117-4dc9-963f-cc9cb5727a71)
![approach_plate_example2](https://github.com/MrAirspace/airspace-charts/assets/144953682/95606663-8317-44bd-90ef-66fd8c7822ca)
![approach_plate_example3](https://github.com/MrAirspace/airspace-charts/assets/144953682/bcfa32c7-55e3-45cf-90f2-d3306610f40c)
![approach_plate_example4](https://github.com/MrAirspace/airspace-charts/assets/144953682/2c6abc47-7662-44c9-807f-0c45beba68a2)


For tailor-made charts, please contact me.
