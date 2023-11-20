# DT4X-on-TwoTank-System

This repository goes along with the article Tree based Diagnosis Enhanced with Meta Knowledge Applied to Dynamic Systems written by Louis Goupil, Louise Travé-Massuyès, Elodie Chanthery, Thibault Kohler and Sébastien Delautier.
It is used to store the dataset used as input to DT4X in order to build the explainable diagnosis tree.

The folder Trees contains images of the tree at different steps of the training and the final form of the tree.

The variables used as input for the training of DT4X are:

mQ0, the measure of the outflow to the customer
mUb, the measure of the position of the valve Vb
mUp, the measure of the output signal of the PI controller
mP1, the measure of the pressure in the tank 1
mP2, the measure of the pressure in the tank 2
my1, the measure of the height of water in the tank 1
my2, the measure of the height of water in the tank 2
mQp, the measure of the input flow to tank 1

The twelve possible faulty scenarios are:

PI controller KO
Pump fault
Sensor fault Up
Sensor fault Ub
Sensor fault Qp
T1 leak
T1 level sensor fault
T1 sensor fault not 0
T2 leak
T2 level sensor fault
Valve Vb stuck closed
Valve Vb stuck open
