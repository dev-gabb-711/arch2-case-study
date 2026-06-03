# Case Study Project 2 Proposal
## CSARCH2 - S06
### Group 6

### Members
- Caindoy, Thistle
- Infante, Gabriel
- Martinez, Gabrielle
- Melanio, Marion
- Omandac, Karl

### Topic Theme
How does RAM work?

Needed
- Group’s title
- Group’s tech stack plan
  - Proposed interactive element. Minimum of 1 interactive element. Make it as detailed as possible so we can evaluate the compatibility to the central website.
  - Mobile-responsive layout if possible
  - Tentative style guide snapshot – proposed virtual exhibit design layout




--------------- Scratch 1 --------------

- Topic: How RAM Works
- Title: Inside RAM - Computer Memory in Motion
- Focus: How RAM retrieves data when the CPU requests it.
- Main Learning Goal: How does RAM find and retrieve data so quickly?


### Section 1: What is RAM?
**Overview Implementation**: The information should contain what RAM is, why it is important in doing computer processes, and slight discussion of how it stores memory and why they are stored there rather than storing it into hdd/sdd instead. You can also have example memory maps of variables like in LBYARCH to see how they are represented and accessed.

**Outline**:
- Hook
  - A starting toe tickling info that would introduce us to the topic
- What is ram?
  - A general explanation of what RAM is and its functions
- Memory
  - A general explanation of what Memory is, its use, and how it communicates with the CPU, which transitions to Von Neumann Architecture
- Von Neumann Architecture
  - A brief version of Section 2, where mainly the interaction of the Memory and the CPU through busses is discussed
- RAM vs ROM
  - A brief comparison of the usage, data handling, and memory size of RAM and ROM

- Hook (Di ko alam basta something na makakakuha ng curiosity nila, could be interactive)
- Explain RAM
- Why does a computer need RAM?
- Why not use storage “directly”?
- Why is it called “memory”?
- Pwede tayo lagay visual examples dito alongside the paragraphs (para pretty pretty na medyo cool ganern)

### Section 2: Inside the RAM - The Internal Data Journey
**Info**: A deep-dive simulation tracking a data stream through a detailed physical diagram of a RAM module. It explains how internal hardware components interact to process requests, combining the step-by-step application flow with immediate hardware definitions and function explanations.

**Implementation**: This section features a high-fidelity, interactive circuit diagram of a RAM stick. Upon loading, an animated data stream (representing an app request) enters the module. The camera dynamically pans and zooms, following the stream as it physically travels through every internal component. As the data "visits" each component, that part highlights, and a modal displays its definition, technical function, and role in the current operation (Reading or Writing). Once the journey is complete, the diagram enters a free-roam state where users can re-click components, and a prominent button appears linking to the next section.

- Unified Narrative: The "App Opening" process is told through the journey of data physically moving within the RAM's architecture.
- The Guided Tour (Data Stream Path):
  - Entry Point (Connection Pins/Gold Contacts): The data stream enters. Pop-up defines the interface between the motherboard and the RAM module.
  - The Brain (SPD Chip & Register/Buffer): The stream hits these first. Explains how the SPD tells the system how to talk to the RAM, and how Control Logic manages the incoming commands.
  - The Routing (Row & Column Decoders): The stream splits into address signals. Pop-up explains how these components translate abstract memory addresses into physical coordinates on the matrix.
  - The Destination (The Memory Array - Banks, Rows, Columns): The stream arrives at the core grid. Explains the hierarchy of how data is stored in massive arrays.
  - The Storage Cell (Transistor & Capacitor): Final zoom-in to the microscopic level. Explains the fundamental dynamic RAM cell, volatility, and the need for electrical refresh cycles.
  - The Retrieval (Sense Amplifiers): (If simulating a "Read" operation) Shows data leaving the cell, being amplified from a tiny charge to a readable 1 or 0.
- After this section, the user is allowed to freely click on the components in the full view of the RAM diagram and details about each component will be shown as well.
- The flow of data will also be continuous throughout the RAM diagram

Section 4: Challenge Quiz
- Last interactive part where we test if they really did understand our lesson
- Good way to see if our delivery was effective
- Reinforce their learning (if they had any…)

Section 5: Conclusion or Wrap Up
- We can add this or not
- We’ll add this if the end of the website look barren or sum

-----------------------------------------------------------------