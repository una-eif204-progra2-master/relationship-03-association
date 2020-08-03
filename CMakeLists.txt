cmake_minimum_required(VERSION 3.14)
project(relationship-03-association)

set(SOURCE_FILES main.cpp Doctor.cpp Doctor.h Paciente.cpp Paciente.h)

add_executable(RelacionAsociacionSimple ${SOURCE_FILES})