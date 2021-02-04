```
"Source-code do terceiro episódio"
ull
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
If (K=105 and N=1) or K=92:Then:1→N:Goto 00:End
If (K=105 and N=2) or K=93:Then:2→N:Goto 00:End
If (K=105 and N=3) or K=94:Then:3→N:Goto 00:End
If (K=105 and N=4) or K=82:Then:4→N:Goto 00:End
If (K=105 and N=5) or K=83:Then:5→N:Goto 00:End
If (K=105 and N=6) or K=84:Then:6→N:Goto 00:End
If (K=105 and N=7) or K=72:Then:7→N:Goto 00:End
If (K=105 and N=8) or K=73 or K=45:Goto 08
End
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
Goto M1
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
DelVar Y₁:DelVar Y₂:DelVar Y₃
Func
BackgroundOff
BorderColor 2
If N=1:Goto
```
