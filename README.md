# Forward Kinematics For 3 dof arm
![IMG_2172](https://github.com/user-attachments/assets/d53d9e08-8f5b-4e4e-baf8-98d6ed901f07)

<br><br>
x = l1 cosθ1 + l2 cos(θ1+θ2) + l3 cos(θ1+θ2+θ3) <br>
y = l1 sinθ1 + l2 sin(θ1+θ2) + l3 sin(θ1+θ2+θ3) <br>
θ = θ1+θ2+θ3 <br>
<br> <br> <br>
# Inverse Kinematics For 3 dof arm
![IMG_2171](https://github.com/user-attachments/assets/1114a9ce-0710-45e0-b577-d31dfe563371)

<br><br>
x2 = x3 - l3 cos(θ)<br>
y2 = y3 - l3 sin(θ)<br>
cosθ2 =  ( x2^2 + y2^2 + l1^2 + l2^2 ) / 2 * l1 * l2 <br>
θ1 = θ - θ2 <br>
θ3 = θ1 + θ2 <br><br><br>

