# Eukaryote taxonomic names with DOIs

Datasets linking eukaryote taxonomic names to DOIs for corresponding publications. The taxonomic names come from Index Fungorum, International Plant Names Index (IPNI) and Index of Organism Names (ION), DOIs, Wikidata QIDs, and bibliographic citations come from [Index Fungorum as a Catalogue of Life Data Package (ColDP)](https://github.com/rdmpage/index-fungorum-coldp), [International Plant Names Index (IPNI) as a Catalogue of Life Data Package (ColDP)](https://github.com/rdmpage/ipni-coldp), and [BioNames as a Catalogue of Life Data Package (ColDP)](https://github.com/rdmpage/bionames-coldp). See [Ten years and a million links: building a global taxonomic library connecting persistent identifiers for names, publications and people](https://doi.org/10.1101/2023.05.29.542697) for background to this work.

The data is provided here is a subset of the data in the above projects (for example, it only includes publications with DOIs, ignoring other persistent identifiers). The data is likely to contain errors, and updates may lag be behind the individual projects.

## Data

The data is provided in the form of tab-delimited (TSV) files, one for each of Index Fungorum, IPNI, and ION. Each file is sorted by taxonomic name, and the ID column includes a database-specific prefix so you could combine all the data into a single database if you wish.

