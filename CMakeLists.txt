cmake_minimum_required(VERSION 3.21)
project(Projet_Takuzu C)

set(CMAKE_C_STANDARD 99)

add_executable(Projet_Takuzu main.c grilles.c grilles.h indice.c indice.h fonctions.c fonctions.h)
