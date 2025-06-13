## Creating a [README](https://data.4tu.nl/s/documents/Guidelines_for_creating_a_README_file.pdf) File

Creating a comprehensive README file is essential for enhancing the findability and reusability of your deposited research data and software in the 4TU.ResearchData repository. A well-structured README improves data organization and provides critical context, making your research outputs more accessible to others. This aligns with the [FAIR](/introduction/fair_data_and_software) principles, ensuring that your data can be efficiently discovered and utilized by other researchers.

Reusing your data not only amplifies its impact but also contributes to the advancement of knowledge in your field. When other researchers can easily access and build upon your work, it enhances your visibility, increases citations, and fosters collaboration, ultimately benefiting your academic career.

## Guidelines for Creating an Effective README File

**1. One README for each dataset:**
* Name the file README (NOT readme, read_me, ABOUT, etc.)
* Write your README as a plain text file and save it as README.txt or README.md if using [Markdown](https://en.wikipedia.org/wiki/Markdown)..
* Use README.pdf when text formatting is important for your file.

**2. Title and Project Description**
* Start with a clear title that indicates the theme of your project.
* Provide a brief overview of the project's objectives and significance.
* Include relevant contextual details for the dataset or software. 

**3. Contents Overview:**
* List all files included in the data package.
* Specify the data contained in each file or group of similar files.
* For multiple files that relate to each other, state the relationship between the files or describe the file structure that holds the dataset.
* Include contact information in case users have questions regarding data files.

**4. Detailed [Metadata](/submission_workflow/data_curation.md#Metadata-Review-Process-Checklist):**
* Describe each dataset with relevant metadata, including:
    * Variable names.
    * Units of measurement.
    * Definitions for codes or symbols used to record missing data.
    * Specialized formats or abbreviations used.
    * Full names/definitions for column headings of tabular data.
    * Methodologies used in data collection or processing.
    * Any data other than raw data that is included.
* Indicate any instrument-specific information needed to understand or interpret the data.
* List software (including version number) used to produce, prepare, render, compress, analyze, and/or needed to read the dataset, if applicable.
* State standards and calibration information, if appropriate.
* Describe any quality-assurance procedures performed on the data.
* Define codes or symbols used to note or characterize low quality/questionable/outliers that people should be aware of.

**5. Sharing and Access Information:**
* State the licensing terms you selected when submitting your data to the repository.
* This license is displayed on the metadata and informs users of their rights and restrictions.
* Read further information on license types.

**6. For Software:**
* Consider including a user guide with detailed instructions on installation and usage. This should include:
    * Dependencies or prerequisites that are required.
    * Consider using a dependency manager such as conda or pip for Python.
    * Installation Instructions: Step-by-step setup guidance. This could include:
        * Downloading software from a repository.
        * Compiling code.
        * Using a package manager.
        * Configuration Files.
        * Examples or templates needed for functionality.
    * Usage Instructions:
        * Specific requirements or dependencies for using the software associated with your data.
        * Clear steps for accessing or running scripts.

It's always better to include too much rather than too little information in your README. However, if it becomes too lengthy, consider submitting some of the information as additional files rather than omitting important details.

By following these guidelines, you will create a README file that not only enhances the discoverability of your research but also supports its reuse by providing essential context and information. This practice contributes to the overall integrity of scientific research and promotes transparency in data sharing.

**Here are some exemplary README files for datasets and software:**

**Datasets**

Forgaci, Claudiu; Adele Therias (2022): Instruments for Sustainable Urban Riverfronts (I-SURF) project data. Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/15127350

Martin Fehlmann, Miguel; Berges, Mario; Jantien Stoter; Garcia Sanchez, Clara (2025): Meteorological Observations and Radiometric Images for Cold climate Heatwave Investigations (MORICHI). Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/c5fb8062-af5d-491a-8faf-8be7fc390f48

Berentsen, Jarne; Wientjes, Emilie; Bos, Peter (2025): Data Underlying: Expansion Microscopy Reveals Thylakoid Organisation Alterations due to Genetic Mutations and Far-Red Light Acclimation. Version 1. 4TU.ResearchData. https://doi.org/10.4121/75fa3c66-8505-4d6a-9bd9-16973e5ca885

Hayo Hendrikse; Hammer, Tim C.; Marnix van den Berg; Tom Willems; Owen, Cody C. et. al. (2025): Data from ice tank tests with vertically sided structures collected during the SHIVER project. Version 2. 4TU.ResearchData. https://doi.org/10.4121/17087462

**Software**

Filippo Airaldi (2025): Source code for the publication: Nonmyopic Global Optimisation via Approximate Dynamic Programming. Version 1. 4TU.ResearchData. software. https://doi.org/10.4121/45406971-2516-4306-a69f-b2ad68e6eaea

**Additional Links**

https://www.makeareadme.com/

https://github.com/18F/open-source-guide/blob/18f-pages/pages/making-readmes-readable.md


