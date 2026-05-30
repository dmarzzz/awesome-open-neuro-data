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
  - [PET](#pet)
  - [fNIRS](#fnirs)
  - [MR Spectroscopy](#mr-spectroscopy)
  - [Quantitative & Microstructure MRI](#quantitative--microstructure-mri)
  - [Spinal Cord](#spinal-cord)
  - [Fetal & Neonatal](#fetal--neonatal)
  - [TMS (Concurrent Stimulation)](#tms-concurrent-stimulation)
  - [Sleep](#sleep)
  - [Clinical & Lesion](#clinical--lesion)
  - [Brain-Computer Interface & Decoding](#brain-computer-interface--decoding)
- [Non-Human Primate](#non-human-primate)
- [Rodent](#rodent)
  - [Electrophysiology](#electrophysiology)
  - [Two-Photon & Calcium Imaging](#two-photon--calcium-imaging)
  - [Functional Ultrasound & Whole-Brain Imaging](#functional-ultrasound--whole-brain-imaging)
- [Other Model Organisms](#other-model-organisms)
  - [Zebrafish](#zebrafish)
  - [C. elegans](#c-elegans)
  - [Other Invertebrates & Songbird](#other-invertebrates--songbird)
- [Organoids & In Vitro](#organoids--in-vitro)
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
- [OpenNeuroPET](https://openneuropet.github.io/) - The PET arm of OpenNeuro, indexing brain PET datasets in PET-BIDS across many tracers, all shared under CC0. A BRAIN Initiative archive.
- [DABI](https://dabi.loni.usc.edu/) - The Data Archive for the BRAIN Initiative, a repository for invasive human and animal neurophysiology (intracranial electrophysiology and related neurodata). Mixed access: public and controlled-access datasets, free account.
- [Canadian Open Neuroscience Platform (CONP)](https://conp.ca/) - A pan-Canadian open-science platform whose portal indexes and serves neuroscience datasets and analysis pipelines through DataLad, spanning many labs, species, and modalities. Free; some datasets download anonymously, others need a free third-party account.

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
- [UCLA Consortium for Neuropsychiatric Phenomics (ds000030)](https://openneuro.org/datasets/ds000030) - A widely cited transdiagnostic dataset: structural and task/rest fMRI from 272 participants spanning healthy controls, schizophrenia, bipolar disorder, and ADHD, in BIDS. Openly downloadable from OpenNeuro under CC0.
- [Transdiagnostic Connectome Project (ds005237)](https://openneuro.org/datasets/ds005237) - Richly phenotyped neuroimaging from 241 individuals across a range of psychiatric diagnoses plus controls, with raw BIDS data and HCP-pipeline derivatives. Openly downloadable from OpenNeuro under CC0.
- [NIMH Healthy Research Volunteer Dataset (ds005752)](https://openneuro.org/datasets/ds005752) - Deeply phenotyped multimodal data from 251 healthy volunteers, combining structural/functional MRI and resting/task MEG with clinical and cognitive measures. Openly downloadable from OpenNeuro under CC0.
- [MICA-MICs](https://portal.conp.ca/dataset?id=projects/mica-mics) - Raw and fully processed multimodal 3T MRI from 50 healthy adults (T1w, quantitative T1, diffusion, resting-state fMRI) with 18 pre-built connectomes across parcellation scales, in BIDS. Openly downloadable via the CONP portal under CC0.
- [BrainLat](https://www.synapse.org/Synapse:syn51549340) - The Latin American Brain Health Institute multimodal dataset: anatomical MRI, resting-state fMRI, diffusion MRI, and high-density resting-state EEG from 780 participants across five Latin American countries, weighted toward neurodegenerative disease. Open via Synapse with a free account.

### EEG

- [Temple University Hospital EEG Corpus (TUH EEG)](https://isip.piconepress.com/projects/tuh_eeg/) - The largest open clinical EEG corpus, with tens of thousands of recordings and annotated subsets for seizures, epilepsy, and artifacts. Free for research and commercial use after emailing a signed registration form (no fee).
- [PhysioNet EEG Motor Movement/Imagery](https://physionet.org/content/eegmmidb/1.0.0/) - 64-channel EEG from 109 subjects recorded during real and imagined motor tasks plus eyes-open/closed baselines. Fully open under the Open Data Commons Attribution License.
- [ERP CORE](https://doi.org/10.18115/D5JW4R) - EEG/ERP data from 40 participants across seven optimized paradigms (N170, MMN, N2pc, N400, P3b, LRP, ERN), bundled with experiment and analysis scripts. Open under CC BY-SA 4.0.
- [Healthy Brain Network EEG](https://neuromechanist.github.io/data/hbn/) - High-density EEG from 3,000+ children and adolescents (ages 5-21) across six passive and active tasks, a transdiagnostic pediatric mental-health resource. The EEG is openly downloadable via NEMAR, OpenNeuro, and S3; richer phenotypic data requires a signed agreement.
- [MPI-Leipzig Mind-Brain-Body (LEMON)](https://openneuro.org/datasets/ds000221) - A multimodal dataset of MRI, 62-channel resting-state EEG, cognition, emotion, and physiology from 228 healthy young and older adults. Fully open under a public-domain dedication.
- [Mother of All BCI Benchmarks (MOABB)](https://moabb.neurotechx.com/docs/dataset_summary.html) - An open framework giving standardized, MNE-compatible access to 150+ public EEG/BCI datasets (motor imagery, P300/ERP, SSVEP, code-VEP, resting state). Software is open; most underlying datasets are openly licensed, a few need separate access.
- [BNCI Horizon 2020 Database](http://bnci-horizon-2020.eu/database/data-sets) - A repository of ~32 open-access BCI/EEG datasets (motor imagery, P300 spellers, auditory oddball, some ECoG/fNIRS) as downloadable MATLAB files. Open under Creative Commons (some carry NC/ND terms).
- [Sleep-EDF Expanded](https://physionet.org/content/sleep-edfx/1.0.0/) - 197 whole-night polysomnographic sleep recordings (EEG, EOG, chin EMG) with expert hypnogram sleep-stage annotations, a standard benchmark for automated sleep staging. Fully open under the Open Data Commons Attribution License.
- [CHB-MIT Scalp EEG Database](https://physionet.org/content/chbmit/1.0.0/) - Long-term scalp EEG from 22 pediatric subjects with intractable seizures, 664 files containing 198 expertly annotated seizures, a classic seizure-detection benchmark. Fully open under the Open Data Commons Attribution License.
- [Broderick Natural Speech EEG](https://datadryad.org/stash/dataset/doi:10.5061/dryad.070jc) - 128-channel EEG from 19 subjects listening to an audiobook, widely used for speech-envelope tracking and temporal response function (TRF) modeling. Openly downloadable from Dryad.
- [THINGS-EEG (Grootswagers)](https://openneuro.org/datasets/ds003825) - EEG from 50 subjects viewing 22,248 images of 1,854 object concepts in rapid serial visual presentation, a large visual-object-recognition resource. Openly downloadable from OpenNeuro under CC0.
- [THINGS-EEG2 (Gifford)](https://osf.io/3jk45/) - Densely sampled 64-channel EEG from 10 subjects across 16,740 image conditions from the THINGS database, plus preprocessed and resting-state data, built for visual encoding/decoding models. Openly downloadable from OSF.
- [EEGEyeNet](https://osf.io/ktv7e/) - Simultaneous 128-channel EEG and video eye-tracking from 356 subjects across three paradigms (47+ hours), a benchmark for eye-movement prediction from EEG. Openly available from OSF.
- [Nencki-Symfonia EEG/ERP](https://openneuro.org/datasets/ds004621) - High-density 128-channel EEG/ERP from 42 healthy adults across three cognitive tasks plus resting state, in BIDS. Openly downloadable from OpenNeuro under CC0.
- [SRM Resting-state EEG](https://openneuro.org/datasets/ds003775) - Four minutes of eyes-closed resting-state EEG from 111 healthy adults, a clean reproducibility-oriented baseline, in BIDS. Openly downloadable from OpenNeuro under CC0.
- [BCI Competition IV](https://www.bbci.de/competition/iv/) - The benchmark datasets from the fourth BCI Competition: EEG motor imagery (cued and uncued), MEG hand-movement direction, and ECoG finger movements. Freely downloadable after agreeing to cite the recording groups.
- [Cuban Human Brain Mapping Project (CHBMP)](https://chbmp-open.loris.ca/) - A population-based normative dataset from 282 healthy adults: high-density resting-state EEG, structural MRI, and cognitive testing. Openly available through a LORIS portal and Synapse, mirrored on CONP.
- [TDBRAIN](https://brainclinics.com/resources/) - Two Decades-Brainclinics Research Archive: resting-state (eyes-open/closed) EEG plus ECG and task data from 1,274 psychiatric patients (MDD, ADHD, OCD, and more), in BIDS. Free after registering and signing a data-use agreement.
- [ZuCo](https://osf.io/q3zws/) - The Zurich Cognitive Language Processing Corpus: simultaneous high-density EEG and eye-tracking from adults reading ~1,100 natural English sentences, built for reading, language, and NLP research. Openly downloadable from OSF.
- [OpenMIIR](https://github.com/sstober/openmiir) - An open EEG dataset of music perception and imagination: 10 subjects listened to and imagined 12 short music fragments in 64-channel EEG. Released under the Open Data Commons PDDL in MNE-compatible format.
- [EEG in Alzheimer's and Frontotemporal Dementia (ds004504)](https://openneuro.org/datasets/ds004504) - Resting-state EEG from 88 participants (Alzheimer's disease, frontotemporal dementia, and healthy controls), a heavily downloaded clinical EEG benchmark, in BIDS. Openly downloadable from OpenNeuro under CC0.
- [Inner Speech (ds003626)](https://openneuro.org/datasets/ds003626) - High-density EEG from 10 subjects performing inner-speech, pronounced-speech, and visualized-condition tasks, a benchmark for imagined-speech decoding, in BIDS. Openly downloadable from OpenNeuro under CC0.
- [SeizeIT2 (ds005873)](https://openneuro.org/datasets/ds005873) - A large multi-center wearable and scalp EEG dataset of 125 patients for focal-seizure detection with behind-the-ear and full-scalp montages, in BIDS. Openly downloadable from OpenNeuro under CC0.
- [Bitbrain Open Access Sleep (ds005555)](https://openneuro.org/datasets/ds005555) - Whole-night polysomnography from 128 subjects combining a wearable dry-EEG headband with clinical-grade PSG and expert sleep staging, in BIDS. Openly downloadable from OpenNeuro under CC0.
- [NATVIEW EEG-fMRI](https://fcon_1000.projects.nitrc.org/indi/retro/nat_view.html) - Simultaneous EEG-fMRI from 22 healthy adults during rest, flickering checkerboard, Inscapes, and movies, with eye tracking and physiology, in BIDS. Openly downloadable via FCP/INDI on AWS S3 under CC BY 4.0.
- [NOD-EEG (Natural Object Dataset)](https://openneuro.org/datasets/ds005811) - EEG from 19 subjects viewing large numbers of naturalistic ImageNet object images, part of a multimodal (EEG/MEG/fMRI) visual-recognition resource, in BIDS. Openly downloadable from OpenNeuro under CC0.

### MEG

- [MOUS (Mother Of Unification Studies)](https://doi.org/10.34973/37n0-yc51) - MEG and fMRI from 204 healthy adults performing a language task plus resting state, in BIDS format on the Donders Repository. Openly downloadable.
- [MNE-Python Sample Datasets](https://mne.tools/stable/documentation/datasets.html) - Bundled example datasets for MNE-Python, including a simultaneous MEG/EEG recording (with MRI) from an audiovisual paradigm, fetched programmatically. Openly accessible; intended for learning and testing.
- [OMEGA (Open MEG Archive)](https://www.mcgill.ca/bic/resources/omega) - A large multi-site MEG archive of 644 participants (resting-state plus task), with anatomical MRI, in BIDS/CTF format covering healthy controls and clinical groups. Free but requires registration and a data-use agreement.
- [MEG-MASC (Gwilliams)](https://osf.io/ag3kj/) - High-quality MEG from 27 English speakers who each listened to two hours of naturalistic stories, with word- and phoneme-level annotations, in BIDS. Openly downloadable from OSF.
- [WAND (Welsh Advanced Neuroimaging Database)](https://gin.g-node.org/CUBRIC/WAND) - A multi-scale dataset from 170 volunteers at Cardiff's CUBRIC: ultra-strong-gradient and 3T/7T structural and functional MRI plus MR spectroscopy, MEG, and TMS, in BIDS. Freely downloadable from G-Node GIN.
- [LibriBrain](https://huggingface.co/datasets/pnpl/LibriBrain) - The largest single-subject MEG speech corpus to date: 50+ hours of within-subject MEG from one participant listening to audiobooks, with aligned transcripts and a PyTorch-ready API. Openly downloadable from Hugging Face under a public-domain license.
- [MEG-SCANS (ds006468)](https://openneuro.org/datasets/ds006468) - Raw MEG from 24 German-speaking subjects listening to two audiobooks plus matrix sentences and chirps, with structural MRI and audiograms, in BIDS. Openly downloadable from OpenNeuro under CC0.
- [NOD-MEG (Natural Object Dataset)](https://openneuro.org/datasets/ds005810) - MEG from 31 subjects viewing large numbers of naturalistic ImageNet object images (the same participants also did fMRI and EEG), a multimodal visual-recognition resource, in BIDS. Openly downloadable from OpenNeuro under CC0.

### Intracranial (iEEG / ECoG)

- [iEEG-fMRI Naturalistic Film (ds003688)](https://openneuro.org/datasets/ds003688) - A multimodal dataset from subjects watching a short audiovisual film: iEEG from 51 subjects, fMRI from 30, with detailed speech/video annotations. Freely downloadable under a public-domain dedication.
- [Kai Miller Human ECoG Library](https://purl.stanford.edu/zk881ps0522) - A standardized library of 204 ECoG datasets from 34 patients across 16 behavioral experiments, with electrode-to-anatomy registration and analysis code. Fully open via the Stanford Digital Repository, no registration.
- [UPENN / RAM Intracranial Memory Data (ds004789)](https://openneuro.org/datasets/ds004789) - Intracranial EEG from epilepsy patients performing verbal free-recall and related memory tasks, largely from the DARPA Restoring Active Memory project, with electrode localizations in BIDS. Freely downloadable from OpenNeuro.
- [DANDI 000623 (single-neuron + iEEG + fMRI)](https://dandiarchive.org/dandiset/000623) - Multimodal recordings from 16 human epilepsy patients watching a film: single-neuron spikes, LFP, iEEG, eye tracking, and fMRI in NWB/BIDS. Openly downloadable under CC-BY-4.0.
- [IEEG.org](https://www.ieeg.org/) - The International Epilepsy Electrophysiology Portal, a NINDS-funded archive of 1200+ human and animal intracranial EEG datasets with imaging and de-identified clinical metadata, browsable and streamable in-platform. Free user account required.
- [MNI Open iEEG Atlas](https://mni-open-ieegatlas.research.mcgill.ca) - A normative atlas of resting and sleep intracranial EEG from ~110 epilepsy patients (~2,300 channels in non-epileptic tissue), served as an open web resource with spectral brain maps. Free registration.
- [Localize-MI](https://doi.org/10.25493/NXN2-05W) - A ground-truth dataset of simultaneous single-pulse intracerebral stimulation and 256-channel HD-EEG in 7 patients (61 sessions), BIDS-formatted, for validating EEG source-localization methods. Open under CC BY 4.0 via EBRAINS.
- [AJILE12 (DANDI 000055)](https://dandiarchive.org/dandiset/000055) - Long-term naturalistic human intracranial ECoG (~12 subjects, 7+ days each) recorded continuously alongside markerless body-pose tracking from synchronized video, in NWB. Openly downloadable from DANDI under CC BY 4.0.
- [Human es-fMRI (ds002799)](https://openneuro.org/datasets/ds002799) - Concurrent intracranial electrical stimulation and fMRI from 26 epilepsy patients, mapping causal stimulation-evoked whole-brain responses, in BIDS. Openly downloadable from OpenNeuro under CC0.

### PET

- [NRM2018 PET Grand Challenge (ds001705)](https://openneuro.org/datasets/ds001705) - Baseline and intervention brain PET data in PET-BIDS from the NRM2018 reconstruction challenge. Openly downloadable from OpenNeuro under CC0.
- [Monash rsPET-fMRI (ds002898)](https://openneuro.org/datasets/ds002898) - Concurrent resting-state fMRI and 18F-FDG PET from 27 healthy controls acquired on a Siemens Biograph mMR. Openly downloadable from OpenNeuro under CC0.
- [First-in-human PS13 COX-1 PET (ds004230)](https://openneuro.org/datasets/ds004230) - A PET-BIDS dataset evaluating the radioligand 11C-PS13 to quantify cyclooxygenase-1 in the human brain. Openly downloadable from OpenNeuro under CC0.
- [Energetic Costs of the Human Connectome (ds004513)](https://openneuro.org/datasets/ds004513) - Simultaneous FDG-PET and BOLD fMRI from 20 participants relating glucose metabolism to functional connectivity, in PET-BIDS. Openly downloadable from OpenNeuro under CC0.

### fNIRS

- [Tufts fNIRS2MW](https://tufts-hci-lab.github.io/code_and_datasets/fNIRS2MW.html) - The Tufts fNIRS-to-Mental-Workload dataset: 8-channel recordings from 68 participants during n-back tasks, with demographics for fairness audits. Open under CC BY 4.0.
- [HD-DOT Ball-Squeezing fNIRS (ds005930)](https://openneuro.org/datasets/ds005930) - A high-density diffuse optical tomography fNIRS dataset in BIDS and SNIRF. Openly downloadable from OpenNeuro under CC0.
- [fNIRS Motion-Artifact (ds005929)](https://openneuro.org/datasets/ds005929) - An fNIRS dataset for characterizing and correcting motion artifacts, in BIDS and SNIRF. Openly downloadable from OpenNeuro under CC0.
- [Electrical & Thermal Finger-Tapping fNIRS (ds005776)](https://openneuro.org/datasets/ds005776) - An fNIRS finger-tapping and stimulation dataset in BIDS and SNIRF. Openly downloadable from OpenNeuro under CC0.

### MR Spectroscopy

- [Big GABA](https://www.nitrc.org/projects/biggaba/) - A multi-vendor, multi-site repository of single-voxel edited MR spectroscopy (MEGA-PRESS and short-TE PRESS) from two dozen research sites on GE, Philips, and Siemens 3T scanners, with tissue-fraction and demographic data. Openly downloadable from NITRC under a non-commercial Creative Commons license.

### Quantitative & Microstructure MRI

- [MICRA](https://osf.io/z3mkn/) - Microstructural Image Compilation with Repeated Acquisitions: five repeated sessions in 6 adults on an ultra-strong-gradient Connectom scanner, spanning multi-shell diffusion, multi-component relaxometry, and quantitative magnetization transfer, for test-retest work. Open on OSF under CC BY.
- [MASSIVE](https://www.massive-data.org/) - One subject scanned 18 times yielding ~8,000 diffusion volumes across five shells (b up to 9,000 s/mm²) plus FLAIR, T1, and T2, for diffusion modeling and methods development. Openly available, raw and processed.
- [Penthera 3T](https://brain.labsolver.org/mds/data-others/brain.html) - Scan-rescan multi-shell diffusion MRI from 13 healthy young adults (two sessions, three scans each) on a Philips 3T scanner, for multi-shell modeling and reliability studies. Openly downloadable.
- [MGH Connectome Diffusion Microstructure Dataset (CDMD)](https://doi.org/10.6084/m9.figshare.c.5315474) - One hour of diffusion MRI per subject from 26 adults on the MGH Connectome scanner at 300 mT/m, sampling two diffusion times and eight gradient strengths, with scan-rescan data and FreeSurfer outputs. Openly downloadable from figshare.

### Spinal Cord

- [Spine Generic Multi-Subject](https://github.com/spine-generic/data-multi-subject) - Quantitative spinal cord MRI from 260 participants across 42 centers on the three major MRI manufacturers, acquired with the standardized spine-generic protocol, in BIDS. Open under CC BY 4.0 via git-annex.

### Fetal & Neonatal

- [Developing Human Connectome Project (dHCP)](https://www.developingconnectome.org/data-release/second-data-release/) - Structural, diffusion, and resting-state functional MRI mapping brain development from 20 weeks gestational age to term, including 558 neonatal subjects and the first open-access fetal fMRI release. Free after registration and signing the user data-use terms.
- [Baby Open Brains (BOBs)](https://openneuro.org/datasets/ds005450) - T1- and T2-weighted infant MRI with expert manual brain-tissue and subcortical segmentations across 71 visits from 51 infants aged 1-9 months, in BIDS. Openly downloadable from OpenNeuro, OSF, and S3.
- [M-CRIB Neonatal Atlas](https://github.com/DevelopmentalImagingMCRI/M-CRIB_atlas) - The Melbourne Children's Regional Infant Brain atlas: manually parcellated neonatal T1/T2 MRI with 100 cortical and subcortical regions compatible with the Desikan-Killiany scheme. Openly available via OSF and GitHub.

### TMS (Concurrent Stimulation)

- [Concurrent TMS-fMRI Causal Connectome (ds005498)](https://openneuro.org/datasets/ds005498) - Concurrent single-pulse TMS and fMRI from 152 participants, with TMS delivered to 11 cortical sites plus resting-state and structural MRI, in BIDS. Openly downloadable from OpenNeuro under CC BY-NC-ND 4.0.
- [TMS-EEG Parietal Decision-Making (ds004917)](https://openneuro.org/datasets/ds004917) - A multimodal dataset pairing structural MRI, diffusion MRI, and task fMRI with a concurrent EEG plus inhibitory-TMS session over parietal cortex during a decision-making task. Openly downloadable from OpenNeuro.

### Sleep

- [National Sleep Research Resource (NSRR)](https://sleepdata.org/) - An NHLBI repository sharing tens of thousands of de-identified polysomnography, actigraphy, and questionnaire records across large cohorts (SHHS, MESA, CHAT, and more), in EDF/XML/CSV. Free after a per-dataset data-access request and use agreement (no fee).

### Clinical & Lesion

- [ATLAS v2.0 (Stroke Lesions)](https://fcon_1000.projects.nitrc.org/indi/retro/atlas.html) - Anatomical Tracings of Lesions After Stroke: 955 T1-weighted MRIs with manually segmented lesion masks across 33 cohorts, a benchmark for lesion-segmentation algorithms, in BIDS. The preprocessed training set is openly available via INDI/NITRC (free registration); the native-space release is gated through ICPSR.
- [ISLES 2022](https://doi.org/10.5281/zenodo.7153326) - Ischemic Stroke Lesion Segmentation: 250 expert-annotated multi-center MRI cases (FLAIR, DWI, ADC) of acute-to-subacute stroke lesions, in NIfTI/BIDS. Openly downloadable from Zenodo under CC BY 4.0.
- [BraTS 2021](https://www.cancerimagingarchive.net/analysis-result/rsna-asnr-miccai-brats-2021/) - The Brain Tumor Segmentation challenge collection: multi-parametric MRI of glioma patients with expert tumor sub-region annotations. The challenge training set (NIfTI) is openly available under CC BY 4.0; the original DICOM source via TCIA carries controlled-access terms.

### Brain-Computer Interface & Decoding

- [Handwriting BCI (Willett et al. 2021)](https://datadryad.org/dataset/doi:10.5061/dryad.wh70rxwmv) - Intracortical motor-cortex recordings (two 96-electrode arrays) as a participant with paralysis attempted handwriting 1,000 sentences over 10.7 hours, the data behind high-performance handwriting brain-to-text. Openly downloadable from Dryad.
- [Speech Neuroprosthesis BCI (Willett et al. 2023)](https://datadryad.org/dataset/doi:10.5061/dryad.x69p8czpq) - Intracortical neural activity from 256 electrodes during ~12,100 attempted-speech sentences, the dataset powering the Brain-to-Text Benchmark '24. Openly downloadable from Dryad.

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
- [TVSD - THINGS Ventral-Stream Spiking Dataset](https://doi.gin.g-node.org/10.12751/g-node.hc7zlv/) - Large-scale multi-electrode spiking from V1, V4, and IT in two macaques viewing ~22,000 natural images from the THINGS database, a benchmark-scale ventral-stream single-unit library. Open under CC BY 4.0 via G-Node GIN.
- [Nonhuman Primate Reaching (O'Doherty/Sabes)](https://zenodo.org/records/3854034) - Sorted sensorimotor-cortex (M1, some M1+S1) electrophysiology with fingertip kinematics from two macaques across 47 sessions and ~26,500 reaches, the standard motor-BCI decoding benchmark. Open under CC BY 4.0 on Zenodo.
- [Parkinsonian Macaque Reach Recordings (DANDI 000947)](https://dandiarchive.org/dandiset/000947) - Reach-related single-unit activity from the basal ganglia of a rhesus macaque before and after MPTP-induced parkinsonism, in NWB. Openly downloadable from DANDI under CC BY 4.0.
- [Macaque Multi-Object Working Memory (DANDI 000620)](https://dandiarchive.org/dandiset/000620) - Frontal-cortex single-unit recordings from rhesus macaques performing a multi-object working-memory task (Watters, Jazayeri), in NWB. Openly downloadable from DANDI under CC BY 4.0.
- [Macaque Wireless ECoG (ds006890)](https://openneuro.org/datasets/ds006890) - Longitudinal multitask wireless electrocorticography from two fully implanted Japanese macaques, an unusual chronic NHP ECoG resource, in BIDS. Openly downloadable from OpenNeuro under CC0.

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
- [Allen Visual Behavior - Neuropixels](https://brain-map.org/circuits-behavior/visual-behavior-neuropixels) - Neuropixels recordings of roughly 200,000 units across 153 mouse sessions spanning visual cortex, thalamus, hippocampus, and midbrain during a change-detection task, with optotagging of inhibitory subclasses. Open as NWB via the AllenSDK.
- [CRCNS hc-23 (MEC Grid Cells)](https://crcns.org/data-sets/hc/hc-23) - Grid-cell and non-grid-cell silicon-probe recordings from layer II/III of rat medial entorhinal cortex during exploration and sleep (Trimper, Colgin et al.). Free download with a CRCNS.org account.
- [CRCNS hc-11 (CA1 Spatial Learning)](https://crcns.org/data-sets/hc/hc-11) - Extracellular hippocampal CA1 recordings from rats during and after novel spatial learning (Grosmark, Long, Buzsaki). Free download with a CRCNS.org account.
- [CRCNS hc-2 (Buzsaki Open-Field)](https://crcns.org/data-sets/hc/hc-2) - Multi-unit extracellular recordings from rat hippocampus during open-field foraging, from the Buzsaki lab. Free download with a CRCNS.org account.

### Two-Photon & Calcium Imaging

- [Allen Brain Observatory - Visual Coding 2-Photon](https://observatory.brain-map.org/visualcoding) - Hundreds of two-photon calcium-imaging sessions (GCaMP6) across mouse visual-cortex areas and depths under standardized visual stimuli. Open via the web portal and AllenSDK; data on AWS in NWB.
- [Allen Visual Behavior - 2-Photon](https://brain-map.org/circuits-behavior/visual-behavior-2p) - Two-photon imaging (GCaMP6f) of 34,619 mouse visual-cortex neurons over 551 sessions, with the same populations re-imaged across days during a change-detection task. Open via the AllenSDK.
- [Stringer & Pachitariu Spontaneous-Activity Recordings](https://janelia.figshare.com/articles/dataset/Recordings_of_ten_thousand_neurons_in_visual_cortex_during_spontaneous_behaviors/6163622) - Two-photon recordings of ~10,000 mouse visual-cortex neurons during spontaneous behavior, with a companion eight-probe Neuropixels release. Freely downloadable from Janelia figshare with analysis code on GitHub.
- [CRCNS ssc-1 (Barrel Cortex 2P)](https://crcns.org/data-sets/ssc/ssc-1) - Two-photon calcium imaging of mouse vibrissal S1 during a pole-localization task (Peron, Svoboda). Free download with a CRCNS.org account.
- [CRCNS ssc-2 (Volumetric Barrel Cortex)](https://crcns.org/data-sets/ssc/ssc-2) - Volumetric two-photon calcium imaging sampling ~75% (~12,000 neurons per mouse) of superficial barrel-cortex neurons during a single-whisker object-localization task (Peron, Svoboda). Free download with a CRCNS.org account.
- [jGCaMP8 Ground-Truth V1 Imaging (DANDI 000168)](https://dandiarchive.org/dandiset/000168) - Simultaneous two-photon calcium imaging and loose-seal cell-attached recordings of GCaMP8-expressing mouse V1 neurons under drifting gratings, giving spike-to-fluorescence ground truth. Open as NWB under CC-BY-4.0 on DANDI.

### Functional Ultrasound & Whole-Brain Imaging

- [Whole-Brain fUS in Awake Mice (Brunner et al.)](https://doi.org/10.5281/zenodo.4905862) - Whole-brain visually evoked activity maps from awake head-fixed mice acquired with functional ultrasound imaging, with anatomical scans, a brain atlas, and registration transforms. Open on Zenodo under CC BY 4.0.
- [fMOST Whole-Brain Mouse Imaging (Zeng Lab)](https://doi.org/10.1038/s41597-024-03761-8) - Raw and downsampled fluorescence micro-optical sectioning tomography (fMOST) whole-brain mouse image volumes plus single-neuron morphology reconstructions, served by the Brain Image Library. Openly downloadable, browser-viewable with no account.

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
- [Tracking Neurons in a Moving Brain (Nguyen, Leifer et al. 2016)](https://ieee-dataport.org/open-access/tracking-neurons-moving-and-deforming-brain-dataset) - Whole-brain calcium imaging from freely behaving *C. elegans* at cellular resolution (RFP + GCaMP6s at 200 Hz) with paired behavioral video, the dataset behind the freely-moving whole-brain tracking pipeline. Open on IEEE DataPort with a free account.
- [Brain-wide Behavior Representations (Atanas, Flavell et al. 2023)](https://dandiarchive.org/dandiset/000776) - Whole-brain calcium imaging paired with behavior across timescales and states in freely moving *C. elegans*, the Flavell-lab corpus (~1 TB NWB). Openly downloadable from DANDI under CC BY 4.0.
- [C. elegans NeuroPAL + Immobilized Calcium (Kato lab)](https://dandiarchive.org/dandiset/000565) - Whole-brain GCaMP activity with matched NeuroPAL structural volumes for single-neuron identification in immobilized worms, in NWB. Openly downloadable from DANDI under CC BY 4.0.
- [OpenWorm Movement Database](https://zenodo.org/communities/open-worm-movement-database/) - A community archive of 14,874 single-worm tracking experiments across 386 genotypes, with videos, WCON skeleton files, and behavioral feature sets. Openly available via Zenodo under CC BY.
- [C. elegans Signal Propagation Atlas (DANDI 001075)](https://dandiarchive.org/dandiset/001075) - The Leifer-lab whole-brain functional connectivity atlas combining single-cell optogenetic activation with calcium imaging (Randi et al., Nature 2023), in NWB. Openly downloadable from DANDI under CC BY 4.0.

### Other Invertebrates & Songbird

- [Whole-Body Neural Activity in Hydra (Hanson et al. 2024)](https://datadryad.org/landing/show?id=doi:10.5061/dryad.h9w0vt4q3) - Dual-channel calcium-imaging movies of whole-body neural activity at single-cell resolution in behaving *Hydra vulgaris*. Openly downloadable under CC0.
- [Chronic HVC Recordings in Singing Zebra Finches](https://figshare.com/articles/dataset/Chronic_Recording_of_HVC_in_Free_Behaving_Zebra_FInch_with_Behaviors_Hand_Annotated/15094219) - Songbird chronic silicon-probe electrophysiology from premotor nucleus HVC during free singing, with synchronized audio and hand-annotated vocalizations. Open under CC BY 4.0.
- [Drosophila Whole-Brain Functional Imaging (Aimon, Mann et al. 2017)](https://data.mendeley.com/datasets/8b6nw2xxhn/1) - Brain-wide two-photon calcium imaging of adult *Drosophila* with anatomical templates, a Virtual Fly Brain ROI atlas, and ROI time series. Openly downloadable on Mendeley Data under CC BY 4.0.
- [CRCNS aa-2 (Avian Auditory)](https://crcns.org/data-sets/aa/aa-2) - About 500 single-unit recordings from zebra finch auditory areas with the natural and synthetic sound stimuli used, as spike-time files (Theunissen lab). Free download with a CRCNS.org account.
- [CRCNS apl-1 (Aplysia)](https://crcns.org/data-sets/aplysia/apl-1) - Fast voltage-sensitive-dye imaging of 1,131 neurons across 10 isolated *Aplysia californica* pedal-ganglion preparations (Bruno & Frost). Free download with a CRCNS.org account.
- [Episodic-Memory Barcodes in Chickadee Hippocampus (Chettih et al. 2024)](https://datadryad.org/dataset/doi:10.5061/dryad.7h44j101z) - Hippocampal electrophysiology and two-photon calcium imaging from food-caching black-capped chickadees, revealing sparse "barcode" memory codes during caching and retrieval. Openly downloadable from Dryad.
- [Xenopus Optic-Tectum Electrophysiology (Ciarleglio et al. 2015)](https://datadryad.org/dataset/doi:10.5061/dryad.18kk6) - Raw patch-clamp recordings from *Xenopus laevis* tadpole optic-tectum neurons across development and visual plasticity. Openly downloadable from Dryad.
- [Bengalese Finch Song Repository](https://figshare.com/articles/dataset/Bengalese_Finch_song_repository/4805749) - Hand-labeled song from four Bengalese finches, a benchmark corpus for birdsong syntax and automated annotation. Open on figshare under CC0.
- [Juvenile Pig Cerebral-Ischemia ECoG/EEG (Fleischer et al.)](https://doi.org/10.18112/openneuro.ds003380.v1.0.0) - Multimodal 16-channel ECoG and electrothalamogram (plus evoked potentials and cardiovascular signals) from juvenile pigs across sedation, gradual ischemia, and recovery, in BIDS/EDF. Openly downloadable from OpenNeuro under CC0.

## Organoids & In Vitro

Recordings from human iPSC-derived brain organoids and in-vitro neural cultures.

- [Human Brain Organoid Firing Sequences (DANDI 001603)](https://dandiarchive.org/dandiset/001603) - Raw and curated extracellular electrophysiology from human iPSC-derived brain organoids, capturing preconfigured neuronal firing sequences, in NWB. Openly downloadable from DANDI under CC BY 4.0.
- [Neural Organoid Shell-MEA Neuromodulation (DANDI 001336)](https://dandiarchive.org/dandiset/001336) - Multi-electrode-array recordings from human neural organoids using conformal shell MEAs during neuromodulation, an unusual in-vitro human-tissue electrophysiology resource, in NWB. Openly downloadable from DANDI under CC BY 4.0.

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
- [FlyEM Optic Lobe](https://www.janelia.org/project-team/flyem/optic-lobe) - A dense connectome of the right optic lobe of a male *Drosophila* (>50,000 neurons spanning >700 cell types), the first proofread region of the full-CNS EM volume (Nern et al. 2025). Released CC-BY via neuPrint, Neuroglancer, and a public Google bucket.
- [FANC (Female Adult Nerve Cord)](https://github.com/htem/FANC_auto_recon) - A GridTape-TEM serial-section EM volume of an adult female *Drosophila* ventral nerve cord with automated segmentation and CAVE-based proofreading. The EM imagery is publicly viewable on BossDB; segmentation access is via joining the FANC community.
- [Kasthuri et al. 2015](https://neurodata.io/data/kasthuri15/) - A saturated reconstruction of a sub-volume of mouse neocortex (3×3×30 nm, ~660 GB) in which all cellular objects and many sub-cellular components are itemized. Hosted openly on BossDB/NeuroData with anonymous read access via the Intern and cloud-volume Python libraries.
- [CREMI Challenge](https://cremi.org/) - "Circuit Reconstruction from Electron Microscopy Images," a benchmark of three serial-section EM volumes of adult *Drosophila* brain (drawn from FAFB) with neuron, synapse, and synaptic-partner ground truth in HDF5. Training and test data are openly downloadable.
- [SNEMI3D Challenge](https://snemi3d.grand-challenge.org/) - The ISBI 2013 3D neurite-segmentation benchmark: serial-section SEM stacks of mouse neocortex (Lichtman lab) with manually delineated ground-truth labels. Available via the Grand Challenge server and mirrored on Zenodo.
- [Ciona Larva Connectome (Ryan et al. 2016)](https://elifesciences.org/articles/16962) - The complete synaptic connectome of the CNS of a *Ciona intestinalis* tadpole larva (177 neurons, 6,618 synapses), one of the few whole-animal connectomes of a chordate. Connectivity matrices are open as eLife supplementary Excel files under CC BY.
- [Fish1 (Larval Zebrafish Whole-Brain EM)](https://fish1-release.storage.googleapis.com/index.html) - A whole-brain serial-section EM connectomic resource for the 7 dpf larval zebrafish (>187,000 segmented somata, ~30 million synapses, 4×4×30 nm) from the Lichtman, Engert, and Google teams. Open to browse via Neuroglancer; editing requires free approval.
- [C. elegans Developmental Connectome (Witvliet et al. 2021)](https://www.nature.com/articles/s41586-021-03778-8) - Serial-section EM reconstructions of the full brain of eight isogenic *C. elegans* across postnatal development, revealing principles of brain maturation. Connectivity data and analysis code are openly available on GitHub.
- [Zebrafish Olfactory Bulb (Wanner et al. 2016)](https://neurodata.io/data/wanner16/) - A dense EM reconstruction of the larval zebrafish olfactory bulb (skeletons of 1,022 neurons, ~98% of the bulb) at 9.25×9.25×25 nm. Openly hosted on BossDB/NeuroData under ODC-By with Neuroglancer viewing and cloud-volume download.

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
