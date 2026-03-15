---
layout: default
title: "fMRI: Resources"
---

## Clinical language fMRI resources

This page contains an overview of and pointers to some key clinical information for clinicians setting up or running a clinical language fMRI program.

Dr. Benjamin also offers consulting on setting up or improving existing clinical language fMRI services — see the [contact page](/contact/).

---

### Key references

Consistent with the interdisciplinary nature of fMRI, a range of disciplines have put forth clinical guidelines in its use. There is not yet a clear model showing how these different professions can best collaborate to improve clinical care. When it develops, such a model may look like that used in the intracarotid amobarbital procedure (IAT or "Wada" test) which fMRI supplements.

The most comprehensive and interdisciplinary guidelines to date have recently been posted by the Organization for Human Brain Mapping, and are [available here](https://apertureneuro.org/article/128149.pdf).

Prior to the release of these:

**Neuropsychology:** Some of the earliest guidelines came from the Division of Neuropsychology, who emphasize the skills required for clinical fMRI and the roles that might be played by different disciplines ([APA Division 40, 2004](https://www.tandfonline.com/doi/full/10.1080/1385404049088718)).

**Radiology:** The American College of Radiology (ACR), the American Society of Neuroradiology (ASNR), and the Society for Pediatric Radiology also provide technical guidelines, revised in 2017. These focus largely on technical aspects of image acquisition. They also provide useful guidelines on reporting of diagnostic imaging (ACR, 2014). A key concern in language fMRI is the cognitive task used, and how this impacts findings. The ASNR have recently provided guidance here ([Black, 2017](https://www.ajnr.org/content/early/2017/08/31/ajnr.A5345)). While a useful starting point, this is based on a survey of what tasks radiologists are using, and there is an urgent need for evidence-based guidelines from clinicians expert in cognitive design.

**Neurology:** A good review of evidence supporting the use of language fMRI for pre-surgical planning is provided in the American Academy of Neurology practice guidelines ([Szaflarski et al., 2017](https://www.neurology.org/content/88/4/395)).

In the past decade, surveys of fMRI use have given clear insights into current practice. Data from a pair of papers are summarized below; other more focused surveys exist including Bargallo's [2020 survey of European programs](https://link.springer.com/content/pdf/10.1007/s00234-020-02397-w.pdf).

---

### What are teams actually doing? What tasks do they use? What software? Who is actually completing fMRI at different sites?

While language fMRI is widely used, what it looks like varies dramatically across programs. We previously surveyed analysts completing fMRI to identify current de-facto standards of practice, as part of a pair of surveys on clinical fMRI use ([Benjamin et al., 2018](https://onlinelibrary.wiley.com/doi/10.1002/hbm.24229)).

Little is known about how language functional MRI (fMRI) is executed in clinical practice in spite of its widespread use. Here we comprehensively documented its execution in surgical planning in epilepsy. A questionnaire focusing on cognitive design, MR acquisition, analysis, and interpretation and practical considerations was developed. Individuals responsible for collecting, analyzing, and interpreting clinical language fMRI data at 63 epilepsy surgical programs responded. The central finding was of marked heterogeneity in all aspects of fMRI. Most programs use multiple tasks, with a fifth routinely using 2, 3, 4 or 5 tasks with a modal run duration of five minutes. Variants of over fifteen protocols are in routine use with forms of noun-verb generation, verbal fluency, and semantic decision-making used most often. Nearly all aspects of data acquisition and analysis vary markedly. Neither of the two best-validated protocols were used by more than 10% of respondents. Preprocessing steps are broadly consistent across sites, language-related blood flow is most often identified using general linear modeling (76% of respondents), and statistical thresholding typically varies by patient (79%). The software SPM is most often used. fMRI programs inconsistently include input from experts with all required skills (imaging, cognitive assessment, MR physics, statistical analysis, brain-behavior relationships). These data highlight marked gaps between the evidence supporting fMRI and its clinical application. Teams performing language fMRI may benefit from evaluating practice with reference to the best-validated protocols to date and ensuring individuals trained in all aspects of fMRI are involved to optimize patient care.

---

### How do clinicians using fMRI interpret the data in surgical planning? Are many teams using it? Does it predict patient outcomes well?

While there are many assumptions about how fMRI is interpreted, there has not been any data on this. In this second survey clinicians detailed their experience with fMRI in surgical planning ([Benjamin et al., 2017](https://onlinelibrary.wiley.com/doi/10.1002/hbm.24039)).

The goal of this study was to document current clinical practice and report patient outcomes in presurgical language functional MRI (fMRI) for epilepsy surgery. Epilepsy surgical programs worldwide were surveyed as to the utility, implementation, and efficacy of language fMRI in the clinic; 82 programs responded. Respondents were predominantly US (61%) academic programs (85%), and evaluated adults (44%), adults and children (40%), or children only (16%). Nearly all (96%) reported using language fMRI. Surprisingly, fMRI is used to guide surgical margins (44% of programs) as well as lateralize language (100%). Sites using fMRI for localization most often use a distance margin around activation of 10mm. While considered useful, 56% of programs reported at least one instance of disagreement with other measures. Direct brain stimulation typically confirmed fMRI findings (74%) when guiding margins, but instances of unpredicted decline were reported by 17% of programs and 54% reported unexpected preservation of function. Programs reporting unexpected decline did not clearly differ from those which did not. Clinicians using fMRI to guide surgical margins do not typically map known language-critical areas beyond Broca's and Wernicke's. This initial data shows many clinical teams are confident using fMRI not only for language lateralization but also to guide surgical margins. Reported cases of unexpected language preservation when fMRI activation is resected, and cases of language decline when it is not, emphasize a critical need for further validation. Comprehensive studies comparing commonly-used fMRI paradigms to predict stimulation mapping and post-surgical language decline remain of high importance.

---

### Do billing guidelines exist?

In the US, clinical billing of fMRI recognizes the fact that language fMRI is multidisciplinary. Multiple CPT codes are available, including:

- **70554:** MRI, brain, fMRI; including test selection and administration of repetitive body part movement and/or visual stimulation, not requiring physician or psychologist administration.
- **70555:** MRI, brain, fMRI; requiring physician or psychologist administration. Must also be billed with 96020.
- **96020:** Neurofunctional testing selection and administration during noninvasive imaging functional brain mapping, with test administered entirely by a physician or psychologist, with review of test results and report.

The survey of clinical analysts, above, also details the codes that teams are actually using and the hours taken.

Discussion on the use of these codes is available in:

- [Bobholz et al. (2007). Clinical Use of Functional Magnetic Resonance Imaging: Reflections on the New CPT Codes. *Neuropsychol. Review* 17(2):189.](https://pmc.ncbi.nlm.nih.gov/articles/PMC4012423/)
- [Hart et al. (2014). Clinical Functional Magnetic Resonance Imaging. *Cognitive & Behavioral Neurology* 20(3):141.](https://pubmed.ncbi.nlm.nih.gov/17846511/)

---

### How should I manage the data? Do any standards exist?

There are now multiple different codified data structures available that help you store your MRI data in a way that is clear, simple, and easily understood by others.

This is extremely beneficial in fMRI for many reasons; in the clinic it will allow you to easily share data with other groups in the future for research, encourage others working with you to fully document their tasks and analysis, and allow future researchers at your institution to revisit and use your data.

A particularly useful standard is **BIDS** — the Brain Imaging Data Structure Specification. This is a quite simple specification that can be set up in a relatively short period of time. Full details are available in the group's brief and clear Nature Scientific Data paper, and in the full specifications on [their website](https://bids.neuroimaging.io).
