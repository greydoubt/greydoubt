<!-- 
ROOM
	ID 101
	NOCYBORGS
	NAME "Egyptian Yahtzee"
	PICT "EgyptianZee.gif"
	PICTURE ID 1 NAME "onept.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 2 NAME "diceeg1.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 3 NAME "diceeg2.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 4 NAME "diceeg3.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 5 NAME "diceeg4.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 6 NAME "diceeg5.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 7 NAME "diceeg6.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 8 NAME "yahtholdgold.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 9 NAME "1markgold.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 10 NAME "2markgold.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 11 NAME "3markgold.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 12 NAME "3xmarkgold.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 13 NAME "4scarablights.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 14 NAME "diceeyeofhorus.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 15 NAME "dicescarab.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 16 NAME "diceanubis.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 17 NAME " λx . ophidia ereц grex          .    أوفيديا إريكس جريكس   .arrowll.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 18 NAME " λx . ophidia ereц grex          .    أوفيديا إريكس جريكس   .arrowrr.gif" TRANSCOLOR 0 ENDPICTURE
	SPOT
		ID 1
		OUTLINE 25,150  55,150  55,177  25,177
		LOC 40,162
		PICTS 1,0,0 2,0,0 3,0,0 4,0,0 5,0,0 6,0,0 7,0,0 14,0,0 15,0,0 16,0,0 ENDPICTS
		ENDSPOT
	SPOT
		ID 2
		OUTLINE 66,149  96,149  96,176  66,176
		LOC 81,161
		PICTS 1,0,0 2,0,0 3,0,0 4,0,0 5,0,0 6,0,0 7,0,0 14,0,0 15,0,0 16,0,0 ENDPICTS
		ENDSPOT
	SPOT
		ID 3
		OUTLINE 107,150  137,150  137,177  107,177
		LOC 122,162
		PICTS 1,0,0 2,0,0 3,0,0 4,0,0 5,0,0 6,0,0 7,0,0 14,0,0 15,0,0 16,0,0 ENDPICTS
		ENDSPOT
	SPOT
		ID 4
		OUTLINE 149,150  179,150  179,177  149,177
		LOC 164,162
		PICTS 1,0,0 2,0,0 3,0,0 4,0,0 5,0,0 6,0,0 7,0,0 14,0,0 15,0,0 16,0,0 ENDPICTS
		ENDSPOT
	SPOT
		ID 5
		OUTLINE 190,149  220,149  220,176  190,176
		LOC 205,161
		PICTS 1,0,0 2,0,0 3,0,0 4,0,0 5,0,0 6,0,0 7,0,0 14,0,0 15,0,0 16,0,0 ENDPICTS
		ENDSPOT
	SPOT
		ID 6
		OUTLINE 230,149  260,149  260,176  230,176
		LOC 246,161
		PICTS 1,0,0 2,0,0 3,0,0 4,0,0 5,0,0 6,0,0 7,0,0 14,0,0 15,0,0 16,0,0 ENDPICTS
		ENDSPOT
	SPOT
		ID 13
		DONTMOVEHERE
		OUTLINE 116,24  170,24  170,40  116,40
		LOC 156,33
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL
myturn GLOBAL
{ dd STRTOATOM EXEC 0 GET crv = ME co =
"@167,34 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 14
		DONTMOVEHERE
		OUTLINE 116,41  170,41  170,56  116,56
		LOC 156,49
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL
myturn GLOBAL
{ dd STRTOATOM EXEC 1 GET 2 * crv = ME co =
"@167,51 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 15
		DONTMOVEHERE
		OUTLINE 116,57  170,57  170,73  116,73
		LOC 156,66
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL
myturn GLOBAL
{ dd STRTOATOM EXEC 2 GET 3 * crv = ME co =
"@167,66 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 16
		DONTMOVEHERE
		OUTLINE 116,74  170,74  170,90  116,90
		LOC 156,83
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL
myturn GLOBAL
{ dd STRTOATOM EXEC 3 GET 4 * crv = ME co =
"@167,84 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 17
		DONTMOVEHERE
		OUTLINE 116,91  170,91  170,107  116,107
		LOC 156,100
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL
myturn GLOBAL
{ dd STRTOATOM EXEC 4 GET 5 * crv = ME co =
"@167,100 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 18
		DONTMOVEHERE
		OUTLINE 116,108  170,108  170,123  116,123
		LOC 156,116
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL
myturn GLOBAL
{ dd STRTOATOM EXEC 5 GET 6 * crv = ME co =
"@167,117 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 19
		DONTMOVEHERE
		OUTLINE 311,7  366,7  366,22  311,22
		LOC 343,16
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dd "[3456]" GREPSTR dt * crv =
 ME co =
"@343,18 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 20
		DONTMOVEHERE
		OUTLINE 311,23  366,23  366,40  311,40
		LOC 343,32
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dd "[456]" GREPSTR dt * crv =
 ME co =
"@343,33 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 21
		DONTMOVEHERE
		OUTLINE 311,41  366,41  366,56  311,56
		LOC 343,49
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dd "[56]" GREPSTR dt * crv =
 ME co =
"@343,51 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 22
		DONTMOVEHERE
		OUTLINE 311,57  366,57  366,72  311,72
		LOC 343,65
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dd "3.*3" GREPSTR 35 *  crv =
 ME co =
"@343,67 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 23
		DONTMOVEHERE
		OUTLINE 311,73  366,73  366,88  311,88
		LOC 343,81
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dd "4" SUBSTR dd "2" SUBSTR AND 35 *  crv =
 ME co =
"@343,82 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 24
		DONTMOVEHERE
		OUTLINE 311,106  366,106  366,121  311,121
		LOC 343,114
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dt crv = ME co =
"@343,117 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 25
		DONTMOVEHERE
		OUTLINE 465,25  509,25  509,40  465,40
		LOC 500,32
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dd " [123] [123] [123] [123] " GREPSTR 25 *  crv =
 ME co =
"@500,32 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 26
		DONTMOVEHERE
		OUTLINE 465,41  509,41  509,57  465,57
		LOC 500,49
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dd " [12] [12] [12] [12] [12] " GREPSTR 40 *  crv =
 ME co =
"@500,49 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 27
		DONTMOVEHERE
		OUTLINE 465,58  509,58  509,74  465,74
		LOC 500,66
		PICTS 1,0,0 9,0,0 ENDPICTS
		SCRIPT
ON SELECT { dd GLOBAL crv GLOBAL co GLOBAL dt GLOBAL
myturn GLOBAL
{ dd " 1 1 1 1 1 1 " GREPSTR 50 *  crv =
 ME co =
"@500,66 That will give you a score of " crv ITOA & LOCALMSG
} myturn ME GETSPOTSTATE NOT AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 28
		DONTMOVEHERE
		OUTLINE 311,89  366,89  366,105  311,105
		LOC 343,97
		PICTS 1,0,0 9,0,0 10,0,0 11,0,0 12,0,0 12,0,0 12,0,0 12,0,0 12,0,0 12,0,0 12,0,0 12,0,0 12,0,0 12,0,0 12,0,0 12,0,0 ENDPICTS
		SCRIPT
ON SELECT { yhtz GLOBAL co GLOBAL dd GLOBAL myturn GLOBAL
crv GLOBAL mysc GLOBAL btt GLOBAL
{ dd "6" SUBSTR yts =
   {
    { "Sorry, you zeroed out your Yahtzee-6 line earlier- you are ineligible for a bonus." LOCALMSG
    } yts yhtz 0 < AND IF
    { ")applause " USERNAME " collects a Yahtzee-6 bonus!" & & ROOMMSG
      "@511,0 Joker rules-- you get to score it on a regular line as well!" LOCALMSG
       200 mysc += ME GETSPOTSTATE 1 + ME SETSPOTSTATE
      1 btt = yhtz ++
    } yts yhtz 0 > AND btt NOT AND IF
   }
   { ;yahtzee for the first time, -1 if yts is 0, 1 if yts is 1
     yts 100 * crv = ME co =
     "@343,101 This will score you a " crv ITOA & LOCALMSG
     { "!WARNING: zeroing out this box makes you ineligible for Yahtzee-6 bonuses!" LOCALMSG
     } crv NOT IF
   } yhtz IFELSE
} myturn IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 29
		DONTMOVEHERE
		OUTLINE 454,77  483,77  483,101  454,101
		LOC 491,91
		PICTS 1,0,0 9,9,0 ENDPICTS
		SCRIPT
ON SELECT { ut GLOBAL myturn GLOBAL
{
 { "@491,91 You need " 80 ut - ITOA & " more points to get the upper table bonus" & LOCALMSG }
 { "@491,91 You already have the upper table bonus!" LOCALMSG
 } ME GETSPOTSTATE NOT IFELSE
} myturn IF
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 12
		DONTMOVEHERE
		OUTLINE 232,140  266,140  266,184  232,184
		LOC 245,162
		PICTS 1,0,0 8,0,0 ENDPICTS
		SCRIPT
ON SELECT { myturn GLOBAL
{ ME GETSPOTSTATE NOT ME SETSPOTSTATE
} myturn 32 GETSPOTSTATE AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 11
		DONTMOVEHERE
		OUTLINE 184,140  231,140  231,184  184,184
		LOC 205,162
		PICTS 1,0,0 8,0,0 ENDPICTS
		SCRIPT
ON SELECT { myturn GLOBAL
{ ME GETSPOTSTATE NOT ME SETSPOTSTATE
} myturn 32 GETSPOTSTATE AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 10
		DONTMOVEHERE
		OUTLINE 141,140  184,140  184,184  141,184
		LOC 164,162
		PICTS 1,0,0 8,0,0 ENDPICTS
		SCRIPT
ON SELECT { myturn GLOBAL
{ ME GETSPOTSTATE NOT ME SETSPOTSTATE
} myturn 32 GETSPOTSTATE AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 9
		DONTMOVEHERE
		OUTLINE 99,140  141,140  141,184  99,184
		LOC 122,162
		PICTS 1,0,0 8,0,0 ENDPICTS
		SCRIPT
ON SELECT { myturn GLOBAL
{ ME GETSPOTSTATE NOT ME SETSPOTSTATE
} myturn 32 GETSPOTSTATE AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 8
		DONTMOVEHERE
		OUTLINE 58,140  99,140  99,184  58,184
		LOC 81,162
		PICTS 1,0,0 8,0,0 ENDPICTS
		SCRIPT
ON SELECT { myturn GLOBAL
{ ME GETSPOTSTATE NOT ME SETSPOTSTATE
} myturn 32 GETSPOTSTATE AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 7
		DONTMOVEHERE
		OUTLINE 17,140  58,140  58,184  17,184
		LOC 40,162
		PICTS 1,0,0 8,0,0 ENDPICTS
		SCRIPT
ON SELECT { myturn GLOBAL
{ ME GETSPOTSTATE NOT ME SETSPOTSTATE
} myturn 32 GETSPOTSTATE AND IF
}
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 31
		NAME "Start Game"
		DONTMOVEHERE
		LOC 459,27
		SCRIPT
ON ENTER { { "A game of yahtzee is currently being played- click play to join!" LOCALMSG } ME GETSPOTSTATE WHONAME "." GREPSTR IF
{ 0 ME SETSPOTSTATE } ME GETSPOTSTATE WHOME == IF
{ POSX 160 RANDOM 224 + SETPOS } POSY 225 < IF
ad GLOBAL "" ad =
"Script by Foxy, ©2003 Graphics by Tybalt & Speck ©2003" STATUSMSG
"For free distribution only!" LOGMSG
{ DUP GLOBAL 0 SWAP =
} [ ref rollt crv mysc ut yhtz plyrs ckbxs myturn co lastroll] FOREACH
al27 GLOBAL
{ dt GLOBAL dd GLOBAL lastroll GLOBAL
  { { EXEC SETSPOTSTATE
    } lastroll STRTOATOM EXEC FOREACH
  } lastroll 0 != IF
    0 dt = [ 0 0 0 0 0 0 ] dd =
   "[ " lastroll =
 { dc = dc 6 + GETSPOTSTATE lck =
  { 6 RANDOM 1 + dv = dv dc SETSPOTSTATE }
  { dc GETSPOTSTATE dv = } lck NOT IFELSE
  dv dt += dd dv 1 - GET 1 + dd dv 1 - PUT
  lastroll "{" + dv ITOA + " " + dc ITOA + " }" + lastroll =
 } [ 1 2 3 4 5 6 ] FOREACH
"[ " { ITOA + " " + } dd FOREACH
" ]" & dd =
lastroll "]" + lastroll =
{ "@105,268 )applause !YAHTZEE-6!!" ROOMMSG
} dd "6" SUBSTR IF
} al27 DEF
 al26 GLOBAL
{ rollt GLOBAL dd GLOBAL dt GLOBAL
crv GLOBAL 0 crv = co GLOBAL 0 co =
{ ")dice2" SAY } rollt 6 == IF
{ 0 cr = rollt --
 { cr ++
  { 7 rollt cr + DUP 3 / 3 * - + cr SETSPOTSTATE
  } cr 6 + GETSPOTSTATE NOT IF
 } { cr 6 < } WHILE
 al26 GLOBAL al26 30 ALARMEXEC
}
{ al27 GLOBAL al27 EXEC
} rollt IFELSE
} al26 DEF
al24 GLOBAL
{ plyrs GLOBAL hsc GLOBAL phsc GLOBAL ref GLOBAL
{  { "@0,100 !Game over!" ROOMMSG
   { "@100,100 ..and our winner is: " ROOMMSG
    "@160,160 )applause !" phsc & "!!" & ROOMMSG
   } hsc IF
   0 ref = 1 sp =
 { 0 sp SETSPOTSTATE sp ++ } { sp 33 < } WHILE
{ ";ź5" SAY } 60 ALARMEXEC
  } plyrs "." GREPSTR NOT IF
} ref IF
} al24 DEF
al25 GLOBAL
{ plyrs GLOBAL al25 GLOBAL al24 GLOBAL
plyrs "^-([0-9]+)-(.*)$" GREPSTR POP
"$1" GREPSUB cp = "$2" GREPSUB oth =
{ oth GREPSUB plyrs = plyrs "^-([0-9]+)-(.*)$" GREPSTR POP
   "$1" GREPSUB cp = "$2" GREPSUB oth =
} { cp ATOI WHONAME "." GREPSTR NOT plyrs "" == NOT AND } WHILE
{ "@" cp ATOI WHOPOS ITOA SWAP ITOA " " & SWAP & & cp ATOI WHONAME " is up!" & & ROOMMSG
  ";ź3" cp & cp ATOI PRIVATEMSG
  oth "-" & cp & "-" & plyrs =
}
{ al24 30 ALARMEXEC
} plyrs "" == NOT IFELSE
} al25 DEF
}
ON SELECT { ref GLOBAL plyrs GLOBAL ad GLOBAL hsc GLOBAL phsc GLOBAL
{ { "A game is currently in session. Click play to join." LOCALMSG }
  { "Resetting game, click again to start a new one." LOCALMSG
    0 ME SETSPOTSTATE ";ź5" SAY
   { cr ++ 0 cr SETSPOTSTATE } { cr 29 < } WHILE
  } ME GETSPOTSTATE WHONAME "." GREPSTR IFELSE
}
{ WHOME ME SETSPOTSTATE 1 ref = "" plyrs = "-" ad = 0 hsc = "" phsc =
 USERNAME " has started a game of Yahtzee-6! Click play to join!" & ROOMMSG
 "@511,0" USERNAME & ", click the roll button to start play after everyone joins." & LOCALMSG
} ME GETSPOTSTATE IFELSE
}
ON INCHAT { ref GLOBAL plyrs GLOBAL phsc GLOBAL hsc GLOBAL
{
 { DUP GLOBAL 0 SWAP =
 } [ ref rollt crv mysc ut yhtz plyrs ckbxs myturn co phsc hsc btt lastroll] FOREACH
 "" plyrs =
} CHATSTR ";ź5" == IF
{ 0 ref = "" plyrs = "" phsc = 0 hsc =
} ref WHOME ME GETSPOTSTATE <> AND IF
;26 inchat
 mysc GLOBAL ckbxs GLOBAL ut GLOBAL yhtz GLOBAL
rollt GLOBAL myturn GLOBAL co GLOBAL dd GLOBAL dt GLOBAL
{ { 0 SWAP SETSPOTSTATE } [ 7 8 9 10 11 12] FOREACH
 1 myturn = 13 sp = ckbxs tckbxs =
{ tckbxs DUP 2 / 2 * - sp SETSPOTSTATE
  2 tckbxs /= sp ++
} { sp 28 < } WHILE
{ 1 28 SETSPOTSTATE
{ yhtz 28 SETSPOTSTATE } yhtz 1 > IF
}
{ 0 28 SETSPOTSTATE } yhtz IFELSE
0 32 SETSPOTSTATE 0 crv = 0 co =
"[]" dd = 0 dt =
ut 80 >= 29 SETSPOTSTATE
{ 0 SWAP SETSPOTSTATE } [ 1 2 3 4 5 6 ] FOREACH
} ";ź3" WHOME ITOA & CHATSTR == IF
;25 inchat
 ref GLOBAL plyrs GLOBAL ad GLOBAL
mysc GLOBAL ckbxs GLOBAL ut GLOBAL yhtz GLOBAL
plyrs GLOBAL hsc GLOBAL phsc GLOBAL al25 GLOBAL
ad "." GREPSTR stt =
{ "-" WHOCHAT ITOA & "-" & ad =
 { "You're already in the game, " WHOCHAT WHONAME &
   WHOCHAT PRIVATEMSG
 }
 { WHOCHAT WHONAME " has joined the game!" & ROOMMSG
  ";ź2" WHOCHAT ITOA & WHOCHAT PRIVATEMSG
  ad plyrs & plyrs =
 } plyrs ad SUBSTR IFELSE
{ "" ad = } stt NOT IF
} CHATSTR ";ź1" == ref AND IF
{ ;initialize variables to play
0 mysc = 0 ckbxs = 0 ut = 0 yhtz =
} CHATSTR ";ź2" WHOME ITOA & == IF
{ al25 90 ALARMEXEC
} ";ź3" CHATSTR == ref AND IF
{ "-$1-" GREPSUB pq =
  "$2" GREPSUB ATOI ps =
  ")applause !" "$1" GREPSUB ATOI WHONAME " has finished with a final score of " & &
  "$2!" GREPSUB &  ROOMMSG
   { "@150,0 !New high score for the game!" ROOMMSG
    "$1" GREPSUB ATOI WHONAME phsc = ps hsc =
   } ps hsc > IF
  plyrs "^(.*)" pq & "(.*)$" & GREPSTR POP
  "$1$2" GREPSUB plyrs =
  al24 GLOBAL al24 60 ALARMEXEC al25 120 ALARMEXEC
} CHATSTR "^;ź4([0-9]+)-([0-9]+)$" GREPSTR ref AND IF
{ { "$1$2" GREPSUB plyrs =
    WHOCHAT WHONAME " has left the game." & ROOMMSG
{ al25 EXEC } "$2" GREPSUB "" == IF
  } plyrs "^(.*)-" WHOCHAT ITOA "-(.*)$" & & GREPSTR IF
} CHATSTR ";ź6" == ref AND IF
}
ON OUTCHAT { { "" CHATSTR = } CHATSTR "^;ź" GREPSTR IF
 ref GLOBAL plyrs GLOBAL al25 GLOBAL
 { "" CHATSTR =
  plyrs "^(.*)-[0-9+]-$" GREPSTR POP
  "$1" GREPSUB plyrs = al25 25 ALARMEXEC
 } ref CHATSTR "player drop" == AND IF
 { "" CHATSTR = plyrs tp = 0 ps =
   "Current players:" LOGMSG
   { ps ++ ps ITOA ". " & "$1" GREPSUB ATOI WHONAME & LOGMSG
     "$2" GREPSUB tp =
   } { tp "^-([0-9]+)-(.*)$" GREPSTR } WHILE
 } ref CHATSTR "player list" == AND IF
}
ON LEAVE { ";ź6" SAY }
		ENDSCRIPT
		ENDSPOT
	SPOT
		ID 32
		NAME "Start - Play - Roll - Quit - Instructions"
		DONTMOVEHERE
		OUTLINE 303,140  504,140  504,184  303,184
		LOC 392,156
		PICTS 13,79,-39 13,98,-39 13,117,-39 13,136,-39 1,0,0 ENDPICTS
		SCRIPT
ON SELECT { MOUSEPOS POP ys =
0 ss =
{ ys < ss += } [ 341 383 423 464 ] FOREACH
[
;"Start"
{31 SELECT}
;"Play"
 { myturn GLOBAL btt GLOBAL lastroll GLOBAL
 { co GLOBAL crv GLOBAL mysc GLOBAL ut GLOBAL ckbxs GLOBAL
    dd GLOBAL yhtz GLOBAL
  { crv mysc +=
    0 btt =
    { { "@491,91 !UPPER TABLE BONUS!" ROOMMSG
        50 mysc +=
      } ut 80 < crv ut + 80 >= AND IF
      crv ut +=
    } co 19 < IF
    "I have a score of " mysc ITOA & SAY
    { 1 co SETSPOTSTATE } co 28 < IF
    { 1 co SETSPOTSTATE dd "6" SUBSTR 2 * 1 - yhtz =
    } co 28 == yhtz NOT AND IF
    12 cs = 0 ckbxs = 1 vl =
    { cs ++ cs GETSPOTSTATE ckd = { 1 ckd = } cs co == IF
      { vl ckbxs += } ckd IF 2 vl *=
    } { cs 27 < } WHILE
   0 myturn =
   { ";ź3" SAY }
   { ; { 50 mysc += } ut 80 > IF
      ";ź4" WHOME ITOA & "-" & mysc ITOA & SAY
    { DUP GLOBAL 0 SWAP =
    } [ rollt crv mysc ut yhtz ckbxs myturn co btt ] FOREACH
   } ckbxs 32767 < yhtz NOT OR IFELSE
 } co IF
 }
 { ";ź1" SAY "dice2" SOUND } myturn IFELSE
}
;"Roll"
 { ref GLOBAL ad GLOBAL rollt GLOBAL crv GLOBAL myturn GLOBAL al25 GLOBAL
{ "" ad = al25 EXEC }
{ { { ME GETSPOTSTATE 1 + ME SETSPOTSTATE
     6 rollt = 0 crv =
     al26 GLOBAL al26 EXEC
    }ME GETSPOTSTATE 4 < IF
  } myturn IF
} ref ad ".." GREPSTR AND IFELSE
}
;"Quit"
 { ref GLOBAL ";ź6" SAY
{ { DUP GLOBAL 0 SWAP =
  } [ rollt crv mysc ut yhtz ckbxs myturn co btt lastroll] FOREACH
}
{";ź5" WHOME PRIVATEMSG } ref IFELSE
}
;"Instructions"
 {
"Instructions are in your log" STATUSMSG
{ LOGMSG } [
"" "***YAHTZEE 6 RULES***" ""
"Six dice, four rolls!"
"Upper Table, Triples, Quads, Short & Full Straights, & Chance:"
"  --all qualify the same as regular Yahtzee"
"Yahtzee is now 6 of a kind"
"Pents is five of a kind"
"Six Straight is 1, 2, 3, 4, 5, and 6, in any order"
"Full House is 2 of a kind and 4 of a kind"
"Half House is 3 of a kind and 3 of a kind"
"Upper Table Bonus is fifty points when you score eighty in the upper table"
"Check the board for other score changes!"
"" "***General Play***" ""
"To start a Yahtzee game, one person clicks on the start game button and becomes the referee."
"Everyone who wants to play- including the referee- clicks on the Play button to join the game."
"When everyone has joined, the referee clicks the Roll button to start play."
"Anyone can join at any time by clicking play."
"Anyone who wants to quit can click the quit button to do so."
"Anyone who leaves the room automatically quits!"
"If the referee leaves the room, the game is over!"
"Click on the start game button to reset the game if that happens."
"When play starts, the person whose turn it is clicks roll to roll for the first time and get their dice."
"You lock and unlock the dice by clicking on them, locked dice are marked."
"Click on the score sheet in the blank spot you want to score in, or click roll up to thrice more."
"When you click on the score sheet, it tells you what you'll score with that option. If you like it, click Play to score that and finish your turn."
"Clicking on the Upper Table Bonus Status box tells you how many points you need to get that bonus"
"Scoring YAHTZEES- you score your first yahtzee the same way you score other scores, by clicking on yahtzee and then play. Score Yahtzee bonuses automatically by first clicking on Yahtzee when you roll one."
"When someone fills out their score card, they automatically give their final score."
"Stick around after you're through- the referee remembers the highest score, and will announce it when everyone finishes!"
"Players can click play to rejoin an ongoing game after they finish. In that case the game continues until everyone either quits or finishes their game."
"" "***Referee Commands" ""
"\x22Player Drop\x22 removes the current player from play and goes to the next one"
"\x22Player List\x22 produces a list in your log of all current players"
"NOTE: it is highly recommended that the referee have the new palace client!"
] FOREACH
}
] ss GET EXEC
		ENDSCRIPT
		ENDSPOT
	DOOR
		ID 32
		DONTMOVEHERE
		DEST 126
		OUTLINE 4,354  62,354  62,380  4,380
		LOC 33,366
		PICTS 17,0,0 ENDPICTS
		ENDDOOR
	DOOR
		ID 33
		DONTMOVEHERE
		DEST 269
		OUTLINE 448,354  508,354  508,379  448,379
		LOC 480,368
		PICTS 18,0,0 ENDPICTS
		SCRIPT
ON INCHAT { nDoIt GLOBAL nDoIt EXEC }
ON ENTER { { CLEARLOOSEPROPS PAINTCLEAR } NBRROOMUSERS 2 < IF }
		ENDSCRIPT
		ENDDOOR
	ENDROOM


-->
ł`જોહરીiorno!!! My name is łSO 9 KNAB 1995(1.0) 2003(2.0)

or as they say on Płanet Irakkis,  Zainab ał Javascript bin H'OLLYw(̵̨̤͕̺͍̮͙̥͖̏̀̔̽͊̆̈̉͡g̭͓͇̤͖͛͑̃̒̏̀̚͡ḻ̡̡͚̎̀̃͂͆͑̒͢͝a̵̧̺͕͙͙̦̗̔̔̐̊̈́̋͜ͅg̷̡͓̫͉̦͍̳͗͗̿̆̿́͟͟  ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞ ê̷͔̻̜͔̄̑̉̏̌̑̒̈́̕͜͜ͅ ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞DD.js


ǯ̷̨̣̰͈̲̮̈́̈́̈́̓̄̊̈́͡′̵̡̨̬͎̙͋̐̂̇̀͊͋͊̊͒ ḑ̷͚̙̰̋́͑̿̕͜͟z̴̧̬̰̙̹̪̬͎͗͋̈́̓͌̒̅̾͟  ʒ̸͈͙̱̙̹̎́̀̔̋̈́́͘͟ d̵̘̟̼͓̮̄͒̊̒̎́̑̒͌̚z̛̛̼͚̬̱͙͒̒̇̌̓́̒̚͜͢ͅư̶͇̞̤̻̫̓́͑͌̃̑͟  ʒ̴̧̨̧͖͖̼̫̙͗͗́̓͌͢͜°̬̥̰͎̰͌̑̈́̋̆͑͒͟͝͞h̸̢̜̞͎͓̯̉̌͑̉́͆͞ư̶̧̧̙̟̤̟͇͍̆̋̄̉̃̂͛͗̕  Є̸̠̮̺̣̗̭̭̥̘̀͆͋͟͡͠͝w̷̡̜̩͎̮͚̥̺͍̰͐̍͛̄̌͠͞ダ̶̲̮̜̪͍͖͓́͊̃̀̀͑̈͑̕͠h̳̼͉̘̙̉̍̎̀͊͗̕͞′̠͕͙͚́̓̉̅͜͠′̛̗͖͈͔̦̠͉͓̾̔̓͊͌ラ̶̡̛̻̫̼̞̥̃̀̇̓̇͛͋͝͡a̶̧̟̜̯͇̘͉̥͐̃̒̆̿̀̃̔͡͠z̷̘͙̟͔̙̘̽̀́̀͋͟ŭ̸̙̤̯͇̺̞̉́̿̅̊͂̽б̶̨͕̬͓̐̂̈̍̾̚͟͠͞о̛̬̯̻͙͖͓̗̥͂̏̎̾̿̿̌ͅу̡̥̮̰͍͖͒͂͐͋̋͊͢к̷̯͙̯̪̬͌̌̓̉̌̓̅̈͌ꙑ̶̡̨̥͚͎̭͌̓͋̓̏́́̑b̛̝̼̜͙̭͌͋̈̾̆́̇̏͢u̧̧͚̺̙̟̪̹͕͑͒́̀̌̋̎͝k͇̗̻̞̗̹̅̊̃̈́̅̄̂y̴̧̡̬̳͉̦̗̻̪̓͒̌͐̄̕͠г̢̟̥̯̜̭͎̮̤̅͛̄̿̿͊̚͝͞л̴͎͇͕̯͕̞͖̊̓̍̔͑́͠͝а̨̛̱̳͖̗̯̫͗́̄̓г̢͓̠͇͎̘̝͑̃̓̓̓͟͢͠ӧ̶̧̢͍̠̜̰̩̫̜͛̐̆̂͘л̧̪̩̺̯̭́̍̌͘͜͜͜͡͝ѝ̷̹͙̝̞͓̹̤̟͋͑͂̀͊͌͐͘͢͠   (̵̨̤͕̺͍̮͙̥͖̏̀̔̽͊̆̈̉͡g̭͓͇̤͖͛͑̃̒̏̀̚͡ḻ̡̡͚̎̀̃͂͆͑̒͢͝a̵̧̺͕͙͙̦̗̔̔̐̊̈́̋͜ͅg̷̡͓̫͉̦͍̳͗͗̿̆̿́͟͟ǫ̸̟̻̺͙̼̗͂͑̍͋͋͑́͛̕͝l̡̦͕̣̪̇̒̑͐́̓͘͜͠͠ͅͅi̷͔̳͍̳̘̪̻̇̌̇̂͂̽)̛̫̮͖̪̯̇͛̒͡ͅ  e̖͇̜̳̲͍̔̅̆̒̍̓͞ ê̷͔̻̜͔̄̑̉̏̌̑̒̈́̕͜͜ͅ ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞ —͉̯͓͌̿͆́͋̄͜͟͡  z̸̡̛͉͖̠̦̬̺̓̈́͛͒͜h̸͙̘̫̻̠͕̺̥̅̂̐̎̌̍̈́͂͘͝ ž̷̧̠̤̖̗͎͚̖͖̘̈́̂̿̾̊̾͠  z̵͙̜͚͚͍̤̖͓͎̆̇̀͛̌͋͋̕͠͠h̸̡̢̨͉̼͔̝̋̏̿͑̓͑͟ͅ′̡̡̟̬͍̿̀͋͗͆̿͘′̲̺̣̫̻̥̤̝̯̬͗͂̾̒̇̿̎̾  ẑ̛͚͚̼̳̠͖̋̒̊̀́  z̥̫̠̯͚̭͓̪̱̆́͗̈͛̄͜h̶̡̤̺͈͙̟͆̈́̇́̈́̀′̦͈͇͇͎̭͎͗͋̄̄̎̂̿̃̓͝′̸̤̮̘̹̊̀̇̄͑̇͞ͅu̸̼͔̰̯̖̐͆͗̏͐̾͡ͅ  ẑ̷̛̲̭͉̪̜̯͌̍̅̿́͢͠ͅ°̵̺̹̫̹͙͇͆̉̋̎̇̿͂͟͞͝  z̨̧̡̼̫͒̿̅̋̚h̴̛̻͇̟̫͈͉͚̀͆̌̐̀̌̈́͡ͅ′͍̠̤͉͓̦̦̦̻́͒͐͌̆̀͡ͅ  ž̴͚̳̞̙͙͖̙͈̏̅̾͋͊͋̈̋͗͢′̨̟͉͔͙̐̅̓̃̀̕͟͠ z̦̬̠̳̻̃͂͋̎́̔͢͢͝ͅ ẕ̸̼̭̙̼̥̠̼̊̂̐͂͂̀͒͜͜͝  ḯ̻̖̮̦͕͊̇͋̂͂͜͝ĭ̙̟͕͈̪̝̤͎̓̅̀̔̎̊̀̐̅͂͢͜ j̷̺̺̰̺̠͎̮̣̘̄͑͗̆͂̏͆ k̵̡̬͔̬̩͇̤͐͊̅͆̃ͅ  —̷̢̛̜̬͔̖̳͆̇̐̀̚͢͠ k̶̛̭̮̝̹̹̬͌̈́͋͜͟͞u̵̧̠̠͍͖͗́̆̉̄͘  k̸͎͈̣̦͌̂̏͋̊͒͢͡°̴̧̰̮̺̮̙̲̯̤̠̊̊̂̿̎̓͋  ķ̘͔̤̠̪̟̮͌̌͑̎̈̊̕′̳̱̞̥͕̥̀̄̽̏̂́̾͞′̴̧̱̖͉̗̾̏͆̾̍͆͌͞͠ͅ q̶̨̩̝̞͙͛̓̒͋͒  ķ̮̠͕̹̩̤̀̉̄̎̕͘̕͢′̨̧͖͇͈̳̣͆̑̑͂́͊͜͡′̥̳̥̦͈̫́̄́̍̔̽̑͞ứ̵͈͔̭͍͓̲͔͙͚́̆̊̏̚͠͡  q̵̢̛̼̥̭̪̼̆͋̂̑̅̚͠°͖̹̲̻̣͍̹͇́͋́̒̓͆͂̆͛͗ k̴̡̺̙͕͉̯̖̯͎͒̏̊͡͝ḣ̷̨̯̜̠̻̿͊͑̎̀͟  č̵̡̨̘͖̥͕͉̔̅̀̅͡͠′̵̸̡̡̛̳̹̰̰̲̣̲̞͕̝͇̟̩̀̀̍̈́̃̊̓̍̓̉̃̉̋͠  ḱ̵̛̛̻̗̻͉͓̀͒͞ḣ̷̭̮̰̙̞̜͎͔̪̜̔̂̈́̾̌̋̋̈́͝u̧̦̲͍̦̯̱̐̅̃̕͞  ḳ̶̡͖̮̖̹̻͐́́̀̔̇̄̑͑͢͝ͅ°̢̢̼̜͍͇͂͗͗̾̒̚ ḽ͉̰̱͈̳̺̰̮̊̍̐̏͆̌̐̕̚  l̵̨̡̛̻̻̺͚͚̤̯̺̈́̊̒̍͛͒͠ l̩̤̬̰̹̘̔̾̍̓̔̚͟′̡̭̖̼̙̩̼͆͑̃͆͆̏̽̄̾̕′̷̢͚͍̟̠͍̖̐́͋̿̓̍͂̆̍  ł̰̬̩̪̥̘̜͙̾̃͗̎̆̓̄̕͜͝͡ l̨̢̥͉̎̍̅̐̚͜͟ḣ̨̘̭̼̜͇̹͓̹̊̀̽͛̎̒̚͞͝  ḷ̡͕͍͎̥̣͚̣̞͉̐̿̇̃̄͊͂̅͘q̨̢͓̣̦̦͙̤́̃̀́̀̑̆w̵͖̥͓͚̽̾͒̀͒͘ͅͅλxǯ̷̨̣̰͈̲̮̈́̈́̈́̓̄̊̈́͡′̵̡̨̬͎̙͋̐̂̇̀͊͋͊̊͒ ḑ̷͚̙̰̋́͑̿̕͜͟z̴̧̬̰̙̹̪̬͎͗͋̈́̓͌̒̅̾͟  ʒ̸͈͙̱̙̹̎́̀̔̋̈́́͘͟ d̵̘̟̼͓̮̄͒̊̒̎́̑̒͌̚z̛̛̼͚̬̱͙͒̒̇̌̓́̒̚͜͢ͅư̶͇̞̤̻̫̓́͑͌̃̑͟  ʒ̴̧̨̧͖͖̼̫̙͗͗́̓͌͢͜°̬̥̰͎̰͌̑̈́̋̆͑͒͟͝͞h̸̢̜̞͎͓̯̉̌͑̉́͆͞ư̶̧̧̙̟̤̟͇͍̆̋̄̉̃̂͛͗̕  Є̸̠̮̺̣̗̭̭̥̘̀͆͋͟͡͠͝w̷̡̜̩͎̮͚̥̺͍̰͐̍͛̄̌͠͞ダ̶̲̮̜̪͍͖͓́͊̃̀̀͑̈͑̕͠h̳̼͉̘̙̉̍̎̀͊͗̕͞′̠͕͙͚́̓̉̅͜͠′̛̗͖͈͔̦̠͉͓̾̔̓͊͌ラ̶̡̛̻̫̼̞̥̃̀̇̓̇͛͋͝͡a̶̧̟̜̯͇̘͉̥͐̃̒̆̿̀̃̔͡͠ḉ̡̣̮̜̗͖̞͕̊̌̽̅͌͞͝,̵̨̬̲͓̯̝͉͋̔̓͑́̂̑ķ̡̗̖̠͓͛͒̾̕͘͡  (̶̨̡̠͈̝̳̫͉͗̆̌͗̽̚2̪̮̥̣̩͔̺͚̗͗̀͛̐͗̽̍ͅ.̷̡̧̥͉̺̺͖͖̭̀̅̾͊̕͝2̧̤̭̹͈͈̭̌̔̀̃͐͟͞͞)̸̢̳͕̦̰̤̲̄̈̊́̒͝ч̨̳̭͍̬̞͍̹̏̂̀͂̿̀͠͠Ӏ̡̫̟̖̲́̐͋͑͡k̙̦̜̖͎̯͕̄̿́̇͐͌̈́̔͠  k̸̢͚͕̔̒̍͛̈̋͐͐͜͠͡ͅư̴̢̫͈̘̣̖̰̝̂̇͗̈́̾̀́͜͞͝ͅ  ž̧̧̮̲̘̩̽̿̇̅̔͘͟′̺̞͓̥̳̰̾̎́̓͞ͅ′͈̳͇͙͈͈̠͐̀̇̑̍̅̾̎͞ͅư̶̡̤͓͈̪͉̠̭̣̈̽̾͋͐̇̉͟͠͞  ž̫̝̦̘̺̦̭̏̇̓͒͢͝͠′͈̰̺̖̪̦̞̀̔̇̓͋̃̏͜͡͠i̢̧̨̖̇̇̀̀̇͟͟͜͠u̸̡̧̫̱͕͔̱̥͍̬͈̩͇̒͋̓̏͐̈̆́͂͒͊̆̕̕̕͟͡͠͡͡  —̝̣̜͙̝̳̰̥̖̅̈́͑̀̾́̊̕͘͞  Є̶̨̗̠̳̜̪̯̬̜̰̒͋̄͋̀ǐ̴̡̪͖̰̜͉͒̎̌̌͞͠ą̵̴̧̛̠̞͈̳̗̥̳̘̪̻͗̑͑́́͆̽̆͊̍̎̂͘̚͘͡͡  —̤̫̖̣̪̫̿͊̾̾̇̈̅͡ ḣ̵̰̜̟̙͓͕̗̣͒͒̽͐̓̀̍̂͝ ʾ̷̦̥̘̹̻̬̯̼͈͐̈̄͌̕̚͝  ḩ̨̮͇̲̇̓̋́́̒͑͢͠ú̵̧͇͇͓̳̩̊̂̋̾́̽͘͟͢  ʾ̷̺̜͈̬̠͍͇͉͓͇̇̆͆̒͝͡°̶̡̢̢̛̱̲̠̮̭̫͐̎̈́̔̏̀̚ͅk̸̰̗͙͉͈̰̓̋̽̉̽̉͌̀̕′̛͉͕̹̣̖̄͒́̄͂̇̾́̾′͉͖̪̞̖̦͂̔͑͂̒̇͊̍͜͢  k̴̨͚̮̠̞̞̙̺͎̓̓̓̇͝′̧̼̦̜̥̞̮̖͑̇͒̿̋̀̀̓͞͡′̶̨͔̼̞̜͖̲̘̀͐͆͝͞u̱̠̗̰̜̾͊̂͟͝͡  k̛̗̮̝̠̠͙̉͠͠͝‡̵̪̞̣̗͕̱̙͔̦̀̎̓̃̀̕͜  ḵ̵͍̝̬͗̏͗͛̎̽̎̕͟‡̶̧̱̠͍̩̗͑͌̊̃̄̊̀̓̕̕͟u̗͔͈͔̤͕̓̓̐̏̍͛͌̋̂̏͜ͅ  l̘̣̠̣͙̪̦̒̓͒̐͌̾ǫ̵̘̺̤̹͇͖̒̍͆͒̈́̋̈̀̄͊͢w̨̠͔͕̠͕͔͕͛͊̎̎̈̾̐̕͞͠a͖̥̜̯͉͆́̎̕͡n̲͕̞̟̺̝̠̓̍̓̔̐ṣ̷̞̰̜̜̰̌͂̒͗̒̃͢͢͢ʹ̨̹͙̼͚͉̩̗͛͆̐̓̉́ͅШ̷̮͚̥̲̘̫̯̰̀̍̒̏̊͆̈́͘͢ͅӀ̵̧̬̮͙̥̮͓̆̈̅̈́͗͞у̵̘͔̺̳̪͓̞̮̯̐͌̋͋̃̔͠ш̵̡̡͎̣͓̝͎̯̰͆͂̂̓̌͘͠Ӏ̵̨̨̧̥͕̙͖̇̅̀̍͑̋͐̕͡Ꙗ  Ꙑ)4 ЧӀхуф

22 Куку
23 Къкъ
24 Къу къу
25 КӀ кӀ
26 КӀу кӀу  તિનકા ઔકાત સી પહરણ
27 Л л
28 Лълъ
29 ЛӀ лӀ
30 Мм
31 Н н
32 О о
33 П п
34 ПӀпӀ
35 ПӀу пӀу
36 Р р
37 С с
38 Т т
39 ТӀтӀ
ISO 9 1995(1.0)
a નાળ લરઘેએ ની
b કેહાન્દે આ શિખર જોહરી
v થા’ન ઉત્તે ખરેએ ની
g gu g′′ g′′u d dž dz dzu e
ë જો ખીચડિ આ લટતાં કેહાન્દે
ž ž′′ ž′′u ž′ z  —̷̢̛̜̬͔̖̳͆̇̐̀̚͢͠ k̶̛̭̮̝̹̹̬͌̈́͋͜͟͞u̵̧̠̠͍͖͗́̆̉̄͘′̨̧͖͇͈̳̣͆̑̑͂́͊͜͡′̥̳̥̦͈̫́̄́̍̔̽̑͞ứ̵͈͔̭͍͓̲͔͙͚́̆̊̏̚͠͡ q̵̢̛̼̥̭̪̼̆͋̂̑̅̚͠°͖̹̲̻̣͍̹͇́͋́̒̓͆͂̆͛͗ k̴̡̺̙͕͉̯̖̯͎͒̏̊͡͝
i  "સાદે સીરો'ન ચડેએ ની"
j Nyxhades
k G'eiko Ferrari ku Eiko Dolphinonivm kj̷̺̺̰̺̠͎̮̣̘̄͑͗̆͂̏͆′′ Eikha k′′u k‡ k‡u l
l′′ l‡ m n
 —̷̢̛̜̬͔̖̳͆̇̐̀̚͢͠ k̶̛̭̮̝̹̹̬͌̈́͋͜͟͞u̵̧̠̠͍͖͗́̆̉̄͘ k̸͎͈̣̦͌̂̏͋̊͒͢͡°̴̧̰̮̺̮̙̲̯̤̠̊̊̂̿̎̓͋ ķ̘͔̤̠̪̟̮͌̌͑̎̈̊̕′̳̱̞̥͕̥̀̄̽̏̂́̾͞ k̸͎͈̣̦͌̂̏͋̊͒͢͡°̴̧̰̮̺̮̙̲̯̤̠̊̊̂̿̎̓͋ ķ̘͔̤̠̪̟̮͌̌͑̎̈̊̕′̳̱̞̥͕̥̀̄̽̏̂́̾͞′̴̧̱̖͉̗̾̏͆̾̍͆͌͞͠ͅ q̶̨̩̝̞͙͛̓̒͋͒ ķ̮̠͕̹̩̤̀̉̄̎̕͘̕͢′̴̧̱̖͉̗̾̏͆̾̍͆͌͞͠ͅ q̶̨̩̝̞͙͛̓̒͋͒ ķ̮̠͕̹̩̤̀̉̄̎̕͘̕͢′̨̧͖͇͈̳̣͆̑̑͂́͊͜͡′̥̳̥̦͈̫́̄́̍̔̽̑͞ứ̵͈͔̭͍͓̲͔͙͚́̆̊̏̚͠͡ q̵̢̛̼̥̭̪̼̆͋̂̑̅̚͠°͖̹̲̻̣͍̹͇́͋́̒̓͆͂̆͛͗ k̴̡̺̙͕͉̯̖̯͎͒̏̊͡͝
01 А а
02 Б б
03 В в
04 Г г
05 Гугу
06 Гъгъ
07 Гъу гъу
08 Д д
09 Дждж
10 Дз дз
11 Дзу дзу
12 Ее
13 Ё ё   सिखइया स्ट्रीट'ान को'ं
14 Жж
15 Жъжъ
16 Жъу жъу
17 Жьжь
18 З з ′̡̡̟̬͍̿̀͋͗͆̿͘′̲̺̣̫̻̥̤̝̯̬͗͂̾̒̇̿̎̾ ẑ̛͚͚̼̳̠͖̋̒̊̀́ z̥̫̠̯͚̭͓̪̱̆́͗̈͛̄͜
19 И и
20 Й й
21 К к  में किताबां विचों पढ़ेया नि.o
.o
.js
o u̧̧͚̺̙̟̪̹͕͑͒́̀̌̋̎͝k͇̗̻̞̗̹̅̊̃̈́̅̄̂y̴̧̡̬̳͉̦̗̻̪̓͒̌͐̄̕͠г̢̟̥̯̜̭͎̮̤̅͛̄̿̿͊̚͝͞л̴͎͇͕̯͕̞͖̊̓̍̔͑́͠͝а̨̛̱̳͖̗̯̫͗́̄̓г̢͓̠͇͎̘̝͑̃̓̓̓͟͢͠ӧ̶̧̢͍̠̜̰̩̫̜͛̐̆̂͘л̧̪̩̺̯̭́̍̌͘͜͜͜͡͝ѝ̷̹͙̝̞͓̹̤̟͋͑͂̀͊͌͐͘͢͠ (̵̨̤͕̺͍̮͙̥͖̏̀̔̽͊̆̈̉͡g̭͓͇̤͖͛͑̃̒̏̀̚͡ḻ̡̡͚̎̀̃͂͆͑̒͢͝a̵̧̺͕͙͙̦̗̔̔̐̊̈́̋͜ͅg̷̡͓̫͉̦͍̳͗͗̿̆̿́͟͟ ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞ ê̷͔̻̜͔̄̑̉̏̌̑̒̈́̕͜͜ͅ ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞ —͉̯͓͌̿͆́͋̄͜͟͡ z̸̡̛͉͖̠̦̬̺̓̈́͛͒͜h̸͙̘̫̻̠͕̺̥̅̂̐̎̌̍̈́͂͘͝ ž̷̧̠̤̖̗͎͚̖͖̘̈́̂̿̾̊̾͠ z̵͙̜͚͚͍̤̖͓͎̆̇̀͛̌͋͋̕͠͠h̸̡̢̨͉̼͔̝̋̏̿͑̓͑͟ͅ′̡̡̟̬͍̿̀͋͗͆̿͘′̲̺̣̫̻̥̤̝̯̬͗͂̾̒̇̿̎̾ ẑ̛͚͚̼̳̠͖̋̒̊̀́ z̥̫̠̯͚̭͓̪̱̆́͗̈͛̄͜h̶̡̤̺͈͙̟͆̈́̇́̈́̀′̦͈͇͇͎̭͎͗͋̄̄̎̂̿̃̓͝′̸̤̮̘̹̊̀̇̄͑̇͞ͅu̸̼͔̰̯̖̐͆͗̏͐̾͡ͅ ẑ̷̛̲̭͉̪̜̯͌̍̅̿́͢͠ͅ°̵̺̹̫̹͙͇͆̉̋̎̇̿͂͟͞͝ z̨̧̡̼̫͒̿̅̋̚h̴̛̻͇̟̫͈͉͚̀͆̌̐̀̌̈́͡ͅ′͍̠̤͉͓̦̦̦̻́͒͐͌̆̀͡ͅ ž̴͚̳̞̙͙͖̙͈̏̅̾͋͊͋̈̋͗͢′̨̟͉͔͙̐̅̓̃̀̕͟͠ z̦̬̠̳̻̃͂͋̎́̔͢͢͝ͅ ẕ̸̼̭̙̼̥̠̼̊̂̐͂͂̀͒͜͜͝ ḯ̻̖̮̦͕͊̇͋̂͂͜͝ĭ̙̟͕͈̪̝̤͎̓̅̀̔̎̊̀̐̅͂͢͜ j̷̺̺̰̺̠͎̮̣̘̄͑͗̆͂̏͆ k̵̡̬͔̬̩͇̤͐͊̅͆̃ͅḣ̷̨̯̜̠̻̿͊͑̎̀͟ č̵̡̨̘͖̥͕͉̔̅̀̅͡͠′̵̸̡̡̛̳̹̰̰̲̣̲̞͕̝͇̟̩̀̀̍̈́̃̊̓̍̓̉̃̉̋͠ ḱ̵̛̛̻̗̻͉͓̀͒͞ḣ̷̭̮̰̙̞̜͎͔̪̜̔̂̈́̾̌̋̋̈́͝u̧̦̲͍̦̯̱̐̅̃̕͞ ḳ̶̡͖̮̖̹̻͐́́̀̔̇̄̑͑͢͝ͅ°̢̢̼̜͍͇͂͗͗̾̒̚ ḽ͉̰̱͈̳̺̰̮̊̍̐̏͆̌̐̕̚ l̵̨̡̛̻̻̺͚͚̤̯̺̈́̊̒̍͛͒͠ l̩̤̬̰̹̘̔̾̍̓̔̚͟′̡̭̖̼̙̩̼͆͑̃͆͆̏̽̄̾̕′̷̢͚͍̟̠͍̖̐́͋̿̓̍͂̆̍ ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞ l̨̢̥͉̎̍̅̐̚͜͟ḣ̨̘̭̼̜͇̹͓̹̊̀̽͛̎̒̚͞͝ ḷ̡͕͍͎̥̣͚̣̞͉̐̿̇̃̄͊͂̅͘q̨̢͓̣̦̦͙̤́̃̀́̀̑̆w̵͖̥͓͚̽̾͒̀͒͘ͅͅλxǯ̷̨̣̰͈̲̮̈́̈́̈́̓̄̊̈́͡′̵̡̨̬͎̙͋̐̂̇̀͊͋͊̊͒ ḑ̷͚̙̰̋́͑̿̕͜͟z̴̧̬̰̙̹̪̬͎͗͋̈́̓͌̒̅̾͟ ʒ̸͈͙̱̙̹̎́̀̔̋̈́́͘͟ d̵̘̟̼͓̮̄͒̊̒̎́̑̒͌̚z̛̛̼͚̬̱͙͒̒̇̌̓́̒̚͜͢ͅư̶͇̞̤̻̫̓́͑͌̃̑͟
p p‡ p‡u r
s t t‡
KNAB 2003(2.0)
a
b
v
g
gw  l̩̤̬̰̹̘̔̾̍̓̔̚͟′̡̭̖̼̙̩̼͆͑̃͆͆̏̽̄̾̕′̷̢͚͍̟̠͍̖̐́͋̿̓̍͂̆̍
ǧ
ǧw
d
dź
dz dzw é,je(2.1′̡̡̟̬͍̿̀͋͗͆̿͘′̲̺̣̫̻̥̤̝̯̬͗͂̾̒̇̿̎̾ ) ë
dz dzw é,je(2j̷̺̺̰̺̠͎̮̣̘̄͑͗̆͂̏͆′̡̡̟̬͍̿̀͋͗͆̿͘′̲̺̣̫̻̥̤̝̯̬͗͂̾̒̇̿̎̾ .1 ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞) ë
dz dzw é,je(2.1′̦͈͇͇͎̭͎͗͋̄̄̎̂̿̃̓͝′̸̤̮̘̹̊̀̇̄͑̇͞ͅ) ë
dz dzw é,je(2.1 ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞) ë
dz dzw é,je(2′̡̡̟̬͍̿̀͋͗͆̿͘′̲̺̣̫̻̥̤̝̯̬͗͂̾̒̇̿̎̾ .1j̷̺̺̰̺̠͎̮̣̘̄͑͗̆͂̏͆) ë
ž
z̄
zw̄
ź
z
i
j
k
kw
q
qw ḉ,ķ (2.2)
ķw l
ł
ļ m n o p ṗ ṗw r
s t ţ
a ā b b v — g ɣ gu g° g′′ ġ g′′u ġ° d d dzh ǯ′ dz ʒ dzu ʒ° e e ë — zh ž zh′′ ẑ zh′′u ẑ° zh′ ž′ z z i i
ĭ j k — ku k° k′′ q k′′u q° kḣ č′̣ kḣu ḳ° l l l′′ ł lḣ ḷ m m n n o o p p pḣ ṗ pḣu ṗ° r r s s
t t tḣ ṭ
40 ТӀу тӀу
41 У у
42 Ф ф
43 ФӀ фӀ
44 Х х
45 Хуху
46 Хъхъ
47 Хъу хъу
48 Хьхь
49 Ц ц
50 Цу цу
51 ЦӀцӀ
52 Ч ч
53 Чъчъ
54 ЧӀчӀ
55 Шш
56 Шъшъ
57 Шъу шъу
58 ШӀшӀ
59 ШӀушӀу
60 Щщ
61 Ъ ъ 
62 Ы ы
63 Ь ь
64 Э э
65 Юю
66 Я я
67 Ӏ Ӏ
68 Ӏу Ӏу
ISO 9 KNAB 1995(1.0) 2003(2.0)
t‡u ţw u u
f f f‡ f̧
h x hu xw h′′ ḩ h′′u ḩw h′ h
c c cu cw c‡ ç
č ć č′′ č č‡ ç̌
š š š′′ s̄ š′′u sw̄ š‡ ş̄ š‡u şw̄ ŝ ś
′′ 
y y
′ 
è e
û ju â ja ‡ x̧ ‡u x̧w
ALA-LC TITUS 1997(3.0) 2000(4.0)
tḣu ṭ°
u w,u f f
fḣ — kh x khu x° kh′′ χ kh′′u χ° kh′ ḥ
ts͡ c ts͡u c° ts͡ḣ c̣ ch čʹ ch′′ č chḣ č̣ sh š sh′′ ŝ sh′′u ŝ° shḣ ṣ̂ shḣu ŝ°̣ shch šʹ
′′ — y ǝ
′ — ė ă
iu͡ — ia͡ — ḣ ʾ ḣu ʾ°




<!-- -->
<center><img align="center" src="https://github-readme-stats.vercel.app/api?username=sator-arepo-tenet-opera-rotas&include_all_commits=true&count_private=true&show_icons=true&line_height=20&title_color=2B5BBD&icon_color=1124BB&text_color=A8A3A7&bg_color=0,000000,130F40" alt="my Github Stats"/><img align="center" src="https://github-readme-stats.vercel.app/api?username=greydoubt&include_all_commits=true&count_private=true&show_icons=true&line_height=20&title_color=2B5BBD&icon_color=1124BB&text_color=A8A3A7&bg_color=0,000000,130F40" alt="my Github Stats"/>
  
[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=sator-arepo-tenet-opera-rotas&theme=dark&background=000000)](https://git.io/streak-stats)[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=greydoubt&theme=dark&background=000000)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=greydoubt&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=sator-arepo-tenet-opera-rotas&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)</center>

<!--
**greydoubt/greydoubt** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


    
    - 01 А а

    - 02 Б б
 
    - 03 В в

    - 04 Г г
    
    - 05 Гугу
   
    - 06 Гъгъ
   
    - 07 Гъу гъу
    
    - 08 Д д

Sikheya street'an cho'n mein kitaaban vichon parheya ni
सिखइया स्ट्रीट'ान को'ं में किताबां विचों पढ़ेया नि
Sikheya street'an cho'n mein kitaaban vichon parheya ni
Once upon a time, I learn't how to read books on the street corner

તિનકા ઔકાત સી પહરણ નાળ લરઘેએ ની
Tinka aukaat c paharaan naal lardhea ni
They called me the girl who cut the pharaoh, standing pallid over the fat of the land

કેહાન્દે આ શિખર જોહરી થા’ન ઉત્તે ખરેએ ની
Kehande aa sikhar jehri thaa’n utte kharea ni
Where is this peak, where is it not visible? There is always another mountain to climb

જો ખીચડિ આ લટતાં કેહાન્દે "સાદે સીરો'ન ચડેએ ની"
Jo khichde aa lattan kehande saade siro'n chadea ni
If the sour grapes die on the vine, it will be said, The Sweet Sadism of Shiva Nyxhades was her own demise

63 Ь ь 64 Э э̛̯̖̜͓̩̣̒̈́̉͋̆ Ꙗ̨̨̰̥̖̺͇͕̠͌̿͌̓̒͒͊́̀͡ Ꙑ̳̲̜̪̮̈́̾̊̂̓̄̿̓͑̏)̴̧̧̱̱͕́̃͌͛̏̒̏͘͟͢͠4̨̡̘̦͈͕̠͇̣͂̽̌͋͟͝ Ч̶̯̦͕͙̣̑̐̆̕͟͢͡͝Ӏ̻͓̣̳̓̊̐͋̇̏͟͞х̸̧̨̪̳̲̰͉̱̻͋̂̾̃͝͡у̡̝̖̭͍̟̟̘̫̀̐͐̈́͗̂̄͌͗̚͟̯̖̤̣̌̌̅͗̂̃̉͘͟ͅф̢̝̖͇͓̜̘̘̔̆̅̑́̽͒͘͜͠g̶̙͙̳̬͌͑͑͌̓͟ ɣ̡̡̹͉͙͖̱͙̇̉̄͒͗̍̂͐̿͠ ģ̡̢̥̦̞̬̀͊́̒̀̕͜ͅư͔͉̦͕̟̮̊̃̾̏̉ g̘͙̘̻͉̖̺̹̺̏̈́̃̌͗͘͜°̷̡̱͕͎͇̹̔͌̄̄̊ ģ̶̻̙̱̤̻̔̿̏̋̀͂̐͢ͅ′̵̢̢͈̰͉̺̆̒̊͊͞͠′̵̫̭͓̘̂̾̔̔͒̽̀͊͘͘͜ͅͅ ġ̨̛̯̯̣͕̫̘̼͋̍͂͆͢ g͇̗̣̥̜̙̝͓͋̓̔̀͊̒͑͗͘′̵̨̯̲̭͙̦̟͉̟̞̆̃̑͂͘͡′̧̬̺̪͍̟̼̏̽̾͛̏͐̿͜͡͡ŭ̶̙̭̥̟̥̭̘̟̺͛̊̿̅̎͗̇͝͡ ġ͚̳̘̖̬͉̌͆̀̄̐̄̌̉̐̒͜°̶̧̞̪͚̾̊͗͂͘͜ ḓ̵͖̦̹͍͊̆̓͒̑͂͗͛ d̡̧̙̪̻̮̗͎͂͌͆̓̓̊̍̅̓ d̷͖̼͓͕̮̽̇̇͌̕z̷͚̯̦͉̙̉̿̐̈́̂͌̑͢͞͝͠ḧ̨͙̯͍̣̲͎́̎̉͌͋̏͆̑̋̚͢ ǯ̷̨̣̰͈̲̮̈́̈́̈́̓̄̊̈́͡′̵̡̨̬͎̙͋̐̂̇̀͊͋͊̊͒ ḑ̷͚̙̰̋́͑̿̕͜͟z̴̧̬̰̙̹̪̬͎͗͋̈́̓͌̒̅̾͟ ʒ̸͈͙̱̙̹̎́̀̔̋̈́́͘͟ d̵̘̟̼͓̮̄͒̊̒̎́̑̒͌̚z̛̛̼͚̬̱͙͒̒̇̌̓́̒̚͜͢ͅư̶͇̞̤̻̫̓́͑͌̃̑͟ ʒ̴̧̨̧͖͖̼̫̙͗͗́̓͌͢͜°̬̥̰͎̰͌̑̈́̋̆͑͒͟͝͞h̸̢̜̞͎͓̯̉̌͑̉́͆͞ư̶̧̧̙̟̤̟͇͍̆̋̄̉̃̂͛͗̕ Є̸̠̮̺̣̗̭̭̥̘̀͆͋͟͡͠͝w̷̡̜̩͎̮͚̥̺͍̰͐̍͛̄̌͠͞ダ̶̲̮̜̪͍͖͓́͊̃̀̀͑̈͑̕͠h̳̼͉̘̙̉̍̎̀͊͗̕͞′̠͕͙͚́̓̉̅͜͠′̛̗͖͈͔̦̠͉͓̾̔̓͊͌ラ̶̡̛̻̫̼̞̥̃̀̇̓̇͛͋͝͡a̶̧̟̜̯͇̘͉̥͐̃̒̆̿̀̃̔͡͠z̷̘͙̟͔̙̘̽̀́̀͋͟ŭ̸̙̤̯͇̺̞̉́̿̅̊͂̽б̶̨͕̬͓̐̂̈̍̾̚͟͠͞о̛̬̯̻͙͖͓̗̥͂̏̎̾̿̿̌ͅу̡̥̮̰͍͖͒͂͐͋̋͊͢к̷̯͙̯̪̬͌̌̓̉̌̓̅̈͌ꙑ̶̡̨̥͚͎̭͌̓͋̓̏́́̑b̛̝̼̜͙̭͌͋̈̾̆́̇̏͢u̧̧͚̺̙̟̪̹͕͑͒́̀̌̋̎͝k͇̗̻̞̗̹̅̊̃̈́̅̄̂y̴̧̡̬̳͉̦̗̻̪̓͒̌͐̄̕͠г̢̟̥̯̜̭͎̮̤̅͛̄̿̿͊̚͝͞л̴͎͇͕̯͕̞͖̊̓̍̔͑́͠͝а̨̛̱̳͖̗̯̫͗́̄̓г̢͓̠͇͎̘̝͑̃̓̓̓͟͢͠ӧ̶̧̢͍̠̜̰̩̫̜͛̐̆̂͘л̧̪̩̺̯̭́̍̌͘͜͜͜͡͝ѝ̷̹͙̝̞͓̹̤̟͋͑͂̀͊͌͐͘͢͠ (̵̨̤͕̺͍̮͙̥͖̏̀̔̽͊̆̈̉͡g̭͓͇̤͖͛͑̃̒̏̀̚͡ḻ̡̡͚̎̀̃͂͆͑̒͢͝a̵̧̺͕͙͙̦̗̔̔̐̊̈́̋͜ͅg̷̡͓̫͉̦͍̳͗͗̿̆̿́͟͟ǫ̸̟̻̺͙̼̗͂͑̍͋͋͑́͛̕͝l̡̦͕̣̪̇̒̑͐́̓͘͜͠͠ͅͅi̷͔̳͍̳̘̪̻̇̌̇̂͂̽)̛̫̮͖̪̯̇͛̒͡ͅ e̖͇̜̳̲͍̔̅̆̒̍̓͞ ê̷͔̻̜͔̄̑̉̏̌̑̒̈́̕͜͜ͅ ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞ —͉̯͓͌̿͆́͋̄͜͟͡ z̸̡̛͉͖̠̦̬̺̓̈́͛͒͜h̸͙̘̫̻̠͕̺̥̅̂̐̎̌̍̈́͂͘͝ ž̷̧̠̤̖̗͎͚̖͖̘̈́̂̿̾̊̾͠ z̵͙̜͚͚͍̤̖͓͎̆̇̀͛̌͋͋̕͠͠h̸̡̢̨͉̼͔̝̋̏̿͑̓͑͟ͅ′̡̡̟̬͍̿̀͋͗͆̿͘′̲̺̣̫̻̥̤̝̯̬͗͂̾̒̇̿̎̾دووپشک ẑ̛͚͚̼̳̠͖̋̒̊̀́ z̥̫̠̯͚̭͓̪̱̆́͗̈͛̄͜h̶̡̤̺͈͙̟͆̈́̇́̈́̀′̦͈͇͇͎̭͎͗͋̄̄̎̂̿̃̓͝′̸̤̮̘̹̊̀̇̄͑̇͞ͅu̸̼͔̰̯̖̐͆͗̏͐̾͡ͅ ẑ̷̛̲̭͉̪̜̯͌̍̅̿́͢͠ͅ°̵̺̹̫̹͙͇͆̉̋̎̇̿͂͟͞͝ z̨̧̡̼̫͒̿̅̋̚h̴̛̻͇̟̫͈͉͚̀͆̌̐̀̌̈́͡ͅ′͍̠̤͉͓̦̦̦̻́͒͐͌̆̀͡ͅ ž̴͚̳̞̙͙͖̙͈̏̅̾͋͊͋̈̋͗͢′̨̟͉͔͙̐̅̓̃̀̕͟͠ z̦̬̠̳̻̃͂͋̎́̔͢͢͝ͅ ẕ̸̼̭̙̼̥̠̼̊̂̐͂͂̀͒͜͜͝ ḯ̻̖̮̦͕͊̇͋̂͂͜͝ĭ̙̟͕͈̪̝̤͎̓̅̀̔̎̊̀̐̅͂͢͜ j̷̺̺̰̺̠͎̮̣̘̄͑͗̆͂̏͆ k̵̡̬͔̬̩͇̤͐͊̅͆̃ͅ —̷̢̛̜̬͔̖̳͆̇̐̀̚͢͠ k̶̛̭̮̝̹̹̬͌̈́͋͜͟͞u̵̧̠̠͍͖͗́̆̉̄͘ k̸͎͈̣̦͌̂̏͋̊͒͢͡°̴̧̰̮̺̮̙̲̯̤̠̊̊̂̿̎̓͋ ķ̘͔̤̠̪̟̮͌̌͑̎̈̊̕′̳̱̞̥͕̥̀̄̽̏̂́̾͞′̴̧̱̖͉̗̾̏͆̾̍͆͌͞͠ͅ q̶̨̩̝̞͙͛̓̒͋͒ ķ̮̠͕̹̩̤̀̉̄̎̕͘̕͢′̨̧͖͇͈̳̣͆̑̑͂́͊͜͡′̥̳̥̦͈̫́̄́̍̔̽̑͞ứ̵͈͔̭͍͓̲͔͙͚́̆̊̏̚͠͡ q̵̢̛̼̥̭̪̼̆͋̂̑̅̚͠°͖̹̲̻̣͍̹͇́͋́̒̓͆͂̆͛͗ k̴̡̺̙͕͉̯̖̯͎͒̏̊͡͝ḣ̷̨̯̜̠̻̿͊͑̎̀͟ č̵̡̨̘͖̥͕͉̔̅̀̅͡͠′̵̸̡̡̛̳̹̰̰̲̣̲̞͕̝͇̟̩̀̀̍̈́̃̊̓̍̓̉̃̉̋͠ ḱ̵̛̛̻̗̻͉͓̀͒͞ḣ̷̭̮̰̙̞̜͎͔̪̜̔̂̈́̾̌̋̋̈́͝u̧̦̲͍̦̯̱̐̅̃̕͞ ḳ̶̡͖̮̖̹̻͐́́̀̔̇̄̑͑͢͝ͅ°̢̢̼̜͍͇͂͗͗̾̒̚ ḽ͉̰̱͈̳̺̰̮̊̍̐̏͆̌̐̕̚ l̵̨̡̛̻̻̺͚͚̤̯̺̈́̊̒̍͛͒͠ l̩̤̬̰̹̘̔̾̍̓̔̚͟′̡̭̖̼̙̩̼͆͑̃͆͆̏̽̄̾̕′̷̢͚͍̟̠͍̖̐́͋̿̓̍͂̆̍ ł̰̬̩̪̥̘̜͙̾̃͗̎̆̓̄̕͜͝͡ l̨̢̥͉̎̍̅̐̚͜͟ḣ̨̘̭̼̜͇̹͓̹̊̀̽͛̎̒̚͞͝ ḷ̡͕͍͎̥̣͚̣̞͉̐̿̇̃̄͊͂̅͘q̨̢͓̣̦̦͙̤́̃̀́̀̑̆w̵͖̥͓͚̽̾͒̀͒͘ͅͅ ḉ̡̣̮̜̗͖̞͕̊̌̽̅͌͞͝,̵̨̬̲͓̯̝͉͋̔̓͑́̂̑ķ̡̗̖̠͓͛͒̾̕͘͡	PICTURE ID 17 NAME " λx . ophidia ereц grex          .    أوفيديا إريكس جريكس   .arrowll.gif" TURNS ANOTHER  z̴̧̬̰̙̹̪̬͎͗͋̈́̓͌̒̅̾͟ ʒ̸͈͙̱̙̹̎́̀̔̋̈́́͘͟ d̵̘̟̼͓̮̄͒̊̒̎́̑̒͌̚z̛̛̼͚̬̱͙͒̒̇̌̓́̒̚͜͢ͅư̶͇̞̤̻̫̓́͑͌̃̑͟ ʒ̴̧̨̧͖͖̼̫̙͗͗́̓͌͢͜°̬̥̰͎̰͌̑̈́̋̆͑͒͟͝͞h̸̢̜̞͎͓̯̉̌͑̉́͆͞ư̶̧̧̙̟̤̟͇͍̆̋̄̉̃̂͛͗̕ Є̸̠̮̺̣̗̭̭̥̘̀͆͋͟͡͠͝w̷̡̜̩͎̮͚̥̺͍̰͐̍͛̄̌͠͞ダ̶̲̮̜̪͍͖͓́͊̃̀̀͑̈͑̕͠ ENDPICTURE
	PICTURE ID 185ꙑꙗxє NAME " λx . ophidia ereц grex          .    أوفيديا إريكس جريكس   .arrowrr.gif" TURNS ANOTHER COLOR z̷̘͙̟͔̙̘̽̀́̀͋͟ŭ̸̙̤̯͇̺̞̉́̿̅̊͂̽б̶̨͕̬͓̐̂̈̍̾̚͟͠͞о̛̬̯̻͙͖͓̗̥͂̏̎̾̿̿̌ͅу̡̥̮̰͍͖͒͂͐͋̋͊͢к̷̯͙̯̪̬͌̌̓̉̌̓̅̈͌ꙑ̶̡̨̥͚͎̭͌̓͋̓̏́́̑b̛̝̼̜͙̭͌͋̈̾̆́̇̏͢u̧̧͚̺̙̟̪̹͕͑͒́̀̌̋̎͝k͇̗̻̞̗̹̅̊̃̈́̅̄̂y̴̧̡̬̳͉̦̗̻̪̓͒̌͐̄̕͠г̢̟̥̯̜̭͎̮̤̅͛̄̿̿͊̚͝͞л̴͎͇͕̯͕̞͖̊̓̍̔͑́͠͝а̨̛̱̳͖̗̯̫͗́̄̓г̢͓̠͇͎̘̝͑̃̓̓̓͟͢͠ӧ̶̧̢͍̠̜̰̩̫̜͛̐̆̂͘л̧̪̩̺̯̭́̍̌͘͜͜͜͡͝ѝ̷̹͙̝̞͓̹̤̟͋͑͂̀͊͌͐͘͢͠  ENDPICTURE (̶̨̡̠͈̝̳̫͉͗̆̌͗̽̚2̪̮̥̣̩͔̺͚̗͗̀͛̐͗̽̍ͅ.̷̡̧̥͉̺̺͖͖̭̀̅̾͊̕͝2̧̤̭̹͈͈̭̌̔̀̃͐͟͞͞)̸̢̳͕̦̰̤̲̄̈̊́̒͝ч̨̳̭͍̬̞͍̹̏̂̀͂̿̀͠͠Ӏ̡̫̟̖̲́̐͋͑͡k̙̦̜̖͎̯͕̄̿́̇͐͌̈́̔͠ k̸̢͚͕̔̒̍͛̈̋͐͐͜͠͡ͅư̴̢̫͈̘̣̖̰̝̂̇͗̈́̾̀́͜͞͝ͅ ž̧̧̮̲̘̩̽̿̇̅̔͘͟′̺̞͓̥̳̰̾̎́̓͞ͅ′͈̳͇͙͈͈̠͐̀̇̑̍̅̾̎͞ͅư̶̡̤͓͈̪͉̠̭̣̈̽̾͋͐̇̉͟͠͞ ž̫̝̦̘̺̦̭̏̇̓͒͢͝͠′͈̰̺̖̪̦̞̀̔̇̓͋̃̏͜͡͠i̢̧̨̖̇̇̀̀̇͟͟͜͠u̸̡̧̫̱͕͔̱̥͍̬͈̩͇̒͋̓̏͐̈̆́͂͒͊̆̕̕̕͟͡͠͡͡ —̝̣̜͙̝̳̰̥̖̅̈́͑̀̾́̊̕͘͞ Є̶̨̗̠̳̜̪̯̬̜̰̒͋̄͋̀ǐ̴̡̪͖̰̜͉͒̎̌̌͞͠ą̵̴̧̛̠̞͈̳̗̥̳̘̪̻͗̑͑́́͆̽̆͊̍̎̂͘̚͘͡͡ —̤̫̖̣̪̫̿͊̾̾̇̈̅͡ ḣ̵̰̜̟̙͓͕̗̣͒͒̽͐̓̀̍̂͝ ʾ̷̦̥̘̹̻̬̯̼͈͐̈̄͌̕̚͝ ḩ̨̮͇̲̇̓̋́́̒͑͢͠ú̵̧͇͇͓̳̩̊̂̋̾́̽͘͟͢ ʾ̷̺̜͈̬̠͍͇͉͓͇̇̆͆̒͝͡°̶̡̢̢̛̱̲̠̮̭̫͐̎̈́̔̏̀̚ͅk̸̰̗͙͉͈̰̓̋̽̉̽̉͌̀̕′̛͉͕̹̣̖̄͒́̄͂̇̾́̾′͉͖̪̞̖̦͂̔͑͂̒̇͊̍͜͢ k̴̨͚̮̠̞̞̙̺͎̓̓̓̇͝′̧̼̦̜̥̞̮̖͑̇͒̿̋̀̀̓͞͡′̶̨͔̼̞̜͖̲̘̀͐͆͝͞u̱̠̗̰̜̾͊̂͟͝͡ k̛̗̮̝̠̠͙̉͠͠͝‡̵̪̞̣̗͕̱̙͔̦̀̎̓̃̀̕͜ ḵ̵͍̝̬͗̏͗͛̎̽̎̕͟‡̶̧̱̠͍̩̗͑͌̊̃̄̊̀̓̕̕͟u̗͔͈͔̤͕̓̓̐̏̍͛͌̋̂̏͜ͅ l̘̣̠̣͙̪̦̒̓͒̐͌̾ǫ̵̘̺̤̹͇͖̒̍͆͒̈́̋̈̀̄͊͢w̨̠͔͕̠͕͔͕͛͊̎̎̈̾̐̕͞͠a͖̥̜̯͉͆́̎̕͡n̲͕̞̟̺̝̠̓̍̓̔̐ṣ̷̞̰̜̜̰̌͂̒͗̒̃͢͢͢ʹ̨̹͙̼͚͉̩̗͛͆̐̓̉́ͅШ̷̮͚̥̲̘̫̯̰̀̍̒̏̊͆̈́͘͢ͅӀ̵̧̬̮͙̥̮͓̆̈̅̈́͗͞у̵̘͔̺̳̪͓̞̮̯̐͌̋͋̃̔͠ш̵̡̡͎̣͓̝͎̯̰͆͂̂̓̌͘͠Ӏ̵̨̨̧̥͕̙͖̇̅̀̍͑̋͐̕͡





01 А а 02 Б б 03 В в 04 Г г 05 Гугу 06 Гъгъ 07 Гъу гъу 08 Д д 09 Дждж 10 Дз дз 11 Дзу дзу 12 Ее 13 Ё ё  सिखइया स्ट्रीट'ान को'ं 14 Жж 15 Жъжъ 16 Жъу жъу 17 Жьжь 18 З з 19 И и 20 Й й 21 К к  में किताबां विचों पढ़ेया नि 22 Куку 23 Къкъ 24 Къу къу 25 КӀ кӀ 26 КӀу кӀу  તિનકા ઔકાત સી પહરણ 27 Л л 28 Лълъ 29 ЛӀ лӀ 30 Мм 31 Н н 32 О о 33 П п 34 ПӀпӀ 35 ПӀу пӀу 36 Р р 37 С с 38 Т т 39 ТӀтӀ ISO 9 1995(1.0) a નાળ લરઘેએ ની b કેહાન્દે આ શિખર જોહરી v થા’ન ઉત્તે ખરેએ ની g gu g′′ g′′u d dž dz dzu e ë જો ખીચડિ આ લટતાં કેહાન્દે ž ž′′ ž′′u ž′ z i "સાદે સીરો'ન ચડેએ ની" j Nyxhades k G'eiko Ferrari ku Eiko Dolphinonivm k′′ Eikha k′′u k‡ k‡u l l′′ l‡ m n o p p‡ p‡u r s t t‡ KNAB 2003(2.0) a b v g gw ǧ ǧw d dź dz dzw é,je(2.1) ë ž z̄ zw̄ ź z i j k kw q qw ḉ,ķ (2.2) ķw l ł ļ m n o p ṗ ṗw r s t ţ a ā b b v — g ɣ gu g° g′′ ġ g′′u ġ° d d dzh ǯ′ dz ʒ dzu ʒ° e e ë — zh ž zh′′ ẑ zh′′u ẑ° zh′ ž′ z z i i ĭ j k — ku k° k′′ q k′′u q° kḣ č′̣ kḣu ḳ° l l l′′ ł lḣ ḷ m m n n o o p p pḣ ṗ pḣu ṗ° r r s s t t tḣ ṭ 40 ТӀу тӀу 41 У у 42 Ф ф 43 ФӀ фӀ 44 Х х 45 Хуху 46 Хъхъ 47 Хъу хъу 48 Хьхь 49 Ц ц 50 Цу цу 51 ЦӀцӀ 52 Ч ч 53 Чъчъ 54 ЧӀчӀ 55 Шш 56 Шъшъ 57 Шъу шъу 58 ШӀшӀ 59 ШӀушӀу 60 Щщ 61 Ъ ъ  62 Ы ы 
 65 Юю 66 Я я 67 Ӏ Ӏ 68 Ӏу Ӏу ISO 9 KNAB 1995(1.0) 2003(2.0) t‡u ţw u u f f f‡ f̧ h x hu xw h′′ ḩ h′′u ḩw h′ h c c cu cw c‡ ç č ć č′′ č č‡ ç̌ š š š′′ s̄ š′′u sw̄ š‡ ş̄ š‡u şw̄ ŝ ś ′′  y y ′  è e û ju â ja ‡ x̧ ‡u x̧w ALA-LC TITUS 1997(3.0) 2000(4.0) tḣu ṭ° u w,u f f fḣ — kh x khu x° kh′′ χ kh′′u χ° kh′ ḥ ts͡ c ts͡u c° ts͡ḣ c̣ ch čʹ ch′′ č chḣ č̣ sh š sh′′ ŝ sh′′u ŝ° shḣ ṣ̂ shḣu ŝ°̣ shch šʹ ′′ — y ǝ ′ — ė ă iu͡ — ia͡ — ḣ ʾ ḣu ʾ°
エєmereldhas͡ c メrts͡uдобро азъ; hu Єwダh′′ラazŭбоукꙑbukyглаголи (glagoli),)c°h x huxw h′′ ḩ h′′u ḩw h′ h ts͡ḣ c̣ ch čʹ š š š′′ s̄ š′′u sw̄ š‡ ş̄iu͡ — ia͡ — ḣ ʾ ḣu ʾ°š‡u şw̄ ŝ śch′′ č chḣ č̣ sh š sh′′ ŝ sh′′u ŝ°x shḣ ṣ̂h′′ — y ǝ x hu Єwダh′′ ḩ h′′u ḩУw h′ h shḣu ŝ°̣ shch šʹШӀушӀу5ꙑꙗxє, ѕѣлозč̣ем

лꙗts͡ḣ̛̯̖̜͓̩̣̒̈́̉͋̆ Ꙗ̨̨̰̥̖̺͇͕̠͌̿͌̓̒͒͊́̀͡ Ꙑ̳̲̜̪̮̈́̾̊̂̓̄̿̓͑̏)̴̧̧̱̱͕́̃͌͛̏̒̏͘͟͢͠4̨̡̘̦͈͕̠͇̣͂̽̌͋͟͝ Ч̶̯̦͕͙̣̑̐̆̕͟͢͡͝Ӏ̻͓̣̳̓̊̐͋̇̏͟͞х̸̧̨̪̳̲̰͉̱̻͋̂̾̃͝͡у̡̝̖̭͍̟̟̘̫̀̐͐̈́͗̂̄͌͗̚͟̯̖̤̣̌̌̅͗̂̃̉͘͟ͅф̢̝̖͇͓̜̘̘̔̆̅̑́̽͒͘͜͠g̶̙͙̳̬͌͑͑͌̓͟ ɣ̡̡̹͉͙͖̱͙̇̉̄͒͗̍̂͐̿͠ ģ̡̢̥̦̞̬̀͊́̒̀̕͜ͅư͔͉̦͕̟̮̊̃̾̏̉ g̘͙̘̻͉̖̺̹̺̏̈́̃̌͗͘͜°̷̡̱͕͎͇̹̔͌̄̄̊ ģ̶̻̙̱̤̻̔̿̏̋̀͂̐͢ͅ′̵̢̢͈̰͉̺̆̒̊͊͞͠′̵̫̭͓̘̂̾̔̔͒̽̀͊͘͘͜ͅͅ ġ̨̛̯̯̣͕̫̘̼͋̍͂͆͢ g͇̗̣̥̜̙̝͓͋̓̔̀͊̒͑͗͘′̵̨̯̲̭͙̦̟͉̟̞̆̃̑͂͘͡′̧̬̺̪͍̟̼̏̽̾͛̏͐̿͜͡͡ŭ̶̙̭̥̟̥̭̘̟̺͛̊̿̅̎͗̇͝͡ ġ͚̳̘̖̬͉̌͆̀̄̐̄̌̉̐̒͜°̶̧̞̪͚̾̊͗͂͘͜ ḓ̵͖̦̹͍͊̆̓͒̑͂͗͛ d̡̧̙̪̻̮̗͎͂͌͆̓̓̊̍̅̓ d̷͖̼͓͕̮̽̇̇͌̕z̷͚̯̦͉̙̉̿̐̈́̂͌̑͢͞͝͠ḧ̨͙̯͍̣̲͎́̎̉͌͋̏͆̑̋̚͢ ǯ̷̨̣̰͈̲̮̈́̈́̈́̓̄̊̈́͡′̵̡̨̬͎̙͋̐̂̇̀͊͋͊̊͒ ḑ̷͚̙̰̋́͑̿̕͜͟z̴̧̬̰̙̹̪̬͎͗͋̈́̓͌̒̅̾͟ ʒ̸͈͙̱̙̹̎́̀̔̋̈́́͘͟ d̵̘̟̼͓̮̄͒̊̒̎́̑̒͌̚z̛̛̼͚̬̱͙͒̒̇̌̓́̒̚͜͢ͅư̶͇̞̤̻̫̓́͑͌̃̑͟ ʒ̴̧̨̧͖͖̼̫̙͗͗́̓͌͢͜°̬̥̰͎̰͌̑̈́̋̆͑͒͟͝͞h̸̢̜̞͎͓̯̉̌͑̉́͆͞ư̶̧̧̙̟̤̟͇͍̆̋̄̉̃̂͛͗̕ Є̸̠̮̺̣̗̭̭̥̘̀͆͋͟͡͠͝w̷̡̜̩͎̮͚̥̺͍̰͐̍͛̄̌͠͞ダ̶̲̮̜̪͍͖͓́͊̃̀̀͑̈͑̕͠h̳̼͉̘̙̉̍̎̀͊͗̕͞′̠͕͙͚́̓̉̅͜͠′̛̗͖͈͔̦̠͉͓̾̔̓͊͌ラ̶̡̛̻̫̼̞̥̃̀̇̓̇͛͋͝͡a̶̧̟̜̯͇̘͉̥͐̃̒̆̿̀̃̔͡͠z̷̘͙̟͔̙̘̽̀́̀͋͟ŭ̸̙̤̯͇̺̞̉́̿̅̊͂̽б̶̨͕̬͓̐̂̈̍̾̚͟͠͞о̛̬̯̻͙͖͓̗̥͂̏̎̾̿̿̌ͅу̡̥̮̰͍͖͒͂͐͋̋͊͢к̷̯͙̯̪̬͌̌̓̉̌̓̅̈͌ꙑ̶̡̨̥͚͎̭͌̓͋̓̏́́̑b̛̝̼̜͙̭͌͋̈̾̆́̇̏͢u̧̧͚̺̙̟̪̹͕͑͒́̀̌̋̎͝k͇̗̻̞̗̹̅̊̃̈́̅̄̂y̴̧̡̬̳͉̦̗̻̪̓͒̌͐̄̕͠г̢̟̥̯̜̭͎̮̤̅͛̄̿̿͊̚͝͞л̴͎͇͕̯͕̞͖̊̓̍̔͑́͠͝а̨̛̱̳͖̗̯̫͗́̄̓г̢͓̠͇͎̘̝͑̃̓̓̓͟͢͠ӧ̶̧̢͍̠̜̰̩̫̜͛̐̆̂͘л̧̪̩̺̯̭́̍̌͘͜͜͜͡͝ѝ̷̹͙̝̞͓̹̤̟͋͑͂̀͊͌͐͘͢͠ (̵̨̤͕̺͍̮͙̥͖̏̀̔̽͊̆̈̉͡g̭͓͇̤͖͛͑̃̒̏̀̚͡ḻ̡̡͚̎̀̃͂͆͑̒͢͝a̵̧̺͕͙͙̦̗̔̔̐̊̈́̋͜ͅg̷̡͓̫͉̦͍̳͗͗̿̆̿́͟͟ǫ̸̟̻̺͙̼̗͂͑̍͋͋͑́͛̕͝l̡̦͕̣̪̇̒̑͐́̓͘͜͠͠ͅͅi̷͔̳͍̳̘̪̻̇̌̇̂͂̽)̛̫̮͖̪̯̇͛̒͡ͅ e̖͇̜̳̲͍̔̅̆̒̍̓͞ ê̷͔̻̜͔̄̑̉̏̌̑̒̈́̕͜͜ͅ ë̸̡̢̗͉̮̻̖͗̆͆̾͒͜͟͝͡͞ —͉̯͓͌̿͆́͋̄͜͟͡ z̸̡̛͉͖̠̦̬̺̓̈́͛͒͜h̸͙̘̫̻̠͕̺̥̅̂̐̎̌̍̈́͂͘͝ ž̷̧̠̤̖̗͎͚̖͖̘̈́̂̿̾̊̾͠ z̵͙̜͚͚͍̤̖͓͎̆̇̀͛̌͋͋̕͠͠h̸̡̢̨͉̼͔̝̋̏̿͑̓͑͟ͅ′̡̡̟̬͍̿̀͋͗͆̿͘′̲̺̣̫̻̥̤̝̯̬͗͂̾̒̇̿̎̾ ẑ̛͚͚̼̳̠͖̋̒̊̀́ z̥̫̠̯͚̭͓̪̱̆́͗̈͛̄͜h̶̡̤̺͈͙̟͆̈́̇́̈́̀′̦͈͇͇͎̭͎͗͋̄̄̎̂̿̃̓͝′̸̤̮̘̹̊̀̇̄͑̇͞ͅu̸̼͔̰̯̖̐͆͗̏͐̾͡ͅ ẑ̷̛̲̭͉̪̜̯͌̍̅̿́͢͠ͅ°̵̺̹̫̹͙͇͆̉̋̎̇̿͂͟͞͝ z̨̧̡̼̫͒̿̅̋̚h̴̛̻͇̟̫͈͉͚̀͆̌̐̀̌̈́͡ͅ′͍̠̤͉͓̦̦̦̻́͒͐͌̆̀͡ͅ ž̴͚̳̞̙͙͖̙͈̏̅̾͋͊͋̈̋͗͢′̨̟͉͔͙̐̅̓̃̀̕͟͠ z̦̬̠̳̻̃͂͋̎́̔͢͢͝ͅ ẕ̸̼̭̙̼̥̠̼̊̂̐͂͂̀͒͜͜͝ ḯ̻̖̮̦͕͊̇͋̂͂͜͝ĭ̙̟͕͈̪̝̤͎̓̅̀̔̎̊̀̐̅͂͢͜ j̷̺̺̰̺̠͎̮̣̘̄͑͗̆͂̏͆ k̵̡̬͔̬̩͇̤͐͊̅͆̃ͅ —̷̢̛̜̬͔̖̳͆̇̐̀̚͢͠ k̶̛̭̮̝̹̹̬͌̈́͋͜͟͞u̵̧̠̠͍͖͗́̆̉̄͘ k̸͎͈̣̦͌̂̏͋̊͒͢͡°̴̧̰̮̺̮̙̲̯̤̠̊̊̂̿̎̓͋ ķ̘͔̤̠̪̟̮͌̌͑̎̈̊̕′̳̱̞̥͕̥̀̄̽̏̂́̾͞′̴̧̱̖͉̗̾̏͆̾̍͆͌͞͠ͅ q̶̨̩̝̞͙͛̓̒͋͒ ķ̮̠͕̹̩̤̀̉̄̎̕͘̕͢′̨̧͖͇͈̳̣͆̑̑͂́͊͜͡′̥̳̥̦͈̫́̄́̍̔̽̑͞ứ̵͈͔̭͍͓̲͔͙͚́̆̊̏̚͠͡ q̵̢̛̼̥̭̪̼̆͋̂̑̅̚͠°͖̹̲̻̣͍̹͇́͋́̒̓͆͂̆͛͗ k̴̡̺̙͕͉̯̖̯͎͒̏̊͡͝ḣ̷̨̯̜̠̻̿͊͑̎̀͟ č̵̡̨̘͖̥͕͉̔̅̀̅͡͠′̵̸̡̡̛̳̹̰̰̲̣̲̞͕̝͇̟̩̀̀̍̈́̃̊̓̍̓̉̃̉̋͠ ḱ̵̛̛̻̗̻͉͓̀͒͞ḣ̷̭̮̰̙̞̜͎͔̪̜̔̂̈́̾̌̋̋̈́͝u̧̦̲͍̦̯̱̐̅̃̕͞ ḳ̶̡͖̮̖̹̻͐́́̀̔̇̄̑͑͢͝ͅ°̢̢̼̜͍͇͂͗͗̾̒̚ ḽ͉̰̱͈̳̺̰̮̊̍̐̏͆̌̐̕̚ l̵̨̡̛̻̻̺͚͚̤̯̺̈́̊̒̍͛͒͠ l̩̤̬̰̹̘̔̾̍̓̔̚͟′̡̭̖̼̙̩̼͆͑̃͆͆̏̽̄̾̕′̷̢͚͍̟̠͍̖̐́͋̿̓̍͂̆̍ ł̰̬̩̪̥̘̜͙̾̃͗̎̆̓̄̕͜͝͡ l̨̢̥͉̎̍̅̐̚͜͟ḣ̨̘̭̼̜͇̹͓̹̊̀̽͛̎̒̚͞͝ ḷ̡͕͍͎̥̣͚̣̞͉̐̿̇̃̄͊͂̅͘q̨̢͓̣̦̦͙̤́̃̀́̀̑̆w̵͖̥͓͚̽̾͒̀͒͘ͅͅ ḉ̡̣̮̜̗͖̞͕̊̌̽̅͌͞͝,̵̨̬̲͓̯̝͉͋̔̓͑́̂̑ķ̡̗̖̠͓͛͒̾̕͘͡ (̶̨̡̠͈̝̳̫͉͗̆̌͗̽̚2̪̮̥̣̩͔̺͚̗͗̀͛̐͗̽̍ͅ.̷̡̧̥͉̺̺͖͖̭̀̅̾͊̕͝2̧̤̭̹͈͈̭̌̔̀̃͐͟͞͞)̸̢̳͕̦̰̤̲̄̈̊́̒͝ч̨̳̭͍̬̞͍̹̏̂̀͂̿̀͠͠Ӏ̡̫̟̖̲́̐͋͑͡k̙̦̜̖͎̯͕̄̿́̇͐͌̈́̔͠ k̸̢͚͕̔̒̍͛̈̋͐͐͜͠͡ͅư̴̢̫͈̘̣̖̰̝̂̇͗̈́̾̀́͜͞͝ͅ ž̧̧̮̲̘̩̽̿̇̅̔͘͟′̺̞͓̥̳̰̾̎́̓͞ͅ′͈̳͇͙͈͈̠͐̀̇̑̍̅̾̎͞ͅư̶̡̤͓͈̪͉̠̭̣̈̽̾͋͐̇̉͟͠͞ ž̫̝̦̘̺̦̭̏̇̓͒͢͝͠′͈̰̺̖̪̦̞̀̔̇̓͋̃̏͜͡͠i̢̧̨̖̇̇̀̀̇͟͟͜͠u̸̡̧̫̱͕͔̱̥͍̬͈̩͇̒͋̓̏͐̈̆́͂͒͊̆̕̕̕͟͡͠͡͡ —̝̣̜͙̝̳̰̥̖̅̈́͑̀̾́̊̕͘͞ Є̶̨̗̠̳̜̪̯̬̜̰̒͋̄͋̀ǐ̴̡̪͖̰̜͉͒̎̌̌͞͠ą̵̴̧̛̠̞͈̳̗̥̳̘̪̻͗̑͑́́͆̽̆͊̍̎̂͘̚͘͡͡ —̤̫̖̣̪̫̿͊̾̾̇̈̅͡ ḣ̵̰̜̟̙͓͕̗̣͒͒̽͐̓̀̍̂͝ ʾ̷̦̥̘̹̻̬̯̼͈͐̈̄͌̕̚͝ ḩ̨̮͇̲̇̓̋́́̒͑͢͠ú̵̧͇͇͓̳̩̊̂̋̾́̽͘͟͢ ʾ̷̺̜͈̬̠͍͇͉͓͇̇̆͆̒͝͡°̶̡̢̢̛̱̲̠̮̭̫͐̎̈́̔̏̀̚ͅk̸̰̗͙͉͈̰̓̋̽̉̽̉͌̀̕′̛͉͕̹̣̖̄͒́̄͂̇̾́̾′͉͖̪̞̖̦͂̔͑͂̒̇͊̍͜͢ k̴̨͚̮̠̞̞̙̺͎̓̓̓̇͝′̧̼̦̜̥̞̮̖͑̇͒̿̋̀̀̓͞͡′̶̨͔̼̞̜͖̲̘̀͐͆͝͞u̱̠̗̰̜̾͊̂͟͝͡ k̛̗̮̝̠̠͙̉͠͠͝‡̵̪̞̣̗͕̱̙͔̦̀̎̓̃̀̕͜ ḵ̵͍̝̬͗̏͗͛̎̽̎̕͟‡̶̧̱̠͍̩̗͑͌̊̃̄̊̀̓̕̕͟u̗͔͈͔̤͕̓̓̐̏̍͛͌̋̂̏͜ͅ l̘̣̠̣͙̪̦̒̓͒̐͌̾ǫ̵̘̺̤̹͇͖̒̍͆͒̈́̋̈̀̄͊͢w̨̠͔͕̠͕͔͕͛͊̎̎̈̾̐̕͞͠a͖̥̜̯͉͆́̎̕͡n̲͕̞̟̺̝̠̓̍̓̔̐ṣ̷̞̰̜̜̰̌͂̒͗̒̃͢͢͢ʹ̨̹͙̼͚͉̩̗͛͆̐̓̉́ͅШ̷̮͚̥̲̘̫̯̰̀̍̒̏̊͆̈́͘͢ͅӀ̵̧̬̮͙̥̮͓̆̈̅̈́͗͞у̵̘͔̺̳̪͓̞̮̯̐͌̋͋̃̔͠ш̵̡̡͎̣͓̝͎̯̰͆͂̂̓̌͘͠Ӏ̵̨̨̧̥͕̙͖̇̅̀̍͑̋͐̕͡Ꙗ Ꙑ)4 ЧӀхуфg ɣ gu g° g′′ ġ g′′u ġ° d d dzh ǯ′ dz ʒ dzu ʒ°hu Єwダh′′ラazŭбоукꙑbukyглаголи (glagoli) e e ë — zh ž zh′′ ẑ zh′′u ẑ° zh′ ž′ z z iĭ j k — ku k° k′′ q k′′u q° kḣ č′̣ kḣu ḳ° l l l′′ ł lḣ ḷqw ḉ,ķ (2.2)чӀk ku ž′′u ž′iu͡ — Єia͡ — ḣ ʾ ḣu ʾ°k′′ k′′u k‡ k‡u lowanšʹШӀушӀу5ꙑꙗxє, ѕѣлозč̣емлꙗ, or just for short エ̨͉̦̣̪̌̊̉̈́̄̍̇͌ͅє̯͇̦̠̞̫́̒̆̐͌̏͛̒͝m̷̟̙̦̬͙̥͕̭̠̅͑̽͘͟͠ê̟̠̼͎̖̞̥̅̎̔͂̂͌̿͒ͅŗ̴̱̦͉̟̾̋̍̐̀͛̅͑̚ȩ͉̠̪̲̘͙̩̼̋̓̏̍̌̉̇̊͘͡ḷ̷͙̼̮̜̇̒̃̇͌̓̎̓ḑ̴̣̣͇̜̭̬̋̀͑͂̇͠͠ͅh̶͇̱̲̣̖̤͓̭͆̽̿̓̌̕ȧ̷̛̙̣͔̭͕̩̐̐̓͛̍̃̇͘͜ş̴̴͙̻̗̖̥̠̳̌̇̏̀̀͂͑̒͒͗̍́̔͌͘͢͜͞͡ͅ c̬̼̘̘̎̄́̿͐̒̅͘͝͞ͅ メ̡͎̯̬̥̯̾̉̈́̋̋̿̚͞r̵̺̹̰̪̈́̀̄̓̋̈͗̑͜͠͝ţ̛̖̮̼͈̮͌́́̇͂̎͆̂̚s̷̷̡̧͉̰͚͙̹̼͔͇̞͕͇̪̺͊̆̐̀̌̽͊̓̐̑́̏̇͐̐͜͡͡ͅủ͎̥͓̗̰̖͆̀͊͑̒̄́̎͐͜д̸̡̛̥̙̟̖̦̹̝́͒̊̄͒̓̓̉о̴̺̫̮̬̭̻̒̀͒̐̆̔̀͘̕͘б̹͇̹̫̝̀͐̍͌̄͘р̶̨̼̝̦̻̍͋͂̊̉͢о͇̝̬̼͛͒̀̓͌ͅ а̧̧̰̽̈̈͆͛͘͜ͅз̷̨̬̳͇̪̣́͌̉̀͋̄͠ъ̡͈̤̟̣̎̃͗͟͜͞͝;̴̩̮͈̟̗̙̤̬̭͍̓̾̃̔̂̚ ḩ̷͇̭̣̖̪̘̺̣́͆͗̐̄͆̌̋̄͘u̙͓͕̟̎̋̂̉̉̉̏̔ͅ Є̖̘̹̬̙͇̙̳̇̋̀͊͒͠͡w̡͖͚̝̩͌̒̽́̋̒͠͞ダ̛͙̣̰̳̯͌́͊̂͘ĥ̷̘̺̗͚͙͕̹͉̻͚̔̎͌͑̊̉̌͞′̴̢̧̱̗̮̞͓̱̇̌͌̓͡͞ͅͅ′̥̤̞͍̮̋̈́̽͛̆͟͞ラ̨̡̛̟̹͇̹̅͆̐̃͐́͆́͜͢͞ȃ̢̛̝̺̠͂̾̅́̚͘͜z̶͇̫̠̘̘̻̦̎̅̽͋̿̄͘͡ŭ̼̙̖̟̣͎̥̠̍̆́̀̎̎̿̚͢͢͝б̹̭̹̟͍̰̱̜̫̲̈́͒̓͐́̐́о̡̼̲̲̘͛̀̃͋͊̅̃͗̎͠у̛̻̯̜͓̔̏͋̍͜͢к̸̡̡̨̣͔̯͇͚̣͎̍͑̐͌̒̕̕͘ꙑ̸̢̡̫̙͍̰͙̮̤̅̂̊̀̀̕͠b̨̡̼͖̤͛̂̑̎̐̇͞ų̴͔̬͇͓͌͆͛͋͛̀̈́̌͟͢͠ͅͅk̴͉̟̥̘͔̻̐̿̾͌́̋͋͘͠ͅͅͅỳ̨͎̫̪̀̔̀̊͋͟͟͝г̞̪̜̪͍͉̫͕̤̀̍͌͋̋̏̏͘͡͝ͅл̴̡̪̖͉͍̩̅̆̎̆̉̈́̀͘а̦̳̺̮͎̤̲̃́̔̊̽̎̌͜ͅͅг̶̧̢̨̛͈̞͇̯͔̿͌̇͟͠ͅо̶̡̭̙̰̟̬̎̌́̆̓̏͟л͎̬̪̜̙̥̒̐̽̈̇͜͟͢и̴̝̪͇̺̮̹̠͍̩̿̍̎̓́̃́̿ (͍̙̯̯̙̫͓́͊̂̋̉̿̕̕̕ͅg̢̧̨̨̛̲̱͈̻̤̩̃̄̐̏̃̇̄̚̕ļ̶̧̨̪̜͓͓̜̑̿͒̆̿̔͌̚a͖̝̠̣̐͋̓̌̏͂ͅg̱̝͙̖̳̜̰̠͇̞̀̀̂͊̂͒̈́͋̒o̭̗̻͎̎̄̃͒͌̕͢͝l̢̜̬̫̜͇̗̎̓͂̎̉͐́͝i̵͙̰͈͔̰̭̪͌̀̔̒͐͜)̻̯̹̺̳̋̎̄̃̌͌́͆̽̚,̛̝̬̭̞͉̱̬̘̘̓̓͗̎̿̕)̴̢̮̤̦̹̟̙̼͖̱͗̎̊̔̀̅̑̓̓č̺̘̝̟͒̊̑̃͆͊͛͟͝°̷̨̳̥͔̋̒̔̽̓͛͜͢͟h̪̖̯͋̇͆̄̚͘͢͡ͅ x̧̞͙̺̼̄̔̋͗̉͘̚͠ͅ h̵̨͇͎͕̤̦̜͋̂̓̔̄͘͢͝u̵͙̤͕͕̼̱̹̓̑͑̃̏̏̚x̝͖͔̹̺̰͛̌͗͐͂̉͂͘w̢̳͙̼̘̺͉̮͋̅͒̌̿͢ h͓̝̼̻͖͛̇͑̅̐̃̿͟′̛͖̹̺̘͔̻̂̃̈͐̂̊̍͛̒′̢͇͓̮̗̠̣̣̠̿̾͒͌̾͛͗ ḩ̷̧̧̧̨̥͍̹̩͔͙̄̇̓̇́̎̄ ḣ̴̛̲̲͔̮͍̀͒͒͌̀͗̾͘′͖̮̥̦͕͕̰̦̐̓̂̀̉̽̐͗̑̽′̛̩̱̱̟̰̭̇͆̍͒͂̋͐̄͜ư̢̠̯̺͙̌̀͋͑ ḩ̷͔͇̹̲͐́̋͐̀̒̕ͅw̡̤̳͖̪̭̖̳̪̲̏͊͂͂̆̿̔ h̷̢̡͈̰̭̝͗͊͛̄̌̾̾͒̚͡′̴̢̳̦͉̫̠̟̬̍͗̃̂̒̈͢ h̷̤̬̱̮͙͖̥̳̥͍͐̑̈́͌͑̊̄͂̍̀ t̸̼̗̦̩̯͎̒̄͐̑͋̕ͅš̴̵̛̱͍̞̜͓̯̻̮̲̗̤͙̬̥̬̯̲͔́̃͊̔̈́̊͋͌́̂͒̅̀̕͡͠ͅͅḣ̸͖͓̹̪̱͙͙̒̾̿̿̌̏͝ c̮̲͕̼̣͈̱̭̖̲̾̔͂͋͌̈́̄̎͐̓̿͘͞͠͡͞ͅ ç̶̮̦̭͉̙͇̮̀̍̈̈́͆͞h̘̼̙͉͉̪͍͕̮͂͗̆͟͡͠ č̢͎͈̘̲̖̯̺͇͂͗̋̌́̄͛̿̕͘ʹ̴̧̡̗̻̭͗͋̓͒̀͝ š̶̨̢̺̟̩̝̫͈͛́̿̃͘͘͡ š̡̧̧̟̫̼͎̭͂̽͒̒̾̄̕ͅ š̺̹̲̝͔͆̿̆̓͊̾̕̕′̶̢̨͙̺̪͉̜̩͍̫̊̓̆̕͠͡͠′̸̮͓̠̯͇̫̳̿̽̒̐̑͌̒̚ s̵̶̢̲̘̹̜̺͍͓͇̗̦̀͊͛̾̓̋̄̐̀̅̋̓̌̾̈́̆͊͟͟͜͠ͅ š͈̰̖̟̾̓̇͛̉̕͢͢′̛̥̖̭͉̥̯̹̳̝̮̓͗͑̌́͂͒̊′͈͇̘̙̹̑͒̋̽̆͂́͜͝u̯̘̜̠͚͓͚̔̉͑̉̌̌ s̢̨̝̜͕͇͕̺̯͂́̏̇͑͢͝͞͠w̸̷̡̢̥͚͖̲̯͕͖̗̪͖̜͕̻̉͑̊͛̓̒̿͒́̄̽̉̎͑̎͛͋̅̈͝͠ š̷̫̱̳̙̠̩̟͒̄̋̐͛͞‡͇͎̹̼̈̈́̑̽́͊͐̚͟͝ ş̵̸̨̛̠͚̟̗͎̮͕͉̹̓̀̔̇̄͌̄̂́̇͐͋̅̾̀̌̚̕̕̕͟͢͟͜ͅͅi̤̺̦̇̈́̃͌̈́̎̑̿̚͢͟͡ü̴̧̨̯͚͍̱̘̮͖̣͚̺̣͍͚͈͈̦̈̿͑̈́͗̐̏̀̈́̉́̽͗͒͡ͅ —̷̰̮̳̻͈͈́̊̅̊̆̓͘ i̵̢̨͈̻̦̭͖̲͐̃͌͒͐͢͢a̶̧̧̛̫̯̤̥̙̗͙̰̙̺̩͔̗̤̭̔̒̇̀̄̾̾̿͜͢͠͡ —̧̛̦̟̬͕̺͍̠͑͌̓͐̒͒̕ ḣ̢̛̠̤̪̩̦͍͈̐̐̓͛̉̈̿̚͝ ʾ̧̛̻͍͎͉̮̫̘̗̗̔͑͂̋͑͗̔ ḩ̶̟͔̬͉̇͌̓̒̽̓͋͒̿̚͜u̷̢̯̭̺̗͖̺̗̓͗̓̅̂͆͒͢ͅ ʾ̧̱̦̩͉̘͙̍͑̾̂͂̎̕°̶̲̪̖̺̩͚̊͊̑͊̕͜͠š̨̲̝͓͈̞̞̙̫̋̾̀̀̊̒͛͝‡̶̳͉͎̳̲͛͊̃̅̈̓̕͘̚ừ̴̼̠̲̹̟̭͂́̏̾̐͂̃̉͟ ş̴̫͚͇͎͈̏̊͊͘͠w̷̧͓̺̫͎̼͎̟͈̠̘͍͉͈̹̾͋̆͑̀͒͗͋̂̄͛̈́̊̎͆̓ͅ ŝ̞̺̰͚̩̳̞̯̈̑̆͗̋͐̈́͐̕ ş̮͔̦̥̟̦͎́̿̓̀͛͗̊͟c̶͚͔̙͚̳̝̣̽̔͐̂̈̃̽͘̕͢͠h̴̪̪͔͉̙̦͈̪̻̹̏͒̿̇̌̀͝′̧̠̫̼̗̦̳̱͇̏̏̆̾̍̾́̅̚͟′̴̣̫͓̻̘̙͗̌̐̌͊̔͘ č͔͔͖͇͖͓́̆̆͌͝ c͙̝̞͍̣̖̱̅̑̔̄̀̎̂ḧ̷͉͙͕̦̪̟̹́̌̒͐̐́͜͞ͅḩ͖̬̮̯͔̭͇̲̇́̎̃̐͂̎̕͞ͅ č̷̡̡͚̣̖͖͎͔͓̣̺̮̟̗̼͕̼͉͙͐̋̊̅̃̎́̾̃̓̈͛͘ͅ s̶̱̳͉̘̪̹̮͊̂̃̇͗͐h̵̠͙̝͎͎̯̹̞̳̔́̽̍͝ š̥̻̗͇̩̞̦̊̃͊͌̈̿́̄̚͟ s̢͕͔̥͍͍̥͍̱̘̿͒̂̊̈̏͂̔͛̉h̛̟͓̮̮̞̮͕͖͖̝͗̀̇̽̓̍̽͝′̷̧̛̤̯̞̊͊̒́̓̚͠͡ͅ′̭̳̙̟̟̞̟̊́̀̉̊̇̏̔͞͞ͅ ŝ̴̨͎̞͍̽̍͗͗̓̀̚͜͡͠ͅ s̴̨̧͔̟̰̥̦̰̟͑̿̽̀͂̕͟h̢͉̭̘͈̖͙̄͌̏̉͘͜͞ͅ′̧͇̥̮̘̻̮̠̩̊̍̍͗̒̏́̿͘′̷͇̪͈̣̬̠̲͛̈̅͒̋́̒̾̉́ū̼͉̖̻̩̞̦͓͗͌̒̀̓́͑͟͡ ŝ̨̛͕̜̳̖͙̂̾͂̎͗̏͂̐͘°̶̢̨̹͕͇̲̖̖͇̓̌̈́͘͘͝ͅx̸̟̗͈̳͙̯̣̣̅̓͐̊͘ s̛̩̮͕̲̝̙͉̐̏͛́̍̀̓̏͢͢h̛̬͎͚͉̻̣͍͊͂̍̉́̕͘͠ḣ̜͍̳͇̑͋̇̄́͟͜ ş̴̢̨̣͍̫̺̩̯̯̑̐͌̀͌̅̂̑̀̌͛̏̓̏̋͘͘͜͞h̦̼̜͈͔́̓̿̑͝′̶̝̝̝̭̫̫͊̄͊͗͗͡′̰̲͉̳͓͇̪͕̬̖̓̋͋̑͐̎͗̚ —̺͚̖̖̰̭̮̺͋̆̑͗̿͆͆͘ y̸̮̣͓̦̳͖̼̱͂́̈̾̀͐̀͝ ǝ̴̞̘̪͇̻̗̭̺͉͑̋̍̿͒̕͜ x̸̨̥̯͍͎͂͌̄͆̐͠ ḩ̠̰͎̖͚͇̾͛̓̀̒̕͠ǔ̯̬͉̪͚̩́̌̿͋̒͛̉̌͘ͅ Є̥̪̻̤͓̤͓̂̑̽̄̐͜ͅw̴̠̮̻͈͍͇̟̬͑̄̏́͜͜͞͞͞͠ダ̭͓͕̘̞͇̮̾̀͐͌͂͗͟h̪̲̹̖̫̹̿͛̽͂̈́̉͐͠͠′̷̼͍̯͖̅̀̾́̂̾͊͞͠ͅ′̢̫̗̗̟̝̽͗͌̑̓ ḩ͔͉̟̖̣̬̩̩̿́̑̄̏̇̔̇̾̿͜͜ h̵̨̳͖̙͕̔͆̂̉͗′̻͓̭̘̆̇̀͌͞ͅ′̷̯͎̜̬̠͈̟̟̹͉͑̾͂̊̀̓̆͡u̱̖̯͚͕̹̙͊̓̊̋̀͑̆̚͜͝ ḩ̸̨̮͈̖̹̜̍̑͑̂̃̓У̧̧̨̩̤̳̰̩̖̀̈́̋̄͋͝w̡̨̩̞̦̲͚̺̳͆͗͌̑̍̚͟ h̷̜̦͉͈̪̅̃̎͂́′̴̨̝̖̤̀̈́̀̓͗̌̈͢͠ ḧ̛͉̝̹͓̥̗́̅̊̔͛̔͗̕͢͟͝ s̨̧̩̠̰̹̔̉̈́̓͆̌̍ͅḩ̸̝͚͈̼̒̂́͌͘͜͞͠͞ḩ̴̥̗̰̘̲̤͔̇̄͛̍͊̑́̕͡u̢̡͖͖̼̺͎̠͍̾̉̽͛̈́̅ ŝ̨͔͖̥̺̏͑̇͘̕͜͠°̢̳͉̪͈̣͉̹̖̺͓̖͉̊͒͋̌̎͗̏̃̊̾̑̃̄͟͜͟͠͝͡ s͉̱̩̗̹̩̗̠̐͗͗͐̃̕͡h̵̗̭̠̺̹̩̳̬̊̽̆́͋͂̊̂̈́̽ͅͅç̯̯͔͍͍̥͍͉̊̀͆̑̿̚ͅḩ̷̛̥̹̤͙̲͇̯̎̾͒͛̈͊͌͜ š̷͎̞̱̗̭̗̻͚̏̀͗̂͑͘̚͘͜͟͡ʹ̶̡̡̱̥͔̹̋͒̾͂̄͐̍̿̍̍͜Ш͖͎̯͚̠̻̞̝̭̓̾͑̓͂̅̊̽̿͌͜Ӏ̥̩̖̦͙̬̫͈̺̬̓̔͌̔͐͝͞у̸̛̙̦̼͍̦̞͎̏̎͒̓́͌͢͜ш̸̪̘̯̟͔͚̪̜̘̌̃̄̅̉̔́͆̀͠Ӏ̷͚͖̝̔̌͗͋̌͘͜͢у̘̳͔̹̠̭͚̞̮̑̏̇̈̓͋̃͡̷̛̮̤̳̥̰̻̙̐̐̀̌̎̾̓̌͞5̵̛͖͍͉̖͕̹͔̟̮̍̽̀̄̅͌͢ꙑ̨̛̼͕̮̗̹̘̯̄̿̽͞ꙗ̝̻̬̙̙͔͉̦̽̀́́̓̀͌͜͠͠͞x̨̥̻͖̝͉̖̗̹̼͆̒̄͛̿̀̕͡͞є͇̝̱̩̹̺̊͌̉͂̌͡͝͝,̠̱͎̬̪̗̔̑̽̽̔̒̎͝͞͝ͅ ѕ̢̢̺͇̤͕̫͖̠̏̾̽̎̔͂̈́̓͢ѣ̴̡̧͖͇͕͓̰̜̣̔́̐̓̆̾̋̽̇͞л̸̨̧̼̲̩̃́̽͊͆͂͘͜о̳̪̺͓̟̮̜͑̈́̄͋̐͘͢з̧͕̘͕͔͈̰̗͙̙͗̈́̽͌͂͛͘ç̸̛͎̤͕̗̻̫͎̩̣̭̪̮̠̙̰̼̌̂̀̓̈̎̑̐͆̈̿̌̏͘͢͡͝ͅе͙̙̟̼̟̂̎̆̈̋́̓͟м͓̗̺̘̩̝̫̞̹̹͛̑͌̆̌̒͘л̧̳̟̟͙͎̰̰̆̊̅̎͋̓͜ꙗ̴̩̪̩̹͈̮͉̲͇͐͛͌͘͠ͅt̴̢̛̰̪̣̣̯̹̟̗͗͌̒̋̓̆̾͋̅s̷̡̡̞̫̬̳̣̩͓̼̼͖̙͚̫̜͐̏͆̊͌̑͐̎͐̓̕͘͡͡͝͠ḩ̸̛̫̬͚͔͕̺̖̰̇͊̂̏͆̍
̷̨̜̯͓̭͎͓͙͑̎̈́͐̆̓̿̈́エ̨͉̦̣̪̌̊̉̈́̄̍̇͌ͅє̯͇̦̠̞̫́̒̆̐͌̏͛̒͝m̷̟̙̦̬͙̥͕̭̠̅͑̽͘͟͠ê̟̠̼͎̖̞̥̅̎̔͂̂͌̿͒ͅŗ̴̱̦͉̟̾̋̍̐̀͛̅͑̚ȩ͉̠̪̲̘͙̩̼̋̓̏̍̌̉̇̊͘͡ḷ̷͙̼̮̜̇̒̃̇͌̓̎̓ḑ̴̣̣͇̜̭̬̋̀͑͂̇͠͠ͅh̶͇̱̲̣̖̤͓̭͆̽̿̓̌̕ȧ̷̛̙̣͔̭͕̩̐̐̓͛̍̃̇͘͜ş̴̴͙̻̗̖̥̠̳̌̇̏̀̀͂͑̒͒͗̍́̔͌͘͢͜͞͡ͅ c̬̼̘̘̎̄́̿͐̒̅͘͝͞ͅ メ̡͎̯̬̥̯̾̉̈́̋̋̿̚͞r̵̺̹̰̪̈́̀̄̓̋̈͗̑͜͠͝ţ̛̖̮̼͈̮͌́́̇͂̎͆̂̚s̷̷̡̧͉̰͚͙̹̼͔͇̞͕͇̪̺͊̆̐̀̌̽͊̓̐̑́̏̇͐̐͜͡͡ͅủ͎̥͓̗̰̖͆̀͊͑̒̄́̎͐͜д̸̡̛̥̙̟̖̦̹̝́͒̊̄͒̓̓̉о̴̺̫̮̬̭̻̒̀͒̐̆̔̀͘̕͘б̹͇̹̫̝̀͐̍͌̄͘р̶̨̼̝̦̻̍͋͂̊̉͢о͇̝̬̼͛͒̀̓͌ͅ а̧̧̰̽̈̈͆͛͘͜ͅз̷̨̬̳͇̪̣́͌̉̀͋̄͠ъ̡͈̤̟̣̎̃͗͟͜͞͝;̴̩̮͈̟̗̙̤̬̭͍̓̾̃̔̂̚ ḩ̷͇̭̣̖̪̘̺̣́͆͗̐̄͆̌̋̄͘u̙͓͕̟̎̋̂̉̉̉̏̔ͅ Є̖̘̹̬̙͇̙̳̇̋̀͊͒͠͡w̡͖͚̝̩͌̒̽́̋̒͠͞ダ̛͙̣̰̳̯͌́͊̂͘ĥ̷̘̺̗͚͙͕̹͉̻͚̔̎͌͑̊̉̌͞′̴̢̧̱̗̮̞͓̱̇̌͌̓͡͞ͅͅ′̥̤̞͍̮̋̈́̽͛̆͟͞ラ̨̡̛̟̹͇̹̅͆̐̃͐́͆́͜͢͞ȃ̢̛̝̺̠͂̾̅́̚͘͜z̶͇̫̠̘̘̻̦̎̅̽͋̿̄͘͡ŭ̼̙̖̟̣͎̥̠̍̆́̀̎̎̿̚͢͢͝б̹̭̹̟͍̰̱̜̫̲̈́͒̓͐́̐́о̡̼̲̲̘͛̀̃͋͊̅̃͗̎͠у̛̻̯̜͓̔̏͋̍͜͢к̸̡̡̨̣͔̯͇͚̣͎̍͑̐͌̒̕̕͘ꙑ̸̢̡̫̙͍̰͙̮̤̅̂̊̀̀̕͠b̨̡̼͖̤͛̂̑̎̐̇͞ų̴͔̬͇͓͌͆͛͋͛̀̈́̌͟͢͠ͅͅk̴͉̟̥̘͔̻̐̿̾͌́̋͋͘͠ͅͅͅỳ̨͎̫̪̀̔̀̊͋͟͟͝г̞̪̜̪͍͉̫͕̤̀̍͌͋̋̏̏͘͡͝ͅл̴̡̪̖͉͍̩̅̆̎̆̉̈́̀͘а̦̳̺̮͎̤̲̃́̔̊̽̎̌͜ͅͅг̶̧̢̨̛͈̞͇̯͔̿͌̇͟͠ͅо̶̡̭̙̰̟̬̎̌́̆̓̏͟л͎̬̪̜̙̥̒̐̽̈̇͜͟͢и̴̝̪͇̺̮̹̠͍̩̿̍̎̓́̃́̿ (͍̙̯̯̙̫͓́͊̂̋̉̿̕̕̕ͅg̢̧̨̨̛̲̱͈̻̤̩̃̄̐̏̃̇̄̚̕ļ̶̧̨̪̜͓͓̜̑̿͒̆̿̔͌̚a͖̝̠̣̐͋̓̌̏͂ͅg̱̝͙̖̳̜̰̠͇̞̀̀̂͊̂͒̈́͋̒o̭̗̻͎̎̄̃͒͌̕͢͝l̢̜̬̫̜͇̗̎̓͂̎̉͐́͝i̵͙̰͈͔̰̭̪͌̀̔̒͐͜)̻̯̹̺̳̋̎̄̃̌͌́͆̽̚,̛̝̬̭̞͉̱̬̘̘̓̓͗̎̿̕)̴̢̮̤̦̹̟̙̼͖̱͗̎̊̔̀̅̑̓̓č̺̘̝̟͒̊̑̃͆͊͛͟͝°̷̨̳̥͔̋̒̔̽̓͛͜͢͟h̪̖̯͋̇͆̄̚͘͢͡ͅ x̧̞͙̺̼̄̔̋͗̉͘̚͠ͅ h̵̨͇͎͕̤̦̜͋̂̓̔̄͘͢͝u̵͙̤͕͕̼̱̹̓̑͑̃̏̏̚x̝͖͔̹̺̰͛̌͗͐͂̉͂͘w̢̳͙̼̘̺͉̮͋̅͒̌̿͢ h͓̝̼̻͖͛̇͑̅̐̃̿͟′̛͖̹̺̘͔̻̂̃̈͐̂̊̍͛̒′̢͇͓̮̗̠̣̣̠̿̾͒͌̾͛͗ ḩ̷̧̧̧̨̥͍̹̩͔͙̄̇̓̇́̎̄ ḣ̴̛̲̲͔̮͍̀͒͒͌̀͗̾͘′͖̮̥̦͕͕̰̦̐̓̂̀̉̽̐͗̑̽′̛̩̱̱̟̰̭̇͆̍͒͂̋͐̄͜ư̢̠̯̺͙̌̀͋͑ ḩ̷͔͇̹̲͐́̋͐̀̒̕ͅw̡̤̳͖̪̭̖̳̪̲̏͊͂͂̆̿̔ h̷̢̡͈̰̭̝͗͊͛̄̌̾̾͒̚͡′̴̢̳̦͉̫̠̟̬̍͗̃̂̒̈͢ h̷̤̬̱̮͙͖̥̳̥͍͐̑̈́͌͑̊̄͂̍̀ t̸̼̗̦̩̯͎̒̄͐̑͋̕ͅš̴̵̛̱͍̞̜͓̯̻̮̲̗̤͙̬̥̬̯̲͔́̃͊̔̈́̊͋͌́̂͒̅̀̕͡͠ͅͅḣ̸͖͓̹̪̱͙͙̒̾̿̿̌̏͝ c̮̲͕̼̣͈̱̭̖̲̾̔͂͋͌̈́̄̎͐̓̿͘͞͠͡͞ͅ ç̶̮̦̭͉̙͇̮̀̍̈̈́͆͞h̘̼̙͉͉̪͍͕̮͂͗̆͟͡͠ č̢͎͈̘̲̖̯̺͇͂͗̋̌́̄͛̿̕͘ʹ̴̧̡̗̻̭͗͋̓͒̀͝ š̶̨̢̺̟̩̝̫͈͛́̿̃͘͘͡ š̡̧̧̟̫̼͎̭͂̽͒̒̾̄̕ͅ š̺̹̲̝͔͆̿̆̓͊̾̕̕′̶̢̨͙̺̪͉̜̩͍̫̊̓̆̕͠͡͠′̸̮͓̠̯͇̫̳̿̽̒̐̑͌̒̚ s̵̶̢̲̘̹̜̺͍͓͇̗̦̀͊͛̾̓̋̄̐̀̅̋̓̌̾̈́̆͊͟͟͜͠ͅ š͈̰̖̟̾̓̇͛̉̕͢͢′̛̥̖̭͉̥̯̹̳̝̮̓͗͑̌́͂͒̊′͈͇̘̙̹̑͒̋̽̆͂́͜͝u̯̘̜̠͚͓͚̔̉͑̉̌̌ s̢̨̝̜͕͇͕̺̯͂́̏̇͑͢͝͞͠w̸̷̡̢̥͚͖̲̯͕͖̗̪͖̜͕̻̉͑̊͛̓̒̿͒́̄̽̉̎͑̎͛͋̅̈͝͠ š̷̫̱̳̙̠̩̟͒̄̋̐͛͞‡͇͎̹̼̈̈́̑̽́͊͐̚͟͝ ş̵̸̨̛̠͚̟̗͎̮͕͉̹̓̀̔̇̄͌̄̂́̇͐͋̅̾̀̌̚̕̕̕͟͢͟͜ͅͅi̤̺̦̇̈́̃͌̈́̎̑̿̚͢͟͡ü̴̧̨̯͚͍̱̘̮͖̣͚̺̣͍͚͈͈̦̈̿͑̈́͗̐̏̀̈́̉́̽͗͒͡ͅ —̷̰̮̳̻͈͈́̊̅̊̆̓͘ i̵̢̨͈̻̦̭͖̲͐̃͌͒͐͢͢a̶̧̧̛̫̯̤̥̙̗͙̰̙̺̩͔̗̤̭̔̒̇̀̄̾̾̿͜͢͠͡ —̧̛̦̟̬͕̺͍̠͑͌̓͐̒͒̕ ḣ̢̛̠̤̪̩̦͍͈̐̐̓͛̉̈̿̚͝ ʾ̧̛̻͍͎͉̮̫̘̗̗̔͑͂̋͑͗̔ ḩ̶̟͔̬͉̇͌̓̒̽̓͋͒̿̚͜u̷̢̯̭̺̗͖̺̗̓͗̓̅̂͆͒͢ͅ ʾ̧̱̦̩͉̘͙̍͑̾̂͂̎̕°̶̲̪̖̺̩͚̊͊̑͊̕͜͠š̨̲̝͓͈̞̞̙̫̋̾̀̀̊̒͛͝‡̶̳͉͎̳̲͛͊̃̅̈̓̕͘̚ừ̴̼̠̲̹̟̭͂́̏̾̐͂̃̉͟ ş̴̫͚͇͎͈̏̊͊͘͠w̷̧͓̺̫͎̼͎̟͈̠̘͍͉͈̹̾͋̆͑̀͒͗͋̂̄͛̈́̊̎͆̓ͅ ŝ̞̺̰͚̩̳̞̯̈̑̆͗̋͐̈́͐̕ ş̮͔̦̥̟̦͎́̿̓̀͛͗̊͟c̶͚͔̙͚̳̝̣̽̔͐̂̈̃̽͘̕͢͠h̴̪̪͔͉̙̦͈̪̻̹̏͒̿̇̌̀͝′̧̠̫̼̗̦̳̱͇̏̏̆̾̍̾́̅̚͟′̴̣̫͓̻̘̙͗̌̐̌͊̔͘ č͔͔͖͇͖͓́̆̆͌͝ c͙̝̞͍̣̖̱̅̑̔̄̀̎̂ḧ̷͉͙͕̦̪̟̹́̌̒͐̐́͜͞ͅḩ͖̬̮̯͔̭͇̲̇́̎̃̐͂̎̕͞ͅ č̷̡̡͚̣̖͖͎͔͓̣̺̮̟̗̼͕̼͉͙͐̋̊̅̃̎́̾̃̓̈͛͘ͅ s̶̱̳͉̘̪̹̮͊̂̃̇͗͐h̵̠͙̝͎͎̯̹̞̳̔́̽̍͝ š̥̻̗͇̩̞̦̊̃͊͌̈̿́̄̚͟ s̢͕͔̥͍͍̥͍̱̘̿͒̂̊̈̏͂̔͛̉h̛̟͓̮̮̞̮͕͖͖̝͗̀̇̽̓̍̽͝′̷̧̛̤̯̞̊͊̒́̓̚͠͡ͅ′̭̳̙̟̟̞̟̊́̀̉̊̇̏̔͞͞ͅ ŝ̴̨͎̞͍̽̍͗͗̓̀̚͜͡͠ͅ s̴̨̧͔̟̰̥̦̰̟͑̿̽̀͂̕͟h̢͉̭̘͈̖͙̄͌̏̉͘͜͞ͅ′̧͇̥̮̘̻̮̠̩̊̍̍͗̒̏́̿͘′̷͇̪͈̣̬̠̲͛̈̅͒̋́̒̾̉́ū̼͉̖̻̩̞̦͓͗͌̒̀̓́͑͟͡ ŝ̨̛͕̜̳̖͙̂̾͂̎͗̏͂̐͘°̶̢̨̹͕͇̲̖̖͇̓̌̈́͘͘͝ͅx̸̟̗͈̳͙̯̣̣̅̓͐̊͘ s̛̩̮͕̲̝̙͉̐̏͛́̍̀̓̏͢͢h̛̬͎͚͉̻̣͍͊͂̍̉́̕͘͠ḣ̜͍̳͇̑͋̇̄́͟͜ ş̴̢̨̣͍̫̺̩̯̯̑̐͌̀͌̅̂̑̀̌͛̏̓̏̋͘͘͜͞h̦̼̜͈͔́̓̿̑͝′̶̝̝̝̭̫̫͊̄͊͗͗͡′̰̲͉̳͓͇̪͕̬̖̓̋͋̑͐̎͗̚ —̺͚̖̖̰̭̮̺͋̆̑͗̿͆͆͘ y̸̮̣͓̦̳͖̼̱͂́̈̾̀͐̀͝ ǝ̴̞̘̪͇̻̗̭̺͉͑̋̍̿͒̕͜ x̸̨̥̯͍͎͂͌̄͆̐͠ ḩ̠̰͎̖͚͇̾͛̓̀̒̕͠ǔ̯̬͉̪͚̩́̌̿͋̒͛̉̌͘ͅ Є̥̪̻̤͓̤͓̂̑̽̄̐͜ͅw̴̠̮̻͈͍͇̟̬͑̄̏́͜͜͞͞͞͠ダ̭͓͕̘̞͇̮̾̀͐͌͂͗͟h̪̲̹̖̫̹̿͛̽͂̈́̉͐͠͠′̷̼͍̯͖̅̀̾́̂̾͊͞͠ͅ′̢̫̗̗̟̝̽͗͌̑̓ ḩ͔͉̟̖̣̬̩̩̿́̑̄̏̇̔̇̾̿͜͜ h̵̨̳͖̙͕̔͆̂̉͗′̻͓̭̘̆̇̀͌͞ͅ′̷̯͎̜̬̠͈̟̟̹͉͑̾͂̊̀̓̆͡u̱̖̯͚͕̹̙͊̓̊̋̀͑̆̚͜͝ ḩ̸̨̮͈̖̹̜̍̑͑̂̃̓У̧̧̨̩̤̳̰̩̖̀̈́̋̄͋͝w̡̨̩̞̦̲͚̺̳͆͗͌̑̍̚͟ h̷̜̦͉͈̪̅̃̎͂́′̴̨̝̖̤̀̈́̀̓͗̌̈͢͠ ḧ̛͉̝̹͓̥̗́̅̊̔͛̔͗̕͢͟͝ s̨̧̩̠̰̹̔̉̈́̓͆̌̍ͅḩ̸̝͚͈̼̒̂́͌͘͜͞͠͞ḩ̴̥̗̰̘̲̤͔̇̄͛̍͊̑́̕͡u̢̡͖͖̼̺͎̠͍̾̉̽͛̈́̅ ŝ̨͔͖̥̺̏͑̇͘̕͜͠°̢̳͉̪͈̣͉̹̖̺͓̖͉̊͒͋̌̎͗̏̃̊̾̑̃̄͟͜͟͠͝͡ s͉̱̩̗̹̩̗̠̐͗͗͐̃̕͡h̵̗̭̠̺̹̩̳̬̊̽̆́͋͂̊̂̈́̽ͅͅç̯̯͔͍͍̥͍͉̊̀͆̑̿̚ͅḩ̷̛̥̹̤͙̲͇̯̎̾͒͛̈͊͌͜ š̷͎̞̱̗̭̗̻͚̏̀͗̂͑͘̚͘͜͟͡ʹ̶̡̡̱̥͔̹̋͒̾͂̄͐̍̿̍̍͜Ш͖͎̯͚̠̻̞̝̭̓̾͑̓͂̅̊̽̿͌͜Ӏ̥̩̖̦͙̬̫͈̺̬̓̔͌̔͐͝͞у̸̛̙̦̼͍̦̞͎̏̎͒̓́͌͢͜ш̸̪̘̯̟͔͚̪̜̘̌̃̄̅̉̔́͆̀͠Ӏ̷͚͖̝̔̌͗͋̌͘͜͢у̘̳͔̹̠̭͚̞̮̑̏̇̈̓͋̃͡̷̛̮̤̳̥̰̻̙̐̐̀̌̎̾̓̌͞5̵̛͖͍͉̖͕̹͔̟̮̍̽̀̄̅͌͢ꙑ̨̛̼͕̮̗̹̘̯̄̿̽͞ꙗ̝̻̬̙̙͔͉̦̽̀́́̓̀͌͜͠͠͞x̨̥̻͖̝͉̖̗̹̼͆̒̄͛̿̀̕͡͞є͇̝̱̩̹̺̊͌̉͂̌͡͝͝,̠̱͎̬̪̗̔̑̽̽̔̒̎͝͞͝ͅ ѕ̢̢̺͇̤͕̫͖̠̏̾̽̎̔͂̈́̓͢ѣ̴̡̧͖͇͕͓̰̜̣̔́̐̓̆̾̋̽̇͞л̸̨̧̼̲̩̃́̽͊͆͂͘͜о̳̪̺͓̟̮̜͑̈́̄͋̐͘͢з̧͕̘͕͔͈̰̗͙̙͗̈́̽͌͂͛͘ç̸̛͎̤͕̗̻̫͎̩̣̭̪̮̠̙̰̼̌̂̀̓̈̎̑̐͆̈̿̌̏͘͢͡͝ͅе͙̙̟̼̟̂̎̆̈̋́̓͟м͓̗̺̘̩̝̫̞̹̹͛̑͌̆̌̒͘л̧̳̟̟͙͎̰̰̆̊̅̎͋̓͜ꙗ̴̩̪̩̹͈̮͉̲͇͐͛͌͘͠ͅt̴̢̛̰̪̣̣̯̹̟̗͗͌̒̋̓̆̾͋̅s̷̡̡̞̫̬̳̣̩͓̼̼͖̙͚̫̜͐̏͆̊͌̑͐̎͐̓̕͘͡͡͝͠ḩ̸̛̫̬͚͔͕̺̖̰̇͊̂̏͆̍
̷̨̜̯͓̭͎͓͙͑̎̈́͐̆̓̿̈́͟
    
    - 09 Дждж
 
    - 10 Дз дз

    - 11 Дзу дзу

    - 12 Ее

    - 13 Ё ё 

    - 14 Жж
    
    - 15 Жъжъ

    - 16 Жъу жъу

    - 17 Жьжь

    - 18 З з

    - 19 И и

    - 20 Й й

    - 21 К к 

    - 22 Куку

    - 23 Къкъ

    - 24 Къу къу

    - 25 КӀ кӀ

    - 26 КӀу кӀу 

    - 27 Л л

    - 28 Лълъ

    - 29 ЛӀ лӀ

    - 30 Мм

    - 31 Н н

    - 32 О о

    - 33 П п

    - 34 ПӀпӀ

    - 35 ПӀу пӀу

    - 36 Р р

    - 37 С с

    - 38 Т т

    - 39 ТӀтӀ

    - ISO 9 1995(1.0)

    - a

    - b

    - v

    - g gu g′′ g′′u d dž dz dzu e

    - ë

    - ž ž′′ ž′′u ž′ z

    - i

    - j

    - k ku k′′ k′′u k‡ k‡u l

    - l′′ l‡ m n

    - o

    - p p‡ p‡u r

    - s t t‡

    - KNAB 2003(2.0)

    - a

    - b

    - v

    - g

    - gw

    - ǧ

    - ǧw

    - d

    - dź

    - dz dzw é,je(2.1) ë

    - ž
    
    - z̄
    
    - zw̄
    
    - ź
    
    - z
    
    - i
    
    - j
    
    - k
    
    - kw
    
    - q
    
    - qw ḉ,ķ (2.2)
    
    - ķw l
    
    - ł
    
    - ļ m n o p ṗ ṗw r
    
    - s t ţ ẹ̩̪͙̫̠̈̓́̍̉̃͆͢
̨̛͙̣̩͍̗͗̌̂͛͑̈̓
̻̻̖̭̹̞̻͕̎͐̒̽̏͐͟ͅ    
̖̯͉̙̮͈̝̼͈̟͛̀̽̉͛̔͡    -̸̛̺̹̰̹̳̗͙̓̓͂̚͞ ę̷̛̜̳̙̲͓̈̈́̿͐̏̄
͙̻͇̻̤̻̎̋̀͋͊̈͆̊͜
̡̦̳̪͍̾͐͊̐̋̓    
̶̧̧͖͔̹͕̓͗̈́̀̓͌͟͠    -̷̡͍̞̟͚͊̋̌̽͂̂ ž̪̙̳̟͕̙̪̃̆̎̇̚͢ ž̢̦̩͖̘̖̺͊͌͛̋̓́̈́͟′͓̹͇̭͓͑̽̏̈́̚͘′̸̧̩̼͔̤͔̂̾̾̈́̽̆͂͜͠ ž̷̛̳͈̯̊̇̈́̔̐͆͘͜͜͡ͅͅ′̜͇̰͙̝̲͉̮͓̗̋̽̀̂̀̉͝′̤̮͎̭̐̍̈̎̑ͅũ̧͖̯͍̫͙̖̮͇̅̅̆͂͜ ž̢̠̜̙̝̎̆͊́̓͗̌͊̚͜͝′̵̨̛͇̘͙̱̤̟͂̔̑̇̚͡ ẕ͕̭̳͎̗̆̇̒̾̾̌̈̓͜
̨̯̖̱̠̆̍̍͆̿̇
̴̼̯̹͓͚̯̫͔̞̓̏̅͊̇͑̚ͅ    
̧̛̤̩̟̳̺͒̊̃̕    -̫̗͎̮̬͍̼̮͈͉̎̅͒̎̓̿̍̀̚͠ ī̲̥̬̙͖̰̖̎͗̾̾
̸̧̡̲̱͍͙̥̪̿̈͆̎͋̎͢͝
̶̥̮̞͔̝̠̤̂̽̋̓̀̐͂̄    
̷̨̮͙̖̲̤̱̖̄̆́͂̃̚ͅ    -̶͓͓̻̱̭̀͑̐̇̚ j̢͚̺̣̖͋̆͐͂̆̽͢͡͠ͅ
̷̰̳͈̣̹͐̈́͗̓͆̽́̈
̶̣̻͇̰̦̦͔̥̬̼̈̀̃̑͌̕    
̷̡̩̘͇̦͙̘͕̐̓̕̕͟͟͞    -̷̧̛͔̪͉̩͆̃̀̀͌̎̓͢͜͡͡ͅ k̵̻̼͓̭̼̤͇̣͙̎̆͛̿͊͛͡ͅ ḵ̨͍̦̟̄́͛́͗͘͜͞ư̞̹̭̜͍̟̮̞͒̾͒͒̈͂͒͂̆ ḳ̶̪͈͎̍͗̀́̑̈́ͅ′̧͇̟͙͖̣͓͕̉̑͋͐̀͠′̴̢̨͍͉͔̹͈̿̊̐͘̚͘͟͠͞ k̙͔̼̖̈͗͒͌̿̊͘͘͜͞ͅ′̸̧̧̨͖̜͕̪̫͙̌̓͒͗̓͡͝ͅ′̶̬̘̺̻͎̥͕̳̑̌͛̌͌̃̋͜u̶͚̥̰̪̺̾̄͛͋̿̆̾̓͡͞ k̵̫̟̲̣̠̩̗̓̊̈̀̑̓͊͛̏‡̗̩̞̻̻̻̇̆̑̑̕͟͢ k̸̞̹͓̮̰̘̆̉̇̉̕͢͞‡̸̡͙̝̞͇͊͒͛̂͑̑͝ư̶̡͔̫̝̬͈̹͒̽̔̐̾̐̌̊͘ͅ l̥̟̖̰͓̽̉͆̓̚
̷̛̭̩̫̻̱̓͑͗͢͝
̨̦̞̣͓͔͇̬̣͆͛̈́͐̚    
̵̛̗̥̳̰̩͎̺̮͙́̏́̅͐̚͠    -̴̧̧̛̥̻͈͇̀̊͊̏͗̈́̈̚ l̶͔̙͖̪͍͔͖̩̯͙͋͐̃͑̀̃̈̓͞͠′̨̦̘͉̩̝̇̀̽̈́͛͞ͅ′̡̱͎̦͇̙̦̱̳͒̓̍͆̍͜ l̷͚̤͖̮̱̠̈̆̈́̓͌̑͋̋̆͡‡̢̣͚̹͓̲͆̈̇̌́͡ m̸̡̨̳̮͚͈͙̙͋͌̃͂̋̉ n͚̣̙̲̫̔̉̀̽̀͞
̵̧̗̭̲͇͔̊̄̆͗̍́͌̚͜͡͠
̡̡̫̫̠͚̰̑̆̓̔͑̾͝    
̥̜̖̘̾̐̃͗͗̈́̀̏͟͠͡    -̸̡̲̺̰̜̦̬͓̙̾̏̿̎͆̃̓̂̚ ơ̤̮͎͔̦̤͒̏̀̑͂͊̾͢͝
̨̛͚͖͓̞̙͗͊̓̑͊͊̋̾͢͠
̨̱͎̦̭̖͒͂̒͊̽ͅͅ    
̲͍̻̙͕̯̱͚̠̣̊̓̌̕͞͞͝͞    -̷̢̛̟̺̙͖̑́́̒̂̀͗́ͅ p̨̯̠̰͚̭̙̐̄̓̾͘ p̵͚̪̝̺̖͐̎͗̚͞‡̺̜͉̭̤̙̋̈̇̄͆̊͑̾͌̕ p̢̝̲̣̣̫͇̳̯̾̓͋̐̿͜‡̴̜̣͎͎͉̟̜̊̉̎̄̈͒̂ư̶̧̩͉̣̆͛̅̅̒̕͠ͅ 
   
    - a ā b b v — g ɣ gu g° g′′ ġ g′′u ġ° d d dzh ǯ′ dz ʒ dzu ʒ° e e ë — zh ž zh′′ ẑ zh′′u ẑ° zh′ ž′ z z i 
    
    - i
    
    - ĭ j k — ku k° k′′ q k′′u q° kḣ č′̣ kḣu ḳ° l l l′′ ł lḣ ḷ m m n n o o p p pḣ ṗ pḣu ṗ° r r s s
    
    - t t tḣ ṭ
    
    - 40 ТӀу тӀу ̛͍̳̻͙̲̰̗͗̊͗̈̍̿̃̾͢͜
̢͇̦͚͓̫͈̃̈́̆̌̕͝    
̷̦͔̩͇̖̰̦̦̝̎͌̓̃́͐͘͡͡͡    -̶̧̛̼̭͉͔̥͕͊̅̍̿̍̎̅̔͐ z̷̶̮͖̟̜͓̤̙͕̦̬̯̫͇̙͉̣̆̇͑̍́̄̈͒̑͊͌̍̓̒̚
̴̧͕͙̺̞͖͙̾̔̽͑͊̽͜
̸͕̦̦̪̗͔͉͙͖̹̽͌̈́͂́̌̔͞͞͡    
̟̲̯̰̼̗̹̱͔̌͊͗͐̄͘͟    -̡̹̳͓̩̲̦̙̇̅́̃͠ z̨̢͍͕͙͎̳̦̰͂̄̃͊̉̔́̒̂̃w̷͉͈̝͎͚̺̟̯̱͉̱̫̓̓̏͆̐̆̄͆̏̉̈̀̌̚̚͟͜͝
̡̬̲͉̩̂̔̓̓̋̔̆͒̇̕
̤̟̞̮̭̒̒̃͑̇̏ͅ    
̶̨͔̖̩̦͌̑͐̐̎͘̕    -̛̻͓̠̗̫̯̗̎̉͑̓́́͞͝͝ ź̡̛̰͔̠̟̩͑̄̄̿̈́̈́̀͞ͅ
̶̢͚͍͈̥̺̞͋͐̓̂̒͜͜͞͞͠
̵̨̛̝̺̼͔͓̏̒̀̅̄͘͝͞    
̶͇͇̯̼̪̀́̚͟͠͞    -̢͇̹̱̻͚̻̲̂̽͑͑̂͝͝ z̵͓̫̗̭̦̄̆͒̈́́̚͠
̛̗͚̙̝͇̰̀̂͊͛̍͊͒͜
̷̡̛̰̩̦͓̘̤̗̄̃̅̂̽͐͂̆̿͜    
̵̧͚̞̮̦͓̱͉͎̄̓̈͐̈́̀    -̷̻̹̠̥͓͇̬̳̒̃͊̒̚ͅ ḯ̷̹̟͉̦͕̹̟̭̭̏̂̆̎̕ͅ
̵̡͇̯̗̘͛͛̓́̈́͢
̷̢͍͓̱͉̐͑̑͆̅̂̃̄̃͞    
̶̧̨̖̙̗̻̘̠̱̃̏̊̓͗̉̊̎̔̍͜    -͍̭͙͚̥͌̀̾̊̚ͅ j̺̼͍͇͚̀̀͐́̑̏̓
͕̘̖͔͕̇̾̌́̃̏͑̚
̴̹̬̦̟̣͚̲͙̑͆̀̎͋͟    
̞̬͓͔͔̋̅͋̒̕͜    -̴̧̡̡̼̻͈͔͍̫̺̈̾͛̑͞ k̵̳̰͍̼͇̘͚̖̲̽̔̆̆͒͗̊̃̚͢͝
̢̛̩͙͉͖͇̯̱̯̼̂͑̀͌͡
̛̣͓̹̗̮͇̜̂̒́̀̓͘͡ͅ    
̧̹̠̮̟̘̊̂́̿̎͌̕͠    -̡̳̖̹͈̮̻̥̐̑͑̇̀̊̚ k̨̡̦͈̥̹̖̮̍̀͗̀̀͆̾̕w̶̹̩̞̜͉̰̜̼͔͛͌́̐̓͋̒̌͘͠
̢̛̫̭̗̳̗̰̹̫͛́̒̋̆͗͐
̨̭͙͇̤̘̟̉͊̐̏̓̔̚ͅ    
̢̢̖͈͖̲̪̀͂͗̽̆̓̓̔̒̅͢    -̧͖̳͇͓̯̞͕́͗̊̿̈́͗́̑́̕͢ q̸̢̛̱̟̮̬̼͙̝̲̒̾͗̉̈̐́̚
    
    - 41 У у
    
    - 42 Ф ф
    
    - 43 ФӀ фӀ
    
    - 44 Х х
    
    - 45 Хуху
    
    - 46 Хъхъ
    
    - 47 Хъу хъу
    
    - 48 Хьхь
    
    - 49 Ц ц   -̵̰͓̦̤͎̯͖͓́́̐̉͛̕͜͠͞͞ 4̴̡͎̟̟̗̐̾͛̀́́͛̕͟͜͟ͅ8͓̳̠̹̪̈̎͐̌̓́͌͢͞ Х̶̛͍̗̤̳͚̭̣̇̏͛̓͌̌͗͗̍͜ь̷̢̝͎̳͚͊͆̄̌͘͜͝х̴̱͓̺̭͙̘͇͇͓̖̐̀͛̒͐̇͘͠ь̷̖̯̭̘̲͕̈́̐̓́͆͋͠͡
̡̠͙̗̪̣̳͓̀̒͆͗̇̑̈́́̒͢
̡͖̲͔̭̩̾̽͒͋͒̾͢͢͞    
̴̫̝̬̗̥̫̳̤͍̰̾̇̑͛̑́    -̷̢̡͉̮͖͙̹̜̺͛̒̈́́͒͒͜͠ 4̵̨̛̟͕̖̦͖̟̘͂̍̿̒̔͜͝9̷̮̤͍̳̰̭̬͔͇́̎̈́͆̊͗͠ Ц̵̧̢̫͈̭̲̺̊̒̌̿͢͟͠͝ ц̵̡̡̦̳͈̻̼̤̔̌̃̽͊͋̑͢͠ͅ
̴̻̺̱̩̉̈̓̆̀͒͡ͅ
̵̨̱̞̝̮̪̣͓͙̍̑̈́̀̀̏̑ͅ    
    
    - 50 Цу цу
   
    - 51 ЦӀцӀ h̵͙͚͇̫̞͔̟͈̬͚̊̆̌͑̀̾͘̚′̧͓̻̥̤̪̥͖̀̀̅̐̇͐͘͢͡ ž̷̞̺̭̳̋̈́̏̅̄͞ͅ′̼͕̗̠̭̯͉͓̃̽́̀̓̆͐͟͡ z̢͚͈͔̰̓̀̍̐͆̏͐͒̋ z̷̡̧̩͕̞̍͛̄̋̈ ì̼̗̤͓̳̂̔̽̐̾̋͛̒͟͝ 
̵̩̞̯̫̦͓̬̂̉̅̀̅͢    
̢̛̺̗͈̗̳̭̱̓̒̑͛̽̃͗̋̓͜    -̷̛̪̤͍͓̯̯̑͛̈̇̐̾͛̓̚ i̴̩̙̜̗̞̠̬̝̓̍̊̿͛̆͆̽͞
   
    - 52 Ч ч
    
    - 53 Чъчъ
    
    - 54 ЧӀчӀ
͈̯̺͍̆͐̄̎̅̍͂̚͜
̵̧͇̘͚̤̜̆̈̈́́̽̄͐̇̾͠ͅ    
̡̪̞̻͍̋̃̓̓͑̎̇͜    -͓̤̫̹̣̫͚̳̣̿̇̆̈͒̽͆̑͝ͅ ļ̷̨̛̰̲͖͕̯͓̦̐͌̿͑̄͑ m̢̝̜͓͚̞̬͉̍̃͊̉̂͢ n̷̙͈̳̖͖̹̰̠͍͒̽͂̇̎́̂̿̓ o̦̙̤̝͖̥̲̭͋̓͛͒̓͟͟ p̷̤̩̺͕̥͎͙̈̒̄̎̏͝͝͠ ṗ̨̧͖͓̥͖̘̈́͌͐̃̆̌̀͌͛͠ ṗ̸̧̢̹͍̭͓̜̮̤͉͒̅̑̉̅̄̓̃͡w̴̻͕͕̹̣͌͂͛̆̍̍̾̏̃͘͜ ṛ͈͙̹̱̊̓̀̐̚͘̕͞
̷͈͎͍̮͚͔̲̇̈̉̀͑͐͟͜
   
    - 55 Шш4̵̧̗̼͔̪͐͛̑̏̾͛ Э̧̨̟̝̪͉̺͐̓́̀͛̑̂̋̌͢ э̴͈̯͎̫͇͈͈̅̒̂́̃͒͘͢͜͡͝ͅ
͔̼̩̝̰͎̫̼̹̖̅̓̅̎̏̌͋̕͞
̝̙̣̫̗͂̐͌̋͜͝    
̶̡̦͔̻͕̰̆̃̏͆̚͞    -͚̳̥̯̱͓̾̆̇̋̿͜͠ 6̶̢͉̯͔̞͕͒̎͋̐̔̋͊̓̀5̶̨̟͈̭͖͈̥͌͛̃͜͠͠ Ю̧̡̖̦͓̱͂̋̀̏͊̀̃ю̴͇̟͍͚̳̹̤͍̘̽͑̌̆̀͐͆̐͝
̴̡̨̯̟͚̳̓͒̊̀͑͌̔̈́̾̎
    
    - 56 Шъшъ
̸̡̹̮̜͔̑̏͒͘͜͠    
̛̛͖͓͕̣͓͌͂̂͘͜͞͠ͅ    -̛̩̹̠̼͇̤̣̫͙͛͆̊̄͝͡ 6̷̧̳̞͕̝͌̀̒̍̊̒̀͠8͇̬̹̰͚́̈́͒̓̈̃͝ Ӏ̴͓̪͖̭̩̎̋͆̉̃у̢̲̪̝͔͉͚͆͐͆̈̿ Ӏ̴̹͕̖̘̲̑̓̐̃̓̚͘у̡̤̬͉̝͐̅̊̊̿̈́̃́̿̕͜
̷͇̪͚̩͇́̓̇̄͘͝
̭̥͇̬̬̔̇̂͐̐͑̀̂    
̸̨̧̰̤͔̤͔̘̯̾̒̽̄͒̀͢͠    -̵̡̻̝̣͖̬̳̲͒̔̃̔̈̽͠ I̹͇͙̗̻͂̾͂̆́̾̑̓͜͜S̢̫̻̣̘͕͔͚̲̋͋̃̆͗͋̀͘Ö̵̦̘̰̣͙̤͙́͑͌̆͂̌͗̊̚ 9̝̞͉̰͚͕͉̹͑̔̀̋͂́͒͝ Ķ̢̛̱͍̭̎̓̾̂̋͑͢Ņ̷̟̮͕̗͔̼̈́̿̉̃̊̿͑͌͒͟͝Ā̧̰̭̗̹͕̟̒̽͌̇̒̇̈́̿͟͞B͈̗͚̼̰̻̮̥̣͆͗̃̓̿͝ 1̵͓̳̬̫̮̓̿̀͌͑̀͘̚͟͜͝͞9̜̩̫͕̞̼̒́̏̀̿̏9̴̧͓͇̳̀͆͒̈́̏͜5̸̨̢̨̮̠͚͔̩̘̟̇̈́̋͋̌̈́̓̓͊͘(̷̢̢̗͙̣̪̏̅̈́̓̾͑̈́̄͛͜1̳̱͍̬̞̘͎͇͙̀̀̓̅͘͜.̶̡̝̪͖̬̥̇͑͒͛̆͐̀̕͞0̸̠̯̞̹̤̿̆̄͡͝͞)̸̢͍̭̩͖̲͎̖̰̌́͌̃͞ 2̷̛̳͈̠̫̠̘͇̐̊̋͜͝0̧̗̲̲̼͑̍̓̑̄̾́͑̑͠0̶̢͕̪̫͖̲͎̫̼̂͂͒͛͛͒͝3̨̡̞̹͎̞̩̯̒̅̓̊̕͠(̴̛̬̬̻̙̪͉̱̅͗̌̈̋͋̌̏̓2̷̣͉̦̗͍̞̄̍̿̎̾̈́̐͂̚.̸̫͕͍̪̘̞̠̺͕̆̐̌̋͡0̧̘͖͚̞̞̄͊̃̂̔͞ͅ)̷̧̡̪̹̟͈̅̈́̓̿̆́̔͠
    
    - 57 Шъу шъу
    
    - 58 ШӀшӀ̧̤͚̭̩̹̮͕͒̆͒̑̚͘
̧͉͈̇̍̎̈͜͟͡    
̜̲̝̥̣͕͐̏͒͗͗͘͝ͅ    -͈̻͇̦͙̞̗̠̓͛̆͘͝ š̨̡͉̱͎̤͂̈́͋̊͞͠ͅ š̩͎͇̫̞̻̱͒̀̇̀̕͢͜ š̡͖̰̥͓̑̃̿̽̋̏͊͝′̧̧̨̯͓͙͙̼͈͂̏̎̆̋͡′̢͔̭̰̼̾̄̿̀̄͊͡͡͝ s̷̸̛̘̙͔͙̲̝̦̙͖̝̭̫̪̐̓̅̒̒̀͆̌̄̊̂̉̃̕͜͜͢͡ š̸̨̛̩͍̘̬͖͐͋͋̾͂̓′̖̫̤̹̭̹̣͌̃̀̉̋̅′̞͎̥͈͔͎͛̊͆̈̕͞ͅu̧̖̗̼̦̬̎͂̿͋̉̇͌̽͠͠ s̛̲͔͕̳̗͇̱̽́͂͐́̃̒̕͢w̷̛̲̻͖̺͎͎̖̳̤̹̰̘̙͓̗̓͛̄́̃̄̔̈́͆̓́͂͆̚͡ š̡̡̭̳̪̘̐̂̆̈͗̐̌̚ͅ‡̴̠̦̜͕͓͔͕̓̇́̋̈́͟͟ ş̛̛̛̱̝͕̟̙̼̩̩̫͍͇̔̀̒̄̓́̋̃̆̕͘͟͞͞ͅ š̷̼̺͖̲͎̻̑̑̿̏̌̆̍̚͠͡‡̢̟͇̳̥́̈́̈̈͋́̔̕͠ṳ̢̨̞̣̞̦̞͍͓̒̄̾̿̈̏̕͡͡ ş̨̢̛̙͕̗͔̦͕͐̔̾͊͟͟w̡̧̡͎̗͇̺̥̲͚͓̳̐̆̇͐͌́̈́͋̄̊͛̋̽͂̚ ŝ͔̖̞̤͈͔̽̏̾̓̂͜ ś̸̯͉̞͖̣̘̻͈͗͗͌̇̽͝͠
̸̧̰̗̩̖̯̣͇̓̅́́̀̀͟͠
    
    - 59 ШӀушӀу


̵͇͍͓͉̦͉̏͋̽̓̏̾͜͝
̴͖̬̺̱̼̔̐̿̅͡    
̶̢̝̦͕͔̥͇̌̏̄̅̍̕͟͟͝    -̡̣̰̻͇͌͒̆̇̑̽ 2̥̹̥̝̱͕̊̐̀͆͒͘͜8̹̘̱͍̊̾́̈̇͢͟͝͝ͅ 

	
    - 60 Щщ
Л̢̳̙̺̮̗͍͉̻̒͊͂̋́̎̂ъ̸̺̰͖̖̖̳̃̃́͊̓͋͢͡ͅл̧̡͈̹͉̟̦͔͐̾̔̔̽̉̈́ъ̡̤̩̭̘͒̔̅̒̉̄̔͡
̫͚̣͙̫͉̗͎̓̃̅͋̍̒́͢͞ͅ
̸̧̨̡̖͙̣̻̺̌͗̍̏͛̓̄́͘͜    



	
    - 61 Ъ ъ 


̛̝͕̝̗͉̗̺̈́́̄̀̇̕͠͞͡    -̭̗͓̜̖̰̾̈̾̍̆̕̚ 2͈̫̖̣̘̖̘̝̿͋̎́̎̔̔̕͟9̨͔̯̙͍̪̇͐̾̅̌̉̔͒̅͟͜͠ͅ Л̷̛̠͍͕̱͈̖͍͎̓́͘͜͡͞Ӏ̧̛͕̼̥̮̥̝̈͒̾̾̽͘ л̢̨͉̰͓̫͔͈̖̰͗̏̑̊̍͝Ӏ̸̢̣̣̯̫͍̦͊͋́͒̅͐́̚ͅͅ
̛̙͕͍̫̰̝̦͓̅͒͑̓̀͜    
̴̡̣̲̳͂̓̓̊̓́̐͆͟͝    -̡̻͓̬͚͔̱̣̮̒̉̊̀̿̈̽͒͊̑ͅ q͎͔̱̤̌̽́̐̉̇̔̀͜͡ͅ


	
    - 62 Ы ы
    
    - 63 Ь ь
    
    - 64 Э э
    
    - 65 Юю
    
    - 66 Я я

ROOM
	ID 141
	NOPAINTING
	NOCYBORGS
	NAME "Scripting Tips & Tools"
	PICT "info5.gif"
	ARTIST "Alissa"
	PICTURE ID 9 NAME "info5a.gif" ENDPICTURE
	PICTURE ID 10 NAME "info5b.gif" ENDPICTURE
	PICTURE ID 11 NAME "info5c.gif" ENDPICTURE
	PICTURE ID 12 NAME "info5d.gif" ENDPICTURE
	PICTURE ID 13 NAME "info5e.gif" ENDPICTURE
	PICTURE ID 14 NAME "info3c.gif" ENDPICTURE
	PICTURE ID 15 NAME "info3d.gif" ENDPICTURE
	PICTURE ID 16 NAME "none.gif" TRANSCOLOR 56 ENDPICTURE
	PICTURE ID 17 NAME "info5aa.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 18 NAME "info5bb.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 19 NAME "info5cc.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 20 NAME "info5dd.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 21 NAME "info5ee.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 22 NAME "info5ff.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 23 NAME "info5gg.gif" TRANSCOLOR 0 ENDPICTURE
	PICTURE ID 24 NAME "info5hh.gif" TRANSCOLOR 0 ENDPICTURE
	SPOT
		ID 5
		DONTMOVEHERE
		OUTLINE 67,145  433,145  433,285  67,285
		LOC 250,215
		PICTS 16,0,0 17,0,0 24,0,0 18,0,0 19,0,0 20,0,0 21,0,0 22,0,0 23,0,0 ENDPICTS
		ENDSPOT
	DOOR
		ID 1
		DONTMOVEHERE
		OUTLINE 63,94  165,94  165,111  63,111
		LOC 114,102
		PICTS 0,0,0 9,0,0 ENDPICTS
		SCRIPT
;~MediaList~;click
ON SELECT { "click" SOUND
{ 1 ME SETSPOTSTATELOCAL } 5 ALARMEXEC
{ 0 ME SETSPOTSTATELOCAL } 40 ALARMEXEC
{ "ftp://ftp.barebones.com/pub/freeware/BBEdit_Lite_4.1.hqx" NETGOTO } 50 ALARMEXEC
}
		ENDSCRIPT
		ENDDOOR
	DOOR
		ID 2
		DONTMOVEHERE
		OUTLINE 172,94  327,94  327,111  172,111
		LOC 249,102
		PICTS 0,0,0 10,0,0 ENDPICTS
		SCRIPT
ON SELECT { "click" SOUND 


	
    - 67 Ӏ Ӏ 
̴̝̼̪̻͔͎͈͇̼͑̇̑̌̄͡    -̴̬̲̱̳̆͊͐̋̉̍͑́͜ a̛̮̩̻̠̣̜̗̽̂͊̎̎͘͟͝͡ ạ̴͚̭̤̣̄̾̏̉̃̂͊͟ b̷̡̧̜̖̠̜̮͉̫̪̽́̐̊̅͝ b̗̙͎̭̟̠̑͌̍̔͑͆̅͌̈́͜ v̢̳̥̗̹̗͗̎̋̂̓̅͑̆̾͜͜ —̷̧̢̡̼̻̞̲̥͓́̅̾̌̌͠ g̢̛̬̬̙͉̖̱̦̈́̃̀͊̓͠ ɣ̷̜͚͎̣͇̗̖͕̰̗͂̓̆͆͛̆͠ g̬͈̖͈̖̹͛͌̄̔̃͂͜ŭ̢̮̖͖̞̼̌̋̀̎͡ͅ g̵̨̡̩̬̠̹͗̔͑̏͒̉͟͞°̨̘̜͎̈́͆̆̓̚ͅ g̶̡͖̗̙͖̏̐̌̍͞′̴̢̻̠̥̘͋͌̇͆̕͟ͅ′̸̧̬̯̹̳̟̯̝̮͑̌̊́̔͂͘͝ͅ ġ̵̨̰̜̪̪̙̾̂̿̑̀͗͐͆̀͠ ģ̢̥̻̲̔̉͐͐̏̈́̈͟′̢̝̗͓̬̭͓̆͗̃̃͆̇′̭̝̮̪͓̥̍̉͊̎͋̾͌̄̄͘͟͜ų͔̥̥͖͙̾͋̆̾̽͟͡ ģ̪̥̯̮̲̠̇͒̌͆̒̌̓̔͟͢͠°̱̰̺̘͓̤̉̽͒̃͆̊̀̕ ḓ̢̛̙͖͈͖̯̝̺͆̄̍̌͂͠ d͖̼͚̟͈̪͖͖̹̙̍̆̀̓̆̎̚͘͡ d̢̡̫͙̲͙̠͆̋̈́̀̐͘͢͞ź̹̟͈̼͔͖̱̯̮̮͌͑̾͘ḩ̦͕̻̬̠̰̿̑͆͂́̈͘͡͠ͅ ǯ̫̯̦̙̲͌͋͐̅̒̋̀͌̆′̸̡͍̼͖̥͇̻͍̫̞̿͌̓̿̀͐̓́̑ d̢̥̝͉͙̘̲̼͔̙̑̓̋̀́̀̑z̨̡̛̗͎̥̄́̋̿̀̐̇͛̽ ʒ̷̧̞̻͎̲̬͌͆̈͒̕͝ d̨̡̛͇̪͈͖̰̭̥͂̆͌̉̕ͅz̢͚̲͕̪̼̣̞̬̮͌̾͑̄͘u̡͈̞͈̭͒̔̎̑̏̂̉͋̇͗ ʒ̖̘̙͕̲̳̠̮͌̀̇̒͜͠͠
    
    - 68 Ӏу Ӏу
    
̡̢̰̬̾͆͋̑͛̕͜    
͚̯̱͇̖̠̩͔̍̂̈́̇̈́͠    -̵̨̛͚̹̤͍̖͕̌̌̇̈́̀̿͆̈͟ k̸̡̢͇͔̱̖̎͑͒̃̔͝͡͠ͅ
̴̧͉͇̭̯͙̙͖̯̍͐̈́̑̏͢͠
̢̘̖͖̭̪̱̖͋͂̾̑́̏́͠    
    - ISO 9 KNAB 1995(1.0) 2003(2.0)
    
    - t‡u ţw u u
̶̛̩͖̠̰͓̇̍͊̃̄̒̋
    
    - f f f‡ f̧ (̵̖̭̺͕̠͒̌̇̾̓2̶̛̖̹̯͚̟̟̀́̑̆͌̐͘.̡͍͕͎̦̪̊̆͂̐͠
    
    - h x hu xw h′′ ḩ h′′u ḩw h′ h 
̱̼̹͕̘̆̀̀̆̑͟͜    -̨̼̦͕̳̮͚̊̔́͌̍̽̍ k̻͍̜͈̭̬̺̖̖̋̈́̓̔̍̈́ͅw̦͕̭͇͙͕̿̂͊̒̐̃̋͜͢
͚̭̺̗̼͍̗̱̌̐͒̒̂̕
    
    - c c cu cw c‡ ç
    ż̧̛̯͚̔̋̅͑͛̿̚͢͜͠w̶̧̜̟̗̘͉̗̦̗̭͚͕͎̺̑͂̉͊͛͑̽̄́̎̓͘͟͠͠
̨͎͈̤͇̩̞̣̍̊͊̄́͆̀͢
̫͓͎͓͍͎͉̙̐̓̈́̒̑́͘͠͞    
̨͉̟̲͍̓͛̓̃̎́̆͘̚͝    -̧̻̬̤̼̥̟͒̆̐̋̄̕͟͜ ź̵͔̭̙̠̹̤̭̩͖̣̈́́͑́̇͂͗̄̚̕
̢̢̛̘̞̹͖͚̤̮̍̈́̑̾̓̿́̈́̅͟
    - č ć č′′ č č‡ ç̌
    
    - š š š′′ s̄ š′′u sw̄ š‡ ş̄ š‡u şw̄ ŝ ś

͇͙̭̫̯̑͂͊̈͑̽̂̚͜    -̸̧̬̹̬̝̹͍̳̭͛́̒͆̋̈ 2̶̢̡͍͖̘̫̎͗̀̊̋̌͟6̨̢̻̯͙̼͎͈͆͛̌̃͆͘̕͢͢ К̴̨͍̖͕͖̫͙͖͌̀̈́̎͋̈̈́̋͢͟Ӏ̴̢̨̦̩̮̹̹̑͊́̔̈̇̈́͢͡у̧͓͕͖̠̀̀̑́̍͋͒̇̕͢͞ͅ к̸̡̞̪̞̣̦̤͔̙̂̒͛̽̈̂̋̆ͅӀ̶̨̩̫̞͙̙̳̖̼͙͛̂̈̓̄͌̅͆͘у̸̛̱̫̟̩̱̥͓͗͌̔͋͗ ̧̛͚͍͍̬̓͑̈́̓̈́͑̈͠
̧͚̳̤̰̼̑̓͛̈́̕
̙̜̝̰͔̰̱̿̉͒͌͘͢    
̧̢͕̳̲̖̝̗̜̑̄̿̀̒̆̒͝ͅ    -̸̭͍͚͔̟͔̃́̊̊̃̌̇͟ 2̭̼͇̙̘̮̺͊̊͐̿́͐͝7̷͓̝̣̗̣̍̍̇̆̚̚͝ Л͙͕̫̞̳̳̻̫̈̃̇͌̄̕͜ л̧̢̣̪̫̩̮̾̍̾̊̑́ͅ
̶̡̛̛̤͚̝̹̥̮̱̖͍͒͌̓̌̿͒̌͘
̛̗̥͔̟͖̣͎͋̉̿̔̿͘͞͠͞    
̴̝͉͕̞̫̠̻̺͚͐͐͛̿̎̊͆͞͠    -̡̗̻͙̰̩͕̙̄͒̿̑͋͢ 3̸̨̡͙̥̻͚̗̱̅͆́̿̇̓͗͌̾0͎͖̞̼̻̩͍͓̑̽̅̇́͘ М̡̗͉͖͙̙͓͗̆̌͑̊͆͡м̞̲͓͖̘͇͙̇͌͛͌̏̕͘͢͝
̷̛̞͙͎̠̮̲̅̈̎̐̚͜͡͝͝
̧͉͉͕̝̅͗̓͐̿́̏͆̕̚    
̡͔̬̪̰͌̓͐͋̓͠͠͠    -̴̨̡̯̫̱̖̭͕̎́̀̄̈́̎ 3̛̯̭͔̳͓̗̥͚̙̂͛̉̀̀ͅ1̲̳̺̲̺̦̑̋͂̇͋̇̐̕ Н̧̖̖͍̤̪̬͓̝̐̆͒̏̔ н̴̺͖̙͎̰͌̊̌̍͞
̴̭͓͔͕͙̖̲̱̭̉͌͒́̐̀̐͟
̬̘͚̯̙̓̀̃͆̈̇̌̍̉͢    



	
    - ′′ 
      -̫̱͖̳̪̦̗͓͂̽͌̈́̀̀ 2̴̧̡̥̗̘̝̰͊͛̀́͠ͅ3̡̖̗͍̲̱̊́̓͗̍̽̓͌̄͡ К̸̻̘͈͕̬͈̐̍͆̆̆̍ъ̛͖͙̦̘̟̎̈́͐̈̕̕̚̕͝ͅк̷̟̭̯̭̿̌̾͛̃̔̚͠ͅъ̸̨̞̼̬̦͙̔̅́̽͒̍̋
̧̼̝̤͕̦̭͚̇̐̇͛̔̎̚͜͝
̷̲̞̹̖̺̦̬̅̈̅͂̈́͞    
̨̹̹̯̫̗͉̯̘̂͂̍́̿͗̍͝    -̧̛͇̩̮͌̆̊͛̊̎̏͘͟͟͢ 2̸̢̼͎̱̖̊̋̏̈́̇͑́̓̉͘4͖̦̫̜̘̓̅̓̑͛͗͂͘͢ К̶̢̰̞̲̲̭̦̬̣̃̌͊̃̇̔̍͛̎͟ъ̻͔̤͓̭̺̃̒̅̅̎̀͗̓̍̈͜ӳ̵̧̰̹̣͙̜͛͂͑̚͢͡ к̢̻͎͎̯̝̐̈̃͐̓̉͒͛ъ̴͎̯̟̫͎̦͍̭̻̈͆̔̀̽̊̑̕͜͞у̶̯̤͍̯̳̖̅́̍͑͛͢ͅ
̵̧̡̘̖̥̝̭̓̿͛̋̔̄͘͢
̷̣̠̠͖͆̀̀́̓̐̾͟͠    
̸̡̛̺̻̖͇̥͂̈́͐̎̃͝ͅ    -̢̯̩̼͈̯̫̏̐̋̀̎͌̾̕ 2̸̢̞͍̘̰̹̘̝̒͑͐̿͆͊͞ͅ5̷͍̫̰͉̰̞̔͌̀̄̔̔ К̷̡̫͕͙͒͛̓̀̈̂͘͜͢͝͞Ӏ̧̱̮͔̳̭͎̓̂̎͛̓͜͞͡ к̛̪͇̯̣̫̥̪͓͈̑̿̍͒̽̎͠ͅӀ̦͓̩̘̺̬̝͈̈͆̄̑͂͊̊̚
̶̨͙̗̘̦̱͈̓̃̀͐̃͟͞
̵̝͍̰̆͐̅̆̓̀͌̎͐͢͟    

̭͕̟̣̬̞̝̾̊̃͌̈͑̉͗̕͜    -̥͈͈̬͙̄̔̔͟͠͡ 3̷̢̨̲̮̘̘͍̖̀͑̈́̿̈͢2̵̛̯̰̼̰̲̿̉̉́́̏̽́̿͟ О̞̫̞͎̺͆̈̂̈̕͜͞ о̢̼̗̹̲̟͍̩̇́̓̽̊
̷̢̭̼̼̺̈́̃̅̈͒̃͝͡͝
̩͉̝̩͎̙̝͓̭̈́̍̎̆̚    
͔͚͕̻̘͔̼͙̉̊̅̾̉̎̀̿̂̑ͅ    -̵̼̱̣̘̮̟̮̯̀̔̅̂͝͞͠͝ 3̝̫͓̯̫͓̮̳͍̄̒̄̾͐͡͠3̵̰̩͍̠̈́͂̄̽̑̀́̃͘͜͢͡ П̸̠̝̦̬̩͚̟͇͒͊͐̆̒̅͞ п̖͕͖̹̔͌́̋͟͞
̤̰̦̹͓͙́́̀̇̎͑͜͞ͅ
̴͍̪̩̯̟̫̅̋̏̑̓̀͂̈    
̷̧̢̛͇͔̫̗͙͍̮̞̆̉͑͒́̃̚͘͝    -̹̱̰̼̺͑͊̏̒̇̾̉͋͘͜ 3̶͓̳̼͇̦̑̂̓̿̂̎̐͛́͝4̧̢̦̜̜͌͐́̓͆͆͘̚͞ П̸̠̹̜̯̰̣̱̭̈́̀̏̽̓̀͠͡Ӏ̢̧͉̳̹̑̋̽̋̅̚͟͟п̢̠̞̦̦̱̹̍̑͑̽͟͝͡Ӏ͓͇̱̜̺̙͕̜͐͋̋̆̇͋̚̕
̸̨̜̙̠̯̱̤͑͆̒͐̾͞
̴̧̖̦̹͔̭̎̂͑́͆͜ͅ    
̴̢̯̙̰͈̖̠̣̌̅͐̇̍̒̀͠͡ͅ
̯̦͖̲͚͕͎͈͍͐̆̇̈́̎̎̍̕    
̷͕̙̙͍̪̰̰̤͐̔͆̃͢͡͞͞    -̼̯͇͔̫̜̪͙͑̒̅̀̓́͢͢ Į̶̞̹̤̗̭̳̞́͊̽̇̂̇̃͆̋͝S̸̨̩̫̫̻͔͉̑͂̆̕͢͡ͅÓ̢̻͈̖̭̣̯́̑̕̕͞ 9̴̡͚̼̝͖̙̟̑̃͗̓̾̂͟͝͡ 1̡̨̥̝̗̇̄̉́͝͡͞͞͝9̷̧̰̝͕̗̥͈̘̲̋̒̓̅̐̃̓̍̐͡9̨̲͎̪̱͈̖̼̥̑͐̐͗͆̔̃̐̋̕͟5̧͍͓̮͉͗͋͆̄͋̎͋̉̌̕ͅ(̧̳͇͔͕̝̎̂̌̄̚͜͜͠1̢̡̖̣̍͊͌̒͒͜͝.̶̘͈̼̘̣͛̒̉͒͑̿̈́̊̚͘0̶̰̠̙͉͋̋̎̉́͑̈̄̕͢)̴̦̬̤̞̺͊͑̆͆́͂͗͘̕͞
̴̨̢̫̩̭͔̺̩̠̹̒͒̌̄̿̚
̘͚̻͎̈̓͂̈̔͒̾̀̓͜͟    
̧̨̣͇͇͈͑͂̌́͝    -̷͔̪̘̣̣̯͕̥̀͌̒͗̀͑ å͍̖̤̬̣̻̲͇̑̒̅̔̑̎͝
    - y y
    
    - ′    
̷̰͓̼̞͖͍̬͊̂͒͊̏̾͌    -̷̻͍̙͎̗̹̹̔̇̓̈̃̎͟ 3̛̯͈͎͉̦̩̳̳̏̍̀͡7̣̙̥̘͛̑̌̀͢͜͠͝ С̷̨̧̣̳̦̰̈̈̒̓͑͗ с̜̦̲̰̦̻͒̂͛̊̃͑̍̾
̴̧͉͇̭̯͙̙͖̯̍͐̈́̑̏͢͠
̢̘̖͖̭̪̱̖͋͂̾̑́̏́͠    

    
    - è e
    
    - û ju â ja ‡ x̧ ‡u x̧w
    
    - ALA-LC TITUS 1997(3.0) 2000(4.0)
    
    - tḣu ṭ°
    
̸̧̜̣̪̞̳͔̟̂͒̽̎͒̂    -̢͎̜̤̼̙̥̣̈͗́̀̄̇͑̚͟ͅ 3̶̧̢̼̙̻͇̤͉̺́̓̄́̌͑̽͘5̺̗͇̙̉͗͋͑̏̀͐͆̅̿͢͢ П̨̧͉͍̝̟̗͒̓̋̊͋͂͞Ӏ̶̡̢̛̩̮͖̓̆͘̕у̷͇̭͇͓͍̀̈́̆͋͘͡͡ п̢̝͉̪͐͐̏̓͆̿͂ͅӀ̶̧̨̧̨̛̲̲̱͇̺̈̃̿̿̈́͊͋͐̈у̵̧̦̘͔͖͉̰͈̌͛͂͗͋
̴̡͕̦̤̙̹̗̙́̍̓̾͘͜͟͝
̧̛̛̺͇̺̹̱̪̮̠̩̅͊̈́͛͆͑͝͠    
̢̹͙̞̘͈̲̪̯̦̉͒́͊̈͊̅͐̕̕    -̶̨͓͓̙̭̲͌̀́̈́̌̅̚͢ 3̵̢͉̪͕̺̦͐̉́͑̏͠6̪̲̻͓͉̊̌͑̀͘͘͠͡ Р̶̛̛͓͔̜̯̫͕̿̋̿̎̽̿́͞ р̴̧͉̤̗̯̜̮͖͑̂̉͑͑̅̊̌̈́̒
̡̡̧̱̬̲͖͉̀̐͆̎̃̾͞
̨̖͈̟̲͉̀͂́͋̚  ̶̛̩͖̠̰͓̇̍͊̃̄̒̋
̦͇̖̹̩̣̼̀̑̔̋̀́
͉̰͙͍̰̜͌̿̍͑͊͑̚͜͞ͅ    
̴̰͖̹̹͎̄̈́̎͞͞͝    -̵̡̛̤͇̲͈̼̪̝̂̑̈́͋̋ͅ 3͓̲̝̫̳̜͕̄́̃͂̿̎̈̽͠8̵̡̪̣͓͎̣̩̐̇̾͌̏͜ Т̴̢̨̨̡̡̣͇̟̬̫̎̓͑͌͐ т̧̛͙͍͓̻͉͈̓̑̍̎͆͠͞
̷̡̢͓̭͉͕̺̫̌̓̿͒̍̅͘͢͞
̷̛̩̹͍̫̟̘́̑̾̋̑̂͘͞    
̧̢̞̫̟̣̳͕̱̓̏̂͛̕͜    -̶̝̞̤̪͂̓͒͒̒͒̇͠ͅ 3̶̟͉̬̤̽̌̐͆͛͟9̴̠͈̻͉͚͙̝͕̱̀̇͛̒̆̽̃̚͡ Т̼̼̫͖̲͕̼̏̽̄̈̿̏̈̏́͘Ӏ̷̲̣͉̞͇̗͎͙̇͊́͗̂̊́̌͊͢ͅт̗͓͔̥͗̇͊̀̓͢͠͡͝ͅӀ̛͉͔̦̤̝̇̇̃͐́͢͠
    - u w,u f f
    
    - fḣ — kh x khu x° kh′′ χ kh′′u χ° kh′ ḥ
    
    - ts͡ c ts͡u c° ts͡ḣ c̣ ch čʹ ch′′ č chḣ č̣ sh š sh′′ ŝ sh′′u ŝ° shḣ ṣ̂ shḣu ŝ°̣ shch šʹ
    
̱̼̹͕̘̆̀̀̆̑͟͜    -̨̼̦͕̳̮͚̊̔́͌̍̽̍ k̻͍̜͈̭̬̺̖̖̋̈́̓̔̍̈́ͅw̦͕̭͇͙͕̿̂͊̒̐̃̋͜͢
͚̭̺̗̼͍̗̱̌̐͒̒̂̕
̨̢̛̗̞̩̫̹̜̟̺̉̈̽̉̏̌͌͞
̦̻͈̠͎̣́̀̔͊̅̍͡͡    
̫̺̗̮̓̈͒̈́̀̈́͜͡͞ͅ    -̡̢̰̼̟͕̠̩̭͗͆͑̋̕͠ q̷̡͈̺̜͚̭͆͐̈́͛̊̈́̌͜w̶̨̞̦̥͙̅̅́͗͋͌́́̇ ḉ̸̨̛̮͔̙̥͉̱̤̞̀͆̿͒̉,̶̡̭̙̦̀͂͌͒̿͛͢ķ̧̨͉̰̖͉̥̙̀̇̈͊͟͝ (̵̖̭̺͕̠͒̌̇̾̓2̶̛̖̹̯͚̟̟̀́̑̆͌̐͘.̡͍͕͎̦̪̊̆͂̐͠2̡͓̮̻͎͓̱̯̺̅̀̓͋̒)̲̼͔̰͎̊̄̔̔͛̈̚̕͞
    - ′′ — y ǝ
    
    - ′ — ė ă
    
    - iu͡ — ia͡ — ḣ ʾ ḣu ʾ°
    
    - 
