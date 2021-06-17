# Data Journal: nan.ai Open Data OCR
This documentation describes the source of the data, how we curated it, and the process of creating the derived data sets.

# Data Sources
Contains handwriting images from from various forms. Image quality varies (majority of the images have high compression rates due to the former onboarding process of the application).

# Derived Datasets

## Common first and last names

- What it contains: common Filipino first and last names used as inputs for autocorrect for OCR
- How it's processed: 
    - Implemented using Python
    - Images are normalized and corrected
    - Handwritten sections are isolated
    - Data is extracted using OCR and stored as values
    - A set of common Filipino first and last names is stored as a text file
- Future work:
    - As of April 2021: Extend list by adding more data extracted from handwriting images.
- Update
    - As of April 2021: Release of initial versions of the derived datasets.

## Common addresses

- What it contains: common Filipino places used as inputs for autocorrect/standardization for OCR
- How it's processed: 
    - Implemented using Python
    - Images are normalized and corrected
    - Handwritten sections are isolated
    - Data is extracted using OCR and stored as values
    - A set of common places in the Philippines is stored as a text file
- Future work
    - As of April 2021: Extend list by adding more data extracted from handwriting images.
- Update
    - As of April 2021: Release of initial versions of the derived datasets.