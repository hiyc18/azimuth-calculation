# azimuth-calculation
Function azimuth-calculation(A As Double, B As Double, C As Double, D As Double) As Double
X=COS(A)*SIN(C)
Y=SIN(A)*COS(C)
Z=COS(D-B)
AA=Y*Z
DD=SIN(D-B)
FF=COS(C)
EE = X - AA 
BB= DD*FF
azimuth-calculation=ATAN2(EE,BB)
End Function
azimuth calculation
