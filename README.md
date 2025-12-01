# ece-465-project

This project aims to provide a series of instructional lab experiments for the ECE 465 course to employ, as a helpful 
tool and supplement to further reinforce concepts that have been explored and discussed in class.

The labs cover topics as follows:

1 - Logic Minimization
--Students will review the basics of Boolean algebra and implement the Karnaugh Map (K-map) and Quine-McCluskey (tabular) methods to minimize Boolean functions, and to realize said Boolean functions in a logic circuit.

2 - Combinational Circuits (Part One)
--Students will focus on exploring the uses of various key combinational circuit components like encoders and decoders, multiplexers (MUX), and comparators, in the context of a seaside eatery's customer console, using priority encoders to "count" payments, comparators to check payments, designing custom components to determine order availabilities, etc., all for the purpose of implementing "checks" to an order and ensuring the kitchen is "pinged" only when an order is accepted.


3 - Combinational Circuits (Part Two)
--Students will continue developing and refining understanding of combinational circuit components and their uses, in the context of a particle accelerator trigger system, which will accept inputs based on the results of the event and the user's preferences, and must return an output 1 if an event is accepted, and 0 if not.  Students must use a combination of decoders/encoders to map information of particle detection to "cases", multiplexers to decide whether the user's preferences and event detection information match, comparators to enforce momentum thresholds, etc.


4 - Timing Hazards
--Students will explore the effects that nonideal time delays on gate outputs, the nature of the “glitches” that result in the output, methods for mitigating these hazards, and how/why these methods work, revisiting the particle accelerator case study in the previous lab, Lab 3.

5 - FSM Analysis
--Students will focus on the implementation and uses of memory elements (in this case, D Flip-Flops) and combinational circuits, and the design of synchronous sequential circuits for a variety of purposes in the context of a sleepy seaside resort town.


(!) Major Note:

--The original <TimingHazards> folder can be considered archived.  The new folder for Lab 4 is <TimingHazards[New]>.
--The directories <CombinationalCircuitAnalysis> and <CombinationalCircuitDesign> are also archived.


