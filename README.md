 # AD-Risk-Contextualisation
Codelists, exposure/outcome definitions and algorithms for "A Risk Contextualization Study of Pediatric Atopic Dermatitis (AD) Patients using a Large UK Population-Based Dataset" study.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification
### Atopic Dermatitis
Atopic Dermatitis (AD) will be identified and defined using a validated AD case definition.[^1] AD case identification will use a combination of AD specific diagnosis codes and two or more AD treatment prescribed on different dates.

## Atopic Dermatitis
- People identified with a specific diagnosis code for [Atopic Dermatitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/0402c36e3628604fa4df5b0254d76b0449f1bda0/Conditions/AD%20(Atopic%20Dermatitis))

### AD treatments

- [Emollients](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Emollients)

#### Topical Steroids:
  - [Mild topical steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/9d049bfbc698dc5678acd29ce171ab26219e0279/Treatments/Mild%20Topical%20Steroids)
  - [Moderate topical steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ef02573cf3e17ed460e566567c3e265552183661/Treatments/Moderate%20Topical%20Steroids)
  - [Potent topical steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/7bca89f6071339cf1ef97990141a69662f9db3b1/Treatments/Potent%20Topical%20Steroids)
  - [Very potent topical steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/f4a35c5bba40c485c13234695477aa9107bbe6af/Treatments/Very%20Potent%20Topical%20Steroids)

- [Topical calcineurin inhibitors](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Topical%20Calcineurin%20Inhibitors)
  
- [Topical anti-infective treatments](https://github.com/MomentumData/Momentum-Data-Codelists/tree/834e32214b94f6e56133fb25bdd9696be350a083/Treatments/Topical%20Anti-Infectives)
  
#### Systemic immunosuppressant treatments:
  - [Methotrexate](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Methotrexate)
  - [Azathioprine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Azathioprine)
  - [Mycophenolate](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Mycophenolate%20Mofetil)
  - [Ciclosporin](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Ciclosporin)
  - Biologics:
    - [Dupilumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Dupilumab)

#### Phototherapy Referral
- [Phototherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Conditions/Phototherapy)

#### Dermatology Referral
Any of:
- [Specialist Dermatology Referral](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Care%20Use/Specialist%20Dermatology%20Referral)
- [Specialist Dermatology Review](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Care%20Use/Specialist%20Dermatology%20Review)

### Trial-similar AD
In addition to the criteria listed above for AD, patients with any of the following diagnosis/medication/procedure codes (made in primary care) will be excluded from the trial similar cohort:
 - [Suicidal Ideation](https://github.com/MomentumData/Momentum-Data-Codelists/tree/7b8c674fd7e4498d21127439397af9fa79a1910b/Conditions/Suicidal%20Ideation)
 - Systemic infections requiring hospitalisation
   - [Encephalitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Encephalitis)
   - [Endocarditis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Endocarditis)
   - [Gastrointestinal infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Gastrointestinal%20Infections)
   - [Infectious hepatitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Infectious%20Hepatitis)
   - [Joint infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Joint%20Infection)
   - [Mentingitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Meningitis)
   - [Bone infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Osteomyelitis%20(Bone%20Infections))
   - [Respiratory infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Respiratory%20Infections)
   - [Sepsis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Sepsis)
   - [Skin infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Skin%20Infections)
 - [Disseminated herpes simplex or zoster:](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/Disseminated%20Herpes%20Simplex%20or%20Zoster)
   - Herpetic septicemia
   - Visceral herpes simplex
   - Herpes viral hepatitis
   - Herpesvirus encephalitis
   - Disseminated herpes viral disease
 - [Humman Immunodeficiency Virus (HIV)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/HIV%20(Humman%20Immunodeficiency%20Virus))
 - [Hepatitis B](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/Hepatitis%20B)
 - [Hepatitis C](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/Hepatitis%20C) 
 - [Psoriasis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Psoriasis)
 - [Seborrheic Dermatitis]()
 - [Systemic lupus erythematosus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Systemic%20lupus%20erythematosus)
 - [Skeletal Dysplasia]()
 - [Retinal Detachment]()
 - [Thrombocytopenia]()
 - [Coagulopathy]()
 - [Platelet Dysfunction]()
 - Malignancies:
   - [Leukemia]()
   - [Lymphoma]()
   - [Sarcoma]()
   - [Solid cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Solid%20Cancer)
   - [Haematological cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Haematological%20Cancer)
  - Immunodeficiency disorders:
   - [Severe Combined Immunodeficiency (SCID)]()
   - [ommon Variable Immunodeficiency (CVID)]()
   - [Hyper-IgM syndromes]()
   - [Wiskott–Aldrich syndrome]()
   - [DiGeorge syndrome with immune dysfunction]()
   - [Chronic Granulomatous Disease (CGD)]()
   - [Severe congenital T- or B-cell defects]()
 - [Systemic JAK inhibitor](https://github.com/MomentumData/Momentum-Data-Codelists/tree/63b7a8c005c19d2fd174ac3be07b0de275b78187/Treatments/JAK-Inhibitors)

### Outcomes
People identified with the respective diagnosis codes recorded in primary or secondary care as for each of the outcomes below:
 - [Hyperlipidaemia]()
 - Serious infections:
   - [Encephalitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Encephalitis)
   - [Endocarditis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Endocarditis)
   - [Gastrointestinal infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Gastrointestinal%20Infections)
   - [Infectious hepatitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Infectious%20Hepatitis)
   - [Joint infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Joint%20Infection)
   - [Mentingitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Meningitis)
   - [Bone infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Osteomyelitis%20(Bone%20Infections))
   - [Respiratory infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Respiratory%20Infections)
   - [Sepsis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Sepsis)
   - [Skin infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Skin%20Infections)
 - [Opportunistic infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Opportunistic%20Infections)
 - [Tuberculosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d375622de34a9ad1cf6aed30e1a88bfb3814fd24/Conditions/Tuberculosis)
 - [Herpes zoster](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Herpes%20Zoster)
 - [Herpes simplex](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Herpes%20Simplex)
 - [Conjuctivitis]()
 - [Eczema Herpeticum]()
 - Malignancy (excluding non-melanoma skin cancer (NMSC)):
    - [Solid cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Solid%20Cancer)
    - [Haematological cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Haematological%20Cancer)
 - [Leukemia]()
 - [Lymphoma]()
 - NMSC:
   - [Basal Cell Carcinoma (BCC)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/BCC%20(Basal%20Cell%20Carcinoma))
   - [Squamous Cell Carcinoma (SCC)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Squamous%20Cell%20Carcinoma)
 - Major Adverse Cardiovascular Event (MACE):
   - [Acute myocardial infarction](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/MI%20(Myocardial%20Infarction))
   - [Unstable angina](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Unstable%20Angina)
   - [Coronary vrevascularisation by PCI or CABG](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Revascularisation%20Procedures)
   - [Ischaemic stroke](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Ischaemic%20Stroke)
   - [Haemorrhagic stroke](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Hemorrahagic%20Stroke)
 - Venous thromboembolism:
   - [Deep vein thrombosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/DVT%20(Deep%20Vein%20Thrombosis))
   - [Pulmonary embolism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/PE%20(Pulmonary%20Embolism))
 - Anxiety:
   - People identified with a diagnosis code for [anxiety episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Anxiety%20Episode) **AND** within 6 months any coded anxiety treatment* in primary care.
   - *List of Anxiety treatments:
     - [Selective Seratonin Reuptake Inhibitors (SSRIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/SSRIs%20(Selective%20Serotonin%20Reuptake%20Inhibitors))
     - [Tricyclic Antidepressants (TCAs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/TCAs%20(Tricyclic%20Antidepressants))
     - [Monoamine Oxidase Inhibitors (MAOIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/MAOIs%20(Monoamine%20Oxidase%20Inhibitors))
     - [Counselling](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Counselling)
     - [Psychotherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Psychotherapy)
     - [Cognitive Behavioural Therapy (CBT)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/CBT%20(Cognitive%20Behaviour%20Therapy))
 - Depression:
   - People identified with a diagnosis code for [recurrent depressive disorder](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/RDD%20(Recurrent%20Depressive%20Disorder)) in primary care.
   - People identified with a diagnosis code for [depressive episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Depressive%20Episodes) **AND** any coded depression treatment** after 365 days in primary care.
   - **List of Depression treatments:
     - [Selective Seratonin Reuptake Inhibitors (SSRIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/SSRIs%20(Selective%20Serotonin%20Reuptake%20Inhibitors))
     - [Tricyclic Antidepressants (TCAs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/TCAs%20(Tricyclic%20Antidepressants))
     - [Monoamine Oxidase Inhibitors (MAOIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/MAOIs%20(Monoamine%20Oxidase%20Inhibitors))
     - [Counselling](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Counselling)
     - [Psychotherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Psychotherapy)
     - [Cognitive Behavioural Therapy (CBT)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/CBT%20(Cognitive%20Behaviour%20Therapy))
 - [Asthma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Conditions/Asthma)
 - [Acne]()
 - [Nausea]()
 - [Vomiting]()
 - [Abdominal Pain Upper]()
 - [Thrombocytopenia]()
 - [Lymphopenia]()
 - [Hyperlipidaemia]()
 - [Neutropenia]()
 - [Fracture/Bone Events]()
 - [Retinal Detachment]()


[^1]: Abuabara, Katrina et al. “Development and Validation of an Algorithm to Accurately Identify Atopic Eczema Patients in Primary Care Electronic Health Records from the UK.” The Journal of investigative dermatology vol. 137,8 (2017): 1655-1662. doi:10.1016/j.jid.2017.03.029
