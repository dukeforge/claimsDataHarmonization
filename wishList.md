### Patient demographics
* **Full name**
* **Date of birth**
* **Identifier from payor**
* Gender
 
### Inpatient visits
* *ED flag (ED only, ED to inpatient, direct inpatient admission)
* DRG
* _Admission source_
* _Place of service_
* **Location**
* **Admit date**
* **Discharge date**
* **Admitting diagnosis**
* **Discharging diagnoses**
* **Procedures performed (ICD, HCPCS, CPT, revenue codes)**
* _Modifiers for CPT codes_
* *Admitting physician
* *Discharging physician
* **Attending physician** NPI *and name
* Provider specialty
  * _Admission source_
  * _Primary diagnosis (at discharge)_
  * _Billed amount_
  * Paid amount
### Outpatient visits
* Location
* Visit provider NPI *and name
* _Provider specialty_
* Date of service
* Diagnoses
* Procedures (CPT, HCPCS, revenue codes)
* _Modifiers for CPT codes_
* _Billed amount_
* Paid amount
___
### Notes
**Bolded** are "Gotta Have". Asterisked are known to be difficult and are "Want to Have". Italicized is "Should Have".

#### Comments from the team
> I think the only thing I can think of off the top of my head that I know would be immediately useful is a way to identify if a claim is final. That’s where most of the headache is in the preprocessing, especially with the complexity of the keys that we are currently using.

> That was going to be my first wish – was a final claim. Absolutely. PartD is received as a final claim, why can’t the other files be too? Stephanie your list is great – I also would have said name, DOB for matching purposes. 3rdly the Date of ACTUAL encounter would be lovely so we know when this event occurred (think Stephanie addressed this), encounter matching with EPIC is not so straightforward because they talk in two different timeframes and we do some assuming. Better identification of type of encounter: did they go ED to Inpatient, etc. The other thing that gets really hairy is the Cross Reference file….current HICN, previous HICN. It’s a bit of a nightmare to walk and cross reference. I know we are more concerned about encounters but I think this is an area for improvement as long as we are dreaming.

#### People
* Stephanie Brinson, PHMO
* Michael Gao, DIHI
* Ursula Rogers, Forge
* Erich Huang, Forge
