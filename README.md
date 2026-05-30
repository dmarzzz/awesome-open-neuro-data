# Awesome Open Neuro Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open, freely available brain and nervous-system datasets.

The goal is simple: aggregate as many links to open-source brain data as we can find, organized so you can go straight to the modality and species you care about. Raw recordings, processed derivatives, atlases, and the archives that host them all count, as long as the data is openly accessible.

Everything here should be **open** (downloadable without a paywall or restrictive license) and **real data** (not just analysis code). Tools and standards that the data depends on get their own section.

## Contents

- [Data Repositories & Archives](#data-repositories--archives)
- [Rodent](#rodent)
  - [Electrophysiology & Two-Photon Imaging](#electrophysiology--two-photon-imaging)
- [Standards & Tools](#standards--tools)
- [Planned Categories](#planned-categories)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

## Data Repositories & Archives

General-purpose archives that host datasets across many labs, species, and modalities.

- [DANDI Archive](https://dandiarchive.org) - The Distributed Archives for Neurophysiology Data Integration. A NIH BRAIN Initiative archive for cellular neurophysiology data, storing everything as standardized [NWB](https://www.nwb.org) files. Hosts the OpenScope datasets and thousands of others; streamable without a full download.

## Rodent

Mouse and rat datasets.

### Electrophysiology & Two-Photon Imaging

- [OpenScope](https://www.allenneuraldynamics.org/projects/openscope) - The Allen Institute's shared neurophysiology observatory. Like an astronomical observatory, scientists worldwide propose experiments that the Institute executes on a standardized platform, recording from thousands of neurons across the mouse brain with either multi-probe Neuropixels or multi-area two-photon calcium imaging. Every dataset is released as NWB on [DANDI](https://dandiarchive.org). See the [OpenScope Databook](https://alleninstitute.github.io/openscope_databook/) for analysis recipes and the [eLife paper](https://elifesciences.org/articles/85550) describing the Allen Brain Observatory data-sharing effort.

## Standards & Tools

The formats and toolkits that make the data above usable.

- [Neurodata Without Borders (NWB)](https://www.nwb.org) - A standardized data format for cellular-resolution neurophysiology, used by DANDI and OpenScope. Bundles raw signals, processed data, and metadata in a single self-describing file.
- [OpenScope Databook](https://alleninstitute.github.io/openscope_databook/) - A collection of reproducible Jupyter notebooks for streaming, exploring, and analyzing OpenScope (and other DANDI/NWB) datasets.

## Planned Categories

Sections we want to fill in next. Open a PR if you have datasets for any of these (or a category we are missing).

- **Human** — broken down by instrument: MRI / fMRI, EEG, MEG, iEEG / ECoG, PET, fNIRS.
- **Non-Human Primate** — electrophysiology, imaging.
- **Other Model Organisms** — zebrafish, drosophila, C. elegans.
- **Connectomics** — electron-microscopy reconstructions and wiring diagrams.
- **Atlases & Reference Spaces** — CCF, brain templates, gene-expression maps.

## Related Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The root of the awesome-list pattern, with links to lists across every domain.

## Contributing

Contributions are welcome. Read [contributing.md](contributing.md) first, then open a pull request. Keep entries open-access, accurately described, and in the right category.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See [license](license).
