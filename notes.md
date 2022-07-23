                                                                 Component
-------



I believe that the beginning of studying react should be based on the foundation of three important parts: components, state, and props.
----

**1-Component Definition:**
---
It is a modular, portable, replaceable, and reusable set of well-defined functionalities that encapsulates its implementation and exporting it as a higher-level interface. It could be also defined as a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.
The component is also a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.
There are two types of components:
-Functional (Stateless)     -Class (Stateful).

**2-Characteristics of Component:**
----
-Reusable     -Replaceable      -No specific context       - Extensible   
-Encapsulated      -Independent


**3-Advanteges**
----
-Ease of deployment, development &Maintenance     -Low cost    
-Reusable     -Reduce complexity     -Independent




                                                                   Props

**1-Abbreviation**
---
It refers for properties. Props is the keyword used in react, it is used to pass(transfer) data between one component and another.

**2-How it is used**
---
Before rendering the props data, we should do two important steps: first, we should define attribute with its value. Then, we should pass it to the child component using props. 

**3-Flow**
---
Actually, the data with props passes in a uni-directional flow. This means that the data is passed one-way (only from parent to child).
In addition, the data in props is read-only. That means data coming from the parent will never be changed by child components.

