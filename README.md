# Data Lifecycle Management: Ensuring Provance and Integreity

# Motivation & Reasoning

> Container Index, Futures and Volatility

* Data Quality 
* Auditing 
* Reproducibility
* Informational Transparency


**Data Lineage** includes the data’s origins, what happens to it and
where it moves over time. Data lineage gives visibility while greatly
simplifying the ability to trace errors back to the root cause in a data
analytics process.

**Data Provenance** refers to records of the inputs, entities, systems,
and processes that influence data of interest, providing a historical
record of the data and its origins. The generated evidence supports
forensic activities such as data-dependency analysis, error/compromise
detection and recovery, auditing, and compliance analysis.

[source, Duke University](<http://people.duke.edu/~ccc14/duke-hts-2018/bioinformatics/data_provenance.html>)

## Data Integrity and Procedures

SHA-256 hashes used properly can confirm both file integrity and authenticity Comparing hashes makes it possible to detect changes in files that would cause errors. The possibility of changes (errors) is proportional to the size of the file; the possibility of errors increase as the file becomes larger. 
[source, Ubuntu Documentation](https://help.ubuntu.com/community/HowToSHA256SUM)


#### Data Tests and Additional Analysis Tools

* Date formats are inconsistent 
* An index masks underlying variation 
* Results have been p-hacked
* Provenance is not documented 
* Date formats are inconsistent 
* Zeros replace missing values 
* Author is untrustworthy 
* Collection process is opaque 
* Data assert unrealistic precision

# Conventions and Specifications

"a record that describes entities and processes involved in producing and delivering or otherwise influencing that resource. Provenance provides a critical foundation for assessing authenticity, enabling trust, and allowing reproducibility. Provenance assertions are a form of contextual metadata and can themselves become important records with their own provenance.


## Provenance management

Provenance is information about entities, activities, and people involved in producing a piece of data or thing, which can be used to form assessments about its quality, reliability or trustworthiness.

* Provenance of the workflow definition
* Provenance of a workflow run
* Provenance of data

[source, open provenance](https://openprovenance.org/)


## Resources

  - [Drewry.co.uk](https://drewry.co.uk/)

  - [Freight Trust and Clearing](<https://freighttrust.com/>)


# License

2020 © FreightTrust and Clearing Corporation
