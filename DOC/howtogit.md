====================
How To work with GIT
====================


Introduction
============

	This document explains minimum requirements needed for participating to FCCI. A lot of additionnal features are detailled in the following on ine documentation \url{https://git-scm.com/book/fr/v2}.

	It is assumed here the reader has already a github account.

FCCI2017 group settings
=======================

Contribute to the FCCI
-----------------------
This assume that you already have a github account, if you don't please visit
and follow the instruction.

#. Fork the repository
  
  Click on the bouton form the https://github.com/fcci2017/FCCI.git, and select
  your account.
  This will create a copy to the fcci repository owned by the fcci organisation.
  This will allow you to modify a copy of the fcci repository whitout applying
  any change ont he main repository before your change are ready to be added.
  Once you considere your improvement idea/suggestion/work are ready to be
  added, you an submit a pull request. A pull request is a change propostion
  that will be reviewed by (all) the other members of the organisation. During
  the review proccess everyone will comment/critic you change proposal allowing
  it to reach a consensual form. Once each comment/critics have been adressed
  through modification or discussion the Pull Request will be merged.  While a
  Pull Request can be summited by anyone who is willing to contribute, a Pull
  Request can only be merged by an FCCI member. It is not allowed to merge your
  own PR even if you have the authority.

#. Clone your fork locally

```bash
git clone https://github.com/fcci2017/FCCI.git
```

#. Remote set up
```bash
git remote add upstream https://github.com/fcci2017/FCCI.git
git remote set-url origin https://github.com/thiollie/FCCI.git
git pull upstream master
```

	\begin{lstlisting}[style=BashInputStyle]
	Test input command
	\end{lstlisting}
	\bigskip

	\begin{lstlisting}[style=BashOutputStyle]
	Test ouput command
	\end{lstlisting}
	\bigskip

Work with your fork
-------------------



\end{document}
