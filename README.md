# Dataset description
In this folder are contained two subfolders whose contains fall data and non fall data, each on their respective folder, each file has an unique name which starts as "f_" for fall files and "nf_" for non fall files, all of which are in a CSV format, the data files contains a set of rows each file has a different number of rows, and each row contains 17 columns, the first one is the timestamp of the sensor read
and the 16 columns left, contains each sector temperature according to the next diagram

![alt text](diagram.png "sensor")

## Fall scenes

| Scene Name            | files         | Scene description                                   |
|-----------------------|---------------|-----------------------------------------------------|
| Normal fall scene     | f_1 - f_101   | Falling from left or the right side of the sensor   |
| Frontal fall scene    | f_102 - f_122 | Falling towards to the sensor                       |
| Chair fall scene 1    | f_123 - f_148 | Falling from a chair                                |
| Chair fall scene 2    | f_149 - f_163 | Falling from a chair sideways                       |
| Chair fall scene 3    | f_164 - f_173 | Falling from a chair sideways                       |
| Near fall scene       | f_174 - f_208 | Falling from left to right but closer to the sensor |
| Diagonal fall scene 1 | f_209 - f_222 | Falling in an angle towards the sensor              |
| Diagonal fall scene 2 | f_223 - f_238 | Falling in an angle towards the sensor              |



## Non-fall scenes

| Scene                         | files            | Scene description                                       |
|-------------------------------|------------------|---------------------------------------------------------|
| walking scene                 | nf_1 - nf_94     | Walking from left to right and right to left            |
| walking picking scene         | nf_95 - nf_136   | Simulating a walk and picking something from the ground |
| walking sitting scene         | nf_137 - nf_182  | Walking side to side and sitting in different positions |
| frontal walking scene         | nf_183 - nf_191  | Walking towards the sensor                              |
| frontal walking picking scene | nf_192 - nf_212  | Walking and picking towards the sensors                 |
| bed scene                     | nf_213  - nf_246 | Walking to a "bed" and lying on it                      |