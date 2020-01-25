# esu-grammar-engineering
Central Alaskan Yup'ik (esu) Grammar <br>
Lonny Strunk and Marcus Martinez

This is a partial grammar built in tdl and based in an HPSG (Head-Driven Phrase Structure Grammar) syntax paradigm. The grammar was built as part of a graduate level grammar engineering course at the University of Washington, taught by Dr. Emily Bender. The Yup'ik examples were built and grammar decisions were made based on research by Miyaoka, O. and Jacobson, S., as well as community input, and knowledge from co-developer Lonny Strunk. 

The grammar was initially developed using the LinGO Grammar Matrix, where language-specific syntactic details can be specificd, and a 'starter' gramamr will be generated. From here, custom tdl edits were made for broader coverage, and testing was done in the tsdb evironment.

The grammar matrix can be found here: http://matrix.delph-in.net/customize/matrix.cgi <br>
Documentation for the matrix can be found here: http://moin.delph-in.net/MatrixDocTop <br>
Documentation for working in the LKB environment can be found here: http://moin.delph-in.net/GrammarEngineeringFaq <br>
and here: http://moin.delph-in.net/LkbTop <br>
Shortcuts for use with LKB in emacs can be found here: http://moin.delph-in.net/LkbMode

Latest Relevant Files: <br>
esu-lab9 contains the most recent grammar tdl files <br>
The latest test sentences can be found at data_and_choices/lab9_testsuite_combined.txt <br>
The latest choices file (unedited tdl exported from the grammar matrix) can be found at data_and_choices/lab7_choices_file_7.t.txt

Grammar Coverage:
-Case <br>
-Agreement <br>
-Argument Optionality <br>
-Adnominal Possessives (incomplete) <br>
-Negation <br>
-Tense, Aspect, Mood <br>
-Clausal Complements (incomplete) <br>
-Adverbial Complements <br>
-Evidentials <br>
-Locative Noun Phrase Modifiers <br>
-Locative Noun Phrase Predicates <br>
-Locative Affix Predicates
-Noun Phrase Predicates
-Adjective Phrase Predicates (incomplete)
-Wh-Questions
-Coordination

