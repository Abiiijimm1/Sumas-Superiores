# Sumas-Superiores
clc
clear
x=1:0.001:4;
y1= (x.^2)+2;
y2= (x.^2)-1;
x3= -2:0.001:3;
y3= (-x3)+1;
x4= 2:0.001:5;
y4= 4*x4+5;
x5= -3:0.001:3;
y5= 3*1/3*(x5.^2);
hold on
plot(x,y1,'r','linewidth',2)
plot(x,y2,'b','linewidth',2)
plot(x3,y3,'y','linewidth',2)
plot(x4,y4,'g','linewidth',2)
plot(x5,y5,'r','linewidth',2)
hold off
