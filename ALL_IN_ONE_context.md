# ALL-IN-ONE CONTEXT PACK (paste into a new chat)


=================== 00_STARTER_PROMPT.md ===================

# Starter prompt (paste into a new chat)

I am applying for Senior Lecturer (Grade DS13), Department of Software Engineering and Information Systems, Faculty of Computer Science and Information Technology (FSKTM), Universiti Putra Malaysia. Closing date: 15 November 2026. I am attaching my context pack: profile, education, publications, code, experience, final CV text, final cover letter, evidence list, rules and to-do list.

Please:
1. Read all files first and summarise my situation in five lines so I can confirm you understood.
2. Follow `10_rules_and_corrections.md` strictly. Never add a claim that my documents do not support. Label planned work as planned.
3. Reply in English. Be direct about weaknesses. Fix wording, not facts.
4. Work through `11_todo.md` with me, starting with the highest-priority item.
5. When you edit the CV or letter, show exactly what changed and why.

My main strengths: metaheuristic and stochastic optimisation (3 Q1 papers, 6 first-author papers of 9 selected). My main gap: no published software engineering work yet (testing, maintenance, security, AI for software engineering). Treat that gap honestly.

=================== 01_profile.md ===================

# Profile

- Name: Mok Ren Hao
- Highest qualification: PhD in Electrical and Electronic Engineering, UMPSA (conferred 20 August 2025)
- Registration: BEM Graduate Engineer, G1276385A (branch: Electronic; approved 21 May 2026)
- Address on CV and letter: Taman Rendang, 26600, Pekan, Pahang (where I live now). Permanent address on IC and BEM certificate: Kota Bharu, Kelantan. I do NOT list a Subang Jaya address (it was used on earlier applications only to suggest proximity to the employer; do not reuse it). Use the Pekan address, with the Kota Bharu address as permanent address on forms.
- Phone: 018-665 7950
- Email: mokrenhao@gmail.com
- ORCID: 0000-0002-6937-0603
- Scopus ID: 57193923199
- Google Scholar: "RenHao Mok"
- GitHub: https://github.com/MokRH
- Languages: Chinese (native), English (fluent), Malay (fluent). SPM 2008 Bahasa Melayu: grade 5C.
- Metrics (as of October 2026): Scopus 321 citations, h-index 9; Google Scholar 364 citations, h-index 9, i10-index 9.
- Current situation: partner and design engineer of RS Technologies Empire (registered partnership, Pekan, Pahang; first registered 27 May 2019 with partners; current registration from July 2024; small business, not profitable, so I am seeking a sustainable academic career). Director and 15% shareholder of INCUS Solutions Sdn. Bhd. (incorporated 12 March 2019; ceased operations 2025; dissolution in progress). No fixed employment contract, so I can start immediately.
- Research area line used on CV: Metaheuristic Computing.
- Photo: formal passport-style, 7:9 crop (assets/mok_ren_hao_cv_photo.jpg).

- IoT and sensing (selling point, advised by a lecturer): my electrical engineering background covers sensor interfacing (ADC, I2C, UART, SPI), PCB design, ESP32/ESP32-CAM and Arduino. I have BASIC skill in MQTT, Node-RED and Grafana. Say "basic level" for those three; never claim advanced IoT platform or cloud experience.

=================== 02_target_job.md ===================

# Target post

- Post: Pensyarah Kanan (Senior Lecturer), Grade DS13, permanent
- Department: Software Engineering and Information Systems (Jabatan Kejuruteraan Perisian dan Sistem Maklumat)
- Faculty: FSKTM, Universiti Putra Malaysia
- Service scheme: University Lecturer; Education Service; Management and Professional group
- Salary range in advert: RM6,210 to RM14,370
- Required areas: Software Security; Software Maintenance; Software Testing; Metaheuristic Computing; AI for Software Engineering
- Closing date: 15 November 2026
- CV language: English
- Letter addressed to: The Dean, Faculty of Computer Science and Information Technology (FSKTM), Universiti Putra Malaysia, 43400 UPM Serdang, Selangor Darul Ehsan. (The faculty page listed Dato' Prof. Dr. Shamala K. Subramaniam as Dean, last updated Feb 2024; current holder not confirmed, so the letter uses the title only.)
- Faculty page also links UPM's eJOBS portal (ejobs.upm.edu.my). Verify in the advert how to apply and any required form or certified copies.

## Fit summary
- Strong: Metaheuristic Computing (thesis, 9 papers, public MATLAB code).
- Gap: Software Testing, Maintenance, Security, AI for SE. The CV and letter present these as a labelled research plan, not completed work.
- Best single improvement still open: a small pilot (for example, SFA variants vs GA/PSO on test case prioritisation) with a GitHub link and short report.

=================== 03_education.md ===================

# Education (from scrolls and transcripts)

| Award | Details |
|---|---|
| Doctor of Philosophy | Field of research: Electrical and Electronic Engineering. UMPSA (formerly Universiti Malaysia Pahang), Faculty of Electrical & Electronic Engineering Technology. Sessions 2019/2020 to 2024/2025. Senate approved and conferred 20 August 2025. Thesis (transcript spelling): "Data-driven Tool using Enhanced Smoothed Functional Algorithm for Nonlinear Modeling and Advanced PID Control Problems". |
| Master of Science | Field of research: Electronic. Faculty of Electrical & Electronics Engineering, UMP. Sessions 2016/2017 to 2017/2018. Senate approved 24 July 2019; scroll dated 16 November 2019. Thesis: "Model-Free Wind Farm Power Production Optimization Using Multi-Resolution Optimized Relative Step Size Random Search". |
| B.Eng (Hons) Electrical Engineering (Electronics) | Second Class (Upper), CGPA 3.13. Senate approved 23 September 2016; scroll 20 November 2016. First graded semester 2013/2014 semester 2, so CV says 2014 to 2016. |
| Diploma in Electrical Engineering (Industrial Electronics) | Second Class, CGPA 3.25. Senate approved 11 February 2014; scroll 12 October 2014. Sessions 2011/2012 to 2013/2014, so CV says 2011 to 2014. |
| SPM | 2008. |

## Thesis results used on the CV
- PhD: proposed NLSFA (norm-limited update vector) and CMSFA (comparative-memory scheme) variants of the smoothed functional algorithm. Tested on a twin rotor system, flexible manipulator, FOPID control of an AVR system and neuroendocrine PID control of a MIMO gantry crane. Benchmarked against PSO and simulated annealing. Function of Demerit improvement "up to 62.62%" (abstract wording is ambiguous, so keep "up to").
- MSc: MR-ORSSRS on the 80-turbine Horns Rev wind farm (six wind directions, five-turbine failure, time-varying wind). Convergence up to 88.89% faster than the MR-SPSA benchmark.
- PhD supervisor and referee: Assoc. Prof. Ts. Dr. Mohd Ashraf Bin Ahmad.

=================== 04_publications.md ===================

# Publications (10 selected; full list on Scopus/ORCID)

Five journal articles (three Q1, two Q3) and five conference papers. First author on six; co-author on four. Quartiles are JCR of the stated year.

| # | Title | Venue, year | Quartile | My role | DOI |
|---|---|---|---|---|---|
| 1 | Improved smoothed functional algorithms-optimized PID controller for efficient speed regulation of wind turbines | IEEE Transactions on Industry Applications, 2025, 61, 7546-7560 | Q1 (JCR 2025) | Co-author (4th of 6 per UMP/UTeM repository record) | 10.1109/TIA.2025.3550137 |
| 2 | An improved marine predators algorithm-tuned fractional-order PID controller for automatic voltage regulator system | Fractal and Fractional, 2023, 7(7), 561 | Q1 (JCR 2023) | Co-author | 10.3390/fractalfract7070561 |
| 3 | Fast and optimal tuning of fractional order PID controller for AVR system based on memorizable-smoothed functional algorithm (MSFA) | Engineering Science and Technology, an International Journal, 2022, 35, 101264 | Q1 (JCR 2022) | First author | 10.1016/j.jestch.2022.101264 |
| 4 | Smoothed Functional Algorithm with Norm-limited Update Vector (NLSFA) for Identification of Continuous-time Fractional-order Hammerstein Models | IETE Journal of Research, 2024, 70(2), 1814-1832 | Q3 (JCR 2024) | First author | 10.1080/03772063.2022.2152879 |
| 5 | Model-free wind farm power production optimization using multi-resolution optimized relative step size random search | IETE Journal of Research, 2022, 68(5), 3158-3172 | Q3 (JCR 2022) | First author | 10.1080/03772063.2020.1754933 |
| 6 | Performance evaluation of smoothed functional algorithm based methods for sigmoid-PID control optimization in MIMO twin-rotor systems | Int. Conf. on Electrical, Control & Computer Engineering, 2023, 411-431 | Conference | First author | 10.1007/978-981-97-3847-2_35 |
| 7 | UMP STEM Bot as Educational Kit for Robotics and Computer Programming (authors listed: Nurul Hazlina Noordin, Mok Ren Hau [sic], Ikhwan Hafiz Mohamad; Faculty of Electrical & Electronic Engineering, UMP) | 8th International Conference on Mechatronics Engineering (ICOM 2022), 2022, pp. 1-8 (supplied by me; matches DOI 10.1049/icp.2022.2256) | Conference | Co-author, second author | 10.1049/icp.2022.2256 |
| 8 | Performance evaluation of random search based methods on model-free wind farm control | Intelligent Manufacturing & Mechatronics, Lecture Notes in Mechanical Engineering, Springer Singapore, 2018, 657-670 | Conference | First author | see CV link |
| 9 | Using spiral dynamic algorithm for maximizing power production of wind farm | International Conference on Applied System Innovation (ICASI), 2017, 1706-1709 | Conference | First author | see CV link |
| 10 | Model-free wind farm control based on random search | IEEE Intl. Conf. on Automatic Control and Intelligent Systems (I2CACIS), 2016, 131-134 | Conference | Co-author (second author per UMP record) | see CV link |

## Notes
- Earlier lists wrongly marked papers 1 and 2 as first author and left paper 4 unmarked. Corrected after checking repository records. Do not revert.
- An h-index of 9 implies more papers than the nine listed; the CV says "selected" and points to Scopus/ORCID.
- Optional extra found in UMP repository: a 2022 NCON-PGR conference abstract on simulated annealing for wind farms (first of two authors). Not on the CV.
- Contribution map used on the CV: SFA variants = papers 1, 3, 4, 6; marine predators algorithm = paper 2; random search and MR-ORSSRS = papers 5, 8, 10; spiral dynamic algorithm = paper 9; educational robotics (UMP STEM Bot) = paper 7.

- **Name spelling:** paper 7 lists me as "Mok Ren Hau" (my name is Mok Ren Hao). Check that Scopus and Google Scholar merge this variant into my profile, and consider asking the publisher for a correction. The paper's own figures show "Mok Ren Hao".
- Paper 7 acknowledges UMP grant RDU202407 (not mine). It says the kit has been used in classes with school children, teachers and undergraduate learners. That supports use of the kit, NOT that I taught undergraduates.

=================== 05_research_code.md ===================

# Research code (GitHub: https://github.com/MokRH)

## Linked from the CV
1. Metaheuristic-AVR (MATLAB): fractional-order PID tuning of an AVR system with SFA, MSFA, NLSFA, CMSFA. Accompanies paper 3 (MSFA).
2. Metaheuristic-BenchmarkFunction (MATLAB): MSFA and CMSFA compared with the Whale Optimization Algorithm on the 23 standard benchmark functions.

## Removed
- Metaheuristic-SystemID (Hammerstein identification, paper 4) is no longer available and was removed from the CV.

## Known issues to fix before relying on these links
- Both READMEs read like hand-off notes ("uploaded" files, second person). Rewrite as neutral documentation.
- AVR README says the uploaded SFA and NLSFA originals never improved the cost. Be ready to state which scripts produced the published numbers, and whether the current code reproduces them.
- AVR: SigmoidTest.m needs a Simulink model that is not included.
- BenchmarkFunction: README describes folders (algorithms/, benchmark/, results/) that do not match the flat file list; quick-start addpath lines break.
- BenchmarkFunction: MSFA/CMSFA compare absolute values, which is wrong for functions with a negative minimum (F8, F16, F19 to F23). Use J < Jbar and re-run.
- BenchmarkFunction: unequal budgets (601 evaluations vs 201 for WOA), WOA run with a single agent, bounds handled differently. No results table. Do not claim superiority over WOA until fixed (30+ runs, equal budgets, mean/SD/best/worst, Wilcoxon test).
- Both: no repository description, topics or licence confirmed.
- Profile: unpin and hide CH341-driver and HTTP-file-server (they only hold third-party executables). Pin the two research repositories.

=================== 06_experience_teaching.md ===================

# Experience, appointments and teaching (each item tied to a document)

## Industry and entrepreneurship (I am the founder, not an employee)
- **RS Technologies Empire, Pekan, Pahang. Co-founder and Design Engineer (partner), 2019 to present.** It is a registered PARTNERSHIP, not a company, so never write "shareholder". SSM old record (printed 27 May 2019): registration CA0289140-H, started and registered 27 May 2019, expiry 26 May 2021, two owners (me and one partner; I do not name my partners or describe their jobs in the CV). Registered activities in 2019: electronics supply and installation, educational electronics design, educational consultation, classes and courses on STEM, event management, IT consultation, robotic design and solution. SSM current record (printed 22 Oct 2026): registration 202403174749 (TR0305108-K), start 1 July 2024, registered 9 July 2024, expires 8 July 2029, status ACTIVE, owner: me (date of entry 1 July 2024). Gap to be ready to explain: the first registration expired 26 May 2021 and the current one starts 1 July 2024. The year 2018 is NOT documented anywhere; use 2019 (also the "STEM BOT 2019" board in paper 7). I design STEM education products from hardware to software: PCB design, assembly, Arduino library, mBlock programming. Products: five-sensor line-following robot, then an eleven-sensor version with higher speed and consistency, then sumo, battle and soccer robots. Products used in school STEM competitions including RBTX. Evidence: certificates of appreciation from schools (not yet in the pack). The UMP STEM Bot educational kit (paper 7, co-authored with Assoc. Prof. Ir. Dr. Nurul Hazlina Binti Noordin) uses my five-IR-sensor control board; the paper's figures read "Supplied by: RS Technologies" and show my name and Dr Nurul Hazlina's on the board. I do NOT have a certificate proving "won most major competitions" or "dominated RBTX", so the CV only says products were used in competitions. Sales were weak because of poor marketing, so the company earns little profit. I am still a partner (owner).
- **INCUS Solutions Sdn. Bhd. Director (research and development role), 2019 to 2025 (ceased operations 2025 for funding reasons; dissolution in progress).** SSM profile (printed 22 Oct 2026): registration 201901008538 (1317866-P), incorporated 12 March 2019, status EXISTING, nature of business R&D on engineering and technology, medical sciences and biotechnology. I am one of five directors, all appointed 12 March 2019, and hold 15 of 100 shares (15%). SSM shows "Director" only. I dropped the "CTO" title; my R&D role is shown through the work (design, development, testing, patent). The ENT surgeon (University Malaya Medical Center) is not named on the SSM record, so describe him only as a collaborator ("in collaboration with an ENT surgeon"), never as a co-founder or company officer. Work was remote during COVID-19. I designed and developed the wireless endoscopy system: Arduino-based battery management and power supply, then an ESP32-CAM camera, then a camera on a CCTV module (GOKE GK7205 SoC). Each iteration was bench-tested by me, then shipped to the ENT surgeon for user-feedback testing, until both were satisfactory. A contract manufacturer then produced small volumes.
- **Patent:** CONFIRMED by me: granted, and I am a named inventor (I could not open the Google Patents page myself). Link on CV: https://patents.google.com/patent/MY196249A/en. The wireless endoscopy system is the subject of Malaysian patent MY196249A, "Wireless Endoscope System" (Google Patents link: https://patents.google.com/patent/MY196249A/en). I could not open the record, so applicant, inventors, filing date, grant date and status are UNVERIFIED. Confirm from the record or the MyIPO certificate that I am a named inventor and that the patent is granted before relying on the word "patented". Hardware IP: it shows innovation and commercialisation, not software engineering.
- Earlier drafts wrongly described these as employment ("Embedded Engineer, part-time", "R&D Hardware Engineer, contract"). Do not use those titles. Older applications to Intel, Nexperia, QIU and SEGI used different titles and dates; the UPM version is the accurate one.
- Not on the academic CV: industrial trainee at ROHM-Wako Electronics (Malaysia), Jun to Sep 2015.
- Dropped for now: "worked with overseas manufacturers" for RS (not mentioned in the latest account). Add back only if true.

## University appointments
- Graduate Research Assistant (Skim Pembantu Penyelidik Siswazah), Universiti Malaysia Pahang, research project RDU190325, 1 April to 30 September 2021. Project leader: Puan Haszuraidah Binti Ishak (FTKEE). Letter dated 1 April 2021. This is an assistantship, NOT a research grant held by me. Project title and my tasks are not stated in the letter.
- Technical service provider, Innovation and Community Knowledge Transfer Grant (CDU240128), UMPSA, led by Assoc. Prof. Ir. Dr. Nurul Hazlina Binti Noordin. Service window 1 June to 31 August 2025; appointment two months (whichever earlier). Scope in the letter: design three robot-based unplugged-coding activities; set up the mBlock environment; program robot behaviours with code blocks; validate in a classroom or simulated classroom; prepare a robot handling guide for teachers; assist one pilot session with students; brief training and demonstration for teachers. The letter lists the scope, so state only what I actually did.

## Teaching and outreach certificates (Malay originals)
- State: Bengkel Asas Kokurikulum Pendidikan Robotik bagi Sekolah Murid Orang Asli (SMOA) Peringkat Negeri Pahang, 2 to 4 October 2024, SK (FELDA) Sungai Koyan, Kuala Lipis, with Jabatan Pendidikan Negeri Pahang and Yayasan Pahang. Certificate of appreciation for contribution and commitment.
- State: "Penggerak Robotik Pahang" certificate (STI programme, robotics co-curriculum for SMOA), signed by the Menteri Besar Pahang; no date shown.
- District: Jurulatih (trainer), Taklimat Pertandingan RBTX Challenge 2023, Daerah Pekan (Pejabat Pendidikan Daerah Pekan).
- District: Hakim (judge), Pekan RoboSTEM Challenge 2024, 16 November 2024.
- Community college: Tenaga Pengajar (instructor), Kursus Robotik, Kolej Komuniti Pekan, 16 December 2023.
- The earlier "more than 100 school students" claim was removed from the CV because no certificate states it.
- Hospital Sultan Ismail, Johor Bahru: letter of appreciation dated 14 June 2020 for contribution during COVID-19 control (addressed to me at Incus Solution Sdn Bhd). Describe it as a letter of appreciation, not "volunteer support".
- UMP Pahang National Hackathon 2019 certificate: attendance only. Not used.
- No evidence exists for university-level coaching of undergraduates, so that claim was removed.

## Referees (contact details are in the CV, not here)
1. Assoc. Prof. Ts. Dr. Mohd Ashraf Bin Ahmad, PhD supervisor, Faculty of Electrical & Electronics Engineering Technology, UMPSA.
2. Assoc. Prof. Ir. Dr. Nurul Hazlina Binti Noordin, same faculty; project leader of CDU240128.
3. Prof. Ts. Dr. Hamdan Bin Daniyal, Chief Information Officer, Center for Development and Information Technology, UMPSA.
Confirm each has agreed to be named. The ENT surgeon is not a referee (weak fit for a software engineering post).

=================== 07_cv_final_text.md ===================

# Mok Ren Hao: Academic CV (restructured, 2 pages)

*Application for Senior Lecturer (DS13), Department of Software Engineering and Information Systems, FSKTM, UPM*

Research area: Metaheuristic Computing | PhD in Electrical & Electronic Engineering | BEM Graduate Engineer (G1276385A)
Taman Rendang, 26600, Pekan, Pahang | 018-665 7950 | mokrenhao@gmail.com | Available immediately
ORCID 0000-0002-6937-0603 | Scopus ID 57193923199 | Google Scholar: RenHao Mok | GitHub: Metaheuristic-AVR, Metaheuristic-BenchmarkFunction
Scopus: 321 citations (as of October 2026), h-index 9. Google Scholar: 364 citations (as of October 2026), h-index 9, i10-index 9.

## Research profile
Researcher in metaheuristic computing and stochastic optimisation. My doctoral work developed two enhanced smoothed functional algorithms for data-driven modelling and control, benchmarked against PSO and simulated annealing. Ten selected publications, three in Q1 journals, six as first author. My problems are black-box, derivative-free optimisation tasks, the same class that search-based software engineering addresses. I am now applying this expertise to software testing, maintenance, security and AI for software engineering, and my electrical engineering background adds sensor and IoT skills (MQTT, Node-RED, Grafana, basic level). I have also co-founded two engineering businesses, in wireless medical devices and STEM robotics.

**Research interests.** Established: metaheuristic computing and stochastic optimisation; data-driven modelling and system identification; sensor interfacing and embedded systems (electrical engineering background). Developing: search-based software engineering (testing, maintenance and security); machine learning for software engineering; IoT data pipelines (MQTT, Node-RED, Grafana, basic level).

## Education
- **Doctor of Philosophy (PhD), Electrical and Electronic Engineering.** UMPSA (formerly UMP), 2019 to August 2025. Thesis: *Data-Driven Tool Using Enhanced Smoothed Functional Algorithm for Nonlinear Modeling and Advanced PID Control Problems.* Proposed NLSFA and CMSFA variants of the smoothed functional algorithm, tested against PSO and SA, with Function of Demerit improvements of up to 62.62%.
- **Master of Science (MSc), field of research: Electronic.** UMP (now UMPSA), 2016 to 2018, awarded 2019. Thesis: *Model-Free Wind Farm Power Production Optimization Using Multi-Resolution Optimized Relative Step Size Random Search* (up to 88.89% faster convergence than MR-SPSA on the 80-turbine Horns Rev wind farm).
- **B.Eng (Hons) Electrical Engineering (Electronics), Second Class (Upper).** UMP (now UMPSA), 2014 to 2016, CGPA 3.13.
- **Diploma in Electrical Engineering (Industrial Electronics), Second Class.** UMP (now UMPSA), 2011 to 2014, CGPA 3.25.

## Publications
Ten selected publications: five journal articles (three Q1, two Q3) and five conference papers; first author on six. Full list with DOIs: 04_publications.md.

## Research contributions
- **Algorithms:** smoothed functional variants for PID and fractional-order PID tuning and Hammerstein identification (papers 1, 3, 4, 6); improved marine predators algorithm (paper 2); random search variants including MR-ORSSRS (papers 5, 8, 10); spiral dynamic algorithm (paper 9).
- **Open research code (MATLAB):** github.com/MokRH/Metaheuristic-AVR, fractional-order PID tuning of an AVR system with four smoothed functional variants (paper 3); github.com/MokRH/Metaheuristic-BenchmarkFunction, MSFA and CMSFA compared with the Whale Optimization Algorithm on 23 benchmark functions.

## Proposed research direction at FSKTM
*Planned work building on the above; not completed work.*
- Search-based software testing: memory-based stochastic optimisers and metaheuristics for test case generation, minimisation and prioritisation, benchmarked against GA, PSO and SA on public benchmarks such as Defects4J.
- Software maintenance: multi-objective search-based refactoring to reduce code smells and improve maintainability.
- Security and AI for software engineering: optimiser-tuned machine learning for defect and vulnerability prediction; parameter optimisation for search-based fuzzing.

## Teaching and academic engagement
- **University, 2025 (UMPSA):** technical service provider (June 2025, two months) for the Innovation and Community Knowledge Transfer Grant CDU240128, led by Assoc. Prof. Ir. Dr. Nurul Hazlina Binti Noordin. Designed three robot-based unplugged-coding activities, programmed robot behaviours in mBlock, prepared a teacher handling guide, assisted a pilot session with students and gave teachers a brief training and demonstration.
- **School, district and community college:** contributed to Pahang's robotics co-curriculum programme for Orang Asli schools (SMOA), including a workshop on 2-4 October 2024 with Jabatan Pendidikan Negeri Pahang (recognised as Penggerak Robotik Pahang); trainer, RBTX Challenge 2023 briefing, and judge, Pekan RoboSTEM Challenge 2024 (PPD Pekan); instructor, robotics course, Kolej Komuniti Pekan (December 2023).
- **Teaching interests:** software testing and quality assurance, software maintenance, secure software development, metaheuristics, AI and optimisation, programming (Python, C/C++), embedded systems and IoT.

## Industry and entrepreneurship
**Co-founder and Design Engineer (partner)**, RS Technologies Empire, Pekan, 2019 to present
- Registered partnership (first registered May 2019; current registration July 2024), co-founded with partners to bring hands-on robotics and programming into schools and competitions through purpose-built STEM products.
- Design the products from hardware to software: PCB design, assembly, C++ (Arduino) libraries and mBlock block-based programming. Products: line-following robots (five sensors, then eleven), then sumo, battle and soccer robots, used in school competitions including RBTX (certificates of appreciation from schools); control boards supplied to UMP for the UMP STEM Bot kit (paper 7).

**Director (research and development)**, INCUS Solutions Sdn. Bhd., 2019 to 2025
- One of five founding directors; 15% shareholder. Led research and development: built a wireless endoscopy system with an ENT surgeon from University Malaya Medical Center as collaborator, because tower systems are bulky and limit remote access. Named inventor of granted Malaysian patent MY196249A (linked on the CV to https://patents.google.com/patent/MY196249A/en).
- Designed and developed the hardware (Arduino-based battery management and power supply, ESP32-CAM, then a GOKE GK7205 CCTV-module camera). Bench-tested each iteration, then the surgeon tested it for feedback; iterated until both were satisfactory, then a contract manufacturer produced small volumes.
- Worked remotely during the COVID-19 lockdown, alongside PhD research. Ceased operations in 2025 for funding reasons; dissolution in progress.

*Interests declared: director and 15% shareholder, INCUS Solutions Sdn. Bhd. (dissolution in progress); partner, RS Technologies Empire. I will follow UPM regulations.*

## Technical skills (page 2 sidebar)
Optimisation and modelling: smoothed functional algorithms, random search, PSO, SA, marine predators; PID and FOPID tuning; system identification. Programming and simulation: Python, MATLAB/Simulink, C/C++, Git/GitHub, PSpice, Multisim, LTspice. Embedded, sensing and IoT: STM32, ESP32 (incl. CAM), Arduino; sensor interfacing (ADC, I2C, UART, SPI); EasyEDA PCB design; MQTT, Node-RED, Grafana (basic).

## Research appointment (page 2 sidebar)
Graduate Research Assistant (Skim Pembantu Penyelidik Siswazah), UMP, project RDU190325, 1 April to 30 September 2021.

## Awards and IP (page 2 sidebar)
- Granted Malaysian patent MY196249A, Wireless Endoscope System (named inventor).
- Certificates of appreciation for robotics training and judging, 2023 to 2024.
- Letter of appreciation from Hospital Sultan Ismail to INCUS (June 2020).

## Referees (contacts in the CV PDF)
Assoc. Prof. Ts. Dr. Mohd Ashraf Bin Ahmad (PhD supervisor); Assoc. Prof. Ir. Dr. Nurul Hazlina Binti Noordin (project leader, CDU240128); Prof. Ts. Dr. Hamdan Bin Daniyal (Chief Information Officer, Center for Development and Information Technology, UMPSA).

=================== 08_cover_letter_final.md ===================

# Cover letter (restructured; date 22 October 2026, update on submission day)

Mok Ren Hao | Taman Rendang, 26600, Pekan, Pahang | 018-665 7950 | mokrenhao@gmail.com

22 October 2026

The Dean
Faculty of Computer Science and Information Technology (FSKTM)
Universiti Putra Malaysia
43400 UPM Serdang
Selangor Darul Ehsan

**Re: Application for Senior Lecturer (Grade DS13), Department of Software Engineering and Information Systems**

Dear Dean and Members of the Selection Committee,

I am applying for the post of Senior Lecturer (DS13) in the Department of Software Engineering and Information Systems at FSKTM. I completed my PhD in Electrical and Electronic Engineering at Universiti Malaysia Pahang Al-Sultan Abdullah (UMPSA) in August 2025, with a thesis on enhanced smoothed functional algorithms for data-driven modelling and control. My research area, metaheuristic computing, is one of the five areas in your advertisement.

I have ten selected publications, three in Q1 journals (including IEEE Transactions on Industry Applications, 2025) and six as first author. My doctoral work proposed two variants of the smoothed functional algorithm and benchmarked them against particle swarm optimisation and simulated annealing, with improvements of up to 62.62% in the Function of Demerit. I have also published on the marine predators algorithm, random search, the spiral dynamic algorithm and educational robotics. MATLAB code for several of these algorithms is available at github.com/MokRH.

The other four areas in the advertisement are software testing, software maintenance, software security and AI for software engineering. My published work is in optimisation and control, not yet in software engineering. My algorithms solve black-box, derivative-free problems, which is the problem class addressed by search-based software engineering. At FSKTM, I plan to begin with test case generation and prioritisation, benchmarked against genetic algorithm, particle swarm and simulated annealing baselines on public benchmarks. I would then extend the work to search-based refactoring and to optimiser-tuned machine learning for defect and vulnerability prediction, and supervise postgraduate students on these topics.

In 2025, I served as technical service provider for UMPSA's Innovation and Community Knowledge Transfer Grant, led by Assoc. Prof. Ir. Dr. Nurul Hazlina Binti Noordin. I designed robot-based unplugged-coding activities, prepared a handling guide for teachers and gave them a brief training and demonstration. I have also contributed to Pahang's robotics programme for Orang Asli schools, trained and judged at Pekan district robotics challenges, and taught a robotics course at Kolej Komuniti Pekan. The UMP STEM Bot paper that I co-authored describes a learning path from block-based to C++ programming, which I would apply in introductory programming courses. I can teach Python, C/C++ and MATLAB, as well as software testing, software maintenance, secure software development, artificial intelligence and optimisation. As an electrical engineer, I can also bring the sensing side of IoT into the classroom: I interface sensors (ADC, I2C, UART, SPI), design the boards, and have basic experience with MQTT, Node-RED and Grafana. I would use these to build hands-on IoT labs in which students test software against real sensor data. My formal lecturing experience is shorter than my research record, and I would welcome UPM's induction and mentoring.

Alongside my PhD, I built two small engineering ventures. In 2019, I became one of five founding directors of INCUS Solutions Sdn. Bhd., where I hold 15% of the shares and led research and development. With an ENT surgeon from University Malaya Medical Center as collaborator, I built a wireless endoscopy system, and I am a named inventor of the granted Malaysian patent MY196249A. INCUS ceased operations in 2025 for funding reasons, and its dissolution is in progress. In 2019, I also co-founded RS Technologies Empire with partners, a registered partnership in which I remain a partner, and which designs hands-on STEM robots for schools and competitions. I worked on both while completing my PhD and a graduate research assistantship at UMP in 2021, and I delivered the INCUS project and my PhD on time.

I have no employment contract, so I can take up the post immediately. I will declare my business interests and follow UPM's regulations on shareholdings, directorships and outside business interests.

I have attached my CV and supporting documents. My referees are Assoc. Prof. Ts. Dr. Mohd Ashraf Bin Ahmad, Assoc. Prof. Ir. Dr. Nurul Hazlina Binti Noordin and Prof. Ts. Dr. Hamdan Bin Daniyal, whose details are in my CV. I would welcome the opportunity to discuss how I can contribute to the department. Thank you for your time and consideration.

Sincerely,

**Mok Ren Hao**
PhD in Electrical and Electronic Engineering, UMPSA
BEM Graduate Engineer (G1276385A)

=================== 09_evidence_pack.md ===================

# Evidence pack (merged PDF, 31 pages, about 8.1 MB)

| Pages | Document |
|---|---|
| 1-2 | Cover letter |
| 3-4 | CV (clickable DOI, Code and GitHub links preserved) |
| 5-6 | PhD scroll and transcript |
| 7-9 | MSc scroll and transcript |
| 10-15 | B.Eng scroll and transcript |
| 16-19 | Diploma scroll and transcript |
| 20 | SPM 2008 |
| 21 | BEM Graduate Engineer certificate |
| 22 | State workshop certificate (SMOA, 2-4 Oct 2024) |
| 23 | Kolej Komuniti Pekan instructor certificate (prints sideways; rotate) |
| 24 | Pahang National Hackathon 2019 (attendance; optional) |
| 25 | Penggerak Robotik Pahang certificate |
| 26 | RBTX Challenge 2023 trainer certificate |
| 27 | Pekan RoboSTEM Challenge 2024 judge certificate |
| 28 | UMP Graduate Research Assistant letter (RDU190325), stipend redacted |
| 29-30 | UMPSA technical service letter (CDU240128), address, payment and bank details redacted |
| 31 | Hospital Sultan Ismail letter of appreciation |

## Redaction rules
- Redact: bank name and account number, home address on the 2025 letter, payment rates and stipends (optional), referee mobile numbers if they prefer.
- Do not redact scrolls, transcripts, SPM, BEM certificate or certificates (identity card numbers are used for verification).
- Use a true redaction tool and test the final PDF by searching for the bank name, the first digits of the account number and your street name. On page 29 a thin sliver of the first address line showed above the black box; redo that box from the original so it extends higher.
- Upload the pack only to the official portal.

## Not yet in the pack
- Certified-copy stamps on SPM, BEM certificate, certificates and letters (check UPM's rule).
- SSM company profile for INCUS (obtained 22 Oct 2026): attach pages 1, 3 and 5 of 7 only (company details, directors, shareholders). Omit pages 2, 4, 6, 7. Redact every IC number and home address (mine and everyone else's); keep names, designations and dates unless a partner objects. Add the note: "Extract of SSM company profile, pages 1, 3 and 5 of 7; other pages omitted and third-party personal data redacted."
- SSM records for RS Technologies Empire: (1) the old record printed 27 May 2019 (2 pages: business information, owners), which proves the 2019 start and the partner; (2) the current record printed 22 Oct 2026 (pages 1 and the owner page), which proves it is active to 8 July 2029. Redact every IC number, date of birth, home address, race and gender (mine and my partner's); keep names, business details and dates. Note for the pack: "Extracts of SSM business records; other pages omitted; personal data redacted." RS registrations must be renewed each period. Attach the FIRST record (2019), the LATEST record (2024) and any renewal record that bridges 26 May 2021 to 1 July 2024, using only the business-information page and the owner page of each, redacted. Do not attach every period if there are many. Add one summary table page (period, registration number, start, expiry, status) so a reviewer sees continuity at a glance. If no record covers 2021 to 2024, soften the CV dates ("registered 2019 and 2024") rather than claim unbroken registration.
- Certificates of appreciation from schools (evidence for the RS Technologies competition claims).
- First page of the UMP STEM Bot paper (paper 7) or the IET/IEEE Xplore record showing title, authors, venue and date; optionally a UMP purchase record for the boards.
- Patent evidence for MY196249A: the grant certificate or MyIPO record and the Google Patents page, showing applicant, inventors, dates and status.


See 12_supporting_documents_checklist.md for the full, current checklist.

=================== 10_rules_and_corrections.md ===================

# Rules and corrections (binding)

## Rules
1. Every claim must be supported by a document or by something I can explain at interview. If unsure, leave it out or ask me.
2. Software testing, maintenance, security and AI for SE are PLANNED work. Always label them as planned. Never write that I have done them.
3. Do not call the 2021 assistantship a research grant.
4. Be direct about weaknesses; do not oversell.
5. Keep degree titles exactly as on the scrolls and transcripts.
6. Public university, permanent post: assume employment and qualifications will be verified.

## Claims removed from earlier drafts (do not restore without documents)
- "Over 6 years of higher-education teaching", FYP and postgraduate supervision, OBE and EAC accreditation work.
- "Q1 IEEE journals" (plural). There is one IEEE Q1 paper, and I am co-author.
- "Embedded systems coaching to more than 50 undergraduates": no certificate or letter exists.
- "COVID-19 volunteer support": the document is a hospital letter of appreciation.
- "Pahang State Robotics and STEM Educator (2022-2025)" as a formal title: only the certificates in 06_experience_teaching.md exist.

## Industry roles: corrected in the latest round
- I am a founder, not an employee. INCUS: Director (R&D role), 2019 to 2025 (the "CTO" title was dropped on 22 Oct 2026; never use it), dissolution in progress. RS Technologies Empire: co-founder, partner (owner) and design engineer, 2019 to present, a registered partnership. Never write "shareholder" or "2018" for RS. The earlier titles "R&D Hardware Engineer (Contract)" and "Embedded Engineer (Part-time)" were wrong and must not be reused.
- The earlier "I joined RS part-time for financial support" story is replaced. Use only the founder story, everywhere.
- Competition claims: only "products used in school competitions, certificates of appreciation from schools". Do not write "won most major competitions" or "dominated RBTX" without certificates or results.
- Outside business: state that I will follow UPM's rules on shareholdings and outside business interests. Check the actual rule in the advert or staff regulations.

- Patent MY196249A: say "patented" only if the record shows a granted patent. Never claim inventorship the record does not show.

- Paper 7 (UMP STEM Bot): I am a co-author (second author), listed as "Mok Ren Hau". Never call it first-author. Do not use it to claim I taught undergraduates.

- INCUS per SSM: I am a Director (appointed 12 March 2019, 15% shareholder). The ENT surgeon is not on the SSM record, so do not write that I co-founded INCUS with him. Refer to him only as "an ENT surgeon from University Malaya Medical Center" and use "in collaboration with". Do not write "co-founder and led" for RS or INCUS beyond what records support.

- Latest reset (22 Oct 2026): CV and letter restructured for clarity. One title and one date per role; each fact appears once. Address and RS ownership are unresolved (see 11_todo.md). "More than 100 students" removed.
- Patent MY196249A: I state it is granted and that I am a named inventor. Keep the wording only if the record confirms both.

- RS Technologies Empire: say only "co-founded with partners". Do not mention a school teacher or name any partner.

- RS Technologies Empire: describe the co-founders only as "partners". Do not mention a school teacher or what a partner manages.

- Confirmed by me on 22 Oct 2026: RS Technologies Empire is a registered partnership (I am a partner); patent MY196249A is granted and I am a named inventor; my academic profile includes the "Mok Ren Hau" spelling; all three referees agreed to be named.

- Address rule: use only the address where I actually live (Pekan). Never list an address where I do not live, including Subang Jaya, to suggest proximity to the employer. State relocation honestly in words if needed.

- IoT skills: MQTT, Node-RED and Grafana are BASIC. Say "basic level". The selling point is the electrical engineering side (sensor interfacing, boards) that supports IoT teaching and research, not advanced IoT platform skills. Hands-on IoT labs are a plan, not a past activity.

## Corrections made
- PhD completed August 2025 (scroll and transcript), not September.
- Authorship fixed: papers 1, 2 and 9 are co-author; paper 4 is first author.
- PhD field is "Electrical and Electronic Engineering" with no "(Control Optimization)" label; MSc field is "Electronic"; B.Eng is "Electrical Engineering (Electronics)".
- Study periods follow transcripts: B.Eng 2014-2016; Diploma 2011-2014; MSc awarded 2019.
- Thesis title spelling follows the transcript ("Modeling").
- Referee list now: supervisor, project leader (Dr Nurul Hazlina), CIO (Prof. Hamdan). ENT surgeon removed.
- Teacher training wording: "gave a brief training and demonstration" (matches the 2025 letter).

=================== 11_todo.md ===================

# To-do before submission (closing 15 November 2026)

## Must do
- [x] Address settled: Taman Rendang, 26600, Pekan, Pahang on CV and letter. On the application form use Pekan as correspondence address and Kota Bharu (IC) as permanent address. Optional: add a sentence that I am willing to relocate to Selangor on appointment (only if true).
- [x] RS Technologies Empire is a registered partnership (confirmed). CV says partner.
- [x] Patent MY196249A confirmed granted, named inventor. Add the patent record or certificate to the pack as evidence.
- [ ] Redo the address redaction on page 29 so no sliver of text shows; re-export that page.
- [ ] Rotate page 23 (Kolej Komuniti certificate) so it reads upright.
- [ ] Update the cover letter date to the submission date.
- [ ] Confirm UPM's rule on certified copies; certify SPM, BEM certificate, certificates and letters if required.
- [ ] Check the portal's file-size limit (pack is about 8.1 MB).
- [x] All three referees agreed to be named.
- [ ] Confirm that every task listed for CDU240128 is something I actually did.

- [x] Patent MY196249A confirmed granted, named inventor. Add the patent record or certificate to the pack as evidence.

- [x] Academic profile includes the "Mok Ren Hau" spelling (confirmed). Paper 7 still needs its conference name, year and pages.

## Strongly recommended
- [ ] Fix the GitHub repositories (see 05_research_code.md): neutral READMEs, licence, description, results table, correct the abs() bug and equal budgets, pin the research repos, unpin executable-only repos. Confirm which scripts produced the published NLSFA results.
- [ ] Software engineering pilot: run SFA variants against GA/PSO/SA on a public test case prioritisation or minimisation benchmark, publish code and a short report, then add one line to the CV (labelled pilot study).
- [ ] Ask Puan Haszuraidah (project RDU190325) for the project title and my tasks; check whether any of my papers acknowledge RDU190325.
- [x] INCUS SSM obtained: director from 12 March 2019, 15% shareholder. CV now says Director (research and development), 2019 to 2025.
- [x] CTO dropped; INCUS role shown as Director (R&D) with the work as evidence.
- [x] RS SSM obtained (old 2019 record and current 2024 record). CV now says partner, RS Technologies Empire, 2019 to present.
- [ ] Redact both RS records (IC numbers, dates of birth, addresses, race, gender, for me and my partner) before attaching; attach old record (2 pages) and current record (business page and owner page).
- [ ] Be ready to explain the gap 26 May 2021 to 1 July 2024 (first registration expired; current one starts July 2024), or get the renewal record.
- [ ] Attach INCUS SSM pages 1, 3 and 5 only, redacted.
- [ ] Check UPM's rules on holding shares or directorships in companies; if approval is needed, plan for it.
- [ ] Collect the schools' certificates of appreciation and add them to the pack; decide whether to add any competition results.
- [ ] Keep the INCUS dissolution status accurate (in progress); update when finished.

## Nice to have
- [ ] Write a one-page research statement and teaching statement in case the portal asks.
- [ ] Add a one-page list of enclosures at the front of the pack.
- [ ] Verify all DOI links and refresh Scopus and Google Scholar numbers on the day.


## Status as of 22 October 2026
Done: letter dated 22 Oct 2026; INCUS (director from 12 Mar 2019, 15% shareholder) and RS Technologies Empire (partnership, 2019; current registration 2024) wording matches SSM; ENT surgeon referred to without a name; paper 7 added; school and certificate claims reduced to what documents show.
Still open: paper 7 conference details; redact and attach SSM extracts; pack fixes (page 29 redaction, rotate page 23, certified copies, file size); CV PDF layout check; GitHub repo fixes; referee consent; Scopus name variant; software engineering pilot.

=================== 12_supporting_documents_checklist.md ===================

# Full checklist of supporting documents (22 Oct 2026)

UPM's own list of required documents has NOT been verified. Check the advert and the eJOBS form. Other Malaysian public universities typically ask for the application form, certified copies of transcripts and certificates, and clear, complete documents; false information voids an application.

Status key: IN PACK = already in the 31-page merged PDF. ADD = missing. FIX = needs correcting.

## 1. Application basics
- Online form or portal submission (route per the advert): ADD
- Final CV and cover letter, re-exported as PDF: FIX (re-export after the latest edits; check the bottom of both CV pages and the links)
- Passport-size photo (assets/mok_ren_hao_cv_photo.jpg): ADD for the form
- Identity card copy, if the form asks: ADD

## 2. Qualifications and registration
- PhD scroll and transcript: IN PACK
- MSc scroll and transcripts: IN PACK
- B.Eng scroll and transcripts: IN PACK
- Diploma scroll and transcripts: IN PACK
- SPM certificate: IN PACK (no certified-copy stamp)
- BEM Graduate Engineer certificate G1276385A: IN PACK (no certified-copy stamp)
- Certified copies, if UPM requires them: FIX

## 3. Research evidence
- Scopus, ORCID, Google Scholar printout with metrics (October 2026): ADD
- JCR quartile proof for the 3 Q1 and 2 Q3 journals: ADD
- First pages of papers 1, 2, 3 and 7 (ICOM 2022): ADD
- Patent MY196249A, grant record showing inventors: ADD
- UMP graduate research assistant letter (RDU190325): IN PACK

## 4. Teaching and engagement
- UMPSA CDU240128 appointment letter: IN PACK, FIX (sliver of address text above the redaction box on page 29)
- SMOA workshop certificate: IN PACK
- Penggerak Robotik Pahang certificate: IN PACK
- RBTX Challenge 2023 trainer certificate: IN PACK
- Pekan RoboSTEM Challenge 2024 judge certificate: IN PACK
- Kolej Komuniti Pekan instructor certificate: IN PACK, FIX (prints sideways, rotate)
- School certificates of appreciation (RS competitions): ADD
- Hospital Sultan Ismail letter of appreciation: IN PACK
- Hackathon 2019 certificate: attendance only, optional, leave out

## 5. Business interests (disclosed)
- INCUS SSM: pages 1, 3 and 5 of 7 only, redacted: ADD (file received, unredacted)
- RS Technologies Empire SSM: 2019 record, any 2021 to 2024 renewal, 2024 record; business and owner pages only; redacted: ADD
- Summary table of SSM records: DONE (see the enclosure list document, section B)
- INCUS dissolution evidence: ADD when available
- UPM outside-business declaration form, if one exists: ADD

## 6. Referees
- All three agreed to be named (confirmed). Give their details on the form.

## 7. Final fixes before upload
- True redaction tool for bank details, IC numbers, dates of birth and addresses. Test the final PDF by searching for a few IC digits and a street name.
- Add the one-page enclosure list (done, see 12_enclosure_list.md) and fill the start pages after the final merge.
- Check the portal's file-size limit (the old pack was about 8 MB).
- Bring originals to any interview.

=================== 12_enclosure_list.md ===================

# Enclosure list and SSM summary (content of the Claude Doc "Supporting Documents - Enclosure List and Company Records Summary")

A. List of enclosures (26 items, grouped: application documents; qualifications; research evidence; teaching and engagement; business interests). Items still to add: 10, 11, 12, 13, 21, 25, 26. Fill start pages after the final merge.

B. Company records summary
- RS Technologies Empire (registered partnership, Pekan): 2019 to 2021, CA0289140-H, start 27-05-2019, expiry 26-05-2021, active when printed 27-05-2019. 2021 to 2024: renewal record to add if available. 2024 to 2029, 202403174749 (TR0305108-K), start 01-07-2024, expiry 08-07-2029, active when printed 22-10-2026. Role: co-founder and design engineer (partner), from 2019.
- INCUS Solutions Sdn. Bhd.: 201901008538 (1317866-P), incorporated 12-03-2019, status Existing on SSM (22-10-2026), ceased operations 2025 with dissolution in progress, Director appointed 12-03-2019 (R&D role), 15 of 100 ordinary shares (15%).
