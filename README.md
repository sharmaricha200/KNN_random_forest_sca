# KNN_random_forest_sca

**Introduction**
Sickle cell anemia is an inherited blood disorder caused by a point mutation from glutamic acid to valine on 6th position of 
ß globin. It results in an abnormality in the oxygen-carrying protein haemoglobin (haemoglobin S) found in red blood cells. 
In sickle cell anemia, the red blood cells become rigid and are shaped like sickles. These irregularly shaped cells can get 
stuck in small blood vessels, which can slow or block blood flow and oxygen to parts of the body. Hydroxyurea, a 
myelosuppressive agent, is an effective drug proven to reduce the frequency of painful episodes by raising the level of HbF 
and the haemoglobin level. However not all patients are able to take that medication due to multiple side effects. This study 
aims to predict if a patient will respond to Hydroxyurea treatment or not based on 23 parameters in blood test, and provide a 
guideline for hospital regarding Hydroxyurea prescription.

**Dataset**
The dataset for this classification study contains 72 patients and 23 parameters. These 23 parameters are: Age, Sex, NAGG, 
N_Haplo, BAN, BEN, CAM, SEN, Weight, HbF, Hb, HbS, RBC, RDW, PCV, Retic, MCV, MCH, WBC, Polys, Plats, Bili, NRBC.  The criteria
used to determine whether certain patient will be a responder or not is 15% FHbF value. The selection of the threshold is based
on published reports that HbF has a beneficial effect at this concentration (Valafar et al. 2000)

