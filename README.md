A repository for [IoT challenge](https://hackerspace.govhack.org/challenges/data_driven_iot_insights_for_sustainable_communities) organised by Telstra Dev as part of the [GovHack2020](https://hackerspace.govhack.org/)  

### Teamname : Augurs  
### Challenge: [Data Driven IoT Insights for sustainable communities](https://hackerspace.govhack.org/challenges/data_driven_iot_insights_for_sustainable_communities)   
An attempt is made to address pandemics like the COVID-19 by presaging the public well in time by leveraging IoT through continuous environmental monitoring.The challenge is expounded in three steps: context, problem definition, and solution.  
### 1.Context:-   
- TinyML edge computing and blockchain  
- Install devices in factories where chemicals are made like recent lebanon accident and check for meteorological factors like temperature of room and automatically 
  alert relevant authorities.  
- To be prepared for pandemics like corona  
    **Reference**: All the information and images below are credited to [netflix documentary](https://www.netflix.com/au/title/81273378)
  - There are about 1.5M viruses in the wild that are not known to us, and  have the potential to jump into the human realm and causing pandemics like the COVID19. Such viruses that interfere with human life to survive and thrive are called Zoonotic viruses.    
  - Since decades zoonotic viruses are causing outbreaks with no vaccines for treatement.  
    Ex: SARSCOV2002 and MERS2012 coronaviruses, that killed in 100s.   
    ![outbreak](https://github.com/nizamphoenix/govt-hack-2020/blob/master/Screenshot%20from%202020-08-16%2012-36-21.png)
  - And then there is epidemic like COVID-19 caused by the SARS-CoV-2 virus, which occured almost after a century and has killed in 1000s.
    **COVID-19** is the disease.**SARS-CoV-2** is the virus which is one among 7 coronaviruses.    
  - There are 7 types of coronaviruses known among which SARS-CoV and MERS-CoV are detrimental than HCoV  
  ![corona](https://github.com/nizamphoenix/govt-hack-2020/blob/master/Screenshot%20from%202020-08-15%2022-32-47.png)
  - Viruses like these need a host to survive like us,humans and their chance of survival increases if the host doesn't fall sick.
    For instance, the virus that caused covid-19 is often paired with bats in the news and other media because amalgamated with bats and did not bother them,however, there are debilitating effects when such a virus intrudes into the human world, and is insidious during the transmission.  
    This is exactly what happened with SARS in 2002, it emerged in an animal market in China where the meat being sold was infected when the animal made contact with a bat infected with SARS.  
    Since then [**EcoHealth Alliance**](https://www.ecohealthalliance.org/personnel/dr-peter-daszak), a scientific group is making errands to bat caves in southern china and examining bats for coronaviruses, and alert the public. The process is risky...IoT can interfere here and help in expediting.  A few years back researchers found a low-risk virus in bats called RaTG13 and later moved on since it did not impose any risk to humans, now while genome sequencing the SARS-CoV-2 they found a 96% match with the RaTG13 virus..they believe SARS-CoV-2 evolved from RaTG13.    
    *The researchers were looking for SARS family of virus and thus overlooked RaTG13.It is impossible to predict all forms of evolution of a virus.*  
 - So how did the virus evolve?
     - The virus might have mutated by jumping from bats to some other animal/reptile/fish before getting to humans.  
     The closest virus similar to  SARS-CoV-2 was in 1918 when a bird with a flu and a human with a flu met the same pig. The human virus and bird virus combined in a cell of the pig and produced **H1N1**
     
 - Organisations like the **WHO** have limited resources and work on voluntray fundings, they elicited a blueprint in 2005 harbingering a pandemic of such a scale, and again later in September 2019 a WHO report warned of an outbreak due to a respiratory pathogen but none took heed due to inadequate use of information.
 
 - Taking heed and early precautions can stop the spread by as much as 95%, which is as shown below
 ### Actual status of disease spread  
 ![Actual](https://github.com/nizamphoenix/govt-hack-2020/blob/master/Screenshot%20from%202020-08-15%2023-18-43.png)  
 ### Had the spread been contained a week ago
 ![1 week](https://github.com/nizamphoenix/govt-hack-2020/blob/master/Screenshot%20from%202020-08-15%2023-19-03.png)
 ### 2 weeks prior containment
 ![2 weeks](https://github.com/nizamphoenix/govt-hack-2020/blob/master/Screenshot%20from%202020-08-15%2023-19-09.png)
 ### 3 weeks prior containment
 ![3weeks](https://github.com/nizamphoenix/govt-hack-2020/blob/master/Screenshot%20from%202020-08-15%2023-19-17.png)
 
 
### 2.Problem definition:-  
It is strange that we live in the information age and yet the crux of the pandemic problem was **inadequate communication**. Had the information of virus spread reached out to the public on their intimate devices(smartphones), perhaps such a catastrophe could have been prevented.  
 
### 3.Solution:-  
IoT enabled sensors like the Telstra Captis for data logging can be used to monitor environments in the wild, using sophisticated devices installed in wildlife, like the bat caves, to record relevant data to pandemic research and send it forth automatically for analysis without any human intervention. Also, placing these IoT devices in regional and urban areas like the streets or shopping malls or restaurants, we can monitor public gatherings and alert each other of the situation, **Urban computing** can be leveraged which is a growing field that heavily relies on IoT. These IoT devices can also provide intelligent insights with **TinyML** like TensorFlow Lite that supports the Arduino family and is used by Telstra's IoT.  
**Blockchain** is required only to ensure data integrity, data that doesn't reflect the actual context of a situation is as good as having none, especially when it is being used to support survival.
