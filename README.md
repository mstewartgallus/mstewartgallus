### Hi there 👋

My name is Molly Stewart-Gallus.

I guess right now I'm just working on my portfolio.

### I'm currently learning

Lately I've been working on [formalizing a small amount of category
theory](https://github.com/mstewartgallus/category-fun) in
[Coq](https://coq.inria.fr/).

I'm playing around with type systems and formal methods right now and
I'm hopeful category theory can help with this.

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

I also played a [little bit](https://github.com/mstewartgallus/peacod)
with [GraalVM](https://www.graalvm.org/) but I found it too
complicated for initial experimentation.  Also GraalVM had troubles
with tail recursion at the time which made it hard to implement
functional languages.  [Cadenza](https://github.com/ekmett/cadenza)
for example went through hoops I didn't want to bother with to
optimize tail calls.

I got heavily into low-level details of the JVM for a while.  I
learned to [use](https://github.com/mstewartgallus/heaps) ByteBuddy
and invokedynamic to insert dynamically optimizable spots into a Java
program.

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

- https://www.linkedin.com/in/mstewartgallus/
- https://github.com/mstewartgallus
- https://gitlab.com/mstewartgallus

### Addendum

I am a trans woman. I used to go by the name "Steven" and use the
email stevenselectronicmail@gmail.com . These details may pop up in
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
