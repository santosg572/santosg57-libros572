prefacio
========

I first encountered Python in 1993 when I joined a small company in Rhode Island. Their pri-
mary product was a GUI-builder for X/Motif that generated code for C, C++, Ada and Python. I
was tasked with extending the object-oriented interface for X/Motif and Python. In the past I’d
become skeptical about the use of interpretive languages, so I began the task with little excite-
ment. Two days later I was hooked. It was easy to develop interfaces that would have taken much
more time and code to develop in C. Soon after, I began to choose interfaces developed using the
Python interface in preference to compiled C code.

After I left the company in Rhode Island, I began to develop applications using Tkinter,
which had become the preeminent GUI for Python. I persuaded one company, where I was
working on contract, to use Python to build a code-generator to help complete a huge project
that was in danger of overrunning time and budget. The project was a success. Four years later
there are many Python programmers in that company and some projects now use Tkinter and
Python for a considerable part of their code.

It was this experience, though, that led me to start writing this book. Very little documenta-
tion was available for Tkinter in the early days. The Tkinter Life Preserver was the first document
that helped people pull basic information together. In 1997 Fredrik Lundh released some excel-
lent documentation for the widget classes on the web, and this has served Tkinter programmers
well in the past couple of years. One of the problems that I saw was that although there were sev-
eral example programs available (the Python distribution contains several), they were mostly brief
in content and did not represent a framework for a full application written with Tkinter. Of
course, it is easy to connect bits of code together to make it do more but when the underlying
architecture relies on an interpreter it is easy to produce an inferior product, in terms of execu-
tion speed, aesthetics, maintainability and extensibility.

So, one of the first questions that I was asked about writing Tkinter was “How do I make an
XXX?” I’d usually hand the person a chunk of code that I’d written and, like most professional
programmers, they would work out the details. I believe strongly that learning from full, working
examples is an excellent way of learning how to program in a particular language and to achieve
particular goals.

When I was training in karate, we frequently traveled to the world headquarters of Shuko-
kai, in New Jersey, to train with the late Sensei Shigeru Kimura. Sensei Kimura often told us “I
can’t teach you how to do this (a particular technique)—you have to steal it.” My approach to
learning Tkinter is similar. If someone in the community has solved a problem, we need to steal
it from them. Now, I am not suggesting that we infringe copyright and professional practice! I
simply mean you should learn from whatever material is available. I hope that you will use the
examples in the book as a starting point for your own creations. In a small number of cases I have
used code or the ideas of other programmers. If this is the case I have given the original author an
appropriate acknowledgment. If you use one of these pieces of code, I’d appreciate it if you would
also acknowledge the original author. After all, what we “steal” has more value than what we pro-
duce ourselves—it came from the Sensei!

I was impressed by the format of Douglas A. Young’s The X Window System: Programming
and Applications with Xt. It is a little old now, but it had a high proportion of complete code
examples, some of which made excellent templates upon which new applications could be built.
Python and Tkinter Programming has some parallels in its layout. You will find much longer
examples than you may be accustomed to in other programming books. I hope that many of the
examples will be useful either as templates or as a source of inspiration for programmers who
have to solve a particular problem.

One side effect of presenting complete examples as opposed to providing code fragments is
that you will learn a great deal about my style of programming. During the extensive reviews for
Python and Tkinter Programming some of the reviewers suggested alternate coding patterns for
some of the examples. Wherever possible, I incorporated their suggestions, so that the examples
now contain the programming styles of several people. I expect that you will make similar
improvements when you come to implement your own solutions.

I hope that you find Python and Tkinter Programming useful. If it saves you even a couple of
hours when you have an application to write, then it will have been worth the time spent reading
the book.


