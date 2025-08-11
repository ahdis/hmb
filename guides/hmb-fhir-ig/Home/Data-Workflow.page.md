## {{page-title}}

1. [Form-Based Data Collection and Exchange](#form-based-data-collection-and-exchange):    
As a first step, both data collection and data exchange for the community-facing forms and referrals are based on FHIR Questionnaires and QuestionnaireResponses.   
Terminology is represented using ValueSets.    

2. [Mapping Collected Data to FHIR Resources](#mapping-collected-data-to-fhir-resources):   
To ensure continuity of care and seamless data flow within clinical systems, an evaluation will be conducted to determine how this information can be mapped to downstream artifacts—such as ServiceRequest or components of a patient summary.

### Form-Based Data Collection and Exchange

{{render:menstrual-bleeding/workflow-q-qr}} 


### Mapping Collected Data to FHIR Resources
To support seamless data exchange within clinical systems—and enable integration into patient summaries—the data collected via FHIR Questionnaires and QuestionnaireResponses is mapped to relevant FHIR resources such as Patient, ServiceRequest, Condition, and others.

{{render:menstrual-bleeding/workflow-resources}} 
