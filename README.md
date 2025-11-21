# ViSVS: On Automatic Singing Voice Synthesis for Vietnamese

[![Conference](https://img.shields.io/badge/Status-Under%20Review%20(ACIIDS%202026)-red)](http://www.aciids.pwr.edu.pl/)
[![Task](https://img.shields.io/badge/Task-Singing%20Voice%20Synthesis-blue)](https://paperswithcode.com/task/singing-voice-synthesis)
[![Language](https://img.shields.io/badge/Language-Vietnamese-green)]()
[![Demo](https://img.shields.io/badge/Demo-Listen%20Here-orange)](https://anonymous.4open.science/w/demo_v2-B86F/)

This repository is the official implementation for the paper **"ViSVS: On Automatic Singing Voice Synthesis for Vietnamese"**, submitted to the **18th Asian Conference on Intelligent Information and Database Systems (ACIIDS 2026)**.

## 📢 Important Notice

**Current Status:** 🟡 **UNDER REVIEW**

To comply with the double-blind review policy of ACIIDS 2026, the source code and dataset are currently **restricted**.
* The full implementation and the **ViSVS Dataset** will be made publicly available immediately upon the paper's acceptance.
* Currently, this repository serves to host the **audio samples** and project information.

---

## 🎵 Abstract

Singing Voice Synthesis (SVS) for tonal languages like Vietnamese presents unique challenges. This paper introduces **ViSVS**, the first comprehensive framework dedicated to Automatic Vietnamese Singing Voice Synthesis.

**Key Contributions:**
1.  **ViSVS Dataset:** We constructed a high-quality dataset containing **3.68 hours** of recordings from **four native Vietnamese singers**, fully annotated with phonemes and lyrics.
2.  **Methodology:** Our system leverages the **DiffSinger** architecture combined with **Large Language Models (LLMs)** to enhance the naturalness and expressiveness of the generated singing voice.
3.  **Performance:** Experimental results show that ViSVS generates intelligible and expressive singing with high fidelity in pitch, rhythm, and phonetic articulation.

## 🎧 Audio Samples (Demo)

We strongly encourage listeners to evaluate the quality of our synthesis through the samples provided.

👉 **[Click here to visit the Anonymous Demo Page](https://anonymous.4open.science/w/demo_v2-B86F/)**

*(This link contains samples comparing ViSVS with Ground Truth and other baselines)*

## 🏗️ Architecture Overview

*The proposed ViSVS framework integrates LLMs into the DiffSinger backbone to capture the nuances of Vietnamese singing.*

*(Architecture diagram will be added here upon publication)*

## 📂 Dataset Details (Upcoming)

The **ViSVS Dataset** will be released with the following specifications:
* **Total Duration:** ~3.68 hours.
* **Speakers:** 4 Native Vietnamese Singers.
* **Annotations:** Time-aligned lyrics, phonemes, pitch, and duration.

## 📚 Citation

If you find this work useful for your research (or wish to cite the preprint), please use the following BibTeX:

```bibtex

@inproceedings{huynh2026visvs,
  title={ViSVS: On Automatic Singing Voice Synthesis for Vietnamese},
  author={Huynh, Nghiep An and Nguyen, Luan Thanh},
  booktitle={Submitted to The 18th Asian Conference on Intelligent Information and Database Systems (ACIIDS 2026)},
  year={2026}
}