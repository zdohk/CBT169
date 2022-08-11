~~~~~~~~~~~~~~~~

//***FILE 169 IS A COLLECTION OF UTILITIES FROM KEVIN WILLIAMS      *   FILE 169
//*           OF MEIJER, INCORPORATED IN GRAND RAPIDS, MICHIGAN.    *   FILE 169
//*           INCLUDED ARE A PROBLEM REPORT FOR APPLIED SYSMODS     *   FILE 169
//*           IN ASSEMBLER LANGUAGE, FOR SMP/E RELEASE 5.  THIS     *   FILE 169
//*           REPORT MIGHT HAVE SOME ADVANTAGES OVER IBM'S          *   FILE 169
//*           "REPORT ERRSYSMODS".                                  *   FILE 169
//*                                                                 *   FILE 169
//*        DISCLAIMER                                               *   FILE 169
//*            THESE PROGRAMS WORK FOR ME, BUT NO WARRANTY          *   FILE 169
//*            OR GUARANTEE IS MADE BY ME OR MEIJER, INC.           *   FILE 169
//*            ABOUT THEIR CORRECT OPERATION.  RUN THEM AT          *   FILE 169
//*            YOUR OWN RISK.                                       *   FILE 169
//*                                                                 *   FILE 169
//*            KEVIN WILLIAMS                                       *   FILE 169
//*            MEIJER, INC., 982/2                                  *   FILE 169
//*            2727 WALKER AVENUE NW                                *   FILE 169
//*            GRAND RAPIDS, MI  49504                              *   FILE 169
//*            (616) 791-3621                                       *   FILE 169
//*                                                                 *   FILE 169
//*                                                                 *   FILE 169
//*         MEMBER     DESCRIPTION                                  *   FILE 169
//*         ------     -----------                                  *   FILE 169
//*         $$DOC      THIS MEMBER                                  *   FILE 169
//*                                                                 *   FILE 169
//*         #RTN       STANDARD LINKAGE MACRO BORROWED FROM         *   FILE 169
//*                    THE NASPA VIP TAPE                           *   FILE 169
//*                                                                 *   FILE 169
//*         #SLC       STANDARD LINKAGE MACRO BORROWED FROM         *   FILE 169
//*                    THE NASPA VIP TAPE                           *   FILE 169
//*                                                                 *   FILE 169
//*         FORTUNE    THIS IS AN EDITED FORTUNE COOKIE FILE        *   FILE 169
//*                    FROM AN OLD DEC PDP-11 RSTS/E SYSTEM         *   FILE 169
//*                    THAT I'VE BEEN CARRYING AROUND WITH ME       *   FILE 169
//*                    FOR MORE THAN 10 YEARS.  I'VE CLEANED        *   FILE 169
//*                    IT UP QUITE A BIT AND MADE IT EASY FOR       *   FILE 169
//*                    ANYONE TO FORMAT:  JUST ADD YOUR OWN         *   FILE 169
//*                    .QUOTE AND .ATTR MACROS AND RUN IT           *   FILE 169
//*                    THROUGH YOUR FAVORITE TEXT PROCESSOR         *   FILE 169
//*                    (OR DCF).  I BELIEVE IT CAME FROM AN         *   FILE 169
//*                    OLD DECUS TAPE, SO IT SHOULD BE PUBLIC       *   FILE 169
//*                    DOMAIN.                                      *   FILE 169
//*                                                                 *   FILE 169
//*         PELISTR5   MODIFIED VERSION OF MICHAEL GEARING'S        *   FILE 169
//*                    PELIST PROGRAM FROM FILE 18 OF THE           *   FILE 169
//*                    NASPA VIP TAPE.  I HAVE MODIFIED IT TO       *   FILE 169
//*                    WORK WITH SMP/E RELEASE 5 ZONES.             *   FILE 169
//*                                                                 *   FILE 169
//*         SMLDATA    AN ENTIRE SEASON OF BOWLING SCORES           *   FILE 169
//*                    FOR SMLSTAT                                  *   FILE 169
//*                                                                 *   FILE 169
//*         SMLJCL     SAMPLE JCL TO RUN SMLSTAT                    *   FILE 169
//*                                                                 *   FILE 169
//*         SMLSTAT    BOWLING STATISTICS PROGRAM WRITTEN IN        *   FILE 169
//*                    PL/I.  I WROTE THIS PROGRAM                  *   FILE 169
//*                    SPECIFICALLY FOR MY LEAGUE (SEYMOUR          *   FILE 169
//*                    MEN'S LEAGUE) FOR USE WITH A XEROX           *   FILE 169
//*                    4045 PRINTER, SO IT WILL PROBABLY NEED       *   FILE 169
//*                    TO BE MODIFIED FOR OTHER LEAGUES             *   FILE 169
//*                    AND/OR PRINTERS.  IT'S NOT INCREDIBLY        *   FILE 169
//*                    WELL DOCUMENTED, SO ANYBODY WHO WANTS        *   FILE 169
//*                    TO USE IT AND HAS ANY QUESTIONS SHOULD       *   FILE 169
//*                    FEEL FREE TO CALL ME.                        *   FILE 169
//*                                                                 *   FILE 169
//*         VTOCSCAN   PROGRAM TO SCAN ALL ONLINE DASD VTOCS        *   FILE 169
//*                    FOR NON-ZERO VALUES IN THE FOUR              *   FILE 169
//*                    RESERVED BYTES BEGINNING AT OFFSET           *   FILE 169
//*                    X'4E' IN THE DSCBS.  THIS PROGRAM IS         *   FILE 169
//*                    USEFUL IF YOU RUN THIRD-PARTY DASD           *   FILE 169
//*                    MANAGEMENT SOFTWARE (E.G. DMS) AND ARE       *   FILE 169
//*                    PLANNING TO INSTALL DFP VERSION 3.           *   FILE 169
//*                                                                 *   FILE 169
~~~~~~~~~~~~~~~~

