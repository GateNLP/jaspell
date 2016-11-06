This is the original JaSpell readme file for reference.

-----------------------------------------------------------------------

  JaSpell :: Java Spelling Checking Package


  What is it?
  -----------

  JaSpell is a 100% pure Java implementation of a spelling checker.

  The Latest Version
  ------------------

  The latest version is available from the JaSpell project web site.
  ( http://jaspell.sourceforge.net/ ).

  Requirements
  ------------

  The following requirements exist for installing and running JaSpell:

   o  Java Interpreter:

      A fully compliant Java runtime environment is needed for JaSpell to operate.

   o  Dictionary Files
    
      A dictionary is a normal text file with the list of valid words, where each line contains
      a word and an associated word frequency.
      
      The package already comes with an English and a Portuguese dictionary.
      Optionally, the spelling checker can also be supplied with a list of words 
      to ignore (these won't be given any sugestions) and a list of common misspellings.

  Installation Instructions and Documentation
  -------------------------------------------

  Unzip the package and from the command line type:
  
  	java pt.tumba.spell.JaSpell
  
  The list of command options will appear on screen.

  Availability, licensing and legal issues
  --------------------------

  JaSpell is released under the BSD License. Source code is included on the package.
