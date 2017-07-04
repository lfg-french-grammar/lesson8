
Lexical-functional grammar fragments, test sets, basic tokenizer, and basic morphological analyzer of French https://github.com/lfg-french-grammar

Author: Leonel Figueiredo de Alencar <leonel.de.alencar@ufc.br> 

Copyright (C) 2016-2017 Leonel F. de Alencar

License: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). For  more information, visit https://creativecommons.org/licenses/by-nc-sa/4.0/

The computational grammar fragments of French were implemented in the Lexical-Functional Grammar (LFG) formalism using the Xerox Linguistic Environment (XLE). To compile a parser from one of the grammar fragments and parse sentences in French, you need XLE, whose documentation you find here:

http://www2.parc.com/isl/groups/nltt/xle/doc/xle_toc.html

On how to obtain a XLE LICENSE, visit http://www2.parc.com/isl/groups/nltt/xle/. 

Each grammar fragment and shallow processing tool is described in detail in one of the 8 chapters of the the following book:

Schwarze, Christoph & Alencar, Leonel F. de. Lexikalisch-funktionale Grammatik: Eine Einführung am Beispiel des Französischen mit computerlinguistischer Implementierung [Lexical-Functional Grammar: A French-based Introduction with Computational Implementation]. Tübingen: Stauffenburg, 2016. X, 271 pp. Stauffenburg Einführungen, 30. ISBN 978-3-95809-411-6.

For more information on this book, visit 

http://lfg-book.blogspot.com.br/2016/01/new-lfg-books-abstract.html
http://linguistlist.org/issues/27/27-761.html

If you use one of the grammar fragments or tools from this site, please cite the URL https://github.com/lfg-french-grammar and the book.

Chapters 1, 2, 3, 4, 5, 6, and 8 of the book are exclusively or mainly devoted to theoretical aspects of LFG and its application to French syntax. The grammatical phenomena discussed in each chapter are implemented in the LFG/XLE grammar fragment described in detail in the chapter. Each chapter also contains a positive test file and a negative test file corresponding to the grammar fragment discussed in the chapter. Chapter 5 also presents a basic tokenizer, and chapter 7 describes the implementation of a morphological analyzer for some subgroups of verbs from the 1st conjugation. 

Each chapter folder in https://github.com/lfg-french-grammar/book contains one or more grammar files, a positive test set, and a negative test set. Besides that, chapters 5 and 7 folders contain source files of the tokenizer and morphological analyzer, respectively. To be able to run the LFG/XLE grammar fragments of chapters 5, 6, and 8, these source files must be compiled into finite-state transducers with the Xerox Finite-State Tools (XFST):

http://web.stanford.edu/~laurik/fsmbook/home.html

The finite-state transducers must be compiled with XFST in the operating system where you are running XLE. Edit the respective path in the morphology.lfg file to point to the location of each transducer file in your system.

FrGramm is a significantly improved version of the grammar fragment from chapter 8. It is the subject of the following paper:
 
Alencar, Leonel Figueiredo de (2017). A computational implementation of periphrastic verb constructions in French. Alfa, Rev. Linguíst. (São José Rio Preto), 61. To appear. http://www.scielo.br/scielo.php?script=sci_serial&pid=1981-5794&lng=en&nrm=iso 

You can download FrGramm from this link:

https://github.com/lfg-french-grammar/frgramm

For bug reports, comments, and suggestions, please write to: leonel.de.alencar@ufc.br

