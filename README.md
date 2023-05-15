# Agentes

Date: April 3, 2023
Slides: Agentes%20b1c39049057146c4bc03132a5292e4b0/Clase-2.pdf
Wk.: 2

processos dinamico 

backpropagacion

### Aprender a representar el conocimiento.

1. que es un agente
2. Estructura de un agene
3. Ejemplos de agentes en IA
4. Que significa actuar de forma racional
5. Omnisciencia, aprendizaje y autonomía (mostrar ejemplo de cada uno).
6. Propiedades y tipos de entorno/ambiente
▪ Totalmente observable, parciamente observable, agente único vs multiagente,
determinista, estocástico, episódico, secuencial, estático, dinámico, discreto
continuo.
7. Tipos de Agentes: Agentes reactivos simples, Deliberativo, híbrido, Agentes reactivos basados en
modelos, Agentes basados en objetivos, Agentes basados en utilidad, Agentes
que aprenden.

### Representacion del problema como espacio de estados

1. Resolucion del problema
2. Metodos de solucion del problema
3. Definicion del problema
4. Representacion del problema
5. Modificacion del estado

### Resolver el problema

1. Agentes que planifican con anticipacion
2. Algoritmos de busqueda
3. Busqueda no informada
4. Primero en profundida
5. Primero en Amplitud
6. Busqueda Costo Uniforme

# Learn to represent the Knowledge

**what is a Agent?**

********what are the components of the architecture of agents? define each one******** 

**what is rationality?**

**what are the components that should have a IA system?**

**An AI system can only have one type of agent?**

# 1. Agents

A agent is a human, software, hardware that act upon its environment. The goal of the agents is in its environment. 

![Untitled](Agentes%20b1c39049057146c4bc03132a5292e4b0/Untitled.png)

## 1.1 Structure of a Agent

Agent = Architecture + program 

- Architecture: is the hardware components like sensors, memory, CPU and so on.
- Program: is where the IA acts, it is the software, algorithms, code and so on that govern its behavior.

**Example of identify the agents and its environment**

![Untitled](Agentes%20b1c39049057146c4bc03132a5292e4b0/Untitled%201.png)

![Untitled](Agentes%20b1c39049057146c4bc03132a5292e4b0/Untitled%202.png)

************************Example of Agents in the real life.************************

- Chat bots
- Virtual Assistants: Siri, Cortana, Alexa and so on
- Autonomous Robots
- Fraud detection agents: Banks and financial institutions(JPMorgan Chase, Bank of America, Wells Fargo, Citibank ….) use agents to detect fraudulent activity by monitoring transactions and flagging suspicious behavior.
- Traffic control agents: Traffic control systems can use agents to manage the flow of traffic by adjusting traffic lights and routing vehicles to reduce congestion.

# 2.Rationality

According to Herbert Simon the optimal rationality is different to ideal rationality because a agent is limited of his architecture.

The optimal rationality is according that sensors, memory and so on of a agents to determined goal.  

# 3. Components of IA system

An IA system should have a combination of this concept to achieve the goals but it could have one or more of this concepts. 

- Omniscience:  the real omniscience(know all is impossible until now ), a IA system should have a gradual level of omniscience because we the humans can’t analyze a lot amount of data, we need to analyze data for find patterns, diagnostic and so on.
- Learning: an AI system learn of data and improve their task.
- Autonomy: an AI system operate without human interventional

# 4. Type of Agents

A agent can have a combination of this types or only one:

- Simple reactive agents: this agents act according only perceive of their environment(have rule for this perceives) , don’t have memory, state.
- Deliberative agents: reason about their actions and plan for the future, have a internal model of the environment  to make decision and can consider multiple course of action.
- Hybrid agents: Simple reactive agents + Deliberative agents.
- Model-based reactive agents: These agents use internal models of the environment to make decisions based on current condition. They can update their models over time as they learn more about the environment.
- Goal-based agents: These agents have a set of goals. They use internal models of the environment to plan and take actions that move them closer to their goals.
- Utility-based agents: These agents use utility or value functions to evaluate different actions and choose the one that maximizes their expected outcome.
- Learning agents: These agents have the ability to learn from their experiences and improve their decision-making over time. They can adapt to changing environments and improve their performance through trial and error.

<aside>
💡 An AI system can haven’t agents

</aside>

# 5. Problem Resolution

The goal is that a program can solve problems. We must define any type of problem according to can solve automatically.

what we need?

1. A common representation for all problems
2. Algorithms that use a strategy to solve problems defined with 1

![Untitled](Agentes%20b1c39049057146c4bc03132a5292e4b0/Untitled%203.png)

## Flash Cards

### Agents

- What is an agent?
    - A human, software or hardware that acts upon its environment.
- What are the components of the architecture of agents?
    - Architecture and program.
- What is rationality?
    - The ability to act according to the agent's goal.
- What are the components that should have an IA system?
    - Omniscience, learning, and autonomy.
- Can an AI system only have one type of agent?
    - No.
- What is a simple reactive agent?
    - An agent that acts according only to what it perceives of its environment.
- What is a hybrid agent?
    - A simple reactive agent + a deliberative agent.
- What is a goal-based agent?
    - An agent that has a set of goals.
- What is a utility-based agent?
    - An agent that uses utility or value functions to evaluate different actions and choose the one that maximizes their expected outcome.

### Problem Resolution

- What is the goal of a program?
    - To solve problems.
- What do we need to solve problems automatically?
    - A common representation for all problems and algorithms that use a strategy to solve problems.
- What is a common representation for all problems?
    - A way to define any type of problem according to be able to solve it automatically.
- What are the methods to solve problems?
    - Algorithms that use a strategy to solve problems.

## Agentes

1. What is an agent?
    - a. A human, software or hardware that acts upon its environment.
    - b. A machine learning algorithm.
    - c. A programming language.
    - d. A type of equation.
2. What are the components of the architecture of agents?
    - a. Architecture and program.
    - b. Sensors, memory, CPU.
    - c. Algorithm and software.
    - d. None of the above.
3. What is rationality?
    - a. The ability to act in the best interest of the agent.
    - b. The ability to act according to the agent's goal.
    - c. The ability to act without any limitations.
    - d. The ability to act without sensors.
4. What are the components that should have an IA system?
    - a. Omniscience, learning, and autonomy.
    - b. Architecture and program.
    - c. Sensors, memory, CPU.
    - d. Algorithms and software.
5. Can an AI system only have one type of agent?
    - a. Yes.
    - b. No.
6. What is a simple reactive agent?
    - a. An agent that acts according only to what it perceives of its environment.
    - b. An agent that has a set of goals.
    - c. An agent that learns from its experiences.
    - d. An agent that uses internal models of the environment to make decisions.
7. What is a hybrid agent?
    - a. A simple reactive agent + a deliberative agent.
    - b. An agent that acts according only to what it perceives of its environment.
    - c. An agent that has a set of goals.
    - d. An agent that learns from its experiences.
8. What is a goal-based agent?
    - a. An agent that has a set of goals.
    - b. An agent that learns from its experiences.
    - c. An agent that uses internal models of the environment to make decisions.
    - d. An agent that acts according only to what it perceives of its environment.
9. What is a utility-based agent?
    - a. An agent that uses utility or value functions to evaluate different actions and choose the one that maximizes their expected outcome.
    - b. An agent that has a set of goals.
    - c. An agent that learns from its experiences.
    - d. An agent that acts according only to what it perceives of its environment.

## Problem Resolution

1. What is the goal of a program?
    - a. To solve problems.
    - b. To create problems.
    - c. To make problems more complicated.
    - d. To ignore problems.
2. What do we need to solve problems automatically?
    - a. A common representation for all problems and algorithms that use a strategy to solve problems.
    - b. Sensors and memory.
    - c. Omniscience and learning.
    - d. Architecture and program.
3. What is a common representation for all problems?
    - a. A way to define any type of problem according to be able to solve it automatically.
    - b. A way to ignore all problems.
    - c. A way to make problems more complicated.
    - d. A way to create problems.
4. What are the methods to solve problems?
    - a. Algorithms that use a strategy to solve problems.
    - b. A way to define the problem.
    - c. A way to represent the problem.
    - d. All of the above.
