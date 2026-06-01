# Vole genome assembly manuscript resources

Repository for source-code links, accession metadata, and coordinate-conversion resources associated with the manuscript:

> **Single-library chromosome-scale diploid assemblies of vole genomes resolve a species-specific duplication implicated in pair bonding**
>
> Mohamed Abuelanin¹, Gulhan Kaya¹, Juniper A. Lake², Christine Lambert², Melody V. Wu³, Kristen M. Berendzen⁴˒⁵, Jonathan M.D. Wood⁶, Ksenia Krasheninnikova⁶, Nancy G. Solomon⁷, Zoe R. Donaldson⁸, Karen L. Bales⁹, Kerstin Howe⁶, Jonas Korlach², Devanand Manoli⁴˒⁵, Jessica Tollkuhn³, Megan Y. Dennis¹†
>
> bioRxiv 2026. doi: [10.64898/2026.03.13.711624](https://doi.org/10.64898/2026.03.13.711624)

## Repository contents

```text
2026-voles-assembly/
├── accessions.tsv                 # Public accessions for assemblies, reads, RNA-seq, and biosamples
├── annotation/                    # EGAPx gene annotation (GFF3) on the corrected hap1 coordinates
├── meadow_vole_chain_files/       # Meadow vole UCD/VGP liftOver chain resources
├── prairie_vole_chain_files/      # Prairie vole UCD/Broad Institute liftOver chain resources
└── README.md
```

The analysis tools are also included as git submodules (see the table below). Clone with `--recursive`, or run `git submodule update --init`, to populate them.

## Analysis repositories

The analysis code is maintained in the original standalone repositories below. Submodule pointers in this repository were included only as a manuscript-submission snapshot; for reuse, clone the original repositories directly.

| Analysis | Repository |
|---|---|
| HiFi + CiFi assembly and scaffolding | [`mydennislab/cifiasm`](https://github.com/mydennislab/cifiasm) |
| CiFi read QC, digestion, and filtering | [`mydennislab/cifi-toolkit`](https://github.com/mydennislab/cifi-toolkit) |
| Scaffold orientation, renaming, and liftOver chains | [`mydennislab/2026-asm-orient`](https://github.com/mydennislab/2026-asm-orient) |
| Linear chromosome ideograms | [`mydennislab/2026-genome-karyoplot`](https://github.com/mydennislab/2026-genome-karyoplot) |
| Circular genome plots | [`mydennislab/2026-genome-circos`](https://github.com/mydennislab/2026-genome-circos) |
| Candidate gene loss and Ka/Ks analyses | [`mydennislab/2026-loss-and-selection`](https://github.com/mydennislab/2026-loss-and-selection) |
| PacBio HiFi methylation browser tracks | [`mydennislab/2026-hifi-methyl-analysis`](https://github.com/mydennislab/2026-hifi-methyl-analysis) |

## Data accessions

See [`accessions.tsv`](accessions.tsv) for the full accession table.

Main study accession: `PRJEB108798`

## Citation

If you use this repository, the assemblies, or the associated analysis code, please cite:

> Mohamed Abuelanin, Gulhan Kaya, Juniper A. Lake, Christine Lambert, Melody V. Wu, Kristen M. Berendzen, Jonathan M.D. Wood, Ksenia Krasheninnikova, Nancy G. Solomon, Zoe R. Donaldson, Karen L. Bales, Kerstin Howe, Jonas Korlach, Devanand Manoli, Jessica Tollkuhn, Megan Y. Dennis. **Single-library chromosome-scale diploid assemblies of vole genomes resolve a species-specific duplication implicated in pair bonding.** bioRxiv 2026. doi: [10.64898/2026.03.13.711624](https://doi.org/10.64898/2026.03.13.711624)

## License

Each analysis tool is licensed in its own repository. Please check the license there before reuse.
