---
path: '/iot'
cover: '../2020-04-11/drone.png'
date: '2020-04-11'
title: 'Physics Behind Drones'
tags: ['drones', 'technology', 'innovation', 'coding', 'tutorial', 'uav']
published: true
---

DRONE
WHAT IS DRONE?
An unmanned aerial vehicle (UAV) or commonly known as drone, is an Aircraft without a Human piolet on board. Drone includes a UAV, a ground based controller, and a system of communications between these two.

PHYSICS BEHIND DRONE:
Physics behind drone is very simple.
The three basic concepts behind flying of drone are:

1. Angular momentum
2. Newtons third law
3. Thrust

Consider a quadcopter.

//IMAGE

Working:
• In this above picture, top view of a drone is considered. In a quadcopter, consider two opposite propellers to rotate in clockwise direction and other two in counter-clockwise direction.
• Let the distance between flight controller and propellers be ‘R’ and radius of each propeller be ‘r’.
• Let ‘M’ be mass of Drone.

THRUST: It is a force or push in specified direction by an object.
• Hence in quadcopters or any multicopters, propellers play major role for exhibiting thrust, that is they exert downward force which pushes the drone upwards. This is how drone flys.
• Remember that force applies by propellers, that is thrust exhibited should be greater than mass of drone

THRUST> MASS OF DRONE [box]

PHYSICS:
One of the common questions asked,
WHY DOES TWO PROPELLERS OF DRONE NEED TO BE TURNED IN CLOCKWISE DIRECTION AND OTHER IN COUNTER-CLOCKWISE DIRECTION?
Newtons third law explains this question.
• Remember, all the propellers push the air downwards. As per NEWTONS third law, FOR EVERY ACTION, THERE IS EQUAL AND OPPOSITE REACTION.
• Since propellers are rotating , that is their rotation is action and so caused angular momentum is reaction (as per Newtons third law).
• Hence, angular momentum gets balanced and more force is applied by propellers which is their thrust. So, THRUST applied is main factor for taking off of drone.
• Hence, More the thrust, more is efficient is the drone.

EXPRESSIONS FOR MAGNITUDE OF TORQUE:

We know that torque is product of angular acceleration and moment of inertia, that is
τ = Iα
τ = torque, around a defined axis (N∙m)
I = moment of inertia (kg∙m2)
α = angular acceleration (radians/s2)

Since propellers are in shape pf circular ring, moment of inertia about its centre is M\*(a^2)/2.
Hence, moment of inertia about any other point which is at a distance ‘d’ with respect to centre is given by PARALLEL AXIS THEOREM.
I = Icm + Md2

I=(M*a^2)/2 + M*(R^2) (box) [for one propeller]
For total inertia, multiply by 4, that is:
I(total)=[(M*a^2)/2 + M*(R^2) ]*4 (box)
Total torque= α *I[total]
HENCE, FOR DRONE TO FLY, THRUST SHOULD BE GREATER THAN total torque,
THRUST > α *[(M*a^2)/2 + M*(R^2) ]*4 (box)
