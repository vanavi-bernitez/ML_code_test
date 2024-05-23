# Overview

Use NLP techniques to find the match between the vehicle references in the "Dataset_vehiculos.xlsx" and all the references in the document "Guia_CSV_331.csv". When there is a match, the corresponding code must be assigned to the "Codigo_Fasecolda" column in the vehicle dataset.

Then validate by comparing the Fasecolda code assigned to each vehicle reference with the correct Fasecolda code for that reference. Return “Yes” if the assignment is correct, otherwise return “No”.

## Main Files

- Updated_Dataset_vehiculos.xlsx: Contains the vehicle data with the Codigo_Fasecolda assigned.
- Guia_CSV_331.csv: Contains the reference guide with valid Codigo values.
- Dataset_vehiculos.xlsx: Base dataset for fasecolda code assignment
- Viviana_Bernal_Code_Test.ipynb: The main script that performs the code.

## Requirements

- Python
- Pandas
- Scikit Learn

## Setup

1. Clone the repository or download the project files to your local machine.
2. Install the required Python packages
3. Ensure the files Dataset_vehiculos.xlsx and Guia_CSV_331.csv are in the same directory as the script Viviana_Bernal_Code_Test.ipynb or change in the code the path of the files.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
