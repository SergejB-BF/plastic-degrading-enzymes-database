# Plastic-Degrading Enzymes Database
https://doi.org/10.5281/zenodo.18317183

## Data Compilation and Curation Methodology 
This database represents a comprehensive compilation of plastic-degrading enzymes gathered from multiple sources:

### Data Sources:

Existing enzyme databases (UniProt, GenBank, BRENDA)
Manual extraction from peer-reviewed research articles
Systematic literature review of plastic biodegradation studies

Curation Process:
Each enzyme entry was manually reviewed and assessed. The assessment scores (1-3) reflect the curator's expert judgment of the strength of evidence linking each enzyme to plastic degradation capability:

Assessment Score 1 (High confidence): Clear experimental evidence demonstrating plastic degradation activity, with quantified efficiency metrics or structural characterization
Assessment Score 2 (Medium confidence): Reasonable evidence from homology, computational predictions, or partial experimental validation
Assessment Score 3 (Lower confidence): Preliminary evidence or cases where research articles show correlation but lack distinct proof of enzyme-substrate degradation efficiency

Important Note: In some original research articles, there is not a distinct or clear correlation between the reported enzyme and substrate degradation efficiency. In such cases, the curator applied scientific judgment to assign appropriate confidence scores based on the available evidence. Users are encouraged to consult original sources (provided in Source_URL column) for detailed context.

## Description

This repository contains a curated database of 597 plastic-degrading enzymes including complete protein sequences, accession numbers, organism information, and quality assessments.

## Database Contents

- **Plastic types covered:** PBST, PBAT, PLA, PHB, PCL, nylon, PP, PS, PU, PUR, PVC blend, PET, HDPE, LDPE, PE, others
- **Total entries:** 597 enzymes
- **Data format:** Microsoft Excel (.xlsx)

## File Structure

- `enzyme_database.xlsx` - Complete database with all enzyme information

## Columns

| Column | Description |
|--------|-------------|
| Plastic_Type | Type of plastic the enzyme degrades (PBST/PBAT/PLA/PHB) |
| Accession_Number | Unique protein database identifier (UniProt/GenBank) |
| Protein_Sequence | Complete amino acid sequence |
| Assessment_Score | Quality rating (1=high, 2=medium, 3=lower confidence) |
| Source_URL | Link to original database entry |
| Organism | Scientific name of source organism |

## Usage

1. Download `enzyme_database.xlsx`
2. Open in Microsoft Excel or compatible software
3. Filter by plastic type or organism as needed
4. Use accession numbers to retrieve additional information from UniProt/GenBank

## Citation

If you use this database in your research, please cite:
```
[Sergej Bohinc]. (2025). Plastic-Degrading Enzymes Database. 
GitHub repository and Zenodo. https://doi.org/10.5281/zenodo.18317183
```

## License

This database is released under CC0 1.0 Universal (Public Domain). You are free to use, modify, and distribute this data for any purpose without restriction.

## Contact

**Author:** [Sergej Bohinc]  
**Email:** [your.email@institution.edu]  
**Institution:** [Biotechnical Faculty - University of Ljubljana ]

## Acknowledgments
This database was compiled through systematic review of existing protein databases and peer-reviewed literature on plastic biodegradation. We acknowledge the original researchers whose experimental work made this compilation possible.

## Last Updated

January 2026
```
