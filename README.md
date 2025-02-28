# Bio-container

## Description

This Docker container contains bioinformatics tools. The container is based on Ubuntu 22.04. It includes all required
dependencies for the tools and supports parallel
assembly. It contains:

* [samtools v1.21](https://github.com/samtools/samtools)
* [bcftools v1.21](https://github.com/samtools/bcftools)
* [vcftools v0.1.16](https://github.com/vcftools/vcftools)

## Running the Container

To build and run the container in interactive mode:

    docker build -t my-bio-container . && docker run -it --rm my-bio-container

## Tool Usage

- To run **samtools**:  
  `samtools --version`

- To run **bcftools**:  
  `bcftools --version`

- To run **vcftools**:  
  `vcftools --version`