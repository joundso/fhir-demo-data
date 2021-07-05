# Synthetic FHIR demo data

## How to generate new ressources/bundles

Following the instructions from [Synthea](https://github.com/synthetichealth/synthea/wiki/Basic-Setup-and-Running) you can easily create your own set of patients by:

1. Downloading synthea [here](https://github.com/synthetichealth/synthea/releases/download/master-branch-latest/synthea-with-dependencies.jar)
2. Run

    ```sh
    cd /directory/you/downloaded/synthea/to
    java -jar synthea-with-dependencies.jar -p 10
    ```

    to create 10 new patients.
