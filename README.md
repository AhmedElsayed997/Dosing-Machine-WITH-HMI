# Dosing-Machine-WITH-HMI

## Dosing and Mixing Automation Project
This project simulates a dosing and mixing system involving multiple feeders, silos, conveyors, and a central mixer. It is designed to automate the precise delivery and mixing of materials for downstream packaging.

## System Components:
	•	Feed Elevator 1 & 2 – Transfers raw materials to their respective silos.
	•	Dosing Silo 1 & 2 – Stores and doses predefined amounts of materials.
	•	Spiral Conveyor 1 & 2 – Transports dosed materials to the mixer.
	•	Mixer – Combines materials from both silos to achieve a homogeneous mixture.
	•	Mixer Gate – Controls material discharge to the packaging section.
	•	Packaging Unit – Final destination where the processed material is collected.

## Technologies Used:
	•	PLC Programming Language: Ladder Diagram (LD)
	•	Software Used: CODESYS
	•	HMI: Simple visual interface for status monitoring and manual overrides

## Functional Description:
	1.	Raw material is lifted via elevators into dosing silos.
	2.	Each silo doses material into its respective spiral conveyor based on predefined timing/conditions.
	3.	Conveyors feed the mixer.
	4.	The mixer combines the materials and opens the discharge gate after completion.
	5.	Final product is sent to the packaging area.
