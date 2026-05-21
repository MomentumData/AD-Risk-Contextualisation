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



[^1]: Abuabara, Katrina et al. “Development and Validation of an Algorithm to Accurately Identify Atopic Eczema Patients in Primary Care Electronic Health Records from the UK.” The Journal of investigative dermatology vol. 137,8 (2017): 1655-1662. doi:10.1016/j.jid.2017.03.029
