\# Git and Github Capstone Project



\## Project Overview



This project demonstrates team collaboration using \*\*Git as the Version Control System (VCS)\*\* and  \*\*branching strategy.



The application is a simple \*\*Wallet API\*\* forked from https://github.com/edureka-devops/walletAPI.git where users can:



\* Add money to wallet

\* Withdraw money from wallet

\* Check wallet balance



This capstone project illustrates how multiple developers collaborate using Git.



\# Branching Strategy



```

master      → Production

release     → Pre-production testing

develop     → Integration branch

feature/\*   → Feature development

```



\---



\# Developer Workflow



\### Lead Developer



Responsibilities:



\* Create master repository

\* Define wallet interfaces

\* Implement wallet features



Features implemented:



\* Add Money

\* Withdraw Money



\### Junior Developer



Responsibilities:



\* Implement logging feature



\---



\# Development Workflow



1\. Developers create feature branches from `develop`

2\. Features are implemented and committed

3\. Code is pushed to GitHub

4\. Feature branches are merged into `release`

5\. QA testing occurs on the release branch

6\. Release branch is merged into `master`

7\. Production deployment occurs from master



\---



