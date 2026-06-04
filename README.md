# Case Study Project 2 Proposal
## CSARCH2 - S04
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
**Overview Implementation**: This introductory section aims to establish the foundational concepts necessary for understanding the inner workings of RAM. Visitors will be introduced to the purpose of computer memory, the role RAM plays in system performance, and how it interacts with the CPU during normal computer operations. Through visual aids, examples, and simplified diagrams, this section will provide the background knowledge needed to understand the more technical concepts presented in later sections.

**Outline**:
- Hook
  - This starting section will explore interesting application uses of RAM through a brief discussion of how a Gen 1 Pokemon Save file is stored. It also discusses how it operates together with the game ROM in the cartrage and explains what happens if the battery inside it dies.
  - This exhibit will explore the architectural principles of volatile memory by analyzing how a game save file is maintained inside a retro cartridge, specifically using a Generation 1 Pokémon game as a case study. Instead of introducing RAM through dry, textbook definitions, the exhibit hooks the audience with a familiar scenario: how a player's digital progress (in-game coordinates, team data, inventory) is actively held in a specialized type of RAM, and the technical breakdown of why that memory completely vanishes when its power source is compromiseThe discussion also establishes an early distinction between RAM and ROM, which will be explored further later in the section.
- What is ram?
  - This subsection provides a general explanation of Random Access Memory (RAM) and its role as the computer's primary working memory. The discussion will focus on RAM as a temporary storage location for data and instructions that are actively being used by the CPU.
  - Key concepts we can include:
    - RAM as a high-speed working area for currently active programs and data.
    - The meaning of "random access" and how any memory location can be accessed directly.
    - Volatility and why RAM contents disappear when power is removed.
    - The relationship between RAM capacity and the number of applications that can be actively used at the same time.
  - Simple real-world analogies may be used to help visitors understand why RAM functions as a temporary workspace rather than a permanent storage location.
- Memory
  - This subsection broadens the discussion to computer memory as a whole. Visitors will learn how information is represented, stored, and accessed within a computer system.
  - A general explanation of what Memory is, its use, and how it communicates with the CPU, which transitions to Von Neumann Architecture
  - Topics we can include:
    - What memory is and why computers require it.
    - How data and instructions are stored as binary values.
    - The concept of memory addresses and how the CPU locates information.
    - Simple memory maps inspired by LBYARCH activities showing how variables are assigned memory locations.
    - Examples demonstrating how a variable's value can be retrieved by referencing its address.
  - The goal is to bridge the gap between programming concepts and physical computer hardware while preparing visitors for the discussion of memory access in later sections.
- Von Neumann Architecture
  - A brief version of Section 2, where mainly the interaction of the Memory and the CPU through busses is discussed.
  - This subsection introduces the role of memory within the broader computer architecture. Rather than providing a complete architectural deep dive, the focus will be on how the CPU communicates with memory.
  - We can include diagrams siguro (?) of these:
    - CPU as the processor of instructions.
    - Memory as the storage location for programs and data.
    - Address buses used to specify memory locations.
    - Data buses used to transfer information.
    - Control signals used to coordinate memory operations.
- RAM vs ROM
  - A brief comparison of the usage, data handling, and memory size of RAM and ROM.
  - We can include:
    - Purpose and function of RAM and ROM.
    - Volatile versus non-volatile storage.
    - Typical capacities and applications.
    - Examples of data commonly stored in each memory type.
    - Why both forms of memory are required for a functioning computer system.
  - A comparison table or visual diagram may be included to help visitors quickly identify the strengths and limitations of each memory technology.

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

### Section 3: Challenge Quiz
**Implementation**: This section will reinforce the viewer's learning by asking questions about the information presented in the previous sections. The question may be one of these types: Multiple Choice, Fill in the Blank and True or False. The question and answer will be stored in the server side to avoid bloating the client side and to avoid getting the answers via inspect element.


(LOWK WE MIGHT NOT NEED THIS)
Section 5: Conclusion or Wrap Up
- We can add this or not
- We’ll add this if the end of the website look barren or sum

-----------------------------------------------------------------
