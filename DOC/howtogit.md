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
  
  Click on the bouton [ADD IMG] form the https://github.com/fcci2017/FCCI.git, and select
  your account.

  This will create a copy to the fcci repository owned by the fcci organisation,
  allowing you to modify a copy of the fcci repository whitout applying any
  change ont he main repository before your change are ready to be added. 
  
  Whne you believe your improvement idea/suggestion/work are ready to be
  added, you an submit a pull request. A pull request is a change propostion
  that will be reviewed by (all) the other members of the organisation. During
  the review proccess everyone will comment/critic you change proposal allowing
  it to reach a consensual form. Once each comment/critics have been adressed
  through modification or discussion the Pull Request will be merged.
  
  While a Pull Request can be summited by anyone who is willing to contribute, a
  Pull Request can only be merged by an FCCI member. It is not allowed to merge
  your own PR even if you have the authority.

#. Clone your fork locally

On you have forked the fcci repository on your own github account you will be
able to clone your own fork (copy) of the repository on (each of) your computer.

```bash
git clone https://github.com/git_username/FCCI.git
```

#. Remote set up
Once you have clone your repository into your computer, you can add a remote
(link to the main repository -- the link to you own fork of the repository is
automatically done when cloning it. -- you can access the list/name of remote
you have set up by using the `git remote -v` command)

```bash
cd FCCI
git remote add upstream https://github.com/fcci2017/FCCI.git
```

This will allow you to pull the last version of the repository from the main
repository. Usually the link to the remote are used in only one direction :
- from the main repository to you computer, -- `git rebase upstrean/master`
- from your comtuper to you own fork (copy of the repository) -- `git push origin branch`
- from you own fork -- Pull Request (done on github website)



Work with your fork
-------------------



\end{document}
