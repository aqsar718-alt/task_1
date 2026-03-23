# Telemetry Data Converter

This project converts telemetry data from two different JSON formats into one clean and consistent format.

Basically, no matter how the input data looks, this program standardizes it into the same structure.


## What it does

- Supports 2 different input formats
- Converts both into one unified format
- Fixes differences in:
  - field names
  - structure
  - timestamp format

## Files

- data-1.json → first input format  
- data-2.json → second input format  
- data-result.json → expected output  
- main.py → main code + tests  

## How to run

Just run:

python main.py

If everything is correct, you’ll see:

Ran 3 tests  
OK  

## Note

If you get a Unicode error, fix it by using:

encoding="utf-8"

while opening JSON files.


## Author

Aqsa Rauf  
BS Physics | Python | AI | Remote Sensing
