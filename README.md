# Trabalho-de-Modelagem-Computacional
Grupo: Arthur Agostinho Nogueira e Bianca Rodrigues de Oliveira Neves

O trabalho realiza pelo Método do Gradiente a otimização de custo de um tanque cilíndrico de armazenamento, na qual o custo é calculado pela fórmula f(r,h)= 150(PI * r^2) + 100(2 * PI * r * h) + 200(PI * r^2), onde r é o raio da base e h é a altura do tanque. No entanto, O tanque deve possuir um volume mínimo de 500m^3, isso gera uma restrição espressa por g(r,h)= 500 - PI * r^2 * h. Para fazer com que o algoritmo respeite o volume mínimo do tanque utilizamos a função de penalização P(r,h)= f(r,h) + mi * [max(0, g(r,h))]^2.
Para esse código assumiremos r=3.8155836121747724 e h=9.148480679540238 para o chute inicial.
