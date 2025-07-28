## {{page-title}}

The following use case illustrates a **possible care scenario** demonstrating how FHIR artefacts—such as Questionnaire, ValueSet, and ServiceRequest—can be used to support forms for self-assessment and structured clinical referrals in the context of Heavy Menstrual Bleeding (HMB).

This example is intended for **illustrative purposes only**.   
All names, characters, and clinical details are fictional. While clinically informed, the scenario may not reflect every aspect of real-world practices or guidelines.

### Flo's Journey: How It All Began
Flo always assumed that her heavy periods were just "how her body works." For years, she organized her life around them—avoiding travel, social events, and even work meetings during her cycle. She often experienced fatigue, occasional dizziness, and needed to change protection every 1–2 hours on heavy days. Since her mother and sister reported similar experiences, she never thought it might be a medical issue.

During a routine check-up at her GP practice, Flo was invited to fill out a **community-facing digital questionnaire** as part of a new women’s health initiative. The questions were simple and respectful, asking about bleeding patterns, impact on daily life, and overall wellbeing. For the first time, Flo began to realize that what she had considered “normal” might actually be a treatable condition.

Later, her GP, Dr. Emma Clark, reviewed the responses with her. Based on the structured input, Dr. Clark explained that Flo’s symptoms aligned with Heavy Menstrual Bleeding (HMB)—a clinical issue that can and should be addressed. Flo was both surprised and relieved. She received information about HMB, treatment options, and what to expect next.

Dr. Clark gathered the information from Flo’s self-assessment questionnaire and added the findings from the clinical evaluation. Recognizing the significant impact of Flo’s symptoms, she completed a **structured digital referral**, combining the self-reported data with key clinical details from the GP visit. Flo was then referred to a specialist at the Medical Center for Women, ensuring that all necessary context—both personal and clinical—was available upfront for a smooth transition into specialist care.

This helped streamline the process, reduce delays, and spared Flo the emotional burden of repeating her story. It marked the start of a more informed and supported care journey—one that acknowledged Flo’s symptoms as valid and treatable, offering her a clear path toward relief and better quality of life.

_For details on the {{pagelink:Data-Workflow}}, please refer to the corresponding section of this implementation guide._


### Flo's First Consult with the Specialist

#### History
- 46yo female, referred by GP for heavy menstrual bleeding
- Anaemic, low iron a year ago
- Perimenopausal symptoms: brain fog, fatigue, weight gain, dry skin, vaginal dryness
- Interested in HRT
- Sexually active with male partner
- Completed family, doesn't want more children

#### Menstrual History
- Menarche age 12
- Previously normal bleeding until second child (now 8yo)
- Dysmenorrhoea first 2 days
- Investigated for endometriosis in 20s - negative

#### Obstetric History
- G2P2
- Both vaginal deliveries at term

#### Gynaecologic History
- Previous Mirena IUD in 20s for contraception, removed for fertility

#### FIGO AUB Parameters
Frequency: Frequent (>20 days)   
Duration: Prolonged (9 days)    
Regularity: Varies by over 1 week    
Flow Volume: Heavy with clots     
Intermenstrual Bleeding (IMB): None

#### General Examination
- Anxious, mildly pale
- Abdomen soft, non-tender
- Cervical examination normal on speculum
- Normal vaginal discharge
- Bulky, mobile uterus
- Adenomyosis
- Bimanual examination, no areas of tenderness
- No adnexal masses palpable
- Small cystocoele
- TA Ultrasound suggestive of small polyp

#### Investigations to Order
- High quality pelvic ultrasound (transvaginal) Day 5-10 of menstrual cycle, to be arranged to check for any underlying pathology including polyps and fibroids
- Urine bHCG (if pregnancy cannot be excluded,  FBC, iron studies to rule out iron deficiency and/anaemia, 
Order other investigations based on the clinical picture, as needed: thyroid studies, PCOS or Bleeding disorders etc, 
STI screen if clinically indicated

#### Assessment
- Heavy menstrual bleeding, perimenopausal

#### Plan
1. Tranexamic acid - script provided
2. Encouraged to use mefenamic acid during next cycle
3. Discuss all management options and encourage shared decision making. Provide patient information and this patient opted for the following plan: Consent for endometrial ablation and polypectomy, hysteroscopy, endometrial biopsy +/- Mirena IUD insertion if unsuitable for ablation
4. Aim to Identify  uterine abnormalities via pelvic ultrasound
5. Repeat blood tests to get more information about her current baseline, this will help us recommend iron supplementation (oral or IV) if iron deficiency and or anaemia is identified, she is also offered bleeding disorder testing as she has a long standing personal history of HMB as well as a family history of same.

Information provided on HMB, Mirena IUD, HRT, tranexamic acid, ablation, recovery, and hysteroscopy

#### Follow-Up Plan
- Review after investigations


*** 
_Note: The specialist use case data was generated in Heidi AI using [WHR](https://www.womenshealthroad.com.au/)’s HMB consult templates, and the GP use case was developed with the support of ChatGPT._
