# ITERATIVE-LINEAR-QUADRATIC-REGULATOR

<img width="740" alt="Screen Shot 2023-04-20 at 2 55 27 PM" src="https://user-images.githubusercontent.com/57395643/233461460-d5d6979d-f2b3-46bb-a50a-991636da4e42.png">


Following are the plots for quadrotor reach a vertical orientation θ = π/2 at thelocationx=3andy=3attimet=5. Duringtherestofthemotion,the robot should try and stay close to the origin. It should also try to keep its control u close to the control needed to keep the robot at rest. We want to make sure the robot reaches the origin z = 0 at the end of the movement.


<img width="735" alt="Screen Shot 2023-04-20 at 2 57 07 PM" src="https://user-images.githubusercontent.com/57395643/233461898-125e9ea2-113a-4412-ad53-aab8818b980a.png">
<img width="532" alt="Screen Shot 2023-04-20 at 2 57 15 PM" src="https://user-images.githubusercontent.com/57395643/233461917-adcba207-d729-4a05-ae87-b801a4275503.png">


we want the robot to do a full flip, trying to reach the upside-down state x = 1.5,y=3and = att=5anduprightstatex=3,y=0andθ=2π
at T = 10 It was difficult to tune the flip. I was able to do the flip but quadrotor lost control after that. As you can see in the plots, theta reaches 180 degrees but looses control afterwards. Following are the plots for the same:
<img width="591" alt="Screen Shot 2023-04-20 at 2 57 30 PM" src="https://user-images.githubusercontent.com/57395643/233461951-63ce8e02-6c1a-4258-9995-e45b707dec83.png">
