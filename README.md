
# University of Nottingham Improvement Engine (Unie)
Inequational reasoning for Improvement Theory

Unie is currently not available on Hackage, but will be shortly. The current
version status is 0.9. It is a fully working system, but we plan to continue
development and add further features.

# Running Unie

The following command will install the necessary packages that Unie requires:

> \> cabal install brick kure GraphSCC split extra monad-loops tuple ansi-terminal

Be sure to execute from the root directory:

> \> ghci /src/Interactive/Inter.hs

Also please use a dark ANSI terminal.

# Getting started

A good way to become familiar with the system is to execute one of the
existing proof scripts. This can be done by using the 'run-script'
command inside Unie:
  
  > unie> run-script "./Improvement Scripts/reverse_ass_b"

Pressing return once the script is active will execute the next command.
A script can be fully executed as follows:
  
  > unie> run-script "./Improvement Scripts/reverse_ass_b"

  > unie> !

Once the script has been run, you may wish to review the proof history:

 > unie> show-hist

Note that a number of scripts rely on the use of definitions
in the 'lib' folders. These are imported by the scripts themselves.

Press tab to see a full list of commands. Typing 
 > unie> man <command_name>

gives information on command usage. Please note, the help/man section is 
currently under development and will be completed soon. Apologies for
the delay.

Please send any queries/bug reports to martin.handley@nottingham.ac.uk

Thank you.