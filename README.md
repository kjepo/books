# Computer science books that I recommend

I am not an expert in any particular field of computer science,
and I can't claim that I've read every book but I can certainly
let you know which books I have enjoyed the most.

For simplicity, I have made links to Wikipedia for all books whenever
possible, and Amazon if not.

When I first want to study a new topic I generally try to go by
the following rules:

- Is the author an expert in the field?
- Are the examples in the book useful?

Take
["The C Programming Language"](https://en.wikipedia.org/wiki/The_C_Programming_Language)
for instance: it was written by Brian Kernighan and Dennis Ritchie
(hence its moniker "K&R").  C was Dennis Ritchie's invention and Brian
Kernighan, who is a top notch technical writer, had his office nearby.
If you want it from the horse's mouth, you can't get any better.
But in addition, every example - from the very first - does some
meaningful task.  I have a strong aversion to textbooks that use
completely moronic examples to illustrate a particular mechanism,
for instance

```
let object = { fruit: "apple", color: "green" };

function foo() {
    let bar = object.fruit;
    console.log(bar);
}
```
I also recommend going on the WWW to look at what textbooks 
are used in college/university courses.

With that prelude, allow me to get on with the list of recommended books.

## Algorithms and Data Structures

Algorithms and Data Structures are at the very heart of computer science
which, according to my belief, is concerned with the study of *computation*.

- The field was pioneered by Donald Knuth whose books
["The Art of Computer Programming"](https://en.wikipedia.org/wiki/The_Art_of_Computer_Programming) (TACP)
certainly fullfils the critera of being written by an expert in the field.
However, the algorithms are described in MIX, an assembly
language for a fictitious processor, thus rendering the algorithms almost incomprehensible.

- For many years, the best introduction to the field was
["The Design and Analysis of Computer Algorithms"](https://www.amazon.com/Design-Analysis-Computer-Algorithms/dp/8131702057) (AHU)
by Aho, Hopcroft and Ullman.  The authors are definitely pioneers in the field, and
excellent writers. They introduced the notion of "pidgeon Algol" which is much more
readable way of presenting algorithms.  In this book, the authors
use a "super Pascal" language instead and as we all know, Pascal is not used much these days.
While the field of Algorithms and Data Structures have
grown and shifted a bit, AHU is still an enjoyable book to read but for instance a
large section is devoted to 2-3-trees which is perhaps not the most obvious choice
for an introductory textbook today.

- The definitive textbook today must be
["Introduction to Algorithms"](https://en.wikipedia.org/wiki/Introduction_to_Algorithms)
(CLRS). It is a hefty book (over 1200 pages) and when I taught the
subject we covered less than half of the book.  Still, this book is an absolute must to
anyone in the field and I can thoroughly recommend.  I am proud to say that I was
mentioned in the 2nd edition of the book.  If you can find me, let me know!

I also want to mention some additional books that I think are interesting.

- ["Data Structures and Network Algorithms"](https://www.amazon.se/-/en/Robert-Endre-Tarjan/dp/0898711878) is a rather small book by Robert Tarjan and while the book covers
network optimization algorithms, the true gem is the introductory chapter which
outlines a very concise notation for writing pseudo code.

- ["Algorithms"](https://www.amazon.com/Algorithms-4th-Robert-Sedgewick/dp/032157351X)
by Robert Sedgewick is the 4th incarnation of an old classic.  While I haven't read
the most recent versions of this book, the first version was most enjoyable and
was full of many "tricks" which have simplified many algorithms.  If you like beautiful
code, this may be the book for you!

- ["Programming Pearls"](https://www.amazon.com/Programming-Pearls-2nd-Jon-Bentley/dp/0201657880/ref=sr_1_1?crid=QEYF6BZ8F1DC&dib=eyJ2IjoiMSJ9.g0foazB5iLdpD1rJmogQwWGK3I5X8urOdCci-oLXTZr28-HfgBHmQ2hkaIAQDNiXwYBdLTAXlnuApjYagHr3l5X5gBIMNlnUfqZKEZQNzrkFKKm39PaP-idDwHdwyyr1SZo9418LQYGSVDN7QpFu7pqbVAdImcp2cMQaWnQQXCXLqEtV-w-N6b7PwsU_teS28CPO9ujySXZ_4qm48GoEmLYZaonKpsesxmA7HHPAxZ0.23pboaVQMxX0jayRJqXTqpCNPZ05jCZq41rKZOW0f5w&dib_tag=se&keywords=programming+pearls&qid=1732472667&sprefix=programming+pear%2Caps%2C347&sr=8-1) by Jon Bentley offers unique and clever solutions
to a lot of problems that have irritated programmers for decades.
Jon Bentley has also written a follow-up, "More Programming Pearls".
If you appreciate beautiful code and like challenging problems, these books are great.

- ["The Algorithm Design Manual"](https://www.amazon.com/Algorithm-Design-Manual-Computer-Science/dp/3030542556/ref=sr_1_1?crid=2IKEUMNNA0BLJ&dib=eyJ2IjoiMSJ9.kra-hU1QVoSLjuPAeduBiUbl3u2zs-yUIUkOrKjpeTo.7LQiDZybS1F4XBznleBrsy4738muphhbtxcuUT-GUTA&dib_tag=se&keywords=skienna+algorithms&qid=1732472816&s=digital-text&sprefix=skienna+algorit%2Cdigital-text%2C437&sr=1-1) is a catalog
of algorithm resources.  It is difficult to describe it, but lots of programmers recommend
it and think it's one of the best overviews on algorithms.

## Programming languages

- ["Programming Languages - Concepts and Constructs"](https://www.amazon.com/Programming-Languages-Concepts-Constructs-2nd/dp/0201590654/ref=sr_1_4?crid=1G6GCN9QHN5BK&dib=eyJ2IjoiMSJ9.SNvHYlH3dzGEJRkRqjAY6woDlf2Py1UQ1yLhvCEfsPfkDB-nwO6y9fttxTca0qzGjLDfNnil9sNyecB6BhBwrdS_ZW8rCvMcXYFs4EZshjvsmlaEbzmN2WOjZMScnPbPgJL5IE6si9LtwAPZbjhp6T44hquSH-YlQhsaqz1H0NI3In_xT-t6hqSkpRStEP9FtqINCLCYRhgviLadzVGM6Sq0dgRP4RP6_k5Ppp-6X68.MuhRw-SwCWz24BJHfszXfM7VRdddj4XhN51FbQ5y0Hw&dib_tag=se&keywords=ravi+sethi&qid=1732489417&s=digital-text&sprefix=ravi+se%2Cdigital-text%2C1037&sr=1-4-catcorr)
by Ravi Sethi (formerly AT&T Bell Labs and co-author of the Dragon Book) is perhaps difficult to get hold of, but
if you want to get an overview of different programming language paradigms then
this is a really nice book.  It describes imperative programming, object-oriented programming,
functional programming, logic programming and concurrent programming.

