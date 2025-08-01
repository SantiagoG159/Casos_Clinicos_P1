# Casos_Cl-nicos_P1
LEER M
LEER frecuencia
    SI frecuencia < 60 O frecuencia > 100 ENTONCES
        fuera_de_rango = fuera_de_rango + 1
    FIN SI
FIN REPETIR
SI fuera_de_rango > 3 ENTONCES
    ESCRIBIR "POTENCIAL ARRITMIA"
SINO
    ESCRIBIR "RÍTMICO"
FIN SI
FIN
