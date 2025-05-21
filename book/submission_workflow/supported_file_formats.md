# Supported File Formats

<style>
    .responsive-iframe-container {
        position: relative;
        overflow: hidden;
        padding-top: 56.25%; /* 16:9 Aspect Ratio */
        width: 100%;
    }

    .responsive-iframe-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
    
    /* Add this block to centralize the caption */
    .caption {
        text-align: center;
        font-style: italic;
        margin-top: 8px;
        color: #666;
    }
</style>

4TU.ResearchData encourages the use of standard, exchangeable, or open file formats, which are widely recognized and supported across various platforms, ensuring that data can be easily shared and reused without compatibility issues. 

**Preferred formats include:**

* Text Formats: .txt (Unicode), .csv
* Markup Formats: .xml, .json
* Compressed Formats: .zip
* Image Formats: .tiff, .png, .jpeg

Click on [this link](https://data.4tu.nl/s/documents/Preferred_File_Formats_2023.pdf) for a full list of recommended file formats.

## NetCDF

4TU.ResearchData excels in handling Network Common Data Form (NetCDF), a self-describing format ideal for multi-dimensional array-oriented data, commonly used in atmospheric sciences and oceanography. 

**Researchers should be aware of these formats for several reasons:**

* **Self-Describing:** NetCDF files include metadata about variables and dimensions, making them machine-readable and easier to understand.
* **Efficient Data Management:** This format is well-suited for complex datasets involving temperature, humidity, and wind speed.
* **Interoperability:** NetCDF facilitates data sharing across different platforms and applications.

## Open-source Project for a Network Data Access Protocol (OPeNDAP)

This data access protocol provided by 4TU.ResearchData enables remote access to scientific datasets over the internet. It allows users to retrieve and manipulate subsets of large datasets without downloading entire files, making data sharing more efficient.

Originally developed for oceanographic and atmospheric sciences, OPeNDAP has expanded to support various scientific fields, including meteorology, climate research, and geospatial data analysis. The protocol operates through a client-server model, where a server hosts datasets and a client retrieves specific portions using standard web technologies. This eliminates the need for users to store large data files locally.

One key feature of OPeNDAP is its compatibility with multiple data formats, such as NetCDF, HDF, and CSV. It provides an API that integrates with many data analysis tools, including Python, MATLAB, and IDL, allowing seamless access to remote data sources.

Because OPeNDAP is open-source and freely available, it promotes data interoperability and collaboration among researchers. By reducing data transfer requirements and improving accessibility, OPeNDAP enhances efficiency in handling large scientific datasets.

## IIIF (International Image Interoperability Framework)

4TU.ResearchData supports the IIIF framework, which provides standardized methods for describing and delivering images over the web, enhancing interoperability across institutions. 

The decision to incorporate IIIF into the repository was made to facilitate seamless sharing and access to diverse image collections. Key benefits include:

* **Interoperability:** Enables users to access images from multiple sources using compatible viewers.
* **High-Quality Delivery:** Supports various image manipulations such as zooming, cropping, and rotation through standardized APIs.
* **Enhanced Research Capabilities:** Allows researchers to compare and analyze visual data from different projects easily.

Watch these videos for more information:

How to work with NetCDF and OPeNDAP

<div class="responsive-iframe-container">
    <iframe src="https://www.youtube.com/embed/vVhH3kp9m4M" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>

</style>

How to use NetCDF and OPeNDAP

<div class="responsive-iframe-container">
    <iframe src="https://www.youtube.com/embed/hVaH02jW7aA" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
