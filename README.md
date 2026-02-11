# Digionei3 Infrastructure Image

## Configuration overview

### `anonymization/recipes`
This folder contains the anonymisation configuration:

- `recipe.dicom`: main anonymisation recipe.
- `uuids.txt`: list of accepted UUIDs. If this file is empty, any UUID is allowed.
- `ROI_normalization.yaml`: row/ROI normalisation rules used for renaming.
- `treatment.csv`: maps `patientID` values to the project they belong to.

### `DICOM_solver/Config`
This folder contains DICOM Solver configuration:

- `config.yaml`: listener and DVH configuration.

### Environment file
Use the `.env` file as an example/template for the environment variables to provide when running the stack.