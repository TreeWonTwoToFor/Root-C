This is a version of the Root Game Engine, but using the C library instead of Python. There's multiple reasons for this, including.
 * Wanting to just become more familiar with the C programming language in general
 * Due to general performance issues with Python (such as no GPU usage, slow pygame surfaces, nested for loop layers, etc.)
 * Buliding RootEngine from scratch now, with the knowledge I have, will hopefully lead to a more well-designed framework.

Also, aside from those reasons for swapping to C specifically, I want to also move away from using AI in my code. The reason isn't because I think that using AI is bad for making projects, but because I want to have a better understanding of all aspects of the code. While I do understand the previous version of the project, some parts that I didn't write myself I don't understand as well as I want (such as the quotidian math, edge detecting for triangle rasterization, etc.).
