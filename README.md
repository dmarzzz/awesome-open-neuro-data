# Awesome Open Neuro Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open, freely available brain and nervous-system datasets.

The goal is simple: aggregate as many links to open-source brain data as we can find, organized so you can go straight to the species and modality you care about. Raw recordings, processed derivatives, atlases, and the archives that host them all count, as long as the data is openly accessible.

Everything here should be **open** (downloadable or streamable without a paywall) and **real data** (not just analysis code). A free registration or a data-usage agreement is noted in the entry. Datasets gated behind a paid or committee-reviewed application are out of scope. Formats and toolkits the data depends on get their own section.

## Contents

- [Data Repositories & Archives](#data-repositories--archives)
- [Human](#human)
  - [MRI / fMRI](#mri--fmri)
  - [EEG](#eeg)
  - [MEG](#meg)
  - [Intracranial (iEEG / ECoG)](#intracranial-ieeg--ecog)
- [Non-Human Primate](#non-human-primate)
- [Rodent](#rodent)
  - [Electrophysiology](#electrophysiology)
  - [Two-Photon & Calcium Imaging](#two-photon--calcium-imaging)
- [Other Model Organisms](#other-model-organisms)
  - [Zebrafish](#zebrafish)
  - [C. elegans](#c-elegans)
  - [Other Invertebrates & Songbird](#other-invertebrates--songbird)
- [Connectomics](#connectomics)
- [Atlases & Reference Spaces](#atlases--reference-spaces)
- [Gene Expression & Transcriptomics](#gene-expression--transcriptomics)
- [Standards & Tools](#standards--tools)
- [Related Awesome Lists](#related-awesome-lists)

## Data Repositories & Archives

General-purpose archives and platforms that host datasets across many labs, species, and modalities.

- [DANDI Archive](https://dandiarchive.org) - The Distributed Archives for Neurophysiology Data Integration, a NIH BRAIN Initiative archive for cellular neurophysiology data stored as standardized [NWB](https://www.nwb.org) files. Hosts the OpenScope datasets and thousands of others; streamable without a full download.
- [OpenNeuro](https://openneuro.org) - A free and open archive of human neuroimaging data hosted by the Stanford Center for Reproducible Neuroscience. Thousands of [BIDS](https://bids.neuroimaging.io)-validated MRI, fMRI, EEG, MEG, iEEG, and PET datasets, all released under CC0.
- [EBRAINS](https://www.ebrains.eu/) - European open research infrastructure (originating in the Human Brain Project) hosting brain atlases, datasets, models, and software spanning molecular to whole-organ scales across species. Free; full access to data and tools requires a free account.
- [CRCNS.org](https://crcns.org/) - Collaborative Research in Computational Neuroscience: curated experimental datasets (sensory, motor, hippocampal, and memory-system recordings) for testing computational models. Free download after creating a free account and agreeing to the terms.
- [NeuroVault](https://neurovault.org/) - A public repository of unthresholded statistical brain maps, parcellations, and atlases from MRI and PET studies, each citable with a DOI. Fully open; no registration to browse or download.
- [NEMAR](https://nemar.org/) - The NeuroElectroMagnetic Data Archive and tools Resource, an open gateway to the human EEG, MEG, and iEEG datasets on OpenNeuro with added discovery, quality assessment, and free compute. Fully open.
- [BossDB](https://bossdb.org/) - The Brain Observatory Storage Service and Database, a cloud-native archive for petascale volumetric electron-microscopy, X-ray microtomography, and light-microscopy data plus segmentations and connectomes. Free, public access.
- [Brain Image Library (BIL)](https://www.brainimagelibrary.org/) - A public archive for large-scale brain microscopy: whole-brain light microscopy, fMOST connectivity, cell counting, and neuron morphology, part of the BRAIN Initiative ecosystem. Open access.
- [NITRC Image Repository (NITRC-IR)](https://www.nitrc.org/ir/) - The XNAT-based image-sharing component of the NeuroImaging Tools and Resources Collaboratory, sharing community MR, PET, and other neuroimaging datasets. Free NITRC account required.
- [FCP / INDI](https://fcon_1000.projects.nitrc.org/) - The International Neuroimaging Data-sharing Initiative, home of the 1000 Functional Connectomes Project and many preprocessed resting-state and structural MRI collections. Free for non-commercial use after free registration.
- [LONI Image & Data Archive (IDA)](https://ida.loni.usc.edu/) - USC's Laboratory of Neuro Imaging archive distributing neuroimaging, clinical, biospecimen, and genetic data for many consortia. Free account; individual studies impose their own data-use approval.
- [Neuroscience Multi-Omic Archive (NeMO)](https://nemoarchive.org/) - A repository for transcriptomic, epigenomic, and chromatin-accessibility data from the BRAIN Initiative, BICCN, and related projects. Mixed access: most data is open, some is controlled-access.
- [SPARC Portal](https://sparc.science/) - The NIH Common Fund "Stimulating Peripheral Activity to Relieve Conditions" portal hosting multi-species datasets, anatomical scaffolds, and models for the peripheral and autonomic nervous system. Open access.
- [G-Node GIN](https://gin.g-node.org/) - The German Neuroinformatics Node's research-data-management service (built on Git and git-annex) for versioned hosting, collaboration, and DOI minting. Free account to create repositories; public repositories are open.
- [Brain-CODE](https://www.braincode.ca/) - The Ontario Brain Institute's neuroinformatics platform aggregating Canadian research data across several neurological and psychiatric conditions. Mixed access: Public Data Releases download directly, Controlled Releases require approval.
- [BRAIN Initiative Data Archives](https://braininitiative.nih.gov/research/data-science-and-informatics/informatics-program) - The NIH BRAIN Initiative informatics page, an authoritative directory of the federated BRAIN data archives (DANDI, OpenNeuro, BossDB, NeMO, NEMAR, BIL, and more). A directory, not itself a data store.

## Human

### MRI / fMRI

- [Human Connectome Project](https://www.humanconnectome.org) - A landmark effort to map structural and functional connectivity of the healthy human brain: high-quality structural MRI, fMRI, diffusion MRI, and resting/task MEG for a subset. Free via ConnectomeDB after accepting the Open Access Data Use Terms.
- [HCP Lifespan (Aging & Development)](https://www.humanconnectome.org/study/hcp-lifespan-aging) - HCP extensions covering healthy aging (ages 36-100+) and development, with multimodal 3T MRI (structural, resting/task fMRI, diffusion, ASL) and deep behavioral data. Free via BALSA registration plus Data Use Terms.
- [ABIDE](https://fcon_1000.projects.nitrc.org/indi/abide/) - The Autism Brain Imaging Data Exchange: resting-state and structural MRI from individuals with autism and matched controls across 20+ sites (ABIDE I and II together total ~2,156 datasets). Open for non-commercial use via free INDI/NITRC registration.
- [ADHD-200](https://fcon_1000.projects.nitrc.org/indi/adhd200/) - Resting-state fMRI and T1 structural MRI from 973 children and adolescents (ADHD and typically developing) across eight sites. Open for non-commercial use via free registration; preprocessed derivatives are also mirrored.
- [1000 Functional Connectomes Project](https://fcon_1000.projects.nitrc.org/fcpClassic/FcpTable.html) - The founding open resting-state release: resting-state and anatomical MRI pooled from 1,000+ healthy adults across ~30 sites. Open for non-commercial use after free registration.
- [NKI-Rockland Sample](https://fcon_1000.projects.nitrc.org/indi/enhanced/) - A large community-ascertained lifespan sample with multiband resting-state and task fMRI, diffusion, structural MRI, and deep phenotyping. Open via free registration and data-usage agreement.
- [Natural Scenes Dataset (NSD)](https://naturalscenesdataset.org/) - High-resolution 7T fMRI from 8 adults who each viewed ~10,000 natural images over 30-40 sessions, built as a benchmark for vision and AI models. Open after signing a short free data-access agreement.
- [Midnight Scan Club](https://openneuro.org/datasets/ds000224) - A precision-mapping dataset: 10 healthy adults each scanned over 10 sessions with ~5 hours of resting-state and task fMRI plus structural MRI. Openly downloadable from OpenNeuro.
- [Individual Brain Charting (IBC)](https://openneuro.org/datasets/ds002685) - Dense-sampling, high-resolution multi-task fMRI from a fixed cohort of 12 participants across dozens of cognitive tasks, with anatomical and diffusion scans. Openly available on OpenNeuro and EBRAINS.
- [studyforrest](https://studyforrest.org/) - A naturalistic-stimulus dataset built around the movie *Forrest Gump*: fMRI (up to ~10 hours per subject), high-field imaging, eye-tracking, and rich annotations. Openly downloadable under the PDDL.
- [Narratives](https://openneuro.org/datasets/ds002345) - Naturalistic fMRI from 345 unique subjects (891 functional scans) listening to 27 spoken stories, organized in BIDS. Openly downloadable from OpenNeuro and via DataLad.
- [COBRE](https://fcon_1000.projects.nitrc.org/indi/retro/cobre.html) - Resting-state fMRI and anatomical MRI from 72 patients with schizophrenia and 75 healthy controls, with phenotypic data. Open for non-commercial use via INDI/COINS.
- [IXI Dataset](https://brain-development.org/ixi-dataset/) - Nearly 600 MRI scans from healthy subjects across three London hospitals, including T1, T2, PD-weighted, MRA, and diffusion images with demographics. Freely downloadable under CC BY-SA 3.0.
- [OASIS](https://sites.wustl.edu/oasisbrains/) - The Open Access Series of Imaging Studies: multi-release MRI (plus fMRI, diffusion, and PET in later releases) spanning healthy aging and Alzheimer's disease, including the multi-thousand-session OASIS-3. Open, with later releases via a free data-use agreement.
- [AOMIC](https://nilab-uva.github.io/AOMIC.github.io/) - The Amsterdam Open MRI Collection: three large BIDS datasets (ID1000, PIOP1, PIOP2) of resting-state and task fMRI, diffusion, and structural MRI with rich psychometrics. Openly downloadable from OpenNeuro.
- [BOLD5000](https://bold5000-dataset.github.io/website/) - Slow event-related fMRI from 4 subjects who each viewed 5,000 real-world images (Scene, COCO, ImageNet), a benchmark for vision and AI. Openly downloadable.
- [SALD](https://fcon_1000.projects.nitrc.org/indi/retro/sald.html) - The Southwest University Adult Lifespan Dataset: resting-state fMRI and structural MRI from 494 healthy adults aged 19-80. Open via free registration.
- [MyConnectome](https://openneuro.org/datasets/ds000031) - A deep-phenotyping single-subject study: ~100 sessions of resting-state and task fMRI, diffusion, and structural MRI from one individual over 18 months. Openly downloadable from OpenNeuro.
- [Courtois NeuroMod](https://www.cneuromod.ca/) - A deep-sampling dataset recording a small cohort over years of naturalistic and task fMRI (movies, video games, audio), distributed via DataLad. Open after agreeing to the access terms.
- [Generic Object Decoding (Kamitani)](https://openneuro.org/datasets/ds001246) - fMRI from subjects viewing and imagining objects across 150+ categories, used for neural decoding and image reconstruction. Openly downloadable from OpenNeuro.
- [Healthy Brain Network MRI](https://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/) - A large transdiagnostic pediatric resource: resting-state and movie-watching fMRI, diffusion, and structural MRI from thousands of children and adolescents. Imaging is openly downloadable; richer phenotypes require an agreement.

### EEG

- [Temple University Hospital EEG Corpus (TUH EEG)](https://isip.piconepress.com/projects/tuh_eeg/) - The largest open clinical EEG corpus, with tens of thousands of recordings and annotated subsets for seizures, epilepsy, and artifacts. Free for research and commercial use after emailing a signed registration form (no fee).
- [PhysioNet EEG Motor Movement/Imagery](https://physionet.org/content/eegmmidb/1.0.0/) - 64-channel EEG from 109 subjects recorded during real and imagined motor tasks plus eyes-open/closed baselines. Fully open under the Open Data Commons Attribution License.
- [ERP CORE](https://doi.org/10.18115/D5JW4R) - EEG/ERP data from 40 participants across seven optimized paradigms (N170, MMN, N2pc, N400, P3b, LRP, ERN), bundled with experiment and analysis scripts. Open under CC BY-SA 4.0.
- [Healthy Brain Network EEG](https://neuromechanist.github.io/data/hbn/) - High-density EEG from 3,000+ children and adolescents (ages 5-21) across six passive and active tasks, a transdiagnostic pediatric mental-health resource. The EEG is openly downloadable via NEMAR, OpenNeuro, and S3; richer phenotypic data requires a signed agreement.
- [MPI-Leipzig Mind-Brain-Body (LEMON)](https://openneuro.org/datasets/ds000221) - A multimodal dataset of MRI, 62-channel resting-state EEG, cognition, emotion, and physiology from 228 healthy young and older adults. Fully open under a public-domain dedication.
- [Mother of All BCI Benchmarks (MOABB)](https://moabb.neurotechx.com/docs/dataset_summary.html) - An open framework giving standardized, MNE-compatible access to 150+ public EEG/BCI datasets (motor imagery, P300/ERP, SSVEP, code-VEP, resting state). Software is open; most underlying datasets are openly licensed, a few need separate access.
- [BNCI Horizon 2020 Database](http://bnci-horizon-2020.eu/database/data-sets) - A repository of ~32 open-access BCI/EEG datasets (motor imagery, P300 spellers, auditory oddball, some ECoG/fNIRS) as downloadable MATLAB files. Open under Creative Commons (some carry NC/ND terms).

### MEG

- [MOUS (Mother Of Unification Studies)](https://doi.org/10.34973/37n0-yc51) - MEG and fMRI from 204 healthy adults performing a language task plus resting state, in BIDS format on the Donders Repository. Openly downloadable.
- [MNE-Python Sample Datasets](https://mne.tools/stable/documentation/datasets.html) - Bundled example datasets for MNE-Python, including a simultaneous MEG/EEG recording (with MRI) from an audiovisual paradigm, fetched programmatically. Openly accessible; intended for learning and testing.

### Intracranial (iEEG / ECoG)

- [iEEG-fMRI Naturalistic Film (ds003688)](https://openneuro.org/datasets/ds003688) - A multimodal dataset from subjects watching a short audiovisual film: iEEG from 51 subjects, fMRI from 30, with detailed speech/video annotations. Freely downloadable under a public-domain dedication.
- [Kai Miller Human ECoG Library](https://purl.stanford.edu/zk881ps0522) - A standardized library of 204 ECoG datasets from 34 patients across 16 behavioral experiments, with electrode-to-anatomy registration and analysis code. Fully open via the Stanford Digital Repository, no registration.
- [UPENN / RAM Intracranial Memory Data (ds004789)](https://openneuro.org/datasets/ds004789) - Intracranial EEG from epilepsy patients performing verbal free-recall and related memory tasks, largely from the DARPA Restoring Active Memory project, with electrode localizations in BIDS. Freely downloadable from OpenNeuro.
- [DANDI 000623 (single-neuron + iEEG + fMRI)](https://dandiarchive.org/dandiset/000623) - Multimodal recordings from 16 human epilepsy patients watching a film: single-neuron spikes, LFP, iEEG, eye tracking, and fMRI in NWB/BIDS. Openly downloadable under CC-BY-4.0.
- [IEEG.org](https://www.ieeg.org/) - The International Epilepsy Electrophysiology Portal, a NINDS-funded archive of 1200+ human and animal intracranial EEG datasets with imaging and de-identified clinical metadata, browsable and streamable in-platform. Free user account required.

## Non-Human Primate

- [PRIME-DE](https://fcon_1000.projects.nitrc.org/indi/indiPRIME.html) - The PRIMate Data Exchange, an open-science resource aggregating functional, diffusion, and structural MRI from non-human primates (primarily macaques) across labs worldwide. Most collections download freely; a few carry a data-usage agreement, noted per collection.
- [Marmoset Brain Mapping](https://marmosetbrainmapping.org/atlas.html) - A multi-version suite of marmoset brain resources from the Silva lab (NIH): multi-modal MRI templates, white-matter tractography atlases, awake resting-state functional connectivity, cortical surfaces, and neuronal tracing. Openly downloadable in NIfTI/GIFTI with online viewers.
- [Marmoset Brain Connectivity Atlas](https://www.marmosetbrain.org/) - A public repository of 143 retrograde fluorescent tracer injections mapping cellular-resolution corticocortical connectivity in the marmoset, registered to a common stereotaxic space. Open under CC-BY-SA 4.0.
- [Brain/MINDS 3D Marmoset Reference Atlas](https://dataportal.brainminds.jp/atlas-package-download-main-page) - RIKEN's 3D digital marmoset brain atlas with normalized multi-modal data (ex vivo T2 MRI, registered Nissl, cortical and subcortical segmentation) in NIfTI, with a 3D Slicer scene. Freely downloadable.
- [Brain/MINDS Marmoset Brain MRI (NA216/eNA91)](https://dataportal.brainminds.jp/marmoset-mri-na216) - The largest public marmoset MRI resource: 483 individuals with T1/T2, diffusion, resting-state fMRI, labels, and connectome matrices in NIfTI/CSV. Open under CC-BY 4.0 via the Brain/MINDS GIN server and DataLad.
- [Brain/MINDS Marmoset Calcium Imaging](https://dataportal.brainminds.jp/caimaging-okano-1) - In vivo one- and two-photon calcium imaging of motor-cortex populations in behaving marmosets, with raw microendoscope TIFFs, extracted time-series, and NWB files. Open under CC-BY 4.0.
- [NMT, CHARM, SARM & D99 Macaque Atlases](https://afni.nimh.nih.gov/NMT) - The NIMH Macaque Template (NMT v2), a group template built from 31 rhesus macaques, bundled with the CHARM cortical, SARM subcortical, and D99 atlases in NIfTI/GIFTI at multiple resolutions. Freely downloadable via AFNI.
- [Neurotycho](http://neurotycho.org/) - RIKEN's open ECoG repository: 128-channel invasive macaque recordings across awake, anesthesia, sleep, visual, and food-tracking tasks, plus simultaneous EEG/ECoG. Released as MATLAB files under CC0.
- [TheVirtualBrain Macaque MRI (ds001875)](https://openneuro.org/datasets/ds001875) - Unprocessed structural, diffusion, and resting-state functional MRI from rhesus macaques in BIDS (~11.5 GB), supporting macaque connectome simulations. Freely downloadable from OpenNeuro under CC0.
- [Macaque Color, Contrast & Spatial Frequency (ds005521)](https://openneuro.org/datasets/ds005521) - Functional MRI from two adult rhesus macaques probing color, contrast, and spatial-frequency tuning, in BIDS (~38.8 GB). Freely downloadable from OpenNeuro under CC0.
- [Brain Catalogue](https://braincatalogue.org/) - An Institut Pasteur online viewer and repository of brain scans across 34 primate species, including macaque, gorilla, and chimpanzee. Viewable and downloadable as NIfTI under CC-BY-SA 3.0.
- [Freiwald & Tsao Macaque Face-Patch Recordings](https://readout.info/downloads/datasets/freiwald-tsao-face-views-am-dataset/) - Single-unit electrophysiology from the macaque face-patch system recorded while monkeys viewed 25 identities across 8 head orientations, distributed via the Neural Decoding Toolbox. Openly downloadable (citation required).

## Rodent

### Electrophysiology

- [OpenScope](https://www.allenneuraldynamics.org/projects/openscope) - The Allen Institute's shared neurophysiology observatory: scientists worldwide propose experiments executed on a standardized platform, recording from thousands of neurons across the mouse brain with multi-probe Neuropixels or multi-area two-photon imaging. Released as NWB on [DANDI](https://dandiarchive.org). See the [OpenScope Databook](https://alleninstitute.github.io/openscope_databook/) and the [eLife paper](https://elifesciences.org/articles/85550).
- [International Brain Laboratory (IBL) Brain-Wide Map](https://www.internationalbrainlab.com/data) - Standardized Neuropixels recordings from hundreds of mice performing a single decision-making task, spanning the whole brain. Fully open under CC-BY via direct links, the ONE API, or the Data Explorer.
- [Allen Visual Coding - Neuropixels](https://brain-map.org/circuits-behavior/visual-coding-neuropixels) - Simultaneous Neuropixels recordings of ~100,000 neurons across mouse cortex, hippocampus, and thalamus during standardized visual stimuli. Freely downloadable via the AllenSDK.
- [Steinmetz et al. 2019 Neuropixels Dataset](https://figshare.com/articles/dataset/Dataset_from_Steinmetz_et_al_2019/9598406) - Neuropixels recordings of ~30,000 neurons across 42 mouse brain regions during a visual discrimination task (Nature 2019). Freely downloadable from figshare; also in NWB and via the Open Neurophysiology Environment.
- [CRCNS hc-3 (Buzsaki Hippocampus)](https://crcns.org/data-sets/hc/hc-3) - Extracellular recordings of 7,737 neurons across rat CA1, CA3, dentate gyrus, and entorhinal cortex over 442 sessions during spatial behaviors. Free download with a CRCNS.org account.
- [Buzsaki Lab Databank](https://buzsakilab.com/wp/database/) - Over 1,000 sessions (~40 TB) of extracellular silicon-probe and intracellular recordings from freely-moving rats and mice across many regions. Openly shared via a Globus endpoint and web share; a subset mirrored on CRCNS.
- [Svoboda / Janelia ALM-1](https://crcns.org/data-sets/motor-cortex/alm-1) - Extracellular electrophysiology from mouse anterior lateral motor cortex during a tactile decision-making task (Li, Chen et al., Nature 2015). Free download with a CRCNS.org account.
- [Allen Institute for Neural Dynamics (AIND) Open Data](https://registry.opendata.aws/allen-nd-open-data/) - Mouse neurophysiology (multi-Neuropixels electrophysiology, imaging, fiber photometry, behavior) from foraging and decision experiments, shared near real-time. Fully open under CC-BY-4.0 via a public AWS S3 bucket and DANDI.
- [Neuropixels Ultra Datasets](https://npultra.steinmetzlab.net/) - Ultra-high-density Neuropixels recordings of thousands of single-unit spatiotemporal waveforms from awake mice across many regions. Browsable online; data freely downloadable from figshare and DANDI (dandiset 000957).
- [UCL Cortexlab Data](https://www.ucl.ac.uk/cortexlab/data) - Open datasets from the Carandini and Harris labs in mice: Neuropixels (single, dual, and eight-probe), widefield calcium imaging, and responses of ~10,000 neurons to gratings and natural images. Freely available via figshare and the UCL repository.

### Two-Photon & Calcium Imaging

- [Allen Brain Observatory - Visual Coding 2-Photon](https://observatory.brain-map.org/visualcoding) - Hundreds of two-photon calcium-imaging sessions (GCaMP6) across mouse visual-cortex areas and depths under standardized visual stimuli. Open via the web portal and AllenSDK; data on AWS in NWB.
- [Allen Visual Behavior - 2-Photon](https://brain-map.org/circuits-behavior/visual-behavior-2p) - Two-photon imaging (GCaMP6f) of 34,619 mouse visual-cortex neurons over 551 sessions, with the same populations re-imaged across days during a change-detection task. Open via the AllenSDK.
- [Stringer & Pachitariu Spontaneous-Activity Recordings](https://janelia.figshare.com/articles/dataset/Recordings_of_ten_thousand_neurons_in_visual_cortex_during_spontaneous_behaviors/6163622) - Two-photon recordings of ~10,000 mouse visual-cortex neurons during spontaneous behavior, with a companion eight-probe Neuropixels release. Freely downloadable from Janelia figshare with analysis code on GitHub.

## Other Model Organisms

### Zebrafish

- [Larval Zebrafish Whole-Brain Light-Sheet (Chen et al. 2018)](https://janelia.figshare.com/articles/dataset/Whole-brain_light-sheet_imaging_data/7272617) - Whole-brain neuronal activity from 18 larval zebrafish (~100,000 neurons each) by light-sheet calcium imaging during visually-evoked behaviors, from the Ahrens lab. Open under CC BY-NC 4.0.
- [Janelia Whole-Brain Functional Recordings (Ahrens et al. 2013)](https://www.janelia.org/open-science/whole-brain-functional-recordings) - The foundational larval-zebrafish whole-brain light-sheet dataset, capturing activity across ~80% of all neurons at single-cell resolution, with analysis software. Freely available.
- [mapzebrain](https://mapzebrain.org/home) - A multimodal anatomical atlas of the 6 dpf larval zebrafish brain integrating expert-annotated regions, transgenic labels, traced single-neuron morphologies, and EM reconstructions in a common space. Free to view and download.
- [Z-Brain](https://zebrafishexplorer.zib.de/) - An open neuroanatomical reference atlas of the 6 dpf larval zebrafish brain built from hundreds of registered brains, with ~294 segmented regions and molecular labels. Freely available.
- [Zebrafish Brain Browser](https://zenodo.org/records/3367709) - 3D-registered confocal expression patterns for 264 transgenic and enhancer-trap lines in 6 dpf larval zebrafish, browsable online and downloadable as a package. Reference brains under CC BY 4.0.

### C. elegans

- [WormID Whole-Brain Corpus](https://wormid.org/) - A harmonized corpus of *C. elegans* whole-brain imaging from 118 worms across 5 labs, combining NeuroPAL structural volumes and GCaMP calcium time series in NWB. Open via the DANDI archive.
- [Kato et al. 2015 Whole-Brain Imaging](https://osf.io/2395t/) - Whole-brain calcium-imaging recordings of immobilized *C. elegans* capturing global dynamics underlying the motor command sequence (Cell 2015). Publicly downloadable on the Open Science Framework.
- [NeuroPAL](https://www.hobertlab.org/neuropal/) - A *C. elegans* multicolor transgene and atlas for whole-brain single-neuron identification, with open-source auto-ID software plus volumetric images and activity recordings on Zenodo. Open.
- [OpenWorm](https://openworm.org/) - An open-science effort to build a complete computational model of *C. elegans*, including a NeuroML connectome of every neuron and connection plus the Sibernetic body-physics simulator. Code and models released under the MIT license.

### Other Invertebrates & Songbird

- [Whole-Body Neural Activity in Hydra (Hanson et al. 2024)](https://datadryad.org/landing/show?id=doi:10.5061/dryad.h9w0vt4q3) - Dual-channel calcium-imaging movies of whole-body neural activity at single-cell resolution in behaving *Hydra vulgaris*. Openly downloadable under CC0.
- [Chronic HVC Recordings in Singing Zebra Finches](https://figshare.com/articles/dataset/Chronic_Recording_of_HVC_in_Free_Behaving_Zebra_FInch_with_Behaviors_Hand_Annotated/15094219) - Songbird chronic silicon-probe electrophysiology from premotor nucleus HVC during free singing, with synchronized audio and hand-annotated vocalizations. Open under CC BY 4.0.

## Connectomics

Electron-microscopy reconstructions, wiring diagrams, and the services that query them.

- [FlyWire](https://flywire.ai) - An openly accessible connectome of an entire adult *Drosophila* brain reconstructed from electron microscopy: ~140K neurons, 50M+ synapses, and 100K+ community annotations, AI-segmented and expert-proofread.
- [MICrONS](https://www.microns-explorer.org/cortical-mm3) - A cubic-millimeter reconstruction of mouse visual cortex (>200,000 cells, >500 million synapses) co-registered with two-photon imaging of ~75,000 of the same neurons. Open via public AWS/GCP buckets and CAVE tools.
- [H01 (Human Cortex 1mm³)](https://h01-release.storage.googleapis.com/landing.html) - A Harvard (Lichtman lab) and Google reconstruction of ~1 mm³ of human temporal cortex: a 1.4-petabyte EM volume with tens of thousands of neurons and 183 million annotated synapses. Browsable via Neuroglancer with programmatic access.
- [FAFB (Full Adult Fly Brain)](https://temca2data.org/) - Serial-section EM of a complete adult *Drosophila* brain at synaptic resolution (Zheng, Lauritzen et al. 2018), available via Virtual Fly Brain/CATMAID and bulk download. CC BY-NC 4.0 (non-commercial).
- [Janelia Hemibrain](https://www.janelia.org/project-team/flyem/hemibrain) - A dense synaptic-resolution reconstruction of a large portion of the adult *Drosophila* central brain (~25,000 neurons). Released CC-BY and queryable through neuPrint.
- [Male CNS Connectome (Drosophila)](https://www.janelia.org/project-team/flyem/male-cns-connectome) - The first complete connectome of an entire male *Drosophila* central nervous system (central brain, optic lobes, and ventral nerve cord). Released CC-BY via neuPrint, Neuroglancer, and direct download.
- [MANC (Male Adult Nerve Cord)](https://www.janelia.org/project-team/flyem/manc-connectome) - A dense connectome of the adult male *Drosophila* ventral nerve cord (~23,000 neurons), the first complete nerve cord connectome. Released CC-BY via neuPrint and a public Google bucket.
- [Larval Drosophila Connectome](https://github.com/brain-networks/larval-drosophila-connectome) - The complete synaptic-resolution connectome of a *Drosophila* larva brain (3,016 neurons, ~548,000 synapses) from Winding et al. 2023. Connectivity data openly available on GitHub.
- [C. elegans Connectome (WormWiring)](https://www.wormwiring.org/) - EM reconstructions of the *C. elegans* nervous system, hosting both the foundational White et al. 1986 connectome and the Cook et al. 2019 whole-animal hermaphrodite and male connectomes. Freely downloadable as spreadsheets.
- [Larval Zebrafish Whole-Brain EM (Hildebrand et al. 2017)](https://neurodata.io/data/hildebrand17/) - Multi-resolution serial-section EM of the anterior quarter of a larval zebrafish including the complete brain (~2.7 TB), with aligned data and reconstructions. Open access.
- [Eyewire / e2198 Mouse Retina](https://blog.eyewire.org/behind-the-science-about-the-data/) - The Seung lab's citizen-science reconstruction of neurons from e2198, a serial block-face SEM volume of adult mouse retina. Reconstruction data and meshes openly available on GitHub.
- [neuPrint](https://neuprint.janelia.org/) - Janelia's open-access web service for querying EM connectomes as a graph (browser, Cypher, Python, R), hosting public *Drosophila* datasets including the hemibrain, MANC, and male CNS connectomes. Free; some access requires a Google login.

## Atlases & Reference Spaces

- [Allen Mouse Brain Common Coordinate Framework (CCFv3)](https://atlas.brain-map.org/) - A 3D average-template reference atlas of the adult mouse brain at 10 µm resolution, parcellating every voxel into ~660 structures. Openly accessible and the standard mouse coordinate space.
- [BigBrain](https://bigbrainproject.org/) - The first openly accessible microscopic-resolution (20 µm) 3D histological model of a single human brain, over 1 TB of data. Open under CC BY-SA 4.0.
- [Julich-Brain Atlas](https://julich-brain-atlas.de/) - 3D probabilistic cytoarchitectonic maps of 200+ human cortical areas and subcortical nuclei, integrating fiber architecture and receptor distributions, served via EBRAINS. Open and free.
- [Waxholm Space Atlas of the Sprague Dawley Rat Brain](https://www.nitrc.org/projects/whs-sd-atlas) - A volumetric atlas of 222 anatomical structures delineated in isotropic MRI and DTI, the standard rat coordinate space. Open under CC BY 4.0.
- [Scalable Brain Atlas](https://scalablebrainatlas.incf.org/) - A web platform giving interactive 2D/3D access to 20+ public brain atlas templates and parcellations across species (human, macaque, marmoset, mouse, rat, ferret), with an API. Publicly accessible.
- [MNI ICBM152 2009 Nonlinear Templates](https://nist.mni.mcgill.ca/icbm-152-nonlinear-atlases-2009/) - The standard stereotaxic human brain templates (symmetric and asymmetric, 0.5-1 mm), the default reference space for most human neuroimaging, in MINC and NIfTI under a permissive license.
- [fsaverage (FreeSurfer)](https://surfer.nmr.mgh.harvard.edu/fswiki/FsAverage) - The standard FreeSurfer surface-based average template for cortical surface analysis, distributed as part of the open-source FreeSurfer package.
- [Talairach Daemon Atlas](https://www.nitrc.org/projects/tal-daemon/) - A digitized version of the classic 1988 Talairach reference atlas with a coordinate-to-label database, distributed openly via NITRC, FSL, and PickAtlas.
- [Brainnetome Atlas](https://atlas.brainnetome.org/) - A connectivity-based parcellation of the human brain into 246 subregions with anatomical and functional connection patterns, freely downloadable in NIfTI.
- [AAL3 Atlas](https://www.gin.cnrs.fr/en/tools/aal/) - The widely used Automated Anatomical Labeling atlas (version 3), a macroscopic parcellation of the human brain in NIfTI, released under the GNU GPL.
- [Schaefer / Yeo Parcellations](https://github.com/ThomasYeoLab/CBIG/tree/master/stable_projects/brain_parcellation/Schaefer2018_LocalGlobal) - Resting-state functional-connectivity parcellations of the human cortex from 100 to 1000 parcels, derived from 1,489 subjects, in NIfTI, GIFTI, and CIFTI.
- [Allen Mouse Brain Connectivity Atlas](https://connectivity.brain-map.org/) - A whole-brain mesoscale connectome of the mouse built from hundreds of anterograde AAV tracing experiments, freely accessible via web, API, and SDK.

## Gene Expression & Transcriptomics

- [Allen Mouse Brain Atlas (ISH)](https://mouse.brain-map.org/) - A genome-wide map of gene expression in the adult mouse brain via in situ hybridization, with a paired reference atlas and Brain Explorer viewer. Freely accessible.
- [Allen Human Brain Atlas (microarray)](https://human.brain-map.org/) - Genome-wide microarray gene-expression data sampled across hundreds of structures in 6 adult human donor brains, with accompanying MRI for spatial reference. Freely downloadable via web, CSV, and API.
- [Allen Brain Cell (ABC) Atlas](https://brain-map.org/atlases-and-data/bkp/abc-atlas) - A platform integrating whole-brain single-cell RNA-seq and MERFISH spatial transcriptomics into a hierarchical cell-type taxonomy (mouse ~4M cells, plus human data). Hosted on AWS, no login; CC BY-NC-SA 4.0.
- [Allen Cell Types Database](https://celltypes.brain-map.org/) - A single-cell survey combining patch-clamp electrophysiology, 3D morphology reconstructions, and RNA-seq from mouse and human cortical cells. Freely downloadable via web tools, API, or the Allen SDK.
- [BICCN / BICAN](https://biccn.org/) - The BRAIN Initiative Cell Census Network: a multimodal reference of brain cell types (transcriptomic, epigenomic, morphological, electrophysiological) across mouse, human, and non-human primate. QC-passing data is public via the R24 archives.
- [BrainSpan: Atlas of the Developing Human Brain](https://www.brainspan.org/) - A developmental transcriptome spanning prenatal-to-adult human brain via RNA-seq and exon microarray, plus prenatal microarray and ISH image data. Freely accessible.
- [Human Protein Atlas - Brain](https://www.proteinatlas.org/humanproteome/brain) - Spatial profiling of the brain combining antibody-based protein localization and RNA expression across 13 anatomical regions, with cross-species comparison. Open under CC BY 4.0 with bulk downloads.
- [CZ CELLxGENE Discover](https://cellxgene.cziscience.com/) - The largest standardized aggregation of single-cell data (44M+ human, 16M+ mouse cells), including many brain datasets, queryable via web explorer and Python/R APIs. Free; data reusable under CC BY.
- [Tabula Muris](https://tabula-muris.sf.czbiohub.org/) - A single-cell transcriptomic compendium of ~100,000 cells across 20 mouse organs including brain tissue. Open under CC BY 4.0.
- [Linnarsson Lab Mouse Brain Atlas](http://mousebrain.org/) - A single-cell RNA-seq atlas of the mouse nervous system (~500k cells) plus a developing-brain atlas, with a data-driven cell-type taxonomy and downloadable loom files. Freely available.
- [Allen Developing Mouse Brain Atlas](https://developingmouse.brain-map.org/) - Genome-scale in situ hybridization gene-expression maps across embryonic and postnatal mouse brain development, freely accessible via web and API.
- [GTEx Portal (brain)](https://gtexportal.org/home/) - Bulk RNA-seq across 13 human brain regions (plus single-nucleus data) from hundreds of postmortem donors; summary expression and TPMs are openly downloadable, with raw data under controlled access.
- [Human Cell Atlas Data Portal](https://data.humancellatlas.org/) - The HCA's open multi-omic repository of ~70 million cells across hundreds of projects, including nervous-system datasets, with downloads in loom, h5ad, and fastq under CC BY 4.0.
- [CZ Single Cell Portal (Broad)](https://singlecell.broadinstitute.org/single_cell) - A repository hosting over 1,000 single-cell studies and tens of millions of cells, including many brain datasets, browsable and downloadable after free registration.
- [PsychENCODE](https://www.psychencode.org/) - Large-scale gene-expression, single-cell, spatial, and regulatory data from human postmortem brain focused on psychiatric disease, distributed via Synapse with free registration (some tiers controlled).
- [Marmoset Gene Atlas (Brain/MINDS)](https://gene-atlas.brainminds.jp/) - Genome-wide, high-resolution in situ hybridization gene-expression data across postnatal-to-adult common marmoset brain; freely accessible for non-commercial use with attribution.
- [STARmap PLUS Mouse CNS Atlas](https://zenodo.org/records/8327576) - A single-cell-resolution spatial transcriptomic atlas of the whole adult mouse brain and spinal cord (1.09M cells, 1,022 genes) from Shi et al. 2023, openly deposited on Zenodo.

## Standards & Tools

The formats and toolkits that make the data above usable.

- [Brain Imaging Data Structure (BIDS)](https://bids.neuroimaging.io) - A community standard for organizing and describing neuroimaging datasets (MRI, EEG, MEG, iEEG, PET). Used by OpenNeuro and the Human Connectome Project.
- [Neurodata Without Borders (NWB)](https://www.nwb.org) - A standardized data format for cellular-resolution neurophysiology, used by DANDI and OpenScope. Bundles raw signals, processed data, and metadata in one self-describing file.
- [OpenScope Databook](https://alleninstitute.github.io/openscope_databook/) - A collection of reproducible Jupyter notebooks for streaming, exploring, and analyzing OpenScope and other DANDI/NWB datasets.
- [MapMyCells](https://brain-map.org/bkp/analyze/mapmycells) - A free Allen Institute web tool that assigns cell-type labels to your own single-cell or spatial transcriptomics data by mapping against whole-brain mouse and human reference taxonomies.

## Related Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The root of the awesome-list pattern, with links to lists across every domain.

## Contributing

Contributions are welcome. Read [contributing.md](contributing.md) first, then open a pull request. Keep entries open-access, accurately described, and in the right category.

This list is dedicated to the public domain under [CC0](license).
