---
layout: default
---
View simple CV layout [here](https://vic-cheung.github.io/simple_cv).<br>
<br>

## EDUCATION
* * *

| Institution                             | Degree        | Area of Study           |                                              |
|:----------------------------------------|:--------------|:------------------------|----------------------------------------------|
| University of California, San Francisco | PhD           | Genetics                | Systems Neuroscience                         |
| University of California, San Diego     | BS            | Microbiology            | minor: Chinese Studies                       |

<br>

Additional Courses:<br>

| Institution                             | Degree        | Area of Study           |                                              |
|:----------------------------------------|:--------------|:------------------------|----------------------------------------------|
| Genentech L.E.A.D Discovery Program     | Certification | Supply Chain Management |                                              |
| Cold Spring Harbor Laboratory           |               | Vision                  | _Linking Circuits, Perception, and Behavior_ |

<br>

## CAREER EXPERIENCE
* * *
### **Computational Biologist**
[Freenome](https://www.freenome.com/about-f)<br>
_APR 2022 - Present_ <br>
- Apply bioinformatics, data science, and computational methods (including AI/ML techniques) to analyze multi-omic data to reveal, model, and interpret changes in both the cancer (pathways, gene activities, proteins) and the immune system (composition, activity, and repertoires) associated with clinical outcomes.
  - Generate new insights and interpretations.
  -Leverage existing computational methods and develop new ones to extract immunological signals from existing and new data.
- Partner cross-functionally in the scientific planning and execution of collaborative projects, such as molecular and cancer biologists, immunologists, computational biologists, medical affairs, commercial, business development.
- Execute research projects to model various biological changes resulting from diseases such as cancer, autoimmune disease, and infection with various business partners.
- Developed a software package for reproducible data analysis for the team.
- Wrote distributed workflows (Flyte) to increase efficiency of scRNAseq alignment and data aggregation from a scale of running for 8 days to half a day. 


**_Technologies used:_**<br>
 - Python (ScanPy, NumPy, Pandas, scikit-learn, Matplotlib, SciPy, Freenome proprietary software)
 - R (fgsea, Seurat)<br>

<br><br>

### **Oncology Bioinformatics & Molecular Oncology- PhD Intern**
[Genentech](https://www.gene.com/)<br>
_SEP 2021 - APR 2022_ <br>
Characterized gene signature development and refinement for T cell signaling pathways in cancer models<br>
- Wrote a data processing pipeline utilizing Scanpy, Numpy, Pandas, scikit-learn, SciPy 
- Performed statistical analyses on different drug treatment populations.
  - Gene set enrichment analysis
  - Differential gene expression analysis
- Utilized supervised batch correction techniques and unsupervised clustering algorithms (UMAP, topic modeling) to visualize and analyze single cell RNA seq data outputs. 
- Wrote custom plotting functions using Matplotlib to better visualize the effect of drug treatments.

**_Technologies used:_**<br>
 - Python (ScanPy, NumPy, Pandas, scikit-learn, Matplotlib, SciPy)
 - R (fgsea, SingleCellExperiment, Seurat, Genentech proprietary software)<br>

<br><br>

### **Graduate Researcher in Single-cell Omics, Systems Neuroscience**
[Evan Feinberg Lab](http://www.evanfeinberglab.com/who-we-are) @ [UCSF](https://tetrad.ucsf.edu/)<br>
_JUL 2016 - DEC 2021_ <br>
**Project 1**<br>
Developed a multiplexed, high-throughput, single-cell sequencing method for neurons that preserve connectivity information in addition to obtaining molecular identity (VECTORseq). Git Repo [here](https://github.com/vic-cheung/vectorseq).
- Wrote the data processing pipeline using Python after genome alignment using Cellranger (10x Genomics) on an AWS EC2 instance.
  - Used unsupervised machine learning techniques such as t-SNE/UMAP clustering to match molecular identities to cellular function and role in behavioral output.
  - Implemented nearest neighbors algorithms to account for batch differences when merging datasets.
- Streamlined brain dissociation techniques and increased neuron survivability yield 100-fold based on data-driven outcomes from clustering analyses.
- Validated clustering results of single-cell sequencing against the [2020 10x sequencing dataset from the Allen Atlas](https://portal.brain-map.org/atlases-and-data/rnaseq/mouse-whole-cortex-and-hippocampus-10x) and that the methodology was functional.
  - Evaluated range of highly variable genes expressed per cluster for the validation of cell identity
- Managed collaborations with the Chan-Zuckerberg Biohub (Spyros Darmanis Group, now @ Genentech)

**_Technologies used:_**<br>
 - AWS (EC2/S3)
 - Linux, bash, CellRanger
 - Python (ScanPy, NumPy, Pandas, scikit-learn, Matplotlib, SciPy)
 - FIJI, Zen
 - Illumina Next Gen Sequencing, 10x Genomics 5' Sequencing
 - stereotaxic surgeries, viral delivery


**Project 2**<br>
Designed an audition-based behavioral paradigm to study sensorimotor integration in the context of mice.<br>
- Wrote custom software to support custom-built hardware using serial communication between MATLAB and an Arduino microprocessor, which increased productivity by - 6-fold from the parallelization and automation of data acquisition, storage, and analysis.
- Used this system in exploring how sensory input is represented in the brain and transformed into behavioral commands, using mice as the model organism.
- Wrote custom analyses software to automate, refine, and interpret both raw behavioral data and fiber photometry signals.
- Used CAD software to design and 3D print custom behavioral apparatuses.
- Refined surgical protocols to increase survival surgery success by 20%. Delivery of viruses, drugs, and organic dyes into the mouse brain.
- Performed physiology recordings on brain slices to validate optogenetic and fiber photometry experiments
- Assembled fiber photometry and optogenetic manipulation equipment to record and perturb neuronal activity in the context of quantitative behavioral assays.

**_Technologies used:_**<br>
 - CAD Software (Onshape, Cura, eMachineShop)
 - MATLAB
 - Arduino (Uno)
 - FIJI, Zen
 - stereotaxic surgeries, viral delivery, fiber optic implants
 - fiber photometry, optogenetics
 - immunohistochemistry

<br><br>

### **Health Data Science Fellow**
[Insight Data Science](https://insightfellows.com/health-data) @Silicon Valley<br>
_MAY 2020 - JUL 2020_ <br>
Developed a predictive clinical calculator to assess Acute Kidney Injury in hospitalized patients, which would result in better management, care/medication dosing, injury prevention, and reduced hospital length of stay, thus freeing up occupied resources and minimizing financial costs to both patient and hospital.
- Utilized PostgreSQL querying to gather relevant data from the MIMIC-III database and manipulated the data with Python Pandas from 25 tables of data, 46,000 patients, thousands of diagnoses and lab tests, and clinical documentation-- generating over 3 million rows of data and 70 unique features comprising lab tests and demographic information. 
- Used supervised machine learning in Python such as regression models from scikit-learn and XGBoost to forecast Acute Kidney Injury, with a predictive accuracy of ~91%.
- Medium Article in Towards Data Science: [Predicting Acute Kidney Injury in Hospitalized Patients Using Machine Learning](https://towardsdatascience.com/predicting-acute-kidney-injury-in-hospitalized-patients-53ca07525e67)

**_Technologies used:_**<br>
 - Python (NumPy, scikit-learn, Matplotlib, SciPy, XGBoost)
 - SQL
 - AWS (EC2, S3, Route 53)
 - Streamlit
 
<br><br><br>
    
## OTHER EXPERIENCE
* * *
### **[Genentech](https://www.gene.com/) Discovery Program L.E.A.D Supply Chain**
[Certification](https://docs.google.com/viewer?url=https://github.com/vic-cheung/vic-cheung.github.io/raw/main/pdfs/VictoriaCheung_SupplyChainCertificate.pdf)<br>
_JUL 2020 - AUG 2020_ <br>
- Learned about the fundamentals of supply chain, how the supply chain spans a variety of roles throughout Genentech's delivery of therapies as well as its involvement in providing medication access to underserved communities and its drive towards sustainability. 
- Chatted with supply chain business leaders to interact with individuals in the industry. 
- Discussed the transferability of skills from the PhD to business/supply chain.
- Participated as Operations Lead in a supply chain simulation where my team and I placed second overall.	

<br><br>

### **Graduate Resarcher--rotation**
[Guo Huang Lab](https://www.cvri.ucsf.edu/~huang/lab/Research.html) @ UCSF<br>
_APR 2016 - JUN 2016_ <br>
Area of Research: Regenerative Potential of Cardiomyocytes<br>
- Performed heart explants for cell culture and subsequent drug studies for the purpose of exploring organ regeneration and repair in neonatal mice—with an emphasis on the pathways that regulate resident stem cell activation and mature cell de-differentiation/proliferation. 
- Explored organ regeneration and development from an evolutionary standpoint across different species of animals i.e. naked mole rat, finch, rat, mouse, zebrafish.
- Utilized innovative and integrated approaches in engineering, single cell analysis, advanced imaging microscopy, drug delivery, and genome manipulation technology.

<br><br>

### **Graduate Resarcher--rotation**
[Dengke Ma Lab](https://malab.ucsf.edu/research) @ UCSF<br>
_SEP 2015 - DEC 2015_ <br>
Area of Research: Homeostatic Response to Extreme Abiotic Factors<br>
- Created a functional mutant line in C. elegans via cDNA microinjections and exposed the mutants to extreme abiotic environments via behavioral assays to understand cellular intrinsic tolerance of hypoxia/anoxia and hypothermia.
- Utilized RNA-seq to identify genes implicated in cryopreservation/hypoxia-tolerance with therapeutic potential.
- Obtained qualitative behavioral data on how animals sensed and responded to changes in internal states to elicit behavior and maintain homeostasis.

<br><br>

### **Research Fellowship: [UCLEADS](https://www.ucop.edu/graduate-studies/initiatives-outreach/uc-leads.html) & [STARS](https://grad.ucsd.edu/diversity/programs/stars/index.html)**
[Andrew D. Huberman Lab](https://hubermanlab.com/about/) @ UCSD<br>
_SEP 2012 - JUL 2015_ <br>
Area of Research: Binocular Plasticity & Dynamic Strategy Implementation in Cuttlefish <br>
- Developed a model of visual perception and prey capture using cuttlefish to study the neural circuit organization supporting flexible eye movements. 
  - Underlying goal: provide insight into amblyopia (lazy eye)
- Optimized behavioral parameters and refined surgical techniques for the novel model organism.
  - Increased consistency between experiments for reproducibility.
- Optimized tracking and analysis of dynamical eye movements using multi-planar high-speed imaging and Simi Motion software.
  - Increased productivity and output by 40%
- 3D-reconstructed neuron structure for morphometric analysis using Neurolucida. 

<br><br>

### **Research Fellowship: [UCSF SRTP](https://graduate.ucsf.edu/srtp)**
[David R. Copenhagen Lab](https://neurograd.ucsf.edu/people/david-copenhagen-phd) @ UCSF<br>
_JUN 2014 - SEP 2014_ <br>
Area of Research: Effects of Light Dependent Ca<sup>2+</sup> Signaling during retinal development<br>
- Explored the effects of light dependent Ca<sup>2+</sup> waves in the developing mouse retina with a focus on the coupling of amacrine cells to melanopsin ganglion cells via gap junctions. 
- Characterized appropriate transgenic lines and established baseline comparisons in adult retina to observe and document deviations from the developed animal to the developing animal.
- Performed retinal dissections for cell coupling studies.

<br><br>

## MENTORSHIP | DIVERSITY
* * *
### **Mentor for Undergraduates**
_JUN 2026 - SEP 2021_ <br>
- Trained and mentored 3 undergraduates on performing research tasks on how to: think independently, plan experiments, perform surgical protocols, and analyze data. Gave career/research advice.
- Post-graduation outcomes of the 3 undergraduates: 
  1. data analyst @[BoxLunch](https://www.boxlunch.com/homepage?cm_mmc=SEM-_-GGL-_-BR-_-DMY-_-541787926_57911524309&gclid=CjwKCAiAx8KQBhAGEiwAD3EiP-FK2iMX9GHn7rNmiIQvYcnjXlKJkunprrDSj0u4bnXOVlWWHPe9YBoC1TMQAvD_BwE)
  2. research scientist @[Alkahest](https://www.alkahest.com/)
  3. applying to medical school

<br>

### **Student Advisor**
[UCSF SRTP](https://graduate.ucsf.edu/srtp)<br>
_JUN 2019 - AUG 2019_ <br>
- Developed curriculum for and taught curriculum to teach rising junior and senior undergraduates on: 
 - how to become a strong graduate school applicant
 - how to create compelling posters and presentations
 - how to write personal statements
 - how to read and dissect scientific papers

<br>

### **Student Teacher**
[UCSF Science and Health Education Partnership](https://sep.ucsf.edu/what-we-do/)<br>
_JAN 2016 - JUN 2016_ <br>
- Created and developed a series of interactive and investigative lesson plans to teach freshman biology.
- Mentored URMs and socioeconomically disadvantaged students on different career paths in science.

<br>

### **UC Leadership Excellence through Advanced Degrees Scholar(UCLEADS)**
[UCSD](https://www.ucop.edu/graduate-studies/initiatives-outreach/uc-leads.html) <br>
_MAR 2013 - JUN 2015_ <br>
"Mentorship program for underprivileged and socioeconomically disadvantaged undergraduates for success in graduate school to later assume positions of leadership in industry, government, public service, and academia following completion of a doctoral STEM degree"
- Two-way avenue: 
  1. Received mentorship from prior two cohorts as part of the incoming cohort
  2. Provided mentorship to the next two cohorts while progressing through the program

<br><br><br>    

## HONORS & AWARDS
* * *

| Year | Title                                                  |
|:-----|:-------------------------------------------------------|
| 2017 | Helmsley Scholar                                       |
| 2015 | UC LEADs Symposium Presentation Award                  |
| 2014 | SACNAS National Research Conference Travel Scholarship |
| 2013 | UCSD STARS Scholarly Presentation Award                |
| 2013 | SACNAS National Research Conference Travel Scholarship |
| 2013 | UCSD Provost Honors                                    |
| 2012 | UCSD Provost Honors                                    |
| 2012 | Kaiser Permanente Valuable Volunteer Award             |
| 2011 | UCSD Provost Honors                                    |
| 2011 | Kaiser Permanente Student Achievement Award            |

<br><br>

## PUBLICATIONS
* * *
Vallania, F., **Cheung, V.**, Zamba, MD., Liu, J., Pasupathy, A., Donnella, H., Bailey, M., Louie, M., Lin, J., Havenith, K., Qin, Y., Pantano, S., Wuerthner, J., van Berkel, PH.; [Identification of Predictive Biomarkers for Response of R/R DLBCL Patients Treated with Loncastuximab Tesirine Using Low Pass Whole-Genome Sequencing (WGS).](https://ash.confex.com/ash/2022/webprogram/Paper168993.html) Blood 2022; 140 (Supplement 1): 3551–3552. doi: https://doi.org/10.1182/blood-2022-168993

**Cheung, V.**, Chung, P., and Feinberg, E.H. (2022) [Transcriptional profiling of mouse projection neurons with VECTORseq](https://doi.org/10.1016/j.xpro.2022.101625) STAR Protocols, 3(3):101625<br>

**Cheung, V.**, Chung, P., Bjorni, M., Shvareva, V.A., Lopez, Y.C., and Feinberg, E.H. (2021) [Virally Encoded Connectivity Transgenic Overlay RNA sequencing (VECTORseq) defines projection neurons involved in sensorimotor integration.](https://doi.org/10.1016/j.celrep.2021.110131) Cell Reports, 37(12):110131<br>

**Cheung, V.** "[Predicting Acute Kidney Injury in Hospitalized Patients Using Machine Learning](https://towardsdatascience.com/predicting-acute-kidney-injury-in-hospitalized-patients-53ca07525e67)" Towards Data Science. Medium, 20 Jun. 2020. Web.<br>

<br><br><br>

## CONFERENCES & TALKS
* * *
#### _Scientific_:

| Year | Event                                                     | Participation  |                                                    |
|:-----|:----------------------------------------------------------|:---------------|:---------------------------------------------------|
| 2023 | American Association for Cancer Research (AACR            | Presenter      | poster presentation                                |
| 2022 | American Society of Hematology (ASH)                      | Presenter      | [poster presentation] (https://www.freenome.com/identification-of-predictive-biomarkers-for-response-of-dlbcl-patients-treated-with-loncastuximab-tesirine)                                |
| 2021 | UCSF S.O.L.V.E. Health Tech: Digital Health Equity Summit | Attendee       |                                                    |
| 2021 | COSYNE (computational and systems neuroscience)           | Attendee       |                                                    |
| 2018 | UCSF Tetrad                                               | Presenter      | 15 min talk                                        |
| 2017 | SFN Annual Conference                                     | Attendee       |                                                    |
| 2017 | UCSF Tetrad                                               | Presenter      | [poster presentation](https://drive.google.com/file/d/1VY1vLNHZ4-AddPjyyCRSl7R-7-u23iEZ/view?usp=sharing)                                |
| 2016 | UC LEADs Research Symposium                               | Attendee       |                                                    |
| 2015 | UC LEADs Research Symposium                               | Presenter      | poster presentation                                |
| 2014 | SFN Annual Conference                                     | Presenter      | poster presentation                                |
| 2014 | UCSF Summer Research Training Program Symposium           | Presenter      | poster presentation + 15 min talk                  |
| 2014 | UCSD Academic Enrichment Program                          | Presenter      | poster presentation                                |
| 2014 | SACNAS National Conference                                | Presenter      | poster presentation                                |
| 2014 | UCLEADs Annual Research Symposium                         | Presenter      | poster presentation                                |
| 2013 | UCSD Academic Enrichment Program                          | Presenter      | poster presentation                                |
| 2013 | SACNAS National Conference                                | Presenter      | poster presentation                                |
| 2013 | UCSD STARS Summer Research Conference                     | Presenter      | 15 min talk                                        

#### _Diversity & Outreach_:

| Year | Event                                                         | Participation  |          |
|:-----|:--------------------------------------------------------------|:---------------|:---------|
| 2022 | SRTP Co-Curriculum: What Can You Do With a PhD?               | Panelist       | 1 hr     |
| 2019 | Northern California Forum for Diversity in Graduate Education | Panelist       | 1 hr     |
| 2018 | Northern California Forum for Diversity in Graduate Education | Panelist       | 1 hr     |

<br>

## MEDIA FEATURES
* * *

| Year |              |                |
|:-----|:-------------|:---------------|
| 2019 | UCSF Poster  | [First Generation to College](https://docs.google.com/viewer?url=https://github.com/vic-cheung/vic-cheung.github.io/raw/main/pdfs/VictoriaCheung_FG2Cposter.pdf) |
| 2019 | UCSF Article |[Students Who Are First in Their Family to Attend College Share Stories, Experiences](https://www.ucsf.edu/news/2019/08/415181/students-who-are-first-their-family-attend-college-share-stories-experiences) |

<br><br><br>
