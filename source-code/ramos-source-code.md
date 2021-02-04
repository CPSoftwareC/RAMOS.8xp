```
"Source-code do quarto episódio"
Full
Lbl 0
ClrHome:1→N:1→M
Output(1,12,"Ramos
Output(2,1,"==========================
Output(3,1,"
Output(3,2,"1: 1 ramo
Output(4,2,"2: 2 ramos
Output(5,2,"3: 3 ramos
Output(6,2,"4: 4 ramos
Output(7,2,"5: 5 ramos
Output(8,2,"6: 6 ramos
Output(9,2,"7: 7 ramos
Output(10,2,"8: Sair
Output(3,14,"9: 8 ramos
Output(4,14,"0: 9 ramos
Output(5,14,"A: 10 ramos
Output(6,14,"B: 11 ramos
Output(7,14,"C: 12 ramos
Output(8,14,"D:Conf. graph
Output(9,14,"E:Informaçöes
Output(10,24,"[1]
Goto M0
Stop
Lbl M0
Repeat K≠0
getKey→K
End
If K=34 and N=8
Then
0→K
Output(N+2,1," "
1→M
Output(M+2,13,"
Goto M1
End
If K=25 and N=1
Then
0→K
Output(N+2,1," "
7→M
Output(M+2,13,"
Goto M1
End
If K=34 and N<8
Then
Output(N+2,1," "
N+1→N
Output(N+2,1,"
End
If K=25 and N>1
Then
Output(N+2,1," "
N-1→N
Output(N+2,1,"
End
If K=26 and N≠8:Then
Output(N+2,1," "
N→M
Output(M+2,13,"
Goto M1
End
If K=26 and N=8:Then
Output(N+2,1," "
7→M
Output(M+2,13,"
Goto M1
End
If (K=105 and N=1) or K=92:Then:1→P:Goto 00:End
If (K=105 and N=2) or K=93:Then:2→P:Goto 00:End
If (K=105 and N=3) or K=94:Then:3→P:Goto 00:End
If (K=105 and N=4) or K=82:Then:4→P:Goto 00:End
If (K=105 and N=5) or K=83:Then:5→P:Goto 00:End
If (K=105 and N=6) or K=84:Then:6→P:Goto 00:End
If (K=105 and N=7) or K=72:Then:7→P:Goto 00:End
If (K=105 and N=8) or K=73 or K=45:Goto 08
If K=74:Then:8→P:Goto 00:End
If K=102:Then:9→P:Goto 00:End
If K=41:Then:10→P:Goto 00:End
If K=42:Then:11→P:Goto 00:End
If K=43:Then:12→P:Goto 00:End
If K=51:Goto C
If K=52:Goto I
Goto M0
Stop
Lbl M1
Repeat K≠0
getKey→K
End
If K=34 and M=7
Then
0→K
Output(M+2,13," "
1→N
Output(N+2,1,"
Goto M0
End
If K=25 and M=1
Then
0→K
Output(M+2,13," "
8→N
Output(N+2,1,"
Goto M0
End
If K=34 and M<7
Then
Output(M+2,13," "
M+1→M
Output(M+2,13,"
End
If K=25 and M>1
Then
Output(M+2,13," "
M-1→M
Output(M+2,13,"
End
If K=24:Then
Output(M+2,13," "
M→N
Output(N+2,1,"
Goto M0
End
If (K=105 and M=1) or K=74:Then:8→P:Goto 00:End
If (K=105 and M=2) or K=102:Then:9→P:Goto 00:End
If (K=105 and M=1) or K=41:Then:10→P:Goto 00:End
If (K=105 and M=1) or K=42:Then:11→N:Goto 00:End
If (K=105 and M=1) or K=43:Then:12→N:Goto 00:End
If (K=105 and M=1) or K=51:Goto C
If (K=105 and M=1) or K=52:Goto I
If K=92:Then:1→P:Goto 00:End
If K=93:Then:2→P:Goto 00:End
If K=94:Then:3→P:Goto 00:End
If K=82:Then:4→P:Goto 00:End
If K=83:Then:5→P:Goto 00:End
If K=84:Then:6→P:Goto 00:End
If K=72:Then:7→P:Goto 00:End
If K=73 or K=45:Goto 08
Goto M1
Stop
Lbl 08
ClrHome
Output(1,8,"CP Software"):Stop
Lbl C
"Config original"
Stop
Lbl I
"Info"
Stop
ClrHome
Input "1° ramo=",Str1
Input "1° condiçäo=",Str2
Input "2° ramo=",Str3
Input "2° condiçäo=",Str4
StringEqu(Str1,X₁):StringEqu(Str2,Y₁):StringEqu(Str3,X₂):StringEqu(Str4,Y₂)
"piecewise(X₁,Y₁,X₂,Y₂)"→Y₁
DispGraph
Stop
Lbl 00
StoreGDB 0
FnOff 
Func
BackgroundOff
BorderColor 2
AxesOn BLACK
If P=1:Goto 1
If P=2:Goto 2
If P=3:Goto 3
If P=4:Goto 4
If P=5:Goto 5
If P=6:Goto 6
If P=7:Goto 7
If P=8:Goto 8
If P=9:Goto 9
If P=10:Goto 10
If P=11:Goto 11
If P=12:Goto 12
Stop
Lbl 1
Disp "lbl 1"
Stop
Lbl 2
Disp "lbl 2"
Stop
Lbl 3
Disp "lbl 3"
Stop
Lbl 4
Disp "lbl 4"
Stop
Lbl 5
Disp "lbl 5"
Stop
Lbl 6
Disp "lbl 6"
Stop
Lbl 7
Disp "lbl 7"
Stop
Lbl 8
Disp "lbl 8"
Stop
Lbl 9
Disp "lbl 9"
Stop
Lbl 10
Disp "lbl 10"
Stop
Lbl 11
Disp "lbl 11"
Stop
Lbl 12
Disp "lbl 12"
Stop
```
