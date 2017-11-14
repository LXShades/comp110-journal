# comp110-journal
Base repository for the COMP110 Research Journal assessment

# What is a journal
I'm not even sure what a journal is, but since it was said to be a good place to write thoughts, I'll write them here and call it a journal.

# Welcome to the journal
## On Djikstra, the author of the go to paper
The influence of his paper in the public eye was not immediate. Indeed the author himself, Dijkstra, was the responsible for a popular pathfinding algorithm of the same name. It was therefore reasonable to assume that the motive behind his dislike of the 'go to' statement, was largely due to the fact that having a single statement to simply 'go to' a destination in code linearly would be far, far too easy for the programmer.  

While there are few who have studied deeply into this perspective--perhaps none at all--it is widely accepted that spaghetti code is malnutritious without a healthy algorithmic sauce.


## Stupid stuff
Granted, Dijkstra's pathfinding algorithm was in fact free. And it actually worked. But programmers work in mysterious ways. This author, for one, has paid their institution £9250 so that they can write essays for their institution. And frankly they make no sense at all.

And I for one would find it humourous that the A* algorithm was originally written entirely in goto statements.

Motive to subtly incorporate his pathfinding algorithm into every programming language on the market, where to write a program you had to place instructions in a complex maze with walls made of 0xCC, for the CPU to find and execute without colliding with the break instructions.

(From Pascal) If the divisor is a constant of c = 2\textsuperscript{n}, where *n* is *n*-ything, the compiler optimises this to a right bitshift.

## Journal -- personal thoughts on the paper itself
The opening paragraph of this paper is very bold. It's littered everywhere with 'go to' statements; frankly I feel that this article is extremely inefficient and looks like spaghetti code. Furthermore, it makes bold claims that 'go to' should be abolished from all programming languages. \textbf{Explore:} Uses of go to in the modern age, particularly in C++. Introduction of structured programming languages. Etc

In paragraph 3, he makes a point to better visualise the dynamic process of the program, noting that code is a static set of instructions representing a dynamic set of processes that is hard for the human brain to process. He wants to create a simpler link between the program (in text) and the process (spread over time).

In paragraph 4 he begins to make things complicated by introducing 'textual indices', where you can point to an area in the code with rough equivalence to the point of the process being performed by a computer. In paragraph 5 if and else statements are illustrated as similarly simple. No doubt, this will all become much more complicated when goto statements come into play.

In paragraph 5, procedures come in. Interestingly these are kind of like areas for goto statements, too. And I can speak from personal experience that writing my code in a messy, linear fashion; despite the cost of maintainability, actually makes it much easier to debug because all the code is written, linearly, in one place. This is one thing I can't wrap my head around in OOP. When things become moduler I struggle to wade through it all. But that's another story.

By paragraph 6, he explains what is essentially the stack. So long as you keep a list of the textual indices, referring to the calling points from which you jumped into the next procedure, you can characterise your progress through the program.

Paragraph 7 introduces while loops. He remarks that we could already theoretically create loop with functions that call themselves (not mentioning the inevitable stack overflow, mind). He remarks that textual indices are no longer sufficient. We've gone too deep. It's over. But not quite. Introducing the dynamic index, counting the number of repetition. With more nested loops, more textual and dynamic indices come in. But the process is still alive, and it's okay.

Paragraph 8 he finally explains why he took us on that perilous journey. The indices are markers of progress. They're vital, but always invisible to the programmer. Except when the programmer's debugging, but we don't want to do that before the bugs appear.

The remainder of his argument is a well-written elucidation of common programming sense. Go to lets you jump around haphazardly with no indications of the program's progress other than the state of the program itself. 

## Journal -- thoughts on the context
It's 1968. Computers aren't even home computers yet. TODO: Read more about the historical context.

## Journal -- thoughts on related papers
*The programming language pascal*: Written with structured programming in mind. Made as a simple starting language. Supported data structures (compare to ALGOL?). Compiler for Pascal was written in Pascal.

## OOP considered harmful?
Explore OOP, such as C++, and how it kind of shares the confusing properties of goto.