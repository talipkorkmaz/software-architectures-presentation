# Software Architecture Patterns

Talip Korkmaz | NETAŞ

---

### What we gonna see ?

- What is Software Architecture and why it is important ? |
- Software Architecture Patterns With Use Cases |
- Use Cases |

---

Wikipedia : 

"An architectural pattern is a general, reusable solution to a commonly occurring problem in software architecture within a given context. 
Architectural patterns are similar to software design pattern but have a broader scope"

---

### Why Software Architecture Matters ?

---

#### A basis for communication

Software architecture is a sort of plan of the system and is primordial for the understanding, the negotiation and the communication between all the stakeholders (user side, customer, management, etc.). In fact, it makes it easier to understand the whole system and therefore makes the decisions process more efficient.

---

#### The earliest decisions

The first decisions taken are at this stage. Those early decisions have a huge importance on the rest of the project and become very difficult to change the more we advance in the process  

---

#### Transferability of the model

Software architecture defines the model of the software and how it will function. Having it makes it possible to reuse this model for other softwares; code can be reused as well as the requirements. All the experience we get while doing that architecture is also transferred. This mean that we know and can reuse the consequences of the early decisions we took on the first place.

---

What is a good software architecture?
 
It’s very difficult to determine what is a good software architecture and there is no real right answer to this question. 
What we can say is that it makes products cheaper to develop and to maintain. 
In general, the facets of a good architecture are all interrelated and depend on each other. Like what?

The software architecture should be strong and easy to maintain when we find bugs
Should have domain concepts that nearly all the members will understand
It should be flexible and extendible, usable on the long term
Make it possible to adapt to requirements
Scalability, scalability & scalability: high capacity
You shouldn’t find repetition in the code
Refactoring should be easy
Should respond positively to change, when adding features, performance should not decrease

--- 

### Keypoints

- The Architecture Defines Constraints on Implementation |
- The Architecture Dictates Organizational Structure |
- The Architecture Inhibits or Enables a System's Quality Attributes |
- Predicting System Qualities by Studying the Architecture |

---

- The Architecture Makes It Easier to Reason about and Manage Change |
- The Architecture Helps in Evolutionary Prototyping |
- The Architecture Enables More Accurate Cost and Schedule Estimates |
- Architecute as a Transferable, Re-usable Model |
- Software Product Lines Share a Common Architecture |

---

- Systems Can Be Built Using Large, Externally Developed Elements |
- Less Is More: It Pays to Restrict the Vocabulary of Design Alternatives |
- An Architecture Permits Template-Based Development |
- An Architecture Can Be the Basis for Training |

---

### Common Software Architectures

- Layered pattern
- Client-server pattern
- Master-slave pattern
- Pipe-filter pattern
- Broker pattern

---

### Common Software Architectures

- Peer-to-peer pattern
- Event-bus pattern
- Model-view-controller pattern
- Blackboard pattern
- Interpreter pattern

---

![Software Architecture](https://mm-software.com/static/Software%20Architecture_en.png)

---

### Layered pattern

Each layer provide services to the next higher layer
Layers are : 

- Presentation layer (also known as UI layer) @Controller
- Application layer (also known as service layer) @Service
- Business logic layer (also known as domain layer) @Entity - DDD
- Data access layer (also known as persistence layer) @Repository

### Usage

General desktop applications.
E commerce web applications.

![Layered Pattern](https://cdn-images-1.medium.com/max/1600/1*jMWk_JqqyyloVPhTs_Zd1A.png)

---

### Client-server pattern

- Dispatcher: Manages Data Flow

---

### Master-slave pattern

- Dispatcher: Manages Data Flow

---

### Pipe-filter pattern

- Dispatcher: Manages Data Flow

---

### Broker pattern

- Dispatcher: Manages Data Flow

---

### Peer-to-peer pattern

- Dispatcher: Manages Data Flow

---

### Event-bus pattern

- Dispatcher: Manages Data Flow

---

### Model-view-controller pattern

- Dispatcher: Manages Data Flow

---

### Blackboard pattern

- Dispatcher: Manages Data Flow