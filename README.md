# CBT473
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 473 is from Scott Finlayson, and contains a program to    *   FILE 473
//*           check for all ASID's (address space id slots) that    *   FILE 473
//*           have become non-reusable. The program displays the    *   FILE 473
//*           list of non-reusable ASID's at the console,           *   FILE 473
//*           together with the total number of ASID's defined,     *   FILE 473
//*           and the total number still available.  Tells you      *   FILE 473
//*           when it's time to IPL.  Useful if you're like our     *   FILE 473
//*           shop and wait a long time between IPL's.  Good for    *   FILE 473
//*           a 24x7, or a pseudo 24x7 environment.                 *   FILE 473
//*                                                                 *   FILE 473
//*           Submitted by Ron Robinson.                            *   FILE 473
//*                                                                 *   FILE 473
//*           Sample output for the program follows:                *   FILE 473
//*                                                                 *   FILE 473
//* NON-REUSEABLE ASIDS: 00487 00488 00489 00490 00491 00492 00493  *   FILE 473
//* NON-REUSEABLE ASIDS: 00494 00496 00497 00498 00499 00500 00501  *   FILE 473
//* NON-REUSEABLE ASIDS: 00502 00503 00504 00505 00506 00507 00508  *   FILE 473
//* NON-REUSEABLE ASIDS: 00509 00510 00511 00512                    *   FILE 473
//* ASID MAX = 00528; ASIDS AVAILABLE = 00147; NON-REUSABLES = 00221*   FILE 473
//*                                                                 *   FILE 473
//*           Please note that the ASID numbers displayed by        *   FILE 473
//*           this report are in decimal, and not in hex.  That     *   FILE 473
//*           display should be adeauate for our purposes,          *   FILE 473
//*           because we care, most of the time, about how MANY     *   FILE 473
//*           non-reusables we have, and not their actual numbers.  *   FILE 473
//*                                                                 *   FILE 473
//*           CHKASVT can be run from TSO as well, as a command,    *   FILE 473
//*           but it also puts its output to the system log, at     *   FILE 473
//*           the same time.                                        *   FILE 473
//*                                                                 *   FILE 473
//*           For support inquiries, please email Sam Golob,        *   FILE 473
//*           sbgolob@cbttape.org                                   *   FILE 473
//*                                                                 *   FILE 473
```
