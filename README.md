# Assignment 3: Locomotion
In this assignment, you will work with your group to implement locomotion techniques that were discussed in class, and in service to your final project.

## Submission Information
You should fill out this information before submitting your assignment. Make sure to document the name and source of any third party assets such as 3D models, textures, or any other content used that was not solely written by you. Include sufficient detail for the instructor or TA to easily find them, such as a download link.

To submit you assignment, you must push the Godot project to the Github classroom repository. It is ok if this doesn't include the APKs, the Android folder, or the addons folder. You must also zip all the APKs (there will be one for each implemented technique) and submit the zip file on Canvas.

Group member 1 name:

Group member 1 email:

Group member 2 name:

Group member 2 email:

Group member 3 name:

Group member 3 email:

Group member 4 name:

Group member 4 email:

Third party assets:

## Technique Selection (10 total points)
As a group, you will need to select and implement a number of locomotion techniques. Specifically, you will design and implement a number of techniques equal to your group size (minimum 2). If you are working in a group of 3, you will select and implement 3 techniques. If you are working alone, you will select and implement 2 techniques. **You CANNOT implement basic grabbing or basic pointing**. 

In this section, you will justify your technique selections.

### Project Recap (1 point)
Provide a high-level summary of your project.

#### Answer

> [!NOTE]
> Your answer goes here.

#### Grading
- -1 points if this section is missing
- -0.5 points if this section is missing sufficient detail

### Identified Locomotion Tasks (3 points)
Identify **2** different locomotion tasks in your project. Describe what the user will need to accomplish, when they will need to perform the task, and how often they will need to perform the task. Add any other information to provide the grader with the context they need. Give each identified task a unique name that you can use to reference it in later sections.

#### Answer

> [!NOTE]
> Your answer goes here.

#### Grading
- -1.5 points if only 1 task is identified
- -3 points if no tasks are identified
- -1.5 points for each identified task that is not a locomotion task

### Identified Technique Options (3 points)
Identify **6** possible locomotion techniques (3 for each of the two previously identified locomotion tasks) from the list below that you can implement to allow the user to accomplish the previously identified tasks. Describe why the technique is a suitable choice for the chosen task. Specifically, address the affordances the technique provides that are required by the task and why the technique's constraints will not be an issue. **It is possible to use the same technique for different tasks, but you must justify it for both tasks**

I specifically want you to focus on the technique's effects on motion sickness, spatial awareness, ease of use, and the user's requirement to accomplish other simultaneous tasks when justifying your chosen techniques.

#### Possible techniques:
 - Continuous movement with velocity-dependent FOV restriction \*
 - Continuous movement with time-dependent FOV restriction \*
 - Walking-in-place using hand swinging movement
 - Translation-gain-based techniques (i.e. "Seven League Boots") \*\*
 - Teleportation with final direction specification
 - Teleportation with rapid transition (rather than instantaneous transition)
 - World-in-Miniature with the abiilty to manipulate the user's point of view
 - Single-point or Dual-point world manipulation
 - A hybrid of any of the listed techniques
 - A different technique not listed here (it is suggested you run this by the professor to verify that it meets the requriements of the assignment)

*\* Continuous movement can be implemented using either view-directed steering, hand-directed steering, or the "human joystick" method*
*\*\* The total physical environment size requirements cannot exceed 4 meters by 4 meters*

#### Answer

> [!NOTE]
> Your answer goes here.

#### Grading
- -1 points for each missing technique, if there are fewer than 6 identified techniques (min 0)
- -1 points if only a single task is represented
- -1 points for each represented task that only has 1 identified technique
- -0.5 for each technique that insufficiently provides justification the technique

### Selected Techniques (3 points)
Of the identified technique options you provided above, identify which ones you will be implementing for this assignment. The number you will implement is dependent on your group size, that is, you will implement a number of techniques equal to the number of members in your group (unless you are working alone, in which case you will implement 2). For each one, remind the grader which task it is for and describe why it is the best technique for the task. If you want to experiment with different techniques for the same task, that is also fine, just describe why this is necessary.

#### Answer

> [!NOTE]
> Your answer goes here

#### Grading
- -3 points if this section is missing
- -1 points for each technique description that is missing the corresponding task description (min 0)
- -1 points for each technique description that fails to justify it as the best technique (min 0)

## Technique Implementation (10 points)
Once you have decided on your locomotion techniques, you will implement them in Godot. All the techniques must be implemented in the same Godot project, and each technique must be implemented in its own scene. The name of the scene should reference the unique name of the technique (see above) so the grader can easily connect the two. Furthermore, each technique scene must be compiled into its own APK (you will submit a zip folder of APKs instead of a single APK).

An environment must be provided for each locomotion technique that allows the grader to evaluate it. This will likely be a pared down, or proxy version, of the environment the technique will be used in for the final project.

For each implemented technique, provide instructions for how the grader is supposed to use it, as well as any known hiccups that will make it so that the grader can grade the technique to the best of their ability.

#### Grader Instructions

> [!NOTE]
> Your instructions go here.


#### Grading
Each implemented technique will be responsible for an equal share of the implementation points. For example, if you are implementing 2 techniques (either working in a group of 2 or individually), each technique will be worth 5 points; 3 techniques are each worth 3.33 points each, and 4 techniques are each worth 2.5 points.

Each technique will be graded on its functionality in the following way:

- 100% if the technique works as expected
- 80% if the technique mostly works, but there are some bugs
- 50% if it is apparent that an effort was made to complete the technique, but it does not work
- 0% if no apparent effort was made
- 0% if the provided environment does not allow the grader to evaluate the technique

*The grader is free to interpolate between these values as they see fit*

