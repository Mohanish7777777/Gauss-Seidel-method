# Gauss-Seidel-method

Question:
Solve the system of equations 𝟒𝒙 + 𝒚 + 𝒛 = 𝟏; 𝒙 + 𝟑𝒚 + 𝒛 = 𝟐; 𝒙 + 𝒚 + 𝟓𝒛 = 𝟑, using
Gauss-Seidel method.

Program:
```python
x0=0; y0=0; z0=0
for i in range (1,10):
x=1/4*(1-y0-z0)
x0=x
y=1/3*(2-x0-z0)
y0=y
z=1/5*(3-x0-y0)
z0=z
print ("The approximate solution of x = %.4f, y= %.4f, z=%.4f"%(x, y,z))
```
Output:
The approximate solution of x = 0.0000, y= 0.5000, z=0.5000
