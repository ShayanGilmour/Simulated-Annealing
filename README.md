# Simulated Annealing Solving Traveling Salesman Problem

Solving Traveling Salesman Problem with Simulated Annealing. In simulated annealing, we have point which is cruising the domain of a function. Here, the function is the cost function: The length of the cycle. And the point, which is a corresponding permutation of a cycle, is moving going to adjacent points in the domain. Here, adjacent point is just a similar permutation: Swapping 2 numbers of the permutation.

Here we have a set of cities:

<p float="left">
  <img src="https://user-images.githubusercontent.com/12760574/130592580-c57b4ede-2ee0-429c-9222-3d09ffb8a4a2.png" width="400" />
</p>

Here I've monitored the answer produces by simulated annealing over `200000` iterations (Less than `2s`).
<p float="left">
  <img src="https://user-images.githubusercontent.com/12760574/130593103-1d66a418-b9ad-4709-b884-1a8046946ae1.png" width="250" />
  <img src="https://user-images.githubusercontent.com/12760574/130593179-e4a0e64e-0613-44de-8995-4a618703390a.png" width="250" />
  <img src="https://user-images.githubusercontent.com/12760574/130593185-87177503-1e7c-489e-a56b-153d99f55a6e.png" width="250" />
</p>

This is a better run which finds the most optimal cycle:

<p float="left">
  <img src="https://user-images.githubusercontent.com/12760574/130593772-ade54e50-9c12-44dc-930f-a3f1d2a632cd.png" width="250" />
  <img src="https://user-images.githubusercontent.com/12760574/130593778-39a21202-d921-482f-bbf3-ed2ed79d20e3.png" width="250" />
  <img src="https://user-images.githubusercontent.com/12760574/130593784-f9f99e53-72dc-4bd8-a53a-e55ee6bc41d3.png" width="250" />
</p>

The code which makes the found cycle visual is also in the notebook.
