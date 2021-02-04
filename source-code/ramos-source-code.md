```
"Source-code do segundo episódio"
StoreGDB 0
DelVar Y₁:DelVar Y₂:DelVar Y₃
Func
BackgroundOff
BorderColor 2
Lbl 0
ClrHome:1→N
Output(1,12,"Ramos
Output(2,1,"==========================
Output(3,1,"
Output(3,2,"1: 1 ramo
Output(4,2,"2: 2 ramos
Output(5,2,"3: 3 ramos
Output(6,2,"4: 4 ramos
Output(7,2,"5: 5 ramos
Output(8,2,"6: 6 ramos
Output(9,2,"7: Pág. seg.
Output(10,2,"8: Sair
Output(10,26,"1
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
1→N
Output(N+2,1,"
End
If K=25 and N=1
Then
0→K
Output(N+2,1," "
8→N
Output(N+2,1,"
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
Goto M0
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
```
