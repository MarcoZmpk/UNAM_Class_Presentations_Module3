![Logo](http://arquitectura.unam.mx/uploads/8/1/1/0/8110907/_2634437.png?131)
## Universidad Nacional Autónoma de México
### Facultad de Ingeniería
#### Técnicas de Programación - Ingeniería Mecatrónica

---
### Temario

- @color[gray](Importancia del software en la mecatrónica) |
- @color[gray](Metodología de la programación orientada a objetos) |
- Desarrollo de sistemas de cómputo orientados a objetos |
- Concepto, uso y aplicaciones de las estructuras de datos compuestas |
- Interfaces gráficas de usuario |
--- 

### Desarrollo de sistemas de cómputo orientados a objetos

Objetivo: El alumno desarrollará programas y sistemas de cómputo mediante el paradigma orientado a objetos.
---
Contenido: 
- 3.1  Análisis y definición de los requerimientos del usuario y del sistema |
- 3.2  Diseño y modelado de sistemas, utilizando el Lenguaje de Modelado Unificado (UML) |
- 3.3  Desarrollo de los subsistemas |
- 3.4  Integración del sistema |
- 3.5  Verificación, validación y pruebas del software |
- 3.6  Mantenimiento del software (depuración, actualización, evolución)|
---
#### Análisis y definición de los requerimientos del usuario y del sistema

Traditional Software Phases

- Requirements Engineering |
- Design |
- Implementation |
- Maintenance |
- Verification and Validation |

---
##### Software Process Model

![Software Process Model](https://i.ytimg.com/vi/laSrDtYtkXU/maxresdefault.jpg)

---
###### Waterfall

![Waterfall](https://xbsoftware.com/wp-content/uploads/2014/10/software-development-life-cycle.png)

* @color[green](OK) Find errors early |
* @color[red](NOK) Not Flexible |
---
###### Spiral

![Spiral](https://i.stack.imgur.com/7VrIo.jpg)

---
###### Spiral

* @color[green](OK) Risk reduction |
* @color[green](OK) Functionality can be added |
* @color[green](OK) Software produced early |

* @color[red](NOK) Specific Expertise |
* @color[red](NOK) Highly dependent on risk analysis |
* @color[red](NOK) Complex and costly to implement |
---
###### Evolutionary Prototyping
![Evolutionary Prototyping](http://1.bp.blogspot.com/U8_T_U3y_AM7YhjqxiabX7ag0W8ES5ZYMiWbO1dfbfc=w451-h237-no)

* @color[green](OK) Inmediate feedback |

* @color[red](NOK) Difficult to plan |
* @color[red](NOK) Not a high quality product |
---
###### Agile Methodology

![Agile Methodology](https://www.360logica.com/blog/wp-content/uploads/2016/07/AGILE-Graphic01.jpg)

---
###### Choosing a software process model

![Choosing a software process model](https://i.ytimg.com/vi/F5fuUs7oJu0/maxresdefault.jpg)

---
##### Requirements Engineering

![Cost of late correction](https://image.slidesharecdn.com/poorbusinessanalysis-v-2-140110041144-phpapp02/95/poor-business-analysis-the-culprit-of-it-project-failure-23-638.jpg?cb=1389327319)

---
##### [Requirements Engineering](https://en.wikipedia.org/wiki/Requirements_engineering)

- Requirements Elicitation |
- Requirements Analysis |
- System modeling |
- Requirements Specification |
- Requirements Validation |
- Requirements Managements |

---
#### [Diseño y modelado de sistemas, utilizando el Lenguaje de Modelado Unificado (UML)](http://www.uml.org/what-is-uml.htm)

Large enterprise applications - the ones that execute core business applications, and keep a company going - must be more than just a bunch of code modules. They must be structured in a way that enables scalability, security, and robust execution under stressful conditions, and their structure - frequently referred to as their architecture - must be defined clearly enough that maintenance programmers can (quickly!) find and fix a bug that shows up long after the original authors have moved on to other projects.

---
##### UML - Unified Modeling Language

UML is a modern approach to modeling and documenting software. In fact, it’s one of the most popular business process modeling techniques.

---
##### [UML - Architecture](https://www.tutorialspoint.com/uml/uml_architecture.htm)

Any real-world system is used by different users. The users can be developers, testers, business people, analysts, and many more. Hence, before designing a system, the architecture is made with different perspectives in mind. The most important part is to visualize the system from the perspective of different viewers. The better we understand the better we can build the system.
---
##### [UML - Structural Modeling](https://www.tutorialspoint.com/uml/uml_modeling_types.htm)

Structural modeling captures the static features of a system. They consist of the following −

* Classes diagrams
* Deployment diagrams
* Package diagrams
* Composite structure diagram
* Component diagram
---
##### [UML - Behavioral Modeling](https://www.tutorialspoint.com/uml/uml_modeling_types.htm)

Behavioral model describes the interaction in the system. It represents the interaction among the structural diagrams. Behavioral modeling shows the dynamic nature of the system. They consist of the following −

* Activity diagrams
* Interaction diagrams
* Use case diagrams

---
##### [UML - Architectural Modeling](https://www.tutorialspoint.com/uml/uml_modeling_types.htm)

Architectural model represents the overall framework of the system. It contains both structural and behavioral elements of the system. Architectural model can be defined as the blueprint of the entire system. Package diagram comes under architectural modeling.

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

Class Notation

![Class Notation](https://www.tutorialspoint.com/uml/images/notation_class.jpg)

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

Object Notation

![Object Notation](https://www.tutorialspoint.com/uml/images/notation_object.jpg)

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

Use Case Notation

![Use Case Notation](https://www.tutorialspoint.com/uml/images/notation_usecase.jpg)

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

Actor Notation

![Actor Notation](https://www.tutorialspoint.com/uml/images/notation_actor.jpg)

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

Interaction Notation

![Interaction Notation](https://www.tutorialspoint.com/uml/images/notation_interaction.jpg)

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

State Machine Notation

![State Machine Notation](https://www.tutorialspoint.com/uml/images/notation_statemachine.jpg)

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

Dependency Notation

![Dependency Notation](https://www.tutorialspoint.com/uml/images/notation_dependency.jpg)

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

Association Notation

![Association Notation](https://www.tutorialspoint.com/uml/images/notation_association.jpg)

---
##### [UML - Basic Notations](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

Generalization Notation

![Generalization Notation](https://www.tutorialspoint.com/uml/images/notation_generalization.jpg)

---
##### [UML - Diagram Examples]

[Class Diagram](https://www.tutorialspoint.com/uml/uml_class_diagram.htm)
[Object Diagram](https://www.tutorialspoint.com/uml/uml_object_diagram.htm)
[Component Diagram](https://www.tutorialspoint.com/uml/uml_component_diagram.htm)
[Deployment Diagram](https://www.tutorialspoint.com/uml/uml_deployment_diagram.htm)
[Use Case Diagram](https://www.tutorialspoint.com/uml/uml_use_case_diagram.htm)
[Interaction Diagram](https://www.tutorialspoint.com/uml/uml_interaction_diagram.htm)
[State Chart Diagram](https://www.tutorialspoint.com/uml/uml_statechart_diagram.htm)
[Activity Diagram](https://www.tutorialspoint.com/uml/uml_activity_diagram.htm)

---
### Questions?

<br>

@fa[envelope gp-contact](zmpk.fi@gmail.com)

@fa[github gp-contact](MarcoZmpk)
---

### 4. Concepto, uso y aplicaciones de las estructuras de datos compuestas

<br>

#### Objetivo:
#### 

---

### 5. Interfaces gráficas de usuario

https://uxdesign.cc/design-better-forms-96fadca0f49c


#### Objetivo:
#### 
---


### Questions?

<br>

@fa[envelope gp-contact](zmpk.fi@gmail.com)

@fa[github gp-contact](MarcoZmpk)

---
#### Referencias
---
