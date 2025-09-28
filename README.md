# Make-Data-Count---Finding-Data-References

🌟 Overview
This repository houses the tooling and scripts developed as part of the Make Data Count initiative, specifically focused on the critical task of identifying, parsing, and aggregating data citations found within scholarly literature and other research outputs.

The primary goal is to provide robust methods for linking research articles to the specific datasets they reference, ensuring proper credit is given to data creators, and enabling accurate metrics for data usage and impact.

💡 Background: Make Data Count
The Make Data Count (MDC) initiative advocates for the adoption of standards, infrastructure, and practices that enable the collection, processing, and exposure of open data metrics. Finding accurate data references is the foundational step for generating standardized data usage metrics (views, downloads, citations) that are FAIR (Findable, Accessible, Interoperable, Reusable).

✨ Features
This project currently supports the following capabilities:

Reference Extraction: Scripts to automatically detect potential data references (DOIs, ARKs, unique identifiers) within text files (e.g., raw text from JATS XML or PDFs).

PID Resolution: Tools to validate and resolve identified identifiers against major PID registries (e.g., DataCite, Crossref, ORCID) to confirm they point to genuine datasets.

Source Aggregation: Logic to structure the extracted citation information into a standardized format compatible with the DataCite Event Data model.

Web Integration Hooks: API endpoints or functions designed to integrate this reference-finding logic into existing scholarly infrastructure.
