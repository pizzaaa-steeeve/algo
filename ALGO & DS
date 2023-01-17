# algo
VAR
   a,b,c:= INTEGER ;
   sentc:= STRING[] ;
BEGIN
  a:= 0 ;
  b:= 1 ;
  c:= 0;
  write("type the sentence")
  read(sentc)
REPEAT
   IF (sentc[a]=" ") THEN
       b:=b+1 ;
   END_IF
  IF (sentc[a] in ["a","e","u","i","o","y"]) THEN
   c:= c +1 ;
   END_IF
   a := a+1 ;
UNTIL (sentc[a]=".")
write( "The length of the sentence ",a+1 )
write ("The number of words in the sentence ",b)
write ("The number of vowels in the sentence ",c)
END
