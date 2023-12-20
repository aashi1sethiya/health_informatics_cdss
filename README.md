# health_informatics_cdss

## Transforming Healthcare: Reducing Medical Errors With

## Clinical Decision Support Systems (****CDSS****) Utilizing A Literature Review

### Abstract

Medical errors are preventable adverse events that can occur at various stages of healthcare delivery, posing risks to patient safety and well-being. Such errors, with impact ranging from mild damage to injury or death, need a thorough knowledge of their underlying causes. The multifaceted character of medical errors highlights major underlying parameters, such as communication failures between healthcare workers and patients. Human parameters like exhaustion, burnout, and insufficient training can impair decision-making and attention, while structural concerns such as defective processes and limited access to crucial information increase the chance of errors. Equipment and technology-related issues, such as malfunctions and insufficient training, are additional sources of errors. Patient-related issues, such as lack of engagement and adherence to treatment regimens, are also crucial.

Clinical Decision Support Systems (CDSS) serve a critical role in addressing the underlying causes of medical errors, providing a holistic approach to improving patient safety. CDSS works as a centralized platform for obtaining and exchanging essential patient information, minimizing the risk of errors, and miscommunications by encouraging enhanced communication among healthcare practitioners. Regarding human aspects, CDSS assists healthcare practitioners by giving real-time, evidence-based guidance, reducing cognitive burden, and providing continuous access to up-to-date clinical knowledge. CDSS connects with electronic health record systems systematically, speeding processes and finding and correcting errors, improving healthcare delivery efficiency. In terms of equipment and technology, CDSS enables real-time monitoring, alarms, and training modules, which contribute to the reduction of errors caused by equipment faults and insufficient training. CDSS systems address patient-related issues by facilitating interaction, offering instructional materials, personalized treatment regimens, and reminders to improve adherence. Furthermore, by allowing the study of reported mistakes and near-misses, CDSS helps to build a culture of continuous learning inside healthcare organizations, supporting openness, accountability, and systemic changes.

<img width="517" alt="image" src="https://github.com/aashi1sethiya/health_informatics_cdss/assets/127284223/d18203d3-3325-4287-a649-780a86823da1">


### Introduction and Literature Review 

**Medical Errors**

Medical errors encompass diverse events with varying levels of potential patient harm (Carver et al., 2023). Broadly defined, a medical error refers to "omission or commission in planning or execution that contributes to unintended results" (Carver et al., 2023). According to the National Academy of Medicine, formally known as the Institute of Medicine (IOM), errors are described as failures in planned actions or the use of incorrect plans to achieve specific goals, marking a shift in the perception of their rarity over the past few decades (Carver et al., 2023). These errors carry substantial consequences, leading to high morbidity, mortality, and significant economic burdens, establishing them as a pressing public health concern and a serious threat to patient safety (Carver et al., 2023). For instance, in the United States, medical mistakes are estimated to result in 44,000 to 98,000 hospital deaths annually, surpassing fatalities from motor vehicle accidents and resulting in estimated costs ranging from 37.6 to 50 billion dollars due to increased healthcare expenses, disability, and lost productivity (Carver et al., 2023).

Of the possible errors that can occur, medication errors, also known as adverse drug events (ADEs), are widely acknowledged as the most common and preventable cause of patient injury, with reported incidence rates of around 6.5 per 100 admissions in acute hospitals (Carver et al., 2023; Justinia et al., 2021). Some of the most common and preventable incidents include prescribing or dispensing the wrong dosage of a medication, drug interactions, or allergic reactions. These errors can originate from various healthcare challenges such as misapplication or lack of expertise, communication challenges in healthcare professionals between themselves or with patients, inadequate supervision, and insufficient staffing leading to overworked professionals (Rodziewicz et al., 2023). 

**What is CDSS?**

A Clinical Decision Support System (CDSS) is specialized software designed to aid healthcare professionals in analyzing patient records and making informed decisions (*Clinical Decision Support System Examples, *2020). It aims to enhance healthcare by providing clinicians with specialized clinical knowledge, patient data, and health information that can be used to formulate recommendations to clinicians and thus assist them in decision-making (Sutton et al., 2020). Nowadays, CDSSs are mainly employed at the point of care, allowing clinicians to integrate their expertise with information and suggestions offered by the CDSS (Sutton et al., 2020). Utilizing Clinical Decision Support Systems (CDSS) significantly decreases the risk of medical errors, acting as both a preventive mechanism and a valuable opinion for healthcare professionals with limited training or experience, thus mitigating common medical knowledge mix-ups (*Clinical Decision Support System Examples, *2020).

 When employed to minimize medication errors, it has demonstrated improvement in clinical outcomes by reducing prescription errors and interactions (Shahmoradi et al., 2021).  

An example comes from a 2009 study of an already implemented model named HIGEA, created by the Health Research Institute of the Gregorio Marañón Hospital and discussed by Ibáñez-Garcia and their team. The meaning behind the acronym name was not provided. They evaluated the knowledge-based system that successfully prevented potential errors with 51% of alerts, with 66% of these cases requiring additional documentation due to errors in the original prescriptions (Ibáñez-Garcia et al., 2009).

Although CDSS offers numerous advantages, there exist potential challenges. Improper or inadequate implementation can limit its ability to identify medication errors or introduce new error types, putting patients at risk (*Clinical Decision Support System Examples, *2020). Pitfalls of improper implementation include missing or outdated data within the training set or knowledge base and result in inaccurate models that recommend incorrect suggestions and make frequent, unnecessary alerts (Van Dort et al., 2020,  Justinia et al., 2021). In 2021, a study investigating overrides of CDSS decisions and alerts by Justinia and their team assessed the appropriateness or reasonableness of the overrides to determine where potential errors in CDSS are. They found prevalent overrides in situations where the benefits of the medication outweighed the risks, dosages should be verified, and unverified patient allergies were present. When they delved into the causes of inappropriate overrides, it was discovered that alert fatigue was a primary cause.

Alert fatigue noted in the study is a common issue with CDSS systems where users become desensitized to alerts due to the unnecessary number of them being produced, which creates a feeling of unreliability towards the system. This distrust or insensitivity can cause users to disregard alerts without thought, causing them to miss potential accurate alerts. Justinia and the team noted an example case regarding medication dosage in a Neonatal Intensive Care Unit (NICU), which predominantly cared for premature infants. The model had solely been trained on standard care medicine, lacking any training data related to accurate dosage for premature infants. Consequently, this deficiency resulted in an under-dosage alert triggered with each dispensation, leaving nurses to ignore the system and assume their dosages were appropriate. The issue of alert fatigue was also discussed as an issue with HIGEA, with some of the causes or limitations being that some demographics were excluded due to rules or knowledge not being established for them, such as those with obesity. There also was a lack of data that could be used overall due to its inability to process natural language, meaning it could miss or wrongly alert ADEs when vital information from doctors' notes, such as diagnosis and symptoms, was not considered. The HIGEA creators combated the issue with pre-screening alerts by a pharmacist instead of the prescribing physician. This idea was backed up by a systematic review of the success of 8 models that utilized at least a clinical physician as a pre-screener, which found 5 of them to decrease redundant alerts significantly (Van Dort et al., 2020). 

