# Awesome-Clinical-Trials-Patient-Engagement

# Top Patient Engagement (Clinical Trials) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Patient Retention, ePRO/eCOA, Remote Monitoring & Decentralized Trial Participation*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Patient Engagement in Clinical Trials**. These tools help sponsors, CROs, and research sites keep participants informed, compliant, and connected throughout the trial lifecycle — from recruitment through retention — using mobile apps, ePRO/eCOA, remote monitoring, and secure communication channels.

**Examples** include Medable, THREAD Science, Science 37, Castor, Clario, Signant Health, YPrime, ObvioHealth, Curebase, and Florence Healthcare (the category leaders).

**Open-source emphasis**: Clinical trial patient engagement has a **small but meaningful open-source ecosystem**. **PROACT 2.0** is a purpose-built open-source patient-doctor communication app developed for cancer trials . **Arcwell** is an open-source clinical research platform that has powered real trials at Penn Medicine and handles 4,000+ custom clinical rules . **OpenClinica Participate** provides integrated ePRO/eCOA without requiring app downloads . **REDCap + MyCap** offers a free participant-facing mobile app for non-profit research . This section documents these self-hostable solutions and their practical applications.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Medable](https://www.medable.com/)**  
  Decentralized clinical trial platform with eConsent, ePRO, eCOA, and remote data collection. Supports BYOD (bring your own device) and patient-centric trial design. Approximately 1 million patients enrolled .

- **[THREAD Science](https://www.threadresearch.com/)**  
  Decentralized clinical trial platform with ePRO, eCOA, remote patient monitoring, and virtual visit tools. Focused on bringing clinical research into patient homes.

- **[Science 37](https://www.science37.com/)**  
  Metasite unified platform for virtual clinical trials. Enables remote participation through eConsent, ePRO, telemedicine, and scheduling in a single app-based experience.

- **[Castor](https://www.castoredc.com/)**  
  Clinical research platform with eConsent, ePRO, and decentralized trial tools. Approximately 7 million patients and 147,000 users . Mobile-compatible tools for remote participation and strong patient engagement .

- **[Clario](https://clario.com/)**  
  Clinical endpoint technology provider with eCOA, ePRO, and cardiac safety solutions. Formed from ERT and Bioclinica merger.

- **[Signant Health](https://www.signanthealth.com/)**  
  Clinical outcome assessment specialist with eCOA, eConsent, and ePRO. Deep expertise in instrument design and linguistic validation.

- **[YPrime](https://www.yprime.com/)**  
  eClinical technology platform with eCOA, ePRO, IRT, and clinical data management. Known for rapid deployment and flexible solutions.

- **[ObvioHealth](https://www.obviohealth.com/)**  
  Decentralized clinical trial platform focused on patient engagement and remote data collection.

- **[Curebase](https://www.curebase.com/)**  
  Decentralized clinical trial platform with eConsent, ePRO, and telemedicine capabilities.

- **[Florence Healthcare](https://florencehc.com/)**  
  Site-focused platform for clinical trial document management and patient engagement.

## Open-Source GitHub Projects

- **[PROACT 2.0](https://github.com/Proact2)**  
  **The most purpose-built open-source patient engagement tool for clinical trials.** Developed at Fondazione IRCCS Istituto Nazionale Tumori in Milan, in collaboration with The Christie (Manchester), within the UpSMART Accelerator project . A mobile and web application for **secure, non-urgent communication** between patients and healthcare providers in cancer trials. Supports **text, audio, and video messaging**, allowing patients to report adverse events and side effects while enabling medical teams to collect PRO data . Includes **questionnaire and survey submission** via Analyst Console for research purposes . **Multilingual** (Italian, English, German, French, Spanish, Dutch). Tested in a feasibility study with 15 phase I patients at Istituto Nazionale dei Tumori, with high satisfaction reported . Planned for use in a multicentric trial (CCE-DART, Horizon 2020) across cancer centers in UK, Spain, France, Germany, and Netherlands . Tech stack: .NET6, C#, Xamarin, React.js. **Mozilla Public License 2.0**. Full code available at github.com/Proact2 .

- **[Arcwell](https://github.com/arcweb/arcwell)**  
  **Open-source clinical research platform with proven production deployments.** Released by Arcweb Technologies in October 2024 . Enables healthcare organizations to **design, build, and deploy clinical trials and wellness protocols** using a robust rules engine for autonomous clinical operations . Supports **eCOA and ePRO collection within an EDC system** — studies can graduate on the same infrastructure . **Successfully implemented at two healthcare institutions**: Researchers at Perelman School of Medicine (University of Pennsylvania) used Arcwell for a clinical trial evaluating a patient navigation tool for antepartum anemia; another healthcare organization built a custom decision support tool on Arcwell handling **4,000+ custom clinical rules** . Data model centers on **Facts, FactTypes, People, Resources, and Events** with configurable dimension schemas for different data types (blood pressure readings, emotion journals, survey responses, PROs, device readings) . **Apache 2.0 license** . Vendor lock-in and total cost of ownership drastically reduced .

- **[OpenClinica Participate](https://github.com/OpenClinica/OpenClinica)**  
  **Integrated ePRO/eCOA module within OpenClinica EDC** — no separate system to manage . Features **zero friction for participants**: no app to download, no username/password to remember. Participants access their dashboard securely from any device (BYOD) . Supports **rich media** (images, video, visual analog scales, interactive elements). **Automated text and email reminders** keep participants on track . Patient-reported data flows directly into the study database in real time with **no manual entry or transcription errors** . **Single checkbox** switches between eCRF and eCOA forms in the same system . **Complete audit trail** capturing patient, clinician, and study team activity in a single view. HIPAA-compliant . Trusted by 1,500+ sponsors, CROs, and research sites worldwide . **Open-source community edition available**; enterprise module may require licensing .

- **[REDCap + MyCap](https://projectredcap.org/)**  
  **Free participant-facing mobile app for non-profit research.** **MyCap** is a customizable app available at no cost to REDCap users . Provides a **centralized study "home"** for participants with messaging, reminders, and access to study information . Participants can **submit data, complete tasks, send/receive messages, and locate study contact information** . Supports **active tasks** using device sensors (e.g., finger tapping for Parkinson's assessment) . **Offline data collection** with automatic sync when connectivity returns . Participants join via QR code or App Link. Available on iOS and Android. **The REDCap Mobile App** (for data collectors) complements MyCap (for participants) . **REDCap itself is free for non-profit organizations** through the REDCap Consortium. Used by 6,000+ institutions in 150+ countries.

- **[REDCap Patient-Facing Technology (PFT) Framework](https://europepmc.org/articles/PMC12150733)**  
  **Documented architecture for building patient-facing tools on REDCap.** Published in 2025, this work describes the design of a PFT based on REDCap for cancer patients to self-track medication concerns and symptoms during care transitions . Leverages **branching logic, piping, smart variables, alerts & notifications, file repository, action tags, field embedding, and API integration** to create a dynamic, user-friendly patient experience . Example: medication and symptom tracking form where severity options for diarrhea only appear if patient selects "Diarrhea" as a symptom — reducing reporting burden . Connects REDCap to **Google Looker Studio** via API for automated data visualization . Provides guidance for developers building sustainable PFT architectures .

### Additional Strong Open-Source Options

- **Patient-Doctor Communication**: **PROACT 2.0** (purpose-built for cancer trials, text/audio/video messaging) .
- **Full Clinical Research Platform**: **Arcwell** (production-proven, Apache 2.0, eCOA/ePRO within EDC) .
- **Integrated ePRO within EDC**: **OpenClinica Participate** (zero-friction BYOD, no app required) .
- **REDCap Ecosystem**: **MyCap** (free participant app), **REDCap PFT Framework** (documented architecture for patient-facing tools) .
- **PharmaLedger / OpenDSU**: Blockchain-based open-source platform for eConsent, clinical trial recruitment, and patient-controlled data sharing .

**Frameworks for building custom systems**: Combine **PROACT 2.0** for patient-provider communication in oncology trials, **Arcwell** for a complete clinical research platform with eCOA/ePRO and rules engine, **OpenClinica Participate** for zero-friction ePRO integrated with EDC, and **REDCap + MyCap** for free participant-facing mobile data collection. Add **PostgreSQL/MySQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Patient engagement platforms handle sensitive clinical trial and patient data; ensure compliance with 21 CFR Part 11, ICH-GCP, HIPAA, GDPR, and applicable regional regulations.
- **Open-source reality**: The open-source ecosystem for clinical trial patient engagement is **small but growing**. **PROACT 2.0** and **Arcwell** are production-proven and actively used in real trials . **OpenClinica Participate** and **REDCap/MyCap** provide mature, integrated ePRO/eCOA capabilities . However, commercial platforms (Medable, THREAD, Science 37) offer broader decentralized trial orchestration, global support infrastructure, and comprehensive patient services that open-source alternatives cannot match without significant institutional investment.
