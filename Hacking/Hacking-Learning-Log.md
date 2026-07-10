# Hacking Learning Log

This file tracks my practical cybersecurity learning through labs, challenges and hands-on exercises.

---

## Entry 001 - Introduction to Offensive Security

**Platform:** TryHackMe
**Date:** 9 July 2026  
**Room:** Offensive Security Intro  
**Focus:** Web enumeration and hidden application functionality

### What I Learned

Offensive security involves approaching systems from the perspective of an attacker. By understanding how systems can be exploited, security professionals can identify weaknesses and improve their defences.

Ethical hacking applies these techniques within legal and authorised environments to identify vulnerabilities without causing harm.

### Practical Exercise

I completed my first TryHackMe room and performed a basic web enumeration exercise against the fictional FakeBank application.

The objective was to identify hidden functionality within the website that was not accessible through the normal user interface.

I used the `dirb` command-line tool to perform directory and page enumeration:

dirb http://fakebank.thm

DIRB used a wordlist containing common directory and page names and tested these against the target website.

The scan identified a hidden page:

/bank-deposit

This page exposed functionality that allowed funds to be added directly to a bank account.

I accessed the hidden page and used the exposed functionality to modify the balance of the provided account, successfully completing the exercise.
