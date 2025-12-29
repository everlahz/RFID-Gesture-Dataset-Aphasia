# RFID-Gesture Dataset for Aphasia Patients (Anonymous Submission)
This dataset supports the paper "RF-GRA: Random Forests-Based RFID-Driven Gesture Recognition Algorithm for Aphasia Patients" (Submitted to Sensor Review).


## Dataset Overview
- **Gesture Types**: 6 daily gestures: `down`, `left`, `pop`, `push`, `right`, `up`

## Data Fields (8 Columns per CSV)
| Field         | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `epc`         | Anonymized RFID tag identifier                                              |
| `atenda`      | Anonymized RFID reader antenna name                                         |
| `atendanum`   | Numeric label of the antenna                                                |
| `phase`       | RFID signal phase                                                           |
| `RSS`         | Received Signal Strength Indicator                                          |
| `timestamp`   | Relative collection timestamp                                               |
| `timestamp2`  | Synchronized secondary timestamp                                            |