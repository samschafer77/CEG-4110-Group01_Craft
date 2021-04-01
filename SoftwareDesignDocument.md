#Software Design Document
#Tank Duel Game with Voxel Engine
1.0 Introduction
1.1 Purpose
1.2 Scope
1.3 References (Craft, Doxygen)
1.4 Overview
2.0 Design Overview
2.1 Introduction
2.2 System Architecture
2.3 System Interfaces
4.4 Constraints and Assumptions
3.0 Object Description
3.1 Objects (Objects used in Craft game)
4.0 Data Design
 	4.1 Entity Relationships (How the objects interact)
5.0 Non-Functional Requirements (System Requirements)
5.1 Performance Requirements
5.2 Design Constraints
6.0 Supplementary Documentation
6.1 Tools Used to Create Diagram
Req 1.0
	Creation of tank the the player will be able to use.
Code:
	Def  Tank():         Def  Tank(x,x1,y,z)
				                    // Dimensions of the tank
				                    result = set()
				                    return result
        
 
Req 1.2.1
	The projectile block shall be implemented in the buldier.py file. The block’s number will be equal to 24.
   The texture for the block will be added in the textures folder, in the texture.png file.
Code:        
	TANK_SHELL = 24
