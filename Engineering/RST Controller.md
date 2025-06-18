Type of [[controller]] which is [[discrete]] controller, that has one addition [[degree of freedom]] in comparison with classical series compensators such as [[PID]] controllers.

![[Pasted image 20250604140250.png]]


Based on 3 signals u{k} - control [[signal]], y{k} - measured output, r{k} -reference signal
Based on Z^1 that is [[backwards shift operator]]  

P it is desired [[closed loop]] polynomial that has desired [[pole]]s location 

the [[polynomial]] equation for P has to be solved to find S and R polynomials 
T is prefilter for reducing [[steady state error]] P(1)/B(1) 

It is mentioned RST calculation: [[Diophantine Equation]] 

A and B are plant polynomials in equations so constants P is desired result of an equation (polynomial as well) R and S can be tuned. As I understand R and S can be any polynomials so to solve such equation we have to define amount of variables in each polynomial (should be based on a properties of TF polynomials).  Maybe like this deg(R) = deg(B) - 1; deg(S) = deg(A) -1. And Here we are comming to the ide of:

![[Pasted image 20250606112902.png]]
p =x*M*  now we heave to define [[matrix]] M.  size(M) = (nA + nB +1) X (nA +nB+1)