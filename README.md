# MSXBasicFizzbuzz
Solution for MSX Fizzbuzz


10 FOR A=1 TO 100 STEP 1
15 IF A MOD 5 = 0 AND A MOD 3 = 0 GOTO 16 ELSE GOTO 20
16 PRINT "FIZZBUZZ"
17 GOTO 60
20 IF A MOD 5 = 0 THEN PRINT "FIZZ" ELSE GOTO 30
30 IF A MOD 3 = 0 THEN PRINT "BUZZ" ELSE GOTO 40
40 PRINT A
60 NEXT A
70 END
