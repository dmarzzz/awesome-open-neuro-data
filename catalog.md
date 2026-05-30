# Open Neuro Data Catalog

A companion to [README.md](README.md) with structured metadata for each dataset: species, modality, format, approximate size, access, and a direct download or data-access link. The README is the canonical curated list; this catalog adds detail for concrete datasets.

Access legend: **open** (no gate) · **free-registration** · **data-use-agreement** · **mixed**. Sizes are approximate and, for portals and growing archives, listed as "varies".

> **Status: complete.** Every dataset and archive in the README has a row here, grouped by the same categories. Sizes for portals are listed as "varies".

## Data Repositories & Archives

| Archive | Scope | Format | Size | Access | Entry / Download |
|---|---|---|---|---|---|
| [DANDI Archive](https://dandiarchive.org) | cellular neurophysiology | various (NWB, BIDS) | varies | open | [link](https://dandiarchive.org/dandiset) |
| [OpenNeuro](https://openneuro.org) | human neuroimaging (MRI/fMRI/EEG/MEG/iEEG/PET) | various (BIDS) | varies | open | [link](https://openneuro.org/search) |
| [EBRAINS](https://www.ebrains.eu/) | general / cross-modal | various | varies | free-registration | [link](https://search.kg.ebrains.eu/) |
| [CRCNS.org](https://crcns.org/) | cellular neurophysiology | various | varies | free-registration | [link](https://crcns.org/data-sets) |
| [NeuroVault](https://neurovault.org/) | human statistical maps / atlases | NIfTI | varies | open | [link](https://neurovault.org/collections/) |
| [NEMAR](https://nemar.org/) | human EEG / MEG / iEEG | BIDS | varies | open | [link](https://nemar.org/dataexplorer) |
| [BossDB](https://bossdb.org/) | EM / connectomics / volumetric | volumetric (Zarr/cloud-volume) | >1 PB | open (tiered) | [link](https://bossdb.org/projects) |
| [Brain Image Library (BIL)](https://www.brainimagelibrary.org/) | microscopy (light/EM) | various | varies | open | [link](https://www.brainimagelibrary.org/) |
| [NITRC Image Repository](https://www.nitrc.org/ir/) | human neuroimaging (XNAT) | DICOM, NIfTI | varies | free-registration | [link](https://www.nitrc.org/ir/) |
| [FCP / INDI](https://fcon_1000.projects.nitrc.org/) | human rest-fMRI / sMRI / dMRI | NIfTI, BIDS | varies | free-registration | [link](https://fcon_1000.projects.nitrc.org/fcpClassic/FcpTable.html) |
| [LONI Image & Data Archive](https://ida.loni.usc.edu/) | human neuroimaging + clinical/genetic | NIfTI, DICOM | varies | mixed | [link](https://ida.loni.usc.edu/) |
| [Neuroscience Multi-Omic Archive (NeMO)](https://nemoarchive.org/) | multi-omic (single-cell, epigenomic) | various | varies | mixed | [link](https://portal.nemoarchive.org/) |
| [SPARC Portal](https://sparc.science/) | peripheral & autonomic nervous system | various | varies | open | [link](https://sparc.science/data?type=dataset) |
| [G-Node GIN](https://gin.g-node.org/) | general / cross-modal (git-versioned) | various | varies | open | [link](https://gin.g-node.org/explore/repos) |
| [Brain-CODE](https://www.braincode.ca/) | general / cross-modal | various | varies | mixed | [link](https://www.braincode.ca/) |
| [BRAIN Initiative Data Archives](https://braininitiative.nih.gov/research/data-science-and-informatics/informatics-program) | directory of NIH BRAIN archives | n/a | n/a | open | [link](https://braininitiative.nih.gov/research/data-science-and-informatics/informatics-program) |
| [OpenNeuroPET](https://openneuropet.github.io/) | human/animal PET | various (PET-BIDS) | varies | open | [link](https://openneuro.org/search/modality/pet) |
| [DABI](https://dabi.loni.usc.edu/) | invasive neurophysiology | various | varies | mixed | [link](https://dabi.loni.usc.edu/search) |
| [Canadian Open Neuroscience Platform (CONP)](https://conp.ca/) | multi-species / cross-modal | DataLad / BIDS / various | varies | open (some free account) | [link](https://portal.conp.ca/datasets) |

## Human — MRI / fMRI / diffusion

| Dataset | Species | Modality | Format | Approx size | Access | Download |
| --- | --- | --- | --- | --- | --- | --- |
| [Human Connectome Project](https://www.humanconnectome.org) | human | MRI / fMRI / dMRI | NIfTI (CIFTI derivatives) | varies (multi-TB) | data-use-agreement | [link](https://db.humanconnectome.org/) |
| [HCP Lifespan (Aging & Development)](https://www.humanconnectome.org/study/hcp-lifespan-aging) | human | MRI / fMRI / dMRI / ASL | NIfTI | ~42 TB (AABC R2) | data-use-agreement | [link](https://balsa.wustl.edu/project?project=AABC2) |
| [ABIDE](https://fcon_1000.projects.nitrc.org/indi/abide/) | human | fMRI (rest) / sMRI | NIfTI + phenotypic CSV | varies | free-registration | [link](http://fcon_1000.projects.nitrc.org/indi/abide/abide_I.html) |
| [ADHD-200](https://fcon_1000.projects.nitrc.org/indi/adhd200/) | human | fMRI (rest) / sMRI | NIfTI + phenotypic CSV | varies | free-registration | [link](https://www.nitrc.org/frs/?group_id=383) |
| [1000 Functional Connectomes Project](https://fcon_1000.projects.nitrc.org/fcpClassic/FcpTable.html) | human | fMRI (rest) / sMRI | NIfTI | varies | free-registration | [link](https://fcon_1000.projects.nitrc.org/fcpClassic/FcpTable.html) |
| [NKI-Rockland Sample](https://fcon_1000.projects.nitrc.org/indi/enhanced/) | human | fMRI (rest/task) / dMRI / sMRI | NIfTI / BIDS | varies | data-use-agreement | [link](https://www.rocklandsample.org/) |
| [Natural Scenes Dataset (NSD)](https://naturalscenesdataset.org/) | human | fMRI (7T, task) | NIfTI + derivatives | large (8 subj, 30-40 sessions) | data-use-agreement | [link](https://naturalscenesdataset.org/) |
| [Midnight Scan Club](https://openneuro.org/datasets/ds000224) | human | fMRI (rest/task) / sMRI | BIDS (NIfTI) | ~27 GB | open | [link](https://openneuro.org/datasets/ds000224) |
| [Individual Brain Charting (IBC)](https://openneuro.org/datasets/ds002685) | human | fMRI (multi-task) / dMRI / sMRI | BIDS (NIfTI) | ~2.5 TB | open | [link](https://openneuro.org/datasets/ds002685) |
| [studyforrest](https://studyforrest.org/) | human | fMRI (naturalistic) / sMRI / eye-tracking | BIDS (NIfTI) | varies | open | [link](https://studyforrest.org/access.html) |
| [Narratives](https://openneuro.org/datasets/ds002345) | human | fMRI (naturalistic listening) | BIDS (NIfTI) | ~142 GB | open | [link](https://openneuro.org/datasets/ds002345) |
| [COBRE](https://fcon_1000.projects.nitrc.org/indi/retro/cobre.html) | human | fMRI (rest) / sMRI | NIfTI + phenotypic CSV | varies | free-registration | [link](https://fcon_1000.projects.nitrc.org/indi/retro/cobre.html) |
| [IXI Dataset](https://brain-development.org/ixi-dataset/) | human | sMRI (T1/T2/PD/MRA) / dMRI | NIfTI (.tar) | ~600 scans | open | [link](http://biomedic.doc.ic.ac.uk/brain-development/downloads/IXI/IXI-T1.tar) |
| [OASIS (1/2/3/4)](https://sites.wustl.edu/oasisbrains/) | human | sMRI / fMRI / dMRI / PET | NIfTI / DICOM (BIDS for OASIS-3) | varies (OASIS-3 ~2,842 sessions) | mixed | [link](https://www.nitrc.org/projects/oasis_brains/) |
| [AOMIC (ID1000 / PIOP1 / PIOP2)](https://nilab-uva.github.io/AOMIC.github.io/) | human | fMRI (rest/task) / dMRI / sMRI | BIDS (NIfTI) | ~97 + 57 + 126 GB | open | [link](https://openneuro.org/datasets/ds003097) |
| [BOLD5000](https://bold5000-dataset.github.io/website/) | human | fMRI (task, vision) / sMRI | NIfTI + derivatives | large (4 subj, 15 sessions) | open | [link](https://bold5000-dataset.github.io/download.html) |
| [SALD (Southwest University Adult Lifespan)](https://fcon_1000.projects.nitrc.org/indi/retro/sald.html) | human | fMRI (rest) / sMRI | BIDS (NIfTI) | 494 subjects | free-registration | [link](https://fcon_1000.projects.nitrc.org/indi/retro/sald.html) |
| [MyConnectome](https://openneuro.org/datasets/ds000031) | human | fMRI (rest/task) / dMRI / sMRI | BIDS (NIfTI) | ~135 GB | open | [link](https://openneuro.org/datasets/ds000031) |
| [Courtois NeuroMod](https://www.cneuromod.ca/) | human | fMRI (naturalistic/task) / sMRI | BIDS (NIfTI), DataLad | large (deep-sampling) | mixed | [link](https://docs.cneuromod.ca/en/latest/ACCESS.html) |
| [Generic Object Decoding (Kamitani)](https://openneuro.org/datasets/ds001246) | human | fMRI (task, vision) | BIDS (NIfTI) | ~20 GB | open | [link](https://openneuro.org/datasets/ds001246) |
| [Healthy Brain Network MRI](https://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/) | human | fMRI (rest/movie) / dMRI / sMRI | BIDS (NIfTI) | very large | mixed | [link](https://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/index.html) |
| [UCLA CNP (ds000030)](https://openneuro.org/datasets/ds000030) | human | MRI / fMRI (psychiatric) | BIDS (NIfTI) | ~85 GB | open (CC0) | [link](https://openneuro.org/datasets/ds000030) |
| [Transdiagnostic Connectome Project (ds005237)](https://openneuro.org/datasets/ds005237) | human | MRI / fMRI | BIDS (NIfTI) | ~1 TB | open (CC0) | [link](https://openneuro.org/datasets/ds005237) |
| [NIMH Healthy Research Volunteer (ds005752)](https://openneuro.org/datasets/ds005752) | human | MRI / fMRI / MEG | BIDS (NIfTI) | ~712 GB | open (CC0) | [link](https://openneuro.org/datasets/ds005752) |
| [MICA-MICs](https://portal.conp.ca/dataset?id=projects/mica-mics) | human | MRI / connectomes | BIDS (NIfTI) | ~70 GB | open (CC0) | [link](https://portal.conp.ca/dataset?id=projects/mica-mics) |
| [BrainLat](https://www.synapse.org/Synapse:syn51549340) | human | MRI / fMRI / dMRI / EEG (clinical) | NIfTI, EEG, CSV | ~780 participants | free Synapse account | [link](https://doi.org/10.7303/syn51549340) |

## Human — EEG

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Temple University Hospital EEG Corpus](https://isip.piconepress.com/projects/tuh_eeg/) | human | EEG (clinical) | EDF | varies (~1.6 TB full corpus) | free-registration | [link](https://isip.piconepress.com/projects/nedc/html/resources.shtml) |
| [PhysioNet EEG Motor Movement/Imagery](https://physionet.org/content/eegmmidb/1.0.0/) | human | EEG | EDF+ | ~3.4 GB | open | [link](https://physionet.org/files/eegmmidb/1.0.0/) |
| [ERP CORE](https://doi.org/10.18115/D5JW4R) | human | EEG / ERP | BIDS (EEG) | varies | open | [link](https://osf.io/thsqg/) |
| [Healthy Brain Network EEG](https://neuromechanist.github.io/data/hbn/) | human | EEG | BIDS (EEG) | ~1.97 TB | mixed | [link](https://nemar.org/dataexplorer/detail?dataset_id=ds005505) |
| [MPI-Leipzig LEMON](https://openneuro.org/datasets/ds000221) | human | EEG + MRI | BIDS | ~397 GB | open | [link](https://openneuro.org/datasets/ds000221) |
| [MOABB](https://moabb.neurotechx.com/docs/dataset_summary.html) | human | EEG (BCI) | MNE objects | varies (157 datasets) | mixed | [link](https://moabb.neurotechx.com/docs/dataset_summary.html) |
| [BNCI Horizon 2020](http://bnci-horizon-2020.eu/database/data-sets) | human | EEG (BCI) | .mat | varies (32 datasets) | open | [link](http://bnci-horizon-2020.eu/database/data-sets) |
| [Sleep-EDF Expanded](https://physionet.org/content/sleep-edfx/1.0.0/) | human | EEG (PSG) | EDF / EDF+ | ~8.1 GB | open | [link](https://physionet.org/files/sleep-edfx/1.0.0/) |
| [CHB-MIT Scalp EEG](https://physionet.org/content/chbmit/1.0.0/) | human | EEG (seizure) | EDF | ~42.6 GB | open | [link](https://physionet.org/files/chbmit/1.0.0/) |
| [Broderick Natural Speech EEG](https://datadryad.org/stash/dataset/doi:10.5061/dryad.070jc) | human | EEG | .mat | varies (19 subj, 128-ch) | open | [link](https://datadryad.org/stash/dataset/doi:10.5061/dryad.070jc) |
| [THINGS-EEG (Grootswagers)](https://openneuro.org/datasets/ds003825) | human | EEG | BIDS (EEG) | ~44 GB | open | [link](https://openneuro.org/datasets/ds003825) |
| [THINGS-EEG2 (Gifford)](https://osf.io/3jk45/) | human | EEG | BrainVision / .npy | varies (10 subj, 64-ch) | open | [link](https://osf.io/3jk45/) |
| [EEGEyeNet](https://osf.io/ktv7e/) | human | EEG + eye-tracking | .mat / .csv | varies (356 subj) | open | [link](https://osf.io/ktv7e/) |
| [Nencki-Symfonia EEG/ERP](https://openneuro.org/datasets/ds004621) | human | EEG / ERP | BIDS (EEG) | ~83 GB | open | [link](https://openneuro.org/datasets/ds004621) |
| [BCI Competition IV](https://www.bbci.de/competition/iv/) | human | EEG / MEG / ECoG (BCI) | .mat / GDF | varies | free-registration | [link](https://www.bbci.de/competition/iv/) |
| [SRM Resting-state EEG](https://openneuro.org/datasets/ds003775) | human | EEG | BIDS (EEG) | ~4.8 GB | open | [link](https://openneuro.org/datasets/ds003775) |
| [Cuban Human Brain Mapping Project](https://chbmp-open.loris.ca/) | human | EEG / MRI / cognition | EDF / NIfTI / CSV | 282 participants | open (LORIS/Synapse/CONP) | [link](https://github.com/conpdatasets/CHBMP) |
| [TDBRAIN](https://brainclinics.com/resources/) | human | EEG / ECG (clinical) | BIDS, raw EEG | ~120 GB, 1,274 subj | free-registration + DUA | [link](https://brainclinics.com/resources/) |
| [ZuCo](https://osf.io/q3zws/) | human | EEG + eye-tracking (reading) | MATLAB, EDF | varies | open (OSF) | [link](https://osf.io/q3zws/) |
| [OpenMIIR](https://github.com/sstober/openmiir) | human | EEG (music imagery) | FIF (MNE) | ~7 GB | open (PDDL) | [link](https://github.com/sstober/openmiir) |
| [EEG Alzheimer's & FTD (ds004504)](https://openneuro.org/datasets/ds004504) | human | EEG | BIDS (EEG) | ~2.8 GB | open (CC0) | [link](https://openneuro.org/datasets/ds004504) |
| [Inner Speech (ds003626)](https://openneuro.org/datasets/ds003626) | human | EEG | BIDS (EEG) | ~20 GB | open (CC0) | [link](https://openneuro.org/datasets/ds003626) |
| [SeizeIT2 (ds005873)](https://openneuro.org/datasets/ds005873) | human | EEG (seizure) | BIDS (EEG) | ~48 GB | open (CC0) | [link](https://openneuro.org/datasets/ds005873) |
| [Bitbrain BOAS Sleep (ds005555)](https://openneuro.org/datasets/ds005555) | human | EEG / PSG | BIDS (EEG) | ~36 GB | open (CC0) | [link](https://openneuro.org/datasets/ds005555) |
| [NATVIEW EEG-fMRI](https://fcon_1000.projects.nitrc.org/indi/retro/nat_view.html) | human | EEG + fMRI | BIDS | varies (22 subj) | open (CC BY 4.0) | [link](https://fcon_1000.projects.nitrc.org/indi/retro/nat_view.html) |
| [NOD-EEG (ds005811)](https://openneuro.org/datasets/ds005811) | human | EEG (vision) | BIDS | ~17 GB | open (CC0) | [link](https://openneuro.org/datasets/ds005811) |

## Human — MEG

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [MOUS (Mother Of Unification Studies)](https://doi.org/10.34973/37n0-yc51) | human | MEG + MRI | BIDS (CTF .ds + NIfTI) | varies (204 subj) | free-registration | [link](https://data.ru.nl/collections/di/dccn/DSC_3011020.09_236) |
| [MNE-Python Sample Datasets](https://mne.tools/stable/documentation/datasets.html) | human | MEG / EEG / MRI | .fif | ~1.5 GB | open | [link](https://mne.tools/stable/documentation/datasets.html) |
| [OMEGA (Open MEG Archive)](https://www.mcgill.ca/bic/resources/omega) | human | MEG + MRI | BIDS (CTF .ds + NIfTI) | varies (644 subj) | data-use-agreement | [link](https://www.mcgill.ca/bic/omega-registration) |
| [MEG-MASC (Gwilliams)](https://osf.io/ag3kj/) | human | MEG | BIDS | varies (27 subj) | open | [link](https://osf.io/ag3kj/) |
| [WAND](https://gin.g-node.org/CUBRIC/WAND) | human | MRI / fMRI / MRS / MEG / TMS | BIDS | 170 participants | open (G-Node GIN) | [link](https://doi.gin.g-node.org/10.12751/g-node.5mv3bf/) |
| [LibriBrain](https://huggingface.co/datasets/pnpl/LibriBrain) | human | MEG (speech) | HDF5 / serialized | ~50 GB | open (public domain) | [link](https://huggingface.co/datasets/pnpl/LibriBrain) |
| [MEG-SCANS (ds006468)](https://openneuro.org/datasets/ds006468) | human | MEG / MRI | BIDS | ~109 GB | open (CC0) | [link](https://openneuro.org/datasets/ds006468) |
| [NOD-MEG (ds005810)](https://openneuro.org/datasets/ds005810) | human | MEG / MRI (vision) | BIDS | ~192 GB | open (CC0) | [link](https://openneuro.org/datasets/ds005810) |

## Human — Intracranial / PET / fNIRS

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [iEEG-fMRI Naturalistic Film (ds003688)](https://openneuro.org/datasets/ds003688) | human | iEEG + fMRI | BIDS | 51 iEEG + 30 fMRI subj | open (CC0) | [link](https://openneuro.org/datasets/ds003688) |
| [Kai Miller Human ECoG Library](https://purl.stanford.edu/zk881ps0522) | human | ECoG | MATLAB | 204 datasets, 34 patients | open (CC BY-SA 4.0) | [link](https://purl.stanford.edu/zk881ps0522) |
| [UPENN / RAM Intracranial Memory (ds004789)](https://openneuro.org/datasets/ds004789) | human | iEEG (ECoG+SEEG) | BIDS, .edf | ~871 GB, 280 subj | open (CC0) | [link](https://openneuro.org/datasets/ds004789) |
| [DANDI 000623 (single-neuron + iEEG + fMRI)](https://dandiarchive.org/dandiset/000623) | human | iEEG + single-neuron + fMRI | NWB + BIDS | ~27.7 GB | open (CC0) | [link](https://dandiarchive.org/dandiset/000623) |
| [IEEG.org](https://www.ieeg.org/) | human + animal | iEEG | portal / API | 1200+ datasets | free-registration | [link](https://www.ieeg.org/) |
| [MNI Open iEEG Atlas](https://mni-open-ieegatlas.research.mcgill.ca) | human | iEEG (normative) | web / spectra | 110 patients, ~2,300 ch | free-registration | [link](https://mni-open-ieegatlas.research.mcgill.ca) |
| [Localize-MI](https://doi.org/10.25493/NXN2-05W) | human | iEEG (SPES) + HD-EEG | BIDS | 7 subj, 61 sessions | open (CC BY 4.0) | [link](https://doi.org/10.25493/NXN2-05W) |
| [NRM2018 PET Grand Challenge (ds001705)](https://openneuro.org/datasets/ds001705) | human | PET | PET-BIDS | 5 individuals | open (CC0) | [link](https://openneuro.org/datasets/ds001705) |
| [Monash rsPET-fMRI (ds002898)](https://openneuro.org/datasets/ds002898) | human | PET (18F-FDG) + fMRI | PET-BIDS | 27 controls | open (CC0) | [link](https://openneuro.org/datasets/ds002898) |
| [First-in-human PS13 COX-1 PET (ds004230)](https://openneuro.org/datasets/ds004230) | human | PET (11C-PS13) | PET-BIDS | varies | open (CC0) | [link](https://openneuro.org/datasets/ds004230) |
| [Tufts fNIRS2MW](https://tufts-hci-lab.github.io/code_and_datasets/fNIRS2MW.html) | human | fNIRS | CSV | 68 subjects | open (CC BY 4.0) | [link](https://tufts-hci-lab.github.io/code_and_datasets/fNIRS2MW.html) |
| [HD-DOT Ball-Squeezing fNIRS (ds005930)](https://openneuro.org/datasets/ds005930) | human | fNIRS | BIDS + SNIRF | varies | open (CC0) | [link](https://openneuro.org/datasets/ds005930) |
| [fNIRS Motion-Artifact (ds005929)](https://openneuro.org/datasets/ds005929) | human | fNIRS | BIDS + SNIRF | varies | open (CC0) | [link](https://openneuro.org/datasets/ds005929) |
| [Finger-Tapping fNIRS (ds005776)](https://openneuro.org/datasets/ds005776) | human | fNIRS | BIDS + SNIRF | varies | open (CC0) | [link](https://openneuro.org/datasets/ds005776) |
| [AJILE12 (DANDI 000055)](https://dandiarchive.org/dandiset/000055) | human | iEEG/ECoG + pose | NWB | ~846 GB | open (CC BY 4.0) | [link](https://dandiarchive.org/dandiset/000055) |
| [Human es-fMRI (ds002799)](https://openneuro.org/datasets/ds002799) | human | iEEG-stim + fMRI | BIDS | ~20 GB | open (CC0) | [link](https://openneuro.org/datasets/ds002799) |
| [Energetic Costs of the Connectome (ds004513)](https://openneuro.org/datasets/ds004513) | human | PET (FDG) + fMRI | PET-BIDS | ~44 GB | open (CC0) | [link](https://openneuro.org/datasets/ds004513) |

## Human — MR Spectroscopy

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Big GABA](https://www.nitrc.org/projects/biggaba/) | human | MRS (MEGA-PRESS / PRESS) | SDAT/RDA/P + CSV | ~0.5 GB/site | open (NC license) | [link](https://www.nitrc.org/frs/?group_id=1019) |

## Human — Quantitative & Microstructure MRI

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [MICRA](https://osf.io/z3mkn/) | human | dMRI / relaxometry / qMT | NIfTI | varies (6 subj x 5 sessions) | open (CC BY) | [link](https://osf.io/z3mkn/) |
| [MASSIVE](https://www.massive-data.org/) | human | dMRI (~8,000 vols) / FLAIR / T1 / T2 | NIfTI | large (1 subj) | open | [link](https://www.massive-data.org/) |
| [Penthera 3T](https://brain.labsolver.org/mds/data-others/brain.html) | human | dMRI (multi-shell, scan-rescan) | NIfTI | varies (13 subj) | open | [link](https://brain.labsolver.org/mds/data-others/brain.html) |
| [MGH Connectome Diffusion Microstructure (CDMD)](https://doi.org/10.6084/m9.figshare.c.5315474) | human | dMRI (300 mT/m) / T1 | NIfTI | large (26 subj) | open | [link](https://doi.org/10.6084/m9.figshare.c.5315474) |

## Human — Spinal Cord

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Spine Generic Multi-Subject](https://github.com/spine-generic/data-multi-subject) | human | spinal cord MRI (qMRI) | NIfTI (BIDS) | ~26 GB (260 subj, 42 sites) | open (CC BY 4.0) | [link](https://github.com/spine-generic/data-multi-subject) |

## Human — Fetal & Neonatal

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Developing Human Connectome Project (dHCP)](https://www.developingconnectome.org/data-release/second-data-release/) | human (neonatal/fetal) | sMRI / dMRI / rfMRI | NIfTI (BIDS) | ~500 GB | free-registration + DUA | [link](https://www.developingconnectome.org/data-release/second-data-release/) |
| [Baby Open Brains (ds005450)](https://openneuro.org/datasets/ds005450) | human (infant) | sMRI + manual segmentations | NIfTI (BIDS) | varies (71 visits) | open | [link](https://openneuro.org/datasets/ds005450) |
| [M-CRIB Neonatal Atlas](https://github.com/DevelopmentalImagingMCRI/M-CRIB_atlas) | human (neonatal) | atlas (T1/T2 + parcellation) | NIfTI | <1 GB | open | [link](https://github.com/DevelopmentalImagingMCRI/M-CRIB_atlas) |

## Human — TMS (Concurrent Stimulation)

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Concurrent TMS-fMRI Causal Connectome (ds005498)](https://openneuro.org/datasets/ds005498) | human | TMS-fMRI / rfMRI / sMRI | BIDS (NIfTI) | varies (152 subj) | open (CC BY-NC-ND 4.0) | [link](https://openneuro.org/datasets/ds005498) |
| [TMS-EEG Parietal Decision-Making (ds004917)](https://openneuro.org/datasets/ds004917) | human | TMS-EEG / fMRI / dMRI | BIDS | varies | open | [link](https://openneuro.org/datasets/ds004917) |

## Human — Sleep

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [National Sleep Research Resource (NSRR)](https://sleepdata.org/) | human | PSG / actigraphy / questionnaire | EDF + XML + CSV | large (tens of thousands of records) | free data-access request + DUA | [link](https://sleepdata.org/datasets) |

## Human — Clinical & Lesion

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [ATLAS v2.0 (Stroke Lesions)](https://fcon_1000.projects.nitrc.org/indi/retro/atlas.html) | human | sMRI (T1) + lesion masks | NIfTI (BIDS) | varies (955 scans) | free-registration (INDI) / restricted (ICPSR native) | [link](https://fcon_1000.projects.nitrc.org/indi/retro/atlas.html) |
| [ISLES 2022](https://doi.org/10.5281/zenodo.7153326) | human | MRI (FLAIR/DWI/ADC) + lesion masks | NIfTI (BIDS) | ~1.7 GB | open (CC BY 4.0) | [link](https://doi.org/10.5281/zenodo.7153326) |
| [BraTS 2021](https://www.cancerimagingarchive.net/analysis-result/rsna-asnr-miccai-brats-2021/) | human | mpMRI + tumor masks | NIfTI / DICOM | ~12 GB (NIfTI) | open (CC BY 4.0) / mixed (TCIA DICOM) | [link](https://www.synapse.org/brats) |

## Human — Brain-Computer Interface & Decoding

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Handwriting BCI (Willett 2021)](https://datadryad.org/dataset/doi:10.5061/dryad.wh70rxwmv) | human | intracortical (motor cortex) | MATLAB | ~1.4 GB | open | [link](https://datadryad.org/dataset/doi:10.5061/dryad.wh70rxwmv) |
| [Speech Neuroprosthesis BCI (Willett 2023)](https://datadryad.org/dataset/doi:10.5061/dryad.x69p8czpq) | human | intracortical (speech motor cortex) | MATLAB (.mat) | ~80 GB | open | [link](https://datadryad.org/dataset/doi:10.5061/dryad.x69p8czpq) |

## Non-Human Primate

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [PRIME-DE](https://fcon_1000.projects.nitrc.org/indi/indiPRIME.html) | macaque (mostly) | MRI / fMRI / diffusion | BIDS / NIfTI | varies (30+ sites, 900+ subjects) | free-registration; per-collection license (mostly CC-BY-NC-SA) | [link](https://fcon_1000.projects.nitrc.org/indi/indiPRIME.html) |
| [Marmoset Brain Mapping](https://marmosetbrainmapping.org/atlas.html) | marmoset | atlas / MRI / fMRI / connectivity | NIfTI / GIFTI | varies (39 marmosets, 709 fMRI runs) | open | [link](https://marmosetbrainmapping.org/atlas.html) |
| [Marmoset Brain Connectivity Atlas](https://www.marmosetbrain.org/) | marmoset | connectivity (tract-tracing) | 3D volumes / web | 143 tracer injections | open (CC-BY-SA 4.0) | [link](https://www.marmosetbrain.org/) |
| [Brain/MINDS 3D Marmoset Reference Atlas](https://dataportal.brainminds.jp/atlas-package-download-main-page) | marmoset | atlas | NIfTI (+ .mrml) | single-brain multimodal | open | [link](https://dataportal.brainminds.jp/atlas-package-download-main-page) |
| [Brain/MINDS Marmoset MRI (NA216/eNA91)](https://dataportal.brainminds.jp/marmoset-mri-na216) | marmoset | MRI / fMRI / diffusion | NIfTI / CSV | 483 individuals | open (CC-BY 4.0) | [link](https://dataportal.brainminds.jp/marmoset-mri-na216) |
| [Brain/MINDS Marmoset Calcium Imaging](https://dataportal.brainminds.jp/caimaging-okano-1) | marmoset | 1p / 2-photon calcium | TIFF / CSV / NWB | large (4 GB chunks) | open (CC-BY 4.0) | [link](https://dataportal.brainminds.jp/caimaging-okano-1) |
| [NMT / CHARM / SARM / D99](https://afni.nimh.nih.gov/NMT) | macaque | atlas / template | NIfTI / GIFTI | 31-macaque template | open | [link](https://afni.nimh.nih.gov/pub/dist/atlases/macaque/nmt/NMT_v2.0_sym.tgz) |
| [Neurotycho](http://neurotycho.org/) | macaque | ECoG | MATLAB (.mat) | varies (4 monkeys, 128-ch) | open (CC0) | [link](http://neurotycho.org/) |
| [TheVirtualBrain Macaque MRI (ds001875)](https://openneuro.org/datasets/ds001875) | macaque | MRI / diffusion / fMRI | BIDS / NIfTI | ~11.5 GB | open (CC0) | [link](https://openneuro.org/datasets/ds001875) |
| [Macaque Color/Contrast/SF (ds005521)](https://openneuro.org/datasets/ds005521) | macaque | fMRI | BIDS / NIfTI | ~38.8 GB | open (CC0) | [link](https://openneuro.org/datasets/ds005521) |
| [Brain Catalogue](https://braincatalogue.org/) | 34 primate species | atlas / MRI | NIfTI | 34 species | open (CC-BY-SA 3.0) | [link](https://braincatalogue.org/) |
| [Freiwald & Tsao Face-Patch](https://readout.info/downloads/datasets/freiwald-tsao-face-views-am-dataset/) | macaque | electrophysiology (single-unit) | MATLAB / CSV / R | 3 monkeys | open (citation required) | [link](https://readout.info/downloads/datasets/freiwald-tsao-face-views-am-dataset/) |
| [TVSD - THINGS Ventral-Stream Spiking](https://doi.gin.g-node.org/10.12751/g-node.hc7zlv/) | macaque | electrophysiology (V1/V4/IT spiking) | spiking / MATLAB | ~3.2 TiB | open (CC BY 4.0) | [link](https://gin.g-node.org/paolo_papale/TVSD) |
| [NHP Reaching (O'Doherty/Sabes)](https://zenodo.org/records/3854034) | macaque | electrophysiology (M1/S1) + kinematics | MATLAB (.mat) | ~24 GB | open (CC BY 4.0) | [link](https://zenodo.org/records/3854034) |
| [Parkinsonian Macaque (DANDI 000947)](https://dandiarchive.org/dandiset/000947) | macaque | electrophysiology | NWB | ~1 TB | open (CC BY 4.0) | [link](https://dandiarchive.org/dandiset/000947) |
| [Macaque Working Memory (DANDI 000620)](https://dandiarchive.org/dandiset/000620) | macaque | electrophysiology | NWB | ~5.5 TB | open (CC BY 4.0) | [link](https://dandiarchive.org/dandiset/000620) |
| [Macaque Wireless ECoG (ds006890)](https://openneuro.org/datasets/ds006890) | macaque | ECoG / iEEG | BIDS | ~44 GB | open (CC0) | [link](https://openneuro.org/datasets/ds006890) |

## Other Mammals (Exotic Species)

| Dataset | Species | Modality | Format | Size | Access | Download |
| --- | --- | --- | --- | --- | --- | --- |
| [Multiscale Representation in Flying Bats (Ulanovsky)](https://doi.org/10.5281/zenodo.4646728) | Egyptian fruit bat | electrophysiology (hippocampal CA1) | MATLAB (.mat) + code (.zip) | ~110 MB | open (CC-BY 4.0) | [link](https://zenodo.org/records/4646728) |
| [Social Coding in Wild Fruit Bats (Ulanovsky)](https://doi.org/10.5281/zenodo.13938638) | Egyptian fruit bat | electrophysiology (hippocampal CA1) | MATLAB (.mat) + code (.zip) | ~3.7 GB | open (CC-BY 4.0) | [link](https://zenodo.org/records/13938638) |
| [Ferret Brain MRI/DTI Templates (Hutchinson)](https://scalablebrainatlas.incf.org/ferret/HSRetal17) | ferret | atlas / template (MRI / DTI) | NIfTI (.nii.gz) | small (152×184×80) | open (citation policy) | [link](https://scalablebrainatlas.incf.org/ferret/HSRetal17) |
| [Awake Dog Resting-State fMRI (ds003830)](https://openneuro.org/datasets/ds003830) | dog (canine) | fMRI (rest) / sMRI | BIDS (NIfTI) | ~9.1 GB | open (CC0) | [link](https://openneuro.org/datasets/ds003830) |
| [Tree Shrew Brain Atlas (9.4T MRI/DTI)](http://www.treeshrewdb.org/MRI/) | tree shrew | atlas / template (MRI / DTI) | NIfTI | varies | open | [link](http://www.treeshrewdb.org/MRI/) |
| [Ovine (Sheep) Brain MRI Atlas](https://www.mcgill.ca/bic/neuroinformatics/brain-atlases-ovine-brain-atlas) | sheep | atlas / template (T1w MRI) | MINC / NIfTI | ~26-413 MB | open | [link](http://packages.bic.mni.mcgill.ca/mni-models/sheep/NIFTI_ovine_05mm.zip) |
| [MSU Comparative Mammalian Brain Collections](https://brains.anatomy.msu.edu/museum/brain/) | 100+ mammal species (dolphin, manatee, elephant, echidna, etc.) | stained sections / MRI (dolphin) | JPEG / images | varies | open (educational use) | [link](https://brains.anatomy.msu.edu/museum/brain/specimens/index.html) |
| [Juvenile Pig Cerebral-Ischemia ECoG/EEG](https://doi.org/10.18112/openneuro.ds003380.v1.0.0) | pig (juvenile) | ECoG / electrothalamogram | BIDS (EDF) | varies | open (CC0) | [link](https://doi.org/10.18112/openneuro.ds003380.v1.0.0) |

## Rodent

| Dataset | Species | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [OpenScope](https://www.allenneuraldynamics.org/projects/openscope) | mouse | Neuropixels / 2-photon | NWB | varies (multi-TB) | open | [link](https://dandiarchive.org/) |
| [IBL Brain-Wide Map](https://www.internationalbrainlab.com/data) | mouse | Neuropixels | ONE/ALF, NWB | ~50 TB (DANDI 000409) | open (CC-BY) | [link](https://dandiarchive.org/dandiset/000409) |
| [Allen Visual Coding - Neuropixels](https://brain-map.org/circuits-behavior/visual-coding-neuropixels) | mouse | Neuropixels | NWB | ~146 GB (~100k neurons) | open | [link](https://allensdk.readthedocs.io/en/latest/visual_coding_neuropixels.html) |
| [Steinmetz et al. 2019](https://figshare.com/articles/dataset/Dataset_from_Steinmetz_et_al_2019/9598406) | mouse | Neuropixels | .mat (also NWB) | ~30k neurons, 39 sessions | open | [link](https://figshare.com/articles/dataset/Dataset_from_Steinmetz_et_al_2019/9598406) |
| [CRCNS hc-3 (Buzsaki Hippocampus)](https://crcns.org/data-sets/hc/hc-3) | rat | silicon-probe | binary (.dat/.eeg) in tar.gz | ~433 GB | free-registration | [link](https://crcns.org/data-sets/hc/hc-3) |
| [Buzsaki Lab Databank](https://buzsakilab.com/wp/database/) | rat / mouse | silicon-probe | NWB, binary | ~40 TB | open | [link](https://buzsakilab.nyumc.org/datasets/) |
| [Svoboda / Janelia ALM-1](https://crcns.org/data-sets/motor-cortex/alm-1) | mouse | silicon-probe | .mat | varies | free-registration | [link](https://crcns.org/data-sets/motor-cortex/alm-1) |
| [AIND Open Data](https://registry.opendata.aws/allen-nd-open-data/) | mouse | Neuropixels / 2p / photometry | NWB | varies (growing) | open (CC-BY-4.0) | [link](https://aind-open-data.s3.amazonaws.com/index.html) |
| [Neuropixels Ultra](https://npultra.steinmetzlab.net/) | mouse | Neuropixels | .mat / NWB | varies | open | [link](https://figshare.com/collections/_/19493588) |
| [UCL Cortexlab Data](https://www.ucl.ac.uk/cortexlab/data) | mouse | Neuropixels / widefield | .mat, NPY, ONE/ALF | varies | open | [link](https://figshare.com/projects/_/41200) |
| [Allen Brain Observatory - Visual Coding 2P](https://observatory.brain-map.org/visualcoding) | mouse | 2-photon | NWB | ~63k neurons | open | [link](https://observatory.brain-map.org/visualcoding) |
| [Allen Visual Behavior - 2P](https://brain-map.org/circuits-behavior/visual-behavior-2p) | mouse | 2-photon | NWB | 34,619 neurons, 551 sessions | open | [link](https://allensdk.readthedocs.io/en/latest/visual_behavior_optical_physiology.html) |
| [Stringer & Pachitariu Spontaneous](https://janelia.figshare.com/articles/dataset/Recordings_of_ten_thousand_neurons_in_visual_cortex_during_spontaneous_behaviors/6163622) | mouse | 2-photon | .mat | ~11.8 GB (~10k neurons) | open | [link](https://janelia.figshare.com/articles/dataset/Recordings_of_ten_thousand_neurons_in_visual_cortex_during_spontaneous_behaviors/6163622) |
| [Allen Visual Behavior - Neuropixels](https://brain-map.org/circuits-behavior/visual-behavior-neuropixels) | mouse | Neuropixels | NWB | ~200k units, 153 sessions | open | [link](https://allensdk.readthedocs.io/en/latest/visual_behavior_neuropixels.html) |
| [CRCNS hc-23 (MEC grid cells)](https://crcns.org/data-sets/hc/hc-23) | rat | silicon-probe | .mat (figshare) | 6 rats | free-registration | [link](https://crcns.org/data-sets/hc/hc-23) |
| [CRCNS hc-11 (CA1 spatial learning)](https://crcns.org/data-sets/hc/hc-11) | rat | silicon-probe | binary / .mat | varies | free-registration | [link](https://crcns.org/data-sets/hc/hc-11) |
| [CRCNS hc-2 (Buzsaki open-field)](https://crcns.org/data-sets/hc/hc-2) | rat | silicon-probe | binary / .mat | varies | free-registration | [link](https://crcns.org/data-sets/hc/hc-2) |
| [CRCNS ssc-1 (barrel cortex 2P)](https://crcns.org/data-sets/ssc/ssc-1) | mouse | 2-photon | NERSC-hosted | varies | free-registration | [link](https://crcns.org/data-sets/ssc/ssc-1) |
| [CRCNS ssc-2 (volumetric 2P)](https://crcns.org/data-sets/ssc/ssc-2) | mouse | 2-photon | NERSC-hosted | ~12,000 neurons/mouse | free-registration | [link](https://crcns.org/data-sets/ssc/ssc-2) |
| [jGCaMP8 V1 (DANDI 000168)](https://dandiarchive.org/dandiset/000168) | mouse | 2-photon + cell-attached | NWB | ~1.38 TB | open (CC-BY-4.0) | [link](https://dandiarchive.org/dandiset/000168) |
| [Whole-Brain fUS in Awake Mice](https://doi.org/10.5281/zenodo.4905862) | mouse | functional ultrasound | MATLAB (.mat) | ~731 MB | open (CC BY 4.0) | [link](https://zenodo.org/records/4905862) |
| [fMOST Whole-Brain Mouse (Zeng Lab)](https://doi.org/10.1038/s41597-024-03761-8) | mouse | fMOST light microscopy + morphology | image volumes + SWC | TB-scale | open | [link](https://www.brainimagelibrary.org/) |

## Other Model Organisms

| Dataset | Organism | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Larval Zebrafish Light-Sheet (Chen 2018)](https://janelia.figshare.com/articles/dataset/Whole-brain_light-sheet_imaging_data/7272617) | zebrafish (larval) | light-sheet calcium | TIFF/MAT in ZIP | ~59.8 GB | open (CC BY-NC 4.0) | [link](https://janelia.figshare.com/articles/dataset/Whole-brain_light-sheet_imaging_data/7272617) |
| [Janelia Whole-Brain Recordings (Ahrens 2013)](https://www.janelia.org/open-science/whole-brain-functional-recordings) | zebrafish (larval) | light-sheet calcium | software + recordings | unknown | open | [link](https://www.janelia.org/open-science/whole-brain-functional-recordings) |
| [mapzebrain](https://mapzebrain.org/home) | zebrafish (larval) | atlas | NIfTI / OBJ / SWC | varies | open | [link](https://mapzebrain.org/home) |
| [Z-Brain](https://zebrafishexplorer.zib.de/) | zebrafish (larval) | atlas | HDF5 / image stacks | varies | open | [link](https://zebrafishexplorer.zib.de/) |
| [Zebrafish Brain Browser](https://zenodo.org/records/3367709) | zebrafish (larval) | atlas | NIfTI | ~4.1 GB | open (CC BY 4.0) | [link](https://zenodo.org/records/3367709) |
| [WormID Whole-Brain Corpus](https://wormid.org/) | C. elegans | light-sheet calcium / atlas | NWB | varies (213 worms, 5 labs) | open | [link](https://wormid.org/datasets) |
| [Kato et al. 2015](https://osf.io/2395t/) | C. elegans | light-sheet calcium | MATLAB (.mat) | ~145 MB | open | [link](https://osf.io/2395t/files/) |
| [NeuroPAL](https://www.hobertlab.org/neuropal/) | C. elegans | calcium / atlas | NWB | ~18 GB (DANDI 000472) | open | [link](https://dandiarchive.org/dandiset/000472) |
| [OpenWorm](https://openworm.org/) | C. elegans | model / connectome | NeuroML / code | varies | open (MIT) | [link](https://github.com/openworm) |
| [Tracking Neurons in a Moving Brain (Nguyen/Leifer 2016)](https://ieee-dataport.org/open-access/tracking-neurons-moving-and-deforming-brain-dataset) | C. elegans | light-sheet calcium | binary / AVI / MAT | ~328 GB | free-registration | [link](https://ieee-dataport.org/open-access/tracking-neurons-moving-and-deforming-brain-dataset) |
| [Brain-wide Behavior Representations (Flavell 2023)](https://dandiarchive.org/dandiset/000776) | C. elegans | light-sheet calcium | NWB | ~1.01 TB | open (CC BY 4.0) | [link](https://dandiarchive.org/dandiset/000776) |
| [NeuroPAL + Immobilized Calcium (Kato lab)](https://dandiarchive.org/dandiset/000565) | C. elegans | light-sheet calcium | NWB | ~46.3 GB | open (CC BY 4.0) | [link](https://dandiarchive.org/dandiset/000565) |
| [OpenWorm Movement Database](https://zenodo.org/communities/open-worm-movement-database/) | C. elegans | behavioral tracking | WCON (JSON) / HDF5 / video | varies (14,874 experiments) | open (CC BY) | [link](https://zenodo.org/communities/open-worm-movement-database/) |
| [Drosophila Whole-Brain Functional Imaging (Aimon/Mann 2017)](https://data.mendeley.com/datasets/8b6nw2xxhn/1) | Drosophila (adult) | 2-photon calcium | NIfTI / TIFF in ZIP | ~3.85 GB | open (CC BY 4.0) | [link](https://data.mendeley.com/datasets/8b6nw2xxhn/1) |
| [Whole-Body Neural Activity in Hydra (Hanson 2024)](https://datadryad.org/landing/show?id=doi:10.5061/dryad.h9w0vt4q3) | Hydra vulgaris | 2-photon calcium | AVI video | ~1.43 GB | open (CC0) | [link](https://datadryad.org/landing/show?id=doi:10.5061/dryad.h9w0vt4q3) |
| [Chronic HVC Recordings in Zebra Finches](https://figshare.com/articles/dataset/Chronic_Recording_of_HVC_in_Free_Behaving_Zebra_FInch_with_Behaviors_Hand_Annotated/15094219) | zebra finch (songbird) | electrophysiology | data + audio in ZIP | ~2.8 GB | open (CC BY 4.0) | [link](https://figshare.com/articles/dataset/Chronic_Recording_of_HVC_in_Free_Behaving_Zebra_FInch_with_Behaviors_Hand_Annotated/15094219) |
| [CRCNS aa-2 (Avian Auditory)](https://crcns.org/data-sets/aa/aa-2) | zebra finch (songbird) | electrophysiology | spike times + WAV | ~180 MB | free-registration | [link](https://portal.nersc.gov/project/crcns/download/aa-2) |
| [CRCNS apl-1 (Aplysia)](https://crcns.org/data-sets/aplysia/apl-1) | Aplysia californica | voltage-sensitive-dye imaging | MATLAB / TXT | ~6.5 GB | free-registration | [link](https://portal.nersc.gov/project/crcns/download/apl-1) |
| [C. elegans Signal Propagation Atlas (DANDI 001075)](https://dandiarchive.org/dandiset/001075) | C. elegans | optogenetics + calcium imaging | NWB | ~4 TB | open (CC BY 4.0) | [link](https://dandiarchive.org/dandiset/001075) |
| [Chickadee Hippocampus Barcodes (Chettih 2024)](https://datadryad.org/dataset/doi:10.5061/dryad.7h44j101z) | black-capped chickadee | electrophysiology + 2-photon (hippocampus) | MATLAB + video | ~38 GB | open | [link](https://datadryad.org/dataset/doi:10.5061/dryad.7h44j101z) |
| [Xenopus Optic-Tectum Ephys (Ciarleglio 2015)](https://datadryad.org/dataset/doi:10.5061/dryad.18kk6) | Xenopus laevis | patch-clamp (optic tectum) | MATLAB (.mat) | ~447 MB | open | [link](https://datadryad.org/dataset/doi:10.5061/dryad.18kk6) |
| [Bengalese Finch Song Repository](https://figshare.com/articles/dataset/Bengalese_Finch_song_repository/4805749) | Bengalese finch | audio song + annotations | .cbin + .not.mat | ~8.7 GB | open (CC0) | [link](https://figshare.com/articles/dataset/Bengalese_Finch_song_repository/4805749) |
| [Octopus Visual System Cell Atlas (Niell 2022)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212528) | Octopus bimaculoides | single-cell RNA-seq (optic lobe) | MTX / TSV / MINiML | varies | open | [link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212528) |
| [Developing Octopus Brain Atlas (Styfhals 2022)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE193622) | Octopus vulgaris | sc / sn RNA-seq (brain) | CSV / RDS / GTF | ~3.7 GB | open | [link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE193622) |
| [Cuttlebase (Sepia bandensis Brain Atlas)](https://cuttlebase.org/) | Sepia bandensis (cuttlefish) | MRI + histology + 3D models | MRI / histology / 3D | varies | open | [link](https://cuttlebase.org/) |
| [Mormyrid Electrosensory Midbrain (Baker 2016)](https://datadryad.org/dataset/doi:10.5061/dryad.892f1) | mormyrid electric fish | ephys (evoked potentials) | MATLAB + Excel | ~322 MB | open (CC0) | [link](https://datadryad.org/dataset/doi:10.5061/dryad.892f1) |
| [Catshark Retina snRNA-seq Atlas (2025)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE282457) | catshark (Scyliorhinus canicula) | snRNA-seq (retina) | FASTQ / matrices / RDS | 17,438 nuclei | open (CC BY 4.0) | [link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE282457) |
| [Lamprey Neural Cell-Type Atlas (Lamanna 2023)](https://lampreybrain.kaessmannlab.org/) | sea lamprey (Petromyzon marinus) | scRNA-seq + in situ sequencing | RDS + ArrayExpress | adult + larval brain | open | [link](https://downloads.kaessmannlab.org/lamprey/) |
| [ARTISTA Axolotl Telencephalon Atlas (Wei 2022)](https://db.cngb.org/stomics/artista/) | axolotl (Ambystoma mexicanum) | spatial transcriptomics (Stereo-seq) | h5ad / RDS / loom / TIFF | 100+ files | open | [link](https://db.cngb.org/stomics/artista/download/) |
| [Turtle Cortex Patch-Clamp (Hemberger 2019)](https://figshare.com/articles/dataset/Turtle_cortex_whole-cell_patch-clamp_recordings/19763017) | turtle (Trachemys scripta) | whole-cell patch-clamp (cortex) | MATLAB (.mat) | ~1.7 GB | open (MIT) | [link](https://figshare.com/articles/dataset/Turtle_cortex_whole-cell_patch-clamp_recordings/19763017) |
| [Ex Vivo Turtle Cortex + Visual Stim (Shew/Wessel)](https://figshare.com/articles/journal_contribution/Ex_vivo_turtle_cortex_with_visual_stimulation_Shew_Lab_Wessel_Lab_/4907009) | turtle | multi-electrode array (visual stim) | data ZIP (14 expts) | ~35 GB | open (CC BY 4.0) | [link](https://figshare.com/articles/journal_contribution/Ex_vivo_turtle_cortex_with_visual_stimulation_Shew_Lab_Wessel_Lab_/4907009) |
| [Eurasian Blackcap 3D Brain Atlas (2026)](https://brainglobe.info/projects/blackcap/index.html) | Eurasian blackcap (Sylvia atricapilla) | atlas (serial 2-photon tomography) | BrainGlobe API / TIFF (25 µm) | 8 brains, 44 regions | open | [link](https://gin.g-node.org/BrainGlobe/blackcap_materials) |
| [Insect Brain Database (InsectBrainDB)](https://insectbraindb.org/) | 30+ insect species | brain atlases + neuron morphologies | OBJ (web + API) | varies | open (CC BY 4.0) | [link](https://insectbraindb.org/app/) |
| [Honeybee Standard Brain (HSBA)](https://www.bcp.fu-berlin.de/en/biologie/arbeitsgruppen/neurobiologie/ag_menzel/beebrain/hsb/index.html) | Apis mellifera | brain atlas (registered template) | TIFF stacks + VRML | ~20 MB | open | [link](https://www.bcp.fu-berlin.de/en/biologie/arbeitsgruppen/neurobiologie/ag_menzel/beebrain/download/index.html) |
| [Honey Bee Antennal Lobe Ca Imaging (Paoli 2024)](https://datadryad.org/dataset/doi:10.5061/dryad.qbzkh18sc) | Apis mellifera | calcium imaging (antennal lobe) | MATLAB .mat | ~277 MB | open (CC0) | [link](https://doi.org/10.5061/dryad.qbzkh18sc) |
| [Bumblebee Standard Brain Atlas (InsectBrainDB)](https://insectbraindb.org/app/species/10) | Bombus terrestris | brain atlas (micro-CT template) | OBJ + micro-CT | varies | open (CC BY 4.0) | [link](https://hdl.handle.net/20.500.12158/SIN-0000010.3) |
| [Harpegnathos Ant Brain Single-Cell (GSE135513)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE135513) | Harpegnathos saltator | scRNA-seq (brain) | DGE matrices | ~84 MB | open | [link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE135513) |
| [Locust Antennal Lobe Tetrode (Pouzat/Laurent)](https://zenodo.org/records/14607) | Schistocerca americana | ephys (tetrode, antennal lobe) | HDF5 | ~2.3 MB | open (CC0) | [link](https://zenodo.org/records/14607) |
| [Monarch Butterfly Standard Brain Atlas (InsectBrainDB)](https://insectbraindb.org/app/species/5) | Danaus plexippus | brain atlas + neurons | OBJ | varies | open (CC BY 4.0) | [link](https://hdl.handle.net/20.500.12158/SIN-0000005.1) |
| [Mosquito Brain Atlas](https://www.mosquitobrains.org/) | Aedes aegypti | brain atlas (template) | MHD/raw + ITK-SNAP | varies | open | [link](https://www.mosquitobrains.org/downloads-and-links) |
| [Uloborus Spider Brain Atlas (BIL)](https://doi.org/10.35077/ace-owl-gum) | Uloborus diversus (spider) | brain atlas (immunofluorescence) | TIFF stacks | varies | open | [link](https://doi.org/10.35077/ace-owl-gum) |
| [Web-Building Spider Brain Single-Cell (GSE241696)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE241696) | Hylyphantes graminicola (spider) | scRNA-seq (brain) | 10x matrices | varies | open | [link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE241696) |
| [Nematostella Single-Cell Atlas (2024)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE200198) | Nematostella vectensis (sea anemone) | scRNA-seq (whole organism) | MTX / GEO + UCSC browser | varies | open (CC BY 4.0) | [link](https://sea-anemone-atlas.cells.ucsc.edu) |
| [Ctenophore Aboral-Organ Volume EM (Mnemiopsis)](https://doi.org/10.6084/m9.figshare.29314115.v1) | Mnemiopsis leidyi (ctenophore) | serial block-face SEM (volume EM) | TIFF stacks | ~71.4 GB | open (CC BY 4.0) | [link](https://doi.org/10.6084/m9.figshare.29314115.v1) |
| [Berghia Head-Ganglia Cell Atlas (Ramirez 2024)](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA698785) | Berghia stephanieae (nudibranch) | scRNA-seq (head ganglia) | SRA / FASTQ | varies | open | [link](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA698785) |
| [Crab STG at Varying pH (Marder 2018)](https://osf.io/r7aes/) | Cancer borealis (crab) | ephys (STG / CG) | ABF / data files | varies | open | [link](https://osf.io/r7aes/files/) |
| [Crab STG at Varying Temperature (Marder)](https://zenodo.org/records/5139650) | Cancer borealis (crab) | ephys (STG) | ABF | ~125 MB | open (CC BY 4.0) | [link](https://zenodo.org/records/5139650) |
| [Leech Ganglion EM + VSD Imaging (Ashaber 2021)](https://leechem.caltech.edu) | Hirudo verbana (leech) | SBF-EM + voltage-sensitive-dye imaging | Neuroglancer + data | varies | open | [link](https://github.com/wagenadl/leechem-public) |

## Organoids & In Vitro

| Dataset | Sample | Modality | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Human Brain Organoid Firing Sequences (DANDI 001603)](https://dandiarchive.org/dandiset/001603) | human organoid (iPSC) | extracellular ephys (in vitro) | NWB | ~322 GB | open | [link](https://dandiarchive.org/dandiset/001603) |
| [Neural Organoid Shell-MEA (DANDI 001336)](https://dandiarchive.org/dandiset/001336) | human organoid (iPSC) | MEA ephys (in vitro) | NWB | ~35 GB | open | [link](https://dandiarchive.org/dandiset/001336) |

## Connectomics — EM Reconstructions

| Dataset | Species | What reconstructed | Format | Approx size | Access | Download |
|---|---|---|---|---|---|---|
| [FlyWire](https://flywire.ai) | *Drosophila* (adult female) | whole-brain connectome (~139K neurons, 50M+ synapses) | Neuroglancer precomputed + CAVE; CSV connectivity (Codex) | volume varies (TB-scale EM); connectivity ~GB | free-registration (CAVE/Google login for queries) | [link](https://codex.flywire.ai/) |
| [MICrONS (cortical mm³)](https://www.microns-explorer.org/cortical-mm3) | mouse (visual cortex, P87) | ~200K cells, ~523M synapses, co-registered 2-photon | Neuroglancer precomputed + CAVE; AWS/GCP buckets | multi-TB | open (Neuroglancer); free-registration for CAVE | [link](https://ngl.microns-explorer.org) |
| [H01 (Human Cortex 1mm³)](https://h01-release.storage.googleapis.com/landing.html) | human (temporal cortex) | ~tens of thousands of neurons, 183M synapses | Neuroglancer precomputed | ~1.4 PB | open | [link](https://h01-release.storage.googleapis.com/landing.html) |
| [FAFB (Full Adult Fly Brain)](https://temca2data.org/) | *Drosophila* (adult) | whole-brain ssEM volume (synaptic resolution) | CATMAID (Neuroglancer via VFB) | ~TB-scale | open; non-commercial (CC BY-NC 4.0) | [link](https://fafb.catmaid.virtualflybrain.org/) |
| [Janelia Hemibrain](https://www.janelia.org/project-team/flyem/hemibrain) | *Drosophila* (adult) | central-brain connectome (~25K neurons) | Neo4j (neuPrint) + CSV adjacency; Neuroglancer | connectivity ~GB | open (CC-BY 4.0) | [link](https://storage.cloud.google.com/hemibrain/v1.2/exported-traced-adjacencies-v1.2.tar.gz) |
| [Male CNS Connectome](https://www.janelia.org/project-team/flyem/male-cns-connectome) | *Drosophila* (adult male) | complete CNS connectome (brain + optic lobes + VNC) | Neo4j (neuPrint); Neuroglancer; flat-file download | varies | open (CC-BY 4.0) | [link](https://janelia-flyem.github.io/male-cns/download/) |
| [MANC (Male Adult Nerve Cord)](https://www.janelia.org/project-team/flyem/manc-connectome) | *Drosophila* (adult male) | VNC connectome (~23K neurons, 10M pre / 74M post sites) | Neo4j (neuPrint); Neuroglancer; flat files | connectivity ~GB | open (CC-BY 4.0) | [link](https://console.cloud.google.com/storage/browser/flyem-manc-exports) |
| [Larval Drosophila Connectome](https://github.com/brain-networks/larval-drosophila-connectome) | *Drosophila* (larva) | whole-brain connectome (3,016 neurons, ~548K synapses; Winding 2023) | CSV / adjacency matrices (zip) | CSV (MB) | open | [link](https://github.com/brain-networks/larval-drosophila-connectome) |
| [C. elegans Connectome (WormWiring)](https://www.wormwiring.org/) | *C. elegans* (+ *P. pacificus*) | White 1986 + Cook 2019 whole-animal connectomes | Excel / CSV (connectivity) | CSV (MB) | open | [link](https://www.wormwiring.org/) |
| [Larval Zebrafish Whole-Brain EM (Hildebrand 2017)](https://neurodata.io/data/hildebrand17/) | larval zebrafish | anterior-quarter ssEM; myelinated projectome | Neuroglancer precomputed | TB-scale | open (ODC-By v1.0) | [link](https://neurodata.io/data/hildebrand17/) |
| [Eyewire / e2198 Mouse Retina](https://blog.eyewire.org/behind-the-science-about-the-data/) | mouse (retina) | citizen-science neuron reconstructions from e2198 SBEM | meshes / skeletons (GitHub) | varies | open | [link](https://blog.eyewire.org/behind-the-science-about-the-data/) |
| [neuPrint](https://neuprint.janelia.org/) | *Drosophila* (multiple) | connectome graph query service (hemibrain, MANC, maleCNS, optic-lobe) | Neo4j (Cypher / Python / R) | varies | open; Google login for full queries | [link](https://neuprint.janelia.org/) |
| [FlyEM Optic Lobe](https://www.janelia.org/project-team/flyem/optic-lobe) | *Drosophila* (adult male) | right optic lobe connectome (>50K neurons, >700 cell types; Nern 2025) | Neo4j (neuPrint); Neuroglancer; flat files | connectivity ~GB | open (CC-BY 4.0) | [link](https://neuprint.janelia.org/?dataset=optic-lobe:v1.0) |
| [FANC (Female Adult Nerve Cord)](https://github.com/htem/FANC_auto_recon) | *Drosophila* (adult female) | VNC ssEM + segmentation (GridTape-TEM) | Neuroglancer (BossDB) + CAVE | TB-scale | mixed (EM open on BossDB; segmentation via community join) | [link](https://github.com/htem/FANC_auto_recon/wiki) |
| [Kasthuri et al. 2015](https://neurodata.io/data/kasthuri15/) | mouse (neocortex) | saturated reconstruction of a sub-volume (all cellular objects) | Neuroglancer precomputed (BossDB) | ~660 GB | open | [link](https://bossdb.org/project/kasthuri2015) |
| [CREMI Challenge](https://cremi.org/) | *Drosophila* (adult) | ssEM volumes w/ neuron + synaptic-partner ground truth (from FAFB) | HDF5 | ~33 GB (2017 release) | open | [link](https://cremi.org/data/) |
| [SNEMI3D Challenge](https://snemi3d.grand-challenge.org/) | mouse (neocortex) | ssSEM stacks w/ neurite segmentation ground truth | image stacks (TIFF) | small (2× 100× 1024² slices) | free-registration (also on Zenodo) | [link](https://zenodo.org/records/7142003) |
| [Ciona Larva Connectome (Ryan 2016)](https://elifesciences.org/articles/16962) | *Ciona intestinalis* (tadpole larva) | whole-CNS connectome (177 neurons, 6,618 synapses) | Excel (connectivity matrices, supp. data) | CSV (MB) | open (CC BY) | [link](https://elifesciences.org/articles/16962/figures) |
| [Fish1 (Larval Zebrafish Whole-Brain EM)](https://fish1-release.storage.googleapis.com/index.html) | larval zebrafish (7 dpf) | whole-brain ssEM (>187K somata, ~30M synapses; 4×4×30 nm) | Neuroglancer precomputed + CAVE | PB-scale (varies) | mixed (open browsing; free-registration to edit) | [link](https://fish1-release.storage.googleapis.com/index.html) |
| [C. elegans Developmental Connectome (Witvliet 2021)](https://www.nature.com/articles/s41586-021-03778-8) | *C. elegans* (8 brains across development) | full-brain connectomes across postnatal stages (ssEM) | CSV / Python / MATLAB (connectivity) | CSV (MB) | open | [link](https://github.com/dwitvliet/nature2021) |
| [Zebrafish Olfactory Bulb (Wanner 2016)](https://neurodata.io/data/wanner16/) | larval zebrafish (olfactory bulb) | dense reconstruction of 1,022 neurons (~98% of OB) | Neuroglancer precomputed (BossDB); skeletons | varies | open (ODC-By v1.0) | [link](https://neurodata.io/data/wanner16/) |

## Atlases & Reference Spaces

| Dataset | Species | Type | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Allen Mouse Brain CCFv3](https://atlas.brain-map.org/) | mouse | reference atlas / parcellation | NRRD, NIfTI | ~660 structures, 10 µm | open | [link](http://download.alleninstitute.org/informatics-archive/current-release/mouse_ccf/) |
| [BigBrain](https://bigbrainproject.org/) | human | reference atlas | NIfTI, MINC | >1 TB, 20 µm | open (CC BY-SA 4.0) | [link](https://www.bigbrainproject.org/maps-and-models.html#download) |
| [Julich-Brain Atlas](https://julich-brain-atlas.de/) | human | parcellation (cytoarchitecture) | NIfTI (via EBRAINS) | 200+ areas | open (free-registration for full EBRAINS) | [link](https://atlases.ebrains.eu/viewer/) |
| [Waxholm Space Rat Atlas](https://www.nitrc.org/projects/whs-sd-atlas) | rat | reference atlas / parcellation | NIfTI-1 | ~1 GB; 222 structures | open (CC BY 4.0) | [link](https://www.nitrc.org/frs/?group_id=1081) |
| [Scalable Brain Atlas](https://scalablebrainatlas.incf.org/) | multi-species | reference atlas (aggregator) | SVG, X3D, STL, API | 20+ templates | open | [link](https://scalablebrainatlas.incf.org/) |
| [MNI ICBM152 2009](https://nist.mni.mcgill.ca/icbm-152-nonlinear-atlases-2009/) | human | reference template | MINC, NIfTI | ~55-360 MB per variant | open (BIC license) | [link](https://nist.mni.mcgill.ca/icbm-152-nonlinear-atlases-2009/) |
| [fsaverage (FreeSurfer)](https://surfer.nmr.mgh.harvard.edu/fswiki/FsAverage) | human | reference atlas (surface) | FreeSurfer surfaces | ships with FreeSurfer | open (FreeSurfer license) | [link](https://surfer.nmr.mgh.harvard.edu/fswiki/DownloadAndInstall) |
| [Talairach Daemon Atlas](https://www.nitrc.org/projects/tal-daemon/) | human | parcellation (labels) | NIfTI (via FSL/PickAtlas) | small | open | [link](https://www.nitrc.org/projects/tal-daemon/) |
| [Brainnetome Atlas](https://atlas.brainnetome.org/) | human | parcellation (connectivity-based) | NIfTI | 246 subregions | open | [link](http://atlas.brainnetome.org/download.html) |
| [AAL3 Atlas](https://www.gin.cnrs.fr/en/tools/aal/) | human | parcellation | NIfTI | ~170 regions | open (GNU GPL) | [link](https://www.gin.cnrs.fr/en/tools/aal/) |
| [Schaefer / Yeo Parcellations](https://github.com/ThomasYeoLab/CBIG/tree/master/stable_projects/brain_parcellation/Schaefer2018_LocalGlobal) | human | parcellation | NIfTI, GIFTI, CIFTI | 100-1000 parcels | open | [link](https://github.com/ThomasYeoLab/CBIG/tree/master/stable_projects/brain_parcellation/Schaefer2018_LocalGlobal/Parcellations) |
| [Allen Mouse Brain Connectivity Atlas](https://connectivity.brain-map.org/) | mouse | connectivity (mesoscale) | image data, API/SDK | whole-brain, 100s of experiments | open | [link](https://connectivity.brain-map.org/) |

## Gene Expression & Transcriptomics

| Dataset | Species | Type | Format | Size | Access | Download |
|---|---|---|---|---|---|---|
| [Allen Mouse Brain Atlas (ISH)](https://mouse.brain-map.org/) | mouse | ISH expression | image data, API/SDK | ~20,000 genes | open | [link](https://mouse.brain-map.org/) |
| [Allen Human Brain Atlas (microarray)](https://human.brain-map.org/) | human | microarray | CSV, API | 6 donors | open | [link](https://human.brain-map.org/static/download) |
| [Allen Brain Cell (ABC) Atlas](https://brain-map.org/atlases-and-data/bkp/abc-atlas) | mouse, human | scRNA-seq / spatial (MERFISH) | h5ad, CSV (S3) | ~4M + ~9M cells (mouse) | open; non-commercial (CC BY-NC) | [link](https://alleninstitute.github.io/abc_atlas_access/) |
| [Allen Cell Types Database](https://celltypes.brain-map.org/) | mouse, human | scRNA-seq (+ ephys, morphology) | SWC, counts, NWB, API | thousands of cells | open | [link](https://celltypes.brain-map.org/data) |
| [BICCN / BICAN](https://biccn.org/) | mouse, human, NHP | multimodal (scRNA / spatial / connectivity) | varies | varies | open (QC-passing public) | [link](https://nemoarchive.org/) |
| [BrainSpan](https://www.brainspan.org/) | human | RNA-seq + exon microarray (developmental) | CSV, image data | prenatal-adult | open | [link](https://www.brainspan.org/static/download.html) |
| [Human Protein Atlas - Brain](https://www.proteinatlas.org/humanproteome/brain) | human, pig, mouse | RNA-seq + IHC + spatial | TSV, XML | 13 regions | open (CC BY 4.0) | [link](https://www.proteinatlas.org/about/download) |
| [CZ CELLxGENE Discover](https://cellxgene.cziscience.com/) | human, mouse, others | scRNA-seq | h5ad, RDS, Census API | 33M+ cells, 436+ datasets | open (CC BY) | [link](https://cellxgene.cziscience.com/datasets) |
| [Tabula Muris](https://tabula-muris.sf.czbiohub.org/) | mouse | scRNA-seq | CSV / Robj (figshare) | ~100,000 cells | open (CC BY 4.0) | [link](https://figshare.com/projects/Tabula_Muris_Transcriptomic_characterization_of_20_organs_and_tissues_from_Mus_musculus_at_single_cell_resolution/27733) |
| [Linnarsson Lab Mouse Brain Atlas](http://mousebrain.org/) | mouse | scRNA-seq | loom | ~500k cells | open | [link](http://mousebrain.org/) |
| [Allen Developing Mouse Brain Atlas](https://developingmouse.brain-map.org/) | mouse | ISH expression (developmental) | image data, API | E11.5-P56 | open | [link](https://developingmouse.brain-map.org/) |
| [GTEx (brain)](https://gtexportal.org/home/) | human | bulk RNA-seq (+ snRNA-seq) | GCT, TSV, h5ad | 13 brain regions | mixed (open summary; controlled raw) | [link](https://gtexportal.org/home/downloads/adult-gtex/overview) |
| [PsychENCODE](https://www.psychencode.org/) | human | scRNA / spatial / bulk + epigenomic | varies (Synapse) | varies | free-registration; some controlled | [link](https://www.synapse.org/) |
| [CZ Single Cell Portal (Broad)](https://singlecell.broadinstitute.org/single_cell) | multi | scRNA-seq | h5ad, MTX, CSV | ~79M cells, 1000+ studies | free-registration | [link](https://singlecell.broadinstitute.org/single_cell) |
| [Human Cell Atlas Data Portal](https://data.humancellatlas.org/) | human | scRNA-seq | loom, h5ad, fastq, MTX | ~70.8M cells, 530 projects | open (CC BY 4.0) | [link](https://explore.data.humancellatlas.org/) |
| [Marmoset Gene Atlas (Brain/MINDS)](https://gene-atlas.brainminds.jp/) | marmoset | ISH expression | image data | genome-wide | open; non-commercial (attribution) | [link](https://gene-atlas.brainminds.jp/) |
| [STARmap PLUS Mouse CNS](https://zenodo.org/records/8327576) | mouse | spatial transcriptomics | h5ad / CSV | 1.09M cells, 1,022 genes | open | [link](https://zenodo.org/records/8327576) |
