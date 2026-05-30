# Awesome Open Neuro Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open, freely available brain and nervous-system datasets.

The goal is simple: aggregate as many links to open-source brain data as we can find, organized so you can go straight to the modality and species you care about. Raw recordings, processed derivatives, atlases, and the archives that host them all count, as long as the data is openly accessible.

Everything here should be **open** (downloadable or streamable without a paywall) and **real data** (not just analysis code). A free registration or a data-usage agreement is noted in the entry. Tools and standards that the data depends on get their own section.

## Contents

- [Data Repositories & Archives](#data-repositories--archives)
- [Human](#human)
  - [MRI / fMRI](#mri--fmri)
- [Non-Human Primate](#non-human-primate)
- [Rodent](#rodent)
  - [Electrophysiology & Two-Photon Imaging](#electrophysiology--two-photon-imaging)
- [Connectomics](#connectomics)
- [Atlases & Reference Spaces](#atlases--reference-spaces)
- [Standards & Tools](#standards--tools)
- [Planned Categories](#planned-categories)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

## Data Repositories & Archives

General-purpose archives that host datasets across many labs, species, and modalities.

- [DANDI Archive](https://dandiarchive.org) - The Distributed Archives for Neurophysiology Data Integration. A NIH BRAIN Initiative archive for cellular neurophysiology data, storing everything as standardized [NWB](https://www.nwb.org) files. Hosts the OpenScope datasets and thousands of others; streamable without a full download.
- [OpenNeuro](https://openneuro.org) - A free and open archive of human neuroimaging data hosted by the Stanford Center for Reproducible Neuroscience. Thousands of [BIDS](https://bids.neuroimaging.io)-validated MRI, fMRI, EEG, MEG, iEEG, and PET datasets, all released under CC0 for maximal reuse.

## Human

### MRI / fMRI

- [Human Connectome Project](https://www.humanconnectome.org) - A landmark effort to map structural and functional connectivity of the healthy human brain, providing high-quality structural MRI, fMRI, diffusion MRI, and MEG data. De-identified data is freely available through ConnectomeDB after a free account registration.

## Non-Human Primate

- [PRIME-DE](https://fcon_1000.projects.nitrc.org/indi/indiPRIME.html) - The PRIMate Data Exchange. An open-science resource aggregating functional, diffusion, and structural MRI from non-human primates (primarily macaques) across labs worldwide. Most collections are openly downloadable; a few carry a data-usage agreement, noted per collection.

## Rodent

Mouse and rat datasets.

### Electrophysiology & Two-Photon Imaging

- [OpenScope](https://www.allenneuraldynamics.org/projects/openscope) - The Allen Institute's shared neurophysiology observatory. Like an astronomical observatory, scientists worldwide propose experiments that the Institute executes on a standardized platform, recording from thousands of neurons across the mouse brain with either multi-probe Neuropixels or multi-area two-photon calcium imaging. Every dataset is released as NWB on [DANDI](https://dandiarchive.org). See the [OpenScope Databook](https://alleninstitute.github.io/openscope_databook/) for analysis recipes and the [eLife paper](https://elifesciences.org/articles/85550) describing the Allen Brain Observatory data-sharing effort.

## Connectomics

Electron-microscopy reconstructions and wiring diagrams.

- [FlyWire](https://flywire.ai) - An openly accessible connectome of an entire adult *Drosophila* (fruit fly) brain, reconstructed from electron microscopy: ~140K neurons, 50M+ synapses, and 100K+ community annotations, AI-segmented and expert-proofread.
- [MICrONS](https://www.microns-explorer.org) - A cubic-millimeter open reconstruction of mouse visual cortex from electron microscopy, with functional two-photon imaging recorded from the same neurons before they were reconstructed. Connectivity and function in the same tissue.

## Atlases & Reference Spaces

- [Allen Brain Map](https://brain-map.org/) - The Allen Institute for Brain Science data portal: free, open-access gene-expression maps, connectivity data, cell-type taxonomies, and 3D reference atlases (including the mouse Common Coordinate Framework) across mouse and human.

## Standards & Tools

The formats and toolkits that make the data above usable.

- [Brain Imaging Data Structure (BIDS)](https://bids.neuroimaging.io) - A community standard for organizing and describing neuroimaging datasets (MRI, EEG, MEG, iEEG, PET). Used by OpenNeuro and the Human Connectome Project.
- [Neurodata Without Borders (NWB)](https://www.nwb.org) - A standardized data format for cellular-resolution neurophysiology, used by DANDI and OpenScope. Bundles raw signals, processed data, and metadata in a single self-describing file.
- [OpenScope Databook](https://alleninstitute.github.io/openscope_databook/) - A collection of reproducible Jupyter notebooks for streaming, exploring, and analyzing OpenScope (and other DANDI/NWB) datasets.

## Planned Categories

Sections we want to fill in next. Open a PR if you have datasets for any of these (or a category we are missing).

- **Human** — dedicated entries for EEG, MEG, iEEG / ECoG, PET, and fNIRS beyond the general archives.
- **Other Model Organisms** — zebrafish, additional *Drosophila* resources, C. elegans (connectome and activity).
- **Single-Cell & Transcriptomics** — spatial and single-cell brain atlases.
- **Behavior & Naturalistic** — datasets pairing neural recordings with rich behavior or naturalistic stimuli.

## Related Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The root of the awesome-list pattern, with links to lists across every domain.

## Contributing

Contributions are welcome. Read [contributing.md](contributing.md) first, then open a pull request. Keep entries open-access, accurately described, and in the right category.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See [license](license).
