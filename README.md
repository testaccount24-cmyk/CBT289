# CBT289
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 289 IS THE PGM TO GENERATE A PTF TAPE XREF REPORT.  THIS  *   FILE 289
//*           PROGRAM, CALLED PHRANQUE, WILL GENERATE FOUR REPORTS: *   FILE 289
//*                                                                 *   FILE 289
//*     REPORT 01  WILL BE A LIST OF ALL THE PTF'S ON THE TAPE      *   FILE 289
//*                                                                 *   FILE 289
//*     REPORT 02  WILL CONTAIN A LIST OF ALL ELEMENTS              *   FILE 289
//*                (MODULE, MACROS, ETC.) ON THE TAPE AND           *   FILE 289
//*                THE PTF'S THAT REFERENCE THEM                    *   FILE 289
//*                                                                 *   FILE 289
//*     REPORT 03  WILL LIST ALL THE COVER LETTERS ON THE TAPE      *   FILE 289
//*                                                                 *   FILE 289
//*     REPORT 04  WILL LIST ALL THE FMID'S ON THE TAPE AND THE     *   FILE 289
//*                PTF'S THAT REFERENCE THOSE FMIDS                 *   FILE 289
//*                                                                 *   FILE 289
//*     This program will help prevent problems in RECEIVE'ing      *   FILE 289
//*     SMPPTFIN-format data.  You can run the data through this    *   FILE 289
//*     program and find out if you are going to RECEIVE the        *   FILE 289
//*     right PTF's or the wrong ones, BEFORE THEY ARE SEEN         *   FILE 289
//*     BY SMP/E.                                                   *   FILE 289
//*                                                                 *   FILE 289
//*     See also:  Programs PUTXREF and SMPUPD from CBT File 118.   *   FILE 289
//*                                                                 *   FILE 289
//*     Brought up to date (z/OS 2.2) by Sam Golob.  But the        *   FILE 289
//*      original load module runs fine.  No source code changes    *   FILE 289
//*      either.  Just using newer versions of IBM macros and       *   FILE 289
//*      modules (IEFSD095 to make big letters on the printout).    *   FILE 289
//*      Load library included here, in TSO XMIT format.            *   FILE 289
//*                                                                 *   FILE 289
//*         email:  sbgolob@cbttape.org                             *   FILE 289
//*                                                                 *   FILE 289
```
