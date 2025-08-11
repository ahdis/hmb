### Heavy Menstrual Bleeding Implementation Guide

### Simplifier.net
* Organization: Women for FHIR (https://simplifier.net/organization/women-for-fhir)
* Project: Heavy Menstrual Bleeding (https://simplifier.net/menstrual-bleeding)
* Guide: FHIR IG (https://simplifier.net/guide/hmb-fhir-ig?version=current)

This Implementation Guide (IG) is hosted on **Simplifier.net**. However, all changes to the IG must be made via this GitHub repository: https://github.com/ahdis/hmb.

### GitHub Repository
Any changes made to the master branch of this repository are automatically transferred to the IG on Simplifier via a webhook.

The generation of the FHIR resource JSON files is performed using SUSHI from the FSH (FHIR Shorthand) source files in the GitHub repository.

#### Process to generate and correctly (re-)place the files:

1. The `.fsh` files are located in the folder:   
   `hmb/input/fsh` — apply your desired changes here.
2. From the main `hmb` folder, run the SUSHI compiler:    
   ```
   sushi .
   ```
3. The generated FHIR JSON files will be located in:    
   `hmb/fsh-generated/resources`
4. Move or copy the updated files into the main folder, replacing the existing ones as needed.
