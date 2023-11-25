# Explicit Model Predictive Control (MPC) using Decision trees and Random forests for differential game

## Abstract—
Here we investigated, the suitability of decision
tree/random forest classifiers for learning the feedback
solutions to time-optimal control problems and pursuit evasion
games involving Dubins vehicles, is investigated. Recent results have shown that feedback solutions to the game of two cars
are bang-bang with the pursuer and evader controls switching
between extreme values based on the relative geometry of
the players. However no explicit formula for the feedback
laws exist. This article demonstrates that this geometry based
logic can be learnt by decision trees/forests quite efficiently,
resulting in relatively simple implementations of the feedback
laws. The laws thus learned matches with analytical solutions
for the variants of the game where these are known. For
the cases where such closed form solutions are unknown, the
decision tree/forest based laws match with optimal trajectories
computed according to other available numerical methods.
Once trained, the decision trees/forests are evidently much
more efficient in computing the instantaneous feedback as
compared with other computational methods designed for this
purpose. The training data for both the optimal control and
game of two cars are generated through available numerical
optimal control tools.




![Screenshot from 2023-11-26 00-40-08](https://github.com/ANKITSINGH47/Explicit-Model-Predictive-Control-MPC-using-Decision-trees-and-Random-forests-for-differential-gam/assets/47277960/6c060a05-c98f-41b8-bbf3-ebf669c4451a)





<br>

![Screenshot from 2023-11-26 00-41-16](https://github.com/ANKITSINGH47/Explicit-Model-Predictive-Control-MPC-using-Decision-trees-and-Random-forests-for-differential-gam/assets/47277960/ee704fca-c21a-425d-8c07-abe06a3d8bef)

<br>
![Screenshot from 2023-11-26 00-41-31](https://github.com/ANKITSINGH47/Explicit-Model-Predictive-Control-MPC-using-Decision-trees-and-Random-forests-for-differential-gam/assets/47277960/2f8b1bea-cdf0-48f3-98ef-c3fc05cf7f84)

<br>
![Screenshot from 2023-11-26 00-41-46](https://github.com/ANKITSINGH47/Explicit-Model-Predictive-Control-MPC-using-Decision-trees-and-Random-forests-for-differential-gam/assets/47277960/1b032bc4-fdde-48d8-925c-c6b8aae0cfc8)

<br>
![Screenshot from 2023-11-26 00-42-05](https://github.com/ANKITSINGH47/Explicit-Model-Predictive-Control-MPC-using-Decision-trees-and-Random-forests-for-differential-gam/assets/47277960/3876874a-da51-48e2-b2bd-178ada1b39ad)


