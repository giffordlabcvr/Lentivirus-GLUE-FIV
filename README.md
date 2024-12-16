## Feline Lentivirus Extension to Lentivirus-GLUE

<img src="md/puma-droplet.jpg" align="right" alt="" width="200" />

Welcome to the GitHub repository for **Lentivirus-GLUE-FIV**: an extension to **[Lentivirus-GLUE](https://github.com/giffordlabcvr/Lentivirus-GLUE)**.

Lentivirus-GLUE is a sequence-oriented resource for comparative genomic analysis of lentiviruses (family Retroviridae, genus Lentivirus), developed using the GLUE software framework.

Feline immunodeficiency virus (FIV) is a lentivirus that infects domestic and wild cats, causing an immune deficiency syndrome similar to human HIV/AIDS. First identified in the 1980s, FIV primarily spreads through bite wounds and is found worldwide, particularly in feral cat populations. The virus targets immune cells, leading to a gradual decline in immune function over time. While infected cats may live many years without severe symptoms, they become more susceptible to secondary infections. Comparative studies of FIV and other lentiviruses, including HIV, provide insights into viral evolution, immune evasion, and potential pathways for therapeutic intervention.

The FIV extension to FIV-GLUE incorporates all published FIV sequence data linked to associated metadata, including information that is sequence-associated (length, publication date); taxonomic (viral genotype, subtype); and isolate-associated (isolation host species, date and location of sampling, isolation source). 

The FIV extension of Lentivirus-GLUE provides functionality for genotyping FIV sequences via **maximum likelihood**. Genotyping can be performed on any sequence of adequate length (typically >300 nucleotides are required for confident assignment). Any genomic region can be genotyped using the approach implemented in FIV-GLUE.

Classification is based on maximum likelihood clade assignment (MLCA) as implemented in GLUE. Sequences are classified into genotypes defined via phylogenetic analysis of full-length reference genome sequences.

For more details on the FIV extension project please see the Lentivirus-GLUE **[User Guide](https://github.com/giffordlabcvr/Lentivirus-GLUE/wiki/)**.

* * * * *


Installation
------------

To install **Lentivirus-GLUE-FIV**, follow the instructions provided in the **[User Guide](https://github.com/giffordlabcvr/Lentivirus-GLUE/wiki)**.

You can choose between:

-   **[Docker-based installation](https://github.com/giffordlabcvr/Lentivirus-GLUE/wiki/Docker-Installation)** for ease of deployment.
-   **[Native installation](https://github.com/giffordlabcvr/Lentivirus-GLUE/wiki/Native-Installation)** for traditional setup.

Lentivirus-GLUE-FIV can be installed as a prebuilt database for quick setup or constructed from scratch via (a project build process) for more customization.

* * * * *

## Data Sources

**Lentivirus-GLUE-FIV** is constructed using sequence data obtained from [NCBI Nucleotide](https://www.ncbi.nlm.nih.gov/nuccore).

* * * * *


## Contributing

We welcome contributions from the community! If you're interested in contributing to Lentivirus-GLUE-FIV, please review our [Contribution Guidelines](./md/CONTRIBUTING.md).

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](./md/code_of_conduct.md)

* * * * *


## License

The project is licensed under the [GNU Affero General Public License v. 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)

* * * * *


## Contact

For questions, issues, or feedback, please open an issue on the [GitHub repository](https://github.com/giffordlabcvr/Lentivirus-GLUE-FIV/issues).

* * * * *
