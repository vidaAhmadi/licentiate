<h3 style="text-align:center;color:#606c71;"><b>Licentiate Thesis</b></h3>
<h1 style="text-align:center;color:#606c71;"><b>Towards Secure Collaborative AI Service Chains</b></h1>

**Abstract**
<p align="justify">At present, Artificial Intelligence (AI) systems have been adopted in many different domains such as healthcare, robotics, automotive, telecommunication systems, security, and finance for integrating intelligence in their services and applications. The intelligent personal assistant such as Siri and Alexa are examples of AI systems making an impact on our daily lives. Since many AI systems are data-driven systems, they require large volumes of data for training and validation, advanced algorithms, computing power and storage in their development process. Collaboration in the AI development process(AI engineering process) will reduce cost and time for the AI applications in the market. However, collaboration introduces the concern of privacy and piracy of intellectual properties, which can be caused by the actors who collaborate in the engineering process.</p>
<p align="justify">TThis work investigates the non-functional requirements, such as privacy and security, for enabling collaboration in AI service chains. It proposes an architectural design approach for collaborative AI engineering and explores
the concept of the pipeline (service chain) for chaining AI functions. In order to enable controlled collaboration between AI artefacts in a pipeline, this work makes use of virtualisation technology to define and implement Virtual Premises (VPs), which act as protection wrappers for AI pipelines. A VP is a virtual policy enforcement point for a pipeline and requires access permission and authenticity for each element in a pipeline before the pipeline can be used. </p>
<p align="justify">Furthermore, the proposed architecture is evaluated in use-case approach that enables quick detection of design flaw during the initial stage of implementation. To evaluate the security level and compliance with security requirements, threat modeling was used to identify potential threats and vulnerabilities of the system and analyses their possible effects. The output of threat modeling was used to define countermeasure to threats related to unauthorised access and execution of AI artefacts.</p>

[Licentiate Thesis](./doc/vax-lic-thesis.pdf)  

*Date of Licentiate seminar: 10 September 2019*

**The following papers are included in this thesis**

**Paper I:** 
<p align="justify">Tutschku, K., Ahmadi Mehri, V., Carlsson, A., Chivukula, K. V., & Christensson, J. "On Resource Description Capabilities of on-board Tools for Resource Management in Cloud Networking and NFV Infrastructures". <i>In IEEE International Conference on Communication Workshops(ICC), 2016, Kuala Lumpur, Malaysia</i></p>

**Abstract**
<p align="justify">The rapid adoption of networks that are based on "cloudification" and Network Function Virtualisation (NFV) comes from the anticipated high cost savings of up to 70% in their build and operation. The high savings are founded in the use of general standard servers, instead of single-purpose hardware, and by efficiency resource sharing through virtualisation concepts.</p>
<p align="justify"> In this paper, we discuss the capabilities of resource description of "on- board" tools, i.e. using standard Linux commands, to enable OPEX savings. We put a focus on monitoring resources on small time-scales and on the variation observed on such scales. We introduce a QoE-based comparative concept that relates guest and host views on "utilisation" and "load" for the analysis of the variations. We describe the order of variations in "utilisation" and "load" by measurement and by graphical analysis of the measurements. We do these evaluations for different host operating systems and monitoring tools.</p>


[Link to paper](https://ieeexplore.ieee.org/abstract/document/7503827)

**Paper II:**
<p align="justify">Ahmadi Mehri, V., Tutschku, K. "Flexible Privacy and High Trust in the Next Generation Internet: the Use Case of Cloud-based Marketplace for AI". <i>In 13th Swedish National Computer Networking Workshop(SNCNW)</i>, 2017, Halmstad, Sweden.</p>

**Abstract**
<p align="justify"> Cloudified architectures facilitate resource access and sharing which is independent from physical locations. They permit high availability of resources at low operational costs. These advantages, however, do not come for free. End users might fear that they loose control over the location of their data and, thus, of their autonomy in deciding to whom the data is communicate to. Thus, strong privacy and trust concerns arise for end users.</p>
<p align="justify">In this work we will review and investigate privacy and trust requirements for Cloud systems in general and for a cloud-based marketplace (CMP) for AI in particular. We will investigate whether and how the current privacy and trust dimensions can be applied to Clouds and for the design of a CMP. We also propose the concept of a "virtual premise" for enabling "Privacy-by- Design" in Clouds. The idea of a "virtual premise" might probably not be a universal solution for any privacy requirement. However, we expect that it provides flexibility in designing privacy in Clouds and thus leading to higher trust. </p>


[Link to paper](http://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1128475&dswid=1073)

**Paper III:**
<p align="justify">Ahmadi Mehri, V., Ilie, D. , Tutschku, K. "Privacy and DRM Requirements for Collaborative Development of AI Application". <i>In 13th International Conference on Availability, Reliability and Security, ARES 2018: Workshop on Interdisciplinary Privacy and Trust, </i> 2018, Hamburg, Germany</p>

**Abstract**
<p align="justify"> The use of data is essential for the capabilities of Data-driven Artificial intelligence (AI), Deep Learning and Big Data analysis techniques. This data usage, however, raises intrinsically the concerns on data privacy. In addition, supporting collaborative development of AI applications across organisations has become a major need in AI system design. Digital Rights Management (DRM) is required to protect intellectual property in such collaboration. As a consequence of DRM, privacy threats and privacy- enforcing mechanisms will interact with each other.</p>
<p align="justify"> This paper describes the privacy and DRM requirements in collaborative AI system design using AI pipelines. It describes the relationships between DRM and privacy and outlines the threats against these non-functional features. Finally, the paper provides first security architecture to protect against the threats on DRM and privacy in collaborative AI design using AI pipelines.</p>

[Link to paper](https://dl.acm.org/citation.cfm?doid=3230833.3233268)


**Paper IV:**

<p align="justify"> Ahmadi Mehri, V., Ilie, D. , Tutschku, K. "Designing a Secure IoT System Architecture from a Virtual Premise for a Collaborative AI Lab". <i>In Network and Distributed System Security Symposium(NDSS): Workshop on Decentralized IoT Systems and Security(DISS)</i>, 2019, San Diego, CA, USA. </P>

**Abstract**
<p align="justify">IoT systems are increasingly composed out of flexible, programmable, virtualised, and arbitrarily chained IoT elements and services using portable code. Moreover, they might be sliced, i.e. allowing multiple logical IoT systems (network + application) to run on top of a shared physical network and compute infrastructure. However, implementing and designing particularly security mechanisms for such IoT systems is challenging since a) promising technologies are still maturing, and b) the relationships among the many requirements, technologies and components are difficult to model a-priori. </P>
<p align="justify"> The aim of the paper is to define design cues for the security architecture and mechanisms of future, virtualised, arbitrarily chained, and eventually sliced IoT systems. Hereby, our focus is laid on the authorisation and authentication of user and host, as well as on code integrity in these virtualised systems. The design cues are derived from the design and implementation of a secure virtual environment for distributed and collaborative AI system engineering using so called AI pipelines. The pipelines apply chained virtual elements and services and facilitate the slicing of the system. The virtual environment is denoted for short as the virtual premise (VP). The use-case of the VP for AI design provides insight into the complex interactions in the architecture, leading us to believe that the VP concept can be generalised to the IoT systems mentioned above. In addition, the use-case permits to derive, implement, and test solutions. This paper describes the flexible architecture of the VP and the design and implementation of access and execution control in virtual and containerised environments.</P>



[Link to paper](http://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1284028&dswid=9634)
