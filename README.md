### Hi there 👋

I am Ms. Molly Stewart-Gallus.

I guess right now I'm just working on my portfolio.

I have personal interests in formal methods but mostly have
professional experience in web development. I'm most looking for
stability and flexible work hours in job positions.

### I'm looking for

I have a personal interest in formal methods but mostly have
professional experience in web development, system administration,
advertising and analytics.  I would strongly value flexible work hours
or part time positions and would also prioritise stability and
work-life balance.  I don't want to go home on Friday and get a call
on the weekend that something is broken.

### I'm currently learning

In 2023 I have been exploring porting my poetry blog over to
[Gatsby](gatsbyjs.com).  Mostly things have been very smooth but I
have found the biggest problems to be Gatsby's lack of documentation.
I can implement missing features I know about.  I can't work around
bugs that have not been documented.  I'm not a fan of GraphQL per se
but I can see the advantages of a unified abstraction over different
data sources.

Also the tutorial documentation for Gatsby gives oversimplified and
fragile designs for cases like blogging.  The suggested designs don't
work for cases like multiple source formats.  Just as a Markdown
plugin might process file nodes into Markdown nodes you want to
implement your own code processing Markdown nodes into a custom type
of nodes.  This isn't really a flaw with Gatsby that the tutorials
give the simplest but most fragile examples.

I have found React components to be less problematic than I initially
expected.  I expected lots of weird problems due to the abstraction
over top the native architecture of the web.  I haven't really found
such problems to be the case so far although my website is relatively
simple.

[MDX](https://mdxjs.com/), a Markdown processor lets you insert React
components into Markdown, is interesting but has some major caveats
that make it a little awkward sometimess.  In particular, while MDX is
probably well suited to writing ad-hoc websites and landing pages MDX
is a little less useful for highly structured content like blog posts.

In 2022 I was have been mostly working on [my bizarro poetry
blog](https://github.com/mstewartgallus/mstewartgallus.github.io) and
relearning modern web development.  I have found using
[Jekyll](https://jekyllrb.com/) to be very copacetic.  The biggest
hiccup was figuring out how to implement a search page which I solved
by integrating [pagefind](pagefind.app]) into my blog.

It has been really fun learning about fluid web typography and other
advanced techniques.  Fonts are definitely a headache online though.

I'm a bit of a perfectionist so my special interest for 2022 has been
accessibility.  Learning how to use a screenreader has been eye
opening.  I found it easiest to get started with Android TalkBack.
Accessibility is very fiddly but makes for satisfying design problems
to tetris in the most amount of information with the least amount of
noise.

Most of my blog problems were fairly typical except for figuring out
how to markup poetry appropriately.  A fair bit of hacks were required
to obtain the appropriate sort of hanging indent presentation and to
obtain the appropriate pauses between sentences.  If you're not
careful with the markup the lines of the poem can run together or
worse the words can.  In the other direction, marking up a poem as an
ordered list might lead to a lot of noise.  Hearing "line m of n"
every single line of a poem might be a little messy.

In the past I was working on [formalizing a small amount of category
theory](https://github.com/mstewartgallus/category-fun) in
[Coq](https://coq.inria.fr/).

I'm playing around with type systems and formal methods right now and
I'm hopeful category theory can help with this.  I've been trying to
figure out how to make internal languages for many types of
categories. [I've
started](https://github.com/mstewartgallus/doublecatrel) on some ideas
to work within double categories like Rel.

I have a hunch you can generalize graded monads and adjoint functors
for a sort of graded [Call By Push
Value](https://en.wikipedia.org/wiki/Call-by-push-value) which ought
to be useful for a compiler IR to simplify optimization.

I got heavily into [category
theory](http://nlab-pages.s3.us-east-2.amazonaws.com/nlab/show/category+theory#idea)
for a while. I am no longer convinced it is so simple to compile
computer programs to a categorical intermediate representation.  But a
start of an effort towards this might be [this
project](https://github.com/mstewartgallus/prologish) which compiles a
continuations based language to co-closed categories in a manner dual
to compiling the STLC to closed categories.  Basically it's dual to
the paper [Compiling to
categories](http://conal.net/papers/compiling-to-categories/) by Conal
Elliott.  I also found tagless final style is very clean for
parametric higher order abstract syntax.

I have found category theory very interesting although it does have
some weaknesses with respect to variable binding and higher category
theory.  Category theory tends towards a very combinatorial sort of
style which makes some things very verbose that would be much clearer
with name binders.  Unfortunately parametric foundations allowing
manipulation of name binders are kind of complicated.  The other big
hurdle with category theory is higher categories: categories of
categories.  Very quickly higher category theory gets messy to play
around with in an actual theorem prover.  I'm not sure if these
problems are fundamental or someone smarter than me can come up with
solutions.

### In the past

I've also been playing with technologies like [PLT
Redex](https://redex.racket-lang.org/) and
[Makam](http://astampoulis.github.io/makam/) (a dialect of [Lambda
Prolog](https://www.lix.polytechnique.fr/~dale/lProlog/)) for rapid
prototyping of programming language interpreters.

You can see a tiny demo language in PLT Redex
[here](https://github.com/mstewartgallus/playground/blob/master/coexp.rkt)

A little language in Makam
[here](https://github.com/mstewartgallus/coc-makam) . Makam works
great for simply typed languages but full dependent types are **way
too** complicated in any implementation.

I got interested in compilers and interpreters for a while. I played a
bit with effect systems like Call-By-Push-Value (basically ANF) and
simple functional optimizations:
https://github.com/mstewartgallus/hs-callbypushvalue
https://github.com/mstewartgallus/compiler-2

I also played a [little bit](https://github.com/mstewartgallus/peacod)
with [GraalVM](https://www.graalvm.org/) but I found it too
complicated for initial experimentation.  Also GraalVM had troubles
with tail recursion at the time which made it hard to implement
functional languages.  [Cadenza](https://github.com/ekmett/cadenza)
for example went through hoops I didn't want to bother with to
optimize tail calls.

I got heavily into low-level details of the JVM for a while.  I
learned to [use](https://github.com/mstewartgallus/heaps)
[ByteBuddy](https://bytebuddy.net/) and
[invokedynamic](https://blogs.oracle.com/javamagazine/post/understanding-java-method-invocation-with-invokedynamic)
to insert dynamically optimizable spots into a Java program.

I got heavily into lock-free programming for a while and
[played](https://github.com/mstewartgallus/stacklock) with making a
more efficient unfair lock implementation based on MCS Locks that uses
a stack instead of a queue. I also tried formalizing a little bit of
it in [TLA+](https://lamport.azurewebsites.net/tla/high-level-view.html).

In the past I got into hard real-time and safety critical stuff for a
while. I
[experimented](https://github.com/mstewartgallus/linted/tree/master)
with breaking a program into separate processes some of which are
verifiable in a safe dialect of [Ada
SPARK](https://www.adacore.com/about-spark). The lock-free queue is
probably broken.  I didn't really get how Ada SPARK was meant to
handle concurrency.

### Contact Me

Please reach me at mollystewartgallus@gmail.com .

### See Also

You may want to look into:

- <a rel="me" href="https://mastodon.lol/@MSpondee">\@MSpondee\@mastodon.lol</a>
- https://www.linkedin.com/in/mstewartgallus/
- https://github.com/mstewartgallus
- https://gitlab.com/mstewartgallus

### Addendum

I am a trans woman. I used to use a different name and email. These details may pop up in
older work.  I do not use the name or email anymore.

<!--
**mstewartgallus/mstewartgallus** is a ✨ _special_ ✨ repository
because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
