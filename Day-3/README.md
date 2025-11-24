# Day 3: Mastery of Object-Oriented Programming (OOP)

**Date:** November 25, 2025  
**Topic:** What is Object-Oriented Programming  
**Source:** Hyperskill - DevOps Engineer with AI Course  
**Learning Path:** Computer Science → Fundamentals → Essentials → Programming Concepts → OOP  
**Reading Time:** 7 minutes

---

## 📚 Overview

Today's focus was on understanding the fundamental concepts of Object-Oriented Programming (OOP), which forms the foundation for modern software development. OOP is essential for DevOps engineers working with Python, Java, and other modern programming languages used in automation, CI/CD pipelines, and infrastructure as code.

---

## 🎯 Key Concepts Learned

### What is OOP?

**Object-Oriented Programming (OOP)** is a programming paradigm based on the concept of **objects** that interact with each other to perform program functions.

- **Objects** are characterized by:
  - **State** (represented by **fields/attributes**)
  - **Behavior** (represented by **methods**)

### The Four Pillars of OOP

#### 1. 🔒 Encapsulation
- **Definition:** Bundling data and methods operating on that data into a single unit
- **Purpose:** Hide internal structure of properties and methods from external access
- **Benefit:** Objects act as "black boxes" - users interact only with the interface, not implementation
- **Real-world analogy:** Like a car - you use the steering wheel and pedals without knowing engine internals

#### 2. 🎨 Abstraction
- **Definition:** Providing simplified, abstract versions of implementations
- **Purpose:** Present only the most relevant features of an object
- **Benefit:** Hide complexity, show only what's necessary for the user
- **Example:** A building class shows floors, area, year - but not construction materials or electrical wiring

#### 3. 🧬 Inheritance
- **Definition:** Mechanism for defining parent-child relationships between classes
- **Purpose:** Reuse common logic while introducing unique concepts
- **Benefit:** Avoid code duplication, create hierarchies of related objects
- **Example:** Vehicle → Car, Truck, Motorcycle (all inherit common vehicle properties)

#### 4. 🔄 Polymorphism
- **Definition:** Literally means "having many forms"
- **Purpose:** Define different implementations for the same method
- **Benefit:** Same interface/name, different actions
- **Example:** A `post()` method works for News (with source), Articles (with author), and Announcements (with expiry date)

---

## 💡 Objects vs Classes

### Objects
- **Definition:** Individual instances with specific characteristics
- **Attributes:** Characterize states or data
- **Methods:** Characterize behavior
- **Real-world examples:** Specific buildings, planes, cars, computers

### Classes
- **Definition:** Templates or blueprints for similar objects
- **Purpose:** Describe common structure of similar objects
- **Relationship:** A class is a template; an object is an instance of that class
- **Encapsulation principle:** Users see only the interface (declared properties and methods), not internal implementation

---

## 📖 Practical Examples from the Lesson

### Example 1: Building Class

**Attributes:**
- Number of floors (integer)
- Area (floating-point, square meters)
- Year of construction (integer)

**Instance Examples:**
- Building 1: floors=4, area=2400.16, year=1966
- Building 2: floors=6, area=3200.54, year=2001

**Note:** Difficult to define behavior for buildings, but excellent for demonstrating attributes

### Example 2: Plane Class

**Attributes:**
- Name (string: "Airbus A320", "Boeing 777")
- Passenger capacity (integer)
- Standard speed (integer)
- Current coordinates (for navigation)

**Behavior (Methods):**
- Transfer passengers from point A to point B
- Changes state: updates current coordinates

**Key Insight:** Unlike buildings, planes have clear, definable behaviors that change their state

---

## 🔗 Connection to DevOps

Understanding OOP is crucial for DevOps engineers because:

1. **Infrastructure as Code (IaC):** Tools like Terraform and Pulumi use object-oriented concepts
2. **Python Automation:** Python is object-oriented; understanding classes is essential for writing automation scripts
3. **CI/CD Pipelines:** Jenkins pipelines, GitLab CI configurations use object-based structures
4. **Container Orchestration:** Kubernetes manifests define objects (Pods, Services, Deployments)
5. **Configuration Management:** Ansible, Puppet, Chef use object-oriented principles
6. **Cloud SDKs:** AWS SDK, Azure SDK, GCP SDK are all object-oriented

---

## 🎓 Key Takeaways

1. **OOP Paradigm:** Programs are collections of interacting objects
2. **Encapsulation is King:** Users interact with interfaces, not implementations
3. **Four Principles:** Encapsulation, Abstraction, Inheritance, Polymorphism
4. **Classes = Blueprints:** Objects = Instances
5. **Universal Concept:** OOP is implemented in C++, C#, Java, Kotlin, Python, Ruby
6. **DevOps Relevance:** Critical for automation, IaC, and modern DevOps tooling

---

## 🔗 Resources

- **Course Link:** [Hyperskill - What is OOP](https://hyperskill.org/learn/step/3614)
- **Course:** DevOps Engineer with AI: CI/CD Pipelines & Docker Skills
- **Provider:** JetBrains Academy

---

## 📝 Next Steps

- Practice implementing classes in Python
- Explore OOP concepts in infrastructure as code
- Apply OOP principles to automation scripts
- Study how Kubernetes uses object-oriented design

---

## 💭 Reflection

OOP is not just a programming concept—it's a way of thinking about problems. As an architect designs buildings from blueprints, developers create software from class templates. This paradigm shift from procedural to object-oriented thinking is essential for writing clean, maintainable, and scalable code in modern DevOps practices.

---

**Progress:** Day 3/365 ✅
**Challenge:** 365 Days of DevOps Mastery - 195 Topics with Practice Exercises
**Repository:** [DevOps Learning Journey](https://github.com/kammelaaradhan/HyperSkill-jetbrains-academy-DevOps-Engineer-with-AI-CI-CD-Pipelines-Docker-Skills)
**Repository:** [DevOps Learning Journey](https://github.com/kammelaaradhan/HyperSkill-jetbrains-academy-DevOps-Engineer-with-AI-CI-CD-Pipelines-Docker-Skills)
