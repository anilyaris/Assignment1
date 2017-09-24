# MC-C3100 Computer Graphics, Fall 2017
# Lehtinen / Kemppinen, Ollikainen, Aarnio
#
# Assignment 1: Introduction

Student name: Anıl YARIŞ
Student number: 643454
Hours spent on requirements (approx.): 3-4 hours
Hours spent on extra credit (approx.): 3-4 hours

# First, some questions about where you come from and how you got started.
# Your answers in this section will be used to improve the course.
# They will not be judged or affect your points, but please answer all of them.
# Keep it short; answering shouldn't take you more than 5-10 minutes.

- What are you studying here at Aalto? (Department, major, minor...?)
Exchange student in Computer Science.
- Which year of your studies is this?
3rd year of my Bachelor's in my home university.
- Is this a mandatory course for you?
It is a must course in my home university.
- Have you had something to do with graphics before? Other studies, personal interests, work?
I have a little bit experience on Unity and how models & textures work, also I like to edit textures ripped from Pokemon games to change patterns & colors and see them on Pokemon models that are also ripped from the game cartridge.
- Do you remember basic linear algebra? Matrix and vector multiplication, cross product, that sort of thing?
Yes, I've taken a linear algebra course in the second semester of my first year in my home university.
- How is your overall programming experience? What language are you most comfortable with?
I've programmed with Python, C, C++, Haskell, Prolog and Java (Verilog as well if it counts) and seen C# in Unity. I mostly prefer using C++, Python or Java. 
- Do you have some experience with these things? (If not, do you have experience with something similar such as C or Direct3D?)
C++: Yes.
C++11: Pretty much (I'm not as strong with the features that came with C++11).
OpenGL: No.
I have experience in C as well.
- Have you used a version control system such as Git, Mercurial or Subversion? Which ones?
I've used Git.
- Did you go to the technology lecture?
No.
- Did you go to exercise sessions?
Yes.
- Did you work on the assignment using Aalto computers, your own computers, or both?
I prefer working on my own computer.
# Which parts of the assignment did you complete? Mark them 'done'.
# You can also mark non-completed parts as 'attempted' if you spent a fair amount of
# effort on them. If you do, explain the work you did in the problems/bugs section
# and leave your 'attempt' code in place (commented out if necessary) so we can see it.

(Try to get everything done! Based on previous data, virtually everyone who put in the work and did well in the first two assignments ended up finishing the course, and also reported a high level of satisfaction at the end of the course.)

                            opened this file (0p): done
                         R1 Moving an object (1p): done
R2 Generating a simple cone mesh and normals (3p): done
  R3 Converting mesh data for OpenGL viewing (3p): done
           R4 Loading a large mesh from file (3p): done

# Did you do any extra credit work?

I did all the recommended and easy extras except the one about camera, plus first and third of the medium ones. Instructions on how to use the implemented features are written in the bottom of the window when the executable is run.
For the third medium extra I implemented importing of PLY files as exemplified, but sample PLY models that I was able to find were very large and they didn't fit the viewport, I could test with a relatively smaller one but I'm still not sure if there are any bugs in my implementation.

# Are there any known problems/bugs remaining in your code?

(Please provide a list of the problems. If possible, describe what you think the cause is, how you have attempted to diagnose or fix the problem, and how you would attempt to diagnose or fix it if you had more time or motivation. This is important: we are more likely to assign partial credit if you help us understand what's going on.)
After doing the viewport correction extra, when the window is extended all text and buttons gets smaller and stick to the edges of the viweport rather than the window, even though the interaction field of the buttons stick to the edge of the window.
I tried to correct this by examining how I can edit the position of the text and buttons, but I couldn't find any field related to position within the internal functions that handle drawing text and buttons.

# Did you collaborate with anyone in the class?

No.

# Any other comments you'd like to share about the assignment or the course so far?

(Was the assignment too long? Too hard? Fun or boring? Did you learn something, or was it a total waste of time? Can we do something differently to help you learn? Please be brutally honest; we won't take it personally.)
When I first viewed the .sln file I got a little bit intimidated and this somewhat discouraged me, and because of this I overcomplicated things for myself in the beginning until I figured out that 
each of the requirements needed around 10 lines of code to implement. The assignment wasn't that hard, but the size of the project is a little bit intimidating considering this is the first assignment,
especially for someone like me who had no experience in coding graphics.

