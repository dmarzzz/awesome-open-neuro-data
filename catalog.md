# Open Neuro Data Catalog

A companion to [README.md](README.md) with structured metadata for each dataset: species, modality, format, approximate size, access, and a direct download or data-access link. The README is the canonical curated list; this catalog adds detail for concrete datasets.

Access legend: **open** (no gate) · **free-registration** · **data-use-agreement** · **mixed**. Sizes are approximate and, for portals and growing archives, listed as "varies".

> **Status: populated category by category.** Human MRI/fMRI, Non-Human Primate, Atlases & Reference Spaces, and Gene Expression & Transcriptomics are done. The remaining categories (general archives, human EEG/MEG/iEEG/PET/fNIRS, rodent, connectomics, model organisms) are being enriched and will land in the next pass.

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
