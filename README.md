import math
ang = float(input("Digit um ângulo: "))
sen = math.sin(math.radians(ang))
cos = math.cos(math.radians(ang))
tan = math.tan(math.radians(ang))
print("O ângulo de {} tem o SENO de {:.2f}, COSSENO {:.2f} e TANGENTE {:.2f}".format(ang, sen, cos, tan))
