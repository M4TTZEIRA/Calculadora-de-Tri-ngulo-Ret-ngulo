from math import sqrt
co = float(input('Qual o Cateto Oposto ?'))
ca = float(input('Qual o Cateto Adjacente'))
h = sqrt(co**2 + ca**2)
#h = math.hypot(co, ca)
print('tendo o cateto oposto sendo {:.2f}, e o Adjacente {:.2f} a Hipotenusa seria: {:.2f}cm'.format(co, ca, h))
