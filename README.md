# Daniel's Java Course
## Introduction
This repository is a set of materials for people wanting to teach Java to complete beginners. It is designed to give students the skills to eventually program for FRC Robotics. As such, some subjects (most notably string processing) are not covered. However, all concepts are taught with good practice in mind, and students who complete the course will have no problem learning new concepts in the future.

### Work in progress
This is a *work in progress*! Not all of the slides are up yet. The slides that are published in the master branch are complete and can be used.

## (Brief) Teaching Guide & Philosophy
This course is split up into lectures, which can be found in the `slides` directory. Each lecture has a pdf with slides. The teacher should go through the slides and explain concepts as they appear. Most slides will have questions on them; teachers should call on students and ask them to answer the questions. If you have a large group size, it may be necessary to add more questions.

When students give answers to questions, it is important to make sure they understand what they are saying. Teachers should challenge their students to provide justification or ask "are you sure," regardless of whether or not a student's answer is right or wrong.

Whenever a new concept is introduced, students will go through the following process:
1. Learning - reading about the concept
2. Reading - seeing and interpreting how that concept works in actual code
3. Group writing - the class, as a group, will write a snippet of code that utilizes the concept
4. Individual writing - after each lecture, students complete individual CodingBat exersizes

Every lecture is accompanied by a notes page. Read the notes for each slide before teaching! There is valuable information in there. None of the slides are meant to be read word for word-- often times additional explanation is needed.

After a lecture is given, you should give students the handout versions of the slides so they can look back at something in case they've forgotten.

### CodingBat
All students should have accounts on codingbat.com. In addition to the exercises listed by default on the site, I have created my own problems that are easier to complete. These can be found at http://codingbat.com/home/sinani201@gmail.com.

## Technical information
### Slides
Slides were created using LaTeX with Beamer. Since the slides are open-source, you are welcome to change them. Compiling a lecture file without any special options will generate a pdf that can be used as a presentation. To generate handout pdfs (versions of the slides that do not have steps or pauses) or notes files (pdfs with notes for teachers), you can use the supplied Makefile. Here are some examples of how to use the makefile:

```bash
make all # Generate presentation slides, handouts, and notes for all lectures
make slides # Only generate presentation slides for all lectures
make handouts # Only generate handout pdfs for all lectures
make notes # Only generate notes pdfs for all lectures
make full2 # Generate presentation slides, handouts, and notes for just lecture 2
make handout1 # Only generate the handout pdf for lecture 1
make slides3 # Only generate the presentation slides for lecture 3
make notes2 # Only generate presentation notes for lecture 2
```

### Examples
Coming soon!

## Collaboration and open-source spirit
If you have suggestions, changes, or are just using ths material, please let me know! I'd love to chat.

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
