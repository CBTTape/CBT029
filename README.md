# CBT029
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)
This is still a work in progress. GitHub repos will be deleted and created during this period...
~~~~~~~~~~~~~~~~

//***FILE 029 IS A PROCEDURE TO ENLARGE THE VTOC OF AN ACTIVE       *   FILE 029
//*           PACK FROM MR SAM GOLOB.  THIS FILE IS IN IEBUPDTE     *   FILE 029
//*           SYSIN FORMAT.                                         *   FILE 029
//*                                                                 *   FILE 029
//*           email:  sbgolob@cbttape.org                           *   FILE 029
//*                                                                 *   FILE 029
//*           THIS PROCEDURE PRESENTS A "COOKBOOK-STYLE" RECIPE     *   FILE 029
//*           FOR ENLARGING THE VTOC OF AN ACTIVE DASD PACK.  THE   *   FILE 029
//*           VTOC INDEX HAS TO BE DEACTIVATED FIRST.  EVERYTHING   *   FILE 029
//*           IS HERE, AND ALL THE "INGREDIENTS" IN THE RECIPE      *   FILE 029
//*           ARE ON THIS TAPE.  IT'S AN EASY TO FOLLOW PATH.       *   FILE 029
//*           ONCE YOU'VE DONE IT A FEW TIMES (BEING CAREFUL OF     *   FILE 029
//*           COURSE) IT'S A PIECE OF CAKE.                         *   FILE 029
//*                                                                 *   FILE 029
//*           THE PROCEDURE INVOLVES BUILDING AN EXTENSION TO THE   *   FILE 029
//*           END OF THE EXISTING VTOC.  THEREFORE, ANY DATASETS    *   FILE 029
//*           LYING ON THE TRACKS FOLLOWING THE END OF THE VTOC,    *   FILE 029
//*           HAVE TO BE MOVED OUT OF THE WAY.                      *   FILE 029
//*                                                                 *   FILE 029
~~~~~~~~~~~~~~~~

