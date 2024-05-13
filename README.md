## Uniform Discretized Integrated Gradients: An effective attribution based method for explaining large language models
![image](https://github.com/swarnava-sr/UDIG/assets/82533666/0cd31f2f-da8b-49a2-888c-5fa516805a37)
Interpolation paths used by UDIG. W is the word of interest and W` is the baseline. The green straight line represents the linear path used by IG for calculating attribution.<br/>
(left) UDIG-Greedy: Grey regions are the neighborhood pof the points chosen on the straight line. Each word in this neighborhood is first monotonized where each red arrow signifies the distance between the word and its corresponding monotonic point. The word closest to its corresponding monotonic form is selected as the anchor word (w4 since the red arrow of w4 has the smallest magnitude).<br/>
(right) UDIG-Max-Count: The word with the highest number of monotonic dimensions (count show in []) is selected as the anchor word (w3 since it has the highest number of monotonic dimensions), which is followed by updating the non-monotonic dimensions to make it monotonic - c1 (red arrow). Repeating thsi process multiple times for each point gives the non-linear blue path for UDIG.


