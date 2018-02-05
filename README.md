# paip-lisp
# Lisp code for the textbook *Paradigms of Artificial Intelligence Programming* (1996)

This page is the index for the Lisp source code files
for the book *Paradigms of Artificial
Intelligence Programming: Case Studies in Common Lisp. by Peter Norvig.  

# Running Code

There is no single "application" to run. Rather, there is a collection of source code files,
duplicating the code in the book. You can read the code or run it as you wish. Lisp is an interactive language,
and you will need to interact with the code to get benefit from it. Some hints:

* You will need a Common Lisp interpreter/compiler/environment. Here's a [discussion](https://www.reddit.com/r/lisp/comments/752wxe/what_is_the_best_common_lisp_interpreter_out_there/) of the options.
* You will always need `(load "auxfns.lisp")`.
* You will need `(requires "`*file*`")`, for the various
instances of *file* that you want to use. (If `requires` does not work properly on
your system you may have to alter its definition, in 
`auxfns.lisp`.  
* The function `do-examples`, which takes as an argument either `:all`
or a chapter number or a list of chapter numbers, can be used to see examples
of the use of various functions.  For example, `(do-examples 1)` shows
the examples from chapter 1.

# The Files

The index below gives the chapter in the book, file
name, and short description for each file.  

<p>
<table border=1>
<tr><td><b><u>CH</u></b> <td><b><u>Filename</u></b><td> <b><u>Description</u></b>
<tr><td>-  <td><a href="README.html">README.html</a><td>		This file: explanation and index
<tr><td>-  <td><a href="examples.lisp">examples.lisp</a><td>	A list of example inputs taken from the book
<tr><td>-  <td><a href="tutor.lisp">tutor.lisp</a><td>		An interpreter for running the examples
<tr><td>24 <td><a href="loop.lisp">loop.lisp</a><td>		Load this first if your Lisp doesn't support ANSI LOOP
<tr><td>-  <td><a href="auxfns.lisp">auxfns.lisp</a><td>		Auxiliary functions; load this before anything else
<tr><td>1  <td><a href="intro.lisp">intro.lisp</a><td>		A few simple definitions
<tr><td>2  <td><a href="simple.lisp">simple.lisp</a><td>		Random sentence generator (two versions)
<tr><td>3  <td><a href="overview.lisp">overview.lisp</a><td>	14 versions of LENGTH and other examples
<tr><td>4  <td><a href="gps1.lisp">gps1.lisp</a><td>		Simple version of General Problem Solver
<tr><td>4  <td><a href="gps.lisp">gps.lisp</a><td>		Final version of General Problem Solver
<tr><td>5  <td><a href="eliza1.lisp">eliza1.lisp</a><td>		Basic version of Eliza program
<tr><td>5  <td><a href="eliza.lisp">eliza.lisp</a><td>		Eliza with more rules; different reader
<tr><td>
<tr><td>6  <td><a href="patmatch.lisp">patmatch.lisp</a><td>	Pattern Matching Utility
<tr><td>6  <td><a href="eliza-pm.lisp">eliza-pm.lisp</a><td>	Version of Eliza using utilities
<tr><td>6  <td><a href="search.lisp">search.lisp</a><td>		Search Utility
<tr><td>6  <td><a href="gps-srch.lisp">gps-srch.lisp</a><td>	Version of GPS using the search utility 
<tr><td>7  <td><a href="student.lisp">student.lisp</a><td>		The Student Program
<tr><td>8  <td><a href="macsyma.lisp">macsyma.lisp</a><td>		The Macsyma Program
<tr><td>8  <td><a href="macsymar.lisp">macsymar.lisp</a><td>	Simplification and integration rules for Macsyma
<tr><td>9-10	<td> &nbsp; <td>		(no files; important functions in <a href="auxfns.lisp">auxfns.lisp</a>	
<tr><td>11 <td><a href="unify.lisp">unify.lisp</a><td>		Unification functions
<tr><td>11 <td><a href="prolog1.lisp">prolog1.lisp</a><td>		First version of Prolog interpreter
<tr><td>11 <td><a href="prolog.lisp">prolog.lisp</a><td>		Final version of Prolog interpreter
<tr><td>12 <td><a href="prologc1.lisp">prologc1.lisp</a><td>	First version of Prolog compiler
<tr><td>12 <td><a href="prologc2.lisp">prologc2.lisp</a><td>	Second version of Prolog compiler
<tr><td>12 <td><a href="prologc.lisp">prologc.lisp</a><td>		Final version of Prolog compiler
<tr><td>12 <td><a href="prologcp.lisp">prologcp.lisp</a><td>	Primitives for Prolog compiler
<tr><td>13 <td><a href="clos.lisp">clos.lisp</a><td>		Some object-oriented and CLOS code
<tr><td>14 <td><a href="krep1.lisp">krep1.lisp</a><td>		Knowledge Representation code: first version 
<tr><td>14 <td><a href="krep2.lisp">krep2.lisp</a><td>		Knowledge Representation code with conjunctions
<tr><td>14 <td><a href="krep.lisp">krep.lisp</a><td>		Final KR code: worlds and attached functions
<tr><td>15 <td><a href="cmacsyma.lisp">cmacsyma.lisp</a><td>	Efficient Macsyma with canonical form
<tr><td>16 <td><a href="mycin.lisp">mycin.lisp</a><td>		The Emycin expert system shell
<tr><td>16 <td><a href="mycin-r.lisp">mycin-r.lisp</a><td>		Some rules for a medical application of emycin
<tr><td>17 <td><a href="waltz.lisp">waltz.lisp</a><td>		A Line-Labeling program using the Waltz algorithm
<tr><td>18 <td><a href="othello.lisp">othello.lisp</a><td>		The Othello playing program and some strategies
<tr><td>18 <td><a href="othello2.lisp">othello2.lisp</a><td>	Additional strategies for Othello
<tr><td>18 <td><a href="edge-tab.lisp">edge-tab.lisp</a><td>	Edge table for Iago strategy
<tr><td>19 <td><a href="syntax1.lisp">syntax1.lisp</a><td>		Syntactic Parser
<tr><td>19 <td><a href="syntax2.lisp">syntax2.lisp</a><td>		Syntactic Parser with semantics
<tr><td>19 <td><a href="syntax3.lisp">syntax3.lisp</a><td>		Syntactic Parser with semantics and preferences
<tr><td>20 <td><a href="unifgram.lisp">unifgram.lisp</a><td>	Unification Parser
<tr><td>21 <td><a href="grammar.lisp">grammar.lisp</a><td>		Comprehensive grammar of English
<tr><td>21 <td><a href="lexicon.lisp">lexicon.lisp</a><td>		Sample Lexicon of English
<tr><td>22 <td><a href="interp1.lisp">interp1.lisp</a><td>		Scheme interpreter, including version with macros
<tr><td>22 <td><a href="interp2.lisp">interp2.lisp</a><td>		A tail recurive Scheme interpreter
<tr><td>22 <td><a href="interp3.lisp">interp3.lisp</a><td>		A Scheme interpreter that handles call/cc
<tr><td>23 <td><a href="compile1.lisp">compile1.lisp</a><td>	Simple Scheme compiler
<tr><td>23 <td><a href="compile2.lisp">compile2.lisp</a><td>	Compiler with tail recursion and primitives
<tr><td>23 <td><a href="compile3.lisp">compile3.lisp</a><td>	Compiler with peephole optimizer
<tr><td>23 <td><a href="compopt.lisp">compopt.lisp</a><td>		Peephole optimizers for compile3.lisp
</table>
<p>
<hr>
<i><a href="http://www.norvig.com">Peter Norvig</a></i>


