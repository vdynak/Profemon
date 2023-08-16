# Profemon
This command line project trains Profemons.

Explanation: Trainers train their profemons, so they can challenge the departments (trainers who specialize in a single type of profemon) to a profemon battle and gain a degree.

The Skill class consists of the name and description of the skil, the total number of times the skill can be used, and the integer that represents the specialty of the skill (0, 1, or 2).

The Profemon class consists of the name and level of the profemon, the current experience, required experience to level up, maximum health, specialty of the profemon, as well as an array of size 3 conraining skills learned by the profemon.
Note: The Profemon class has an enumeration type called "Specialty" with three values: ML, Software, or Hardware.

The Trainer class consists of a vector of profemons which represents a profedex, a profemon array of size 3 which represents the trainer's current team, and a pointer to a profemon which is currently selected from the team.

Note: Each trainer has a team of three profemons and a profedex. The profedex is storage for all the profemons collected by the trainer. Each trainer can choose to have one profemon accompany them at all times.

Note: The Department classes will inherit from the Trainer class.
