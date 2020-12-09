## The SIR model
The SIR model is one of the simplest compartmental models, and many models are derivatives of this basic form. The model consists of three compartments:

* **S:** The number of susceptible individuals. When a susceptible and an infectious individual come into "infectious contact", the susceptible individual contracts the disease and transitions to the infectious compartment.
* **I:** The number of infectious individuals. These are individuals who have been infected and are capable of infecting susceptible individuals.
* **R:** For the number of removed (and immune) or deceased individuals. These are individuals who have been infected and have either recovered from the disease and entered the removed compartment, or died. It is assumed that the number of deaths is negligible with respect to the total population. This compartment may also be called "recovered" or "resistant".

This model is reasonably predictive for infectious diseases that are transmitted from human to human, and where recovery confers lasting resistance, such as COVID-19, measles, mumps and rubella.

And that are the results: 

![Grap1](https://user-images.githubusercontent.com/63415652/101559838-9817d900-3987-11eb-815e-7cc6ce7b0b84.PNG)

The solution of this system, under the conditions and parameters previously indicated, shows that:

1.- The susceptible curve always decreases with time, as with the SI system.
2.- The infected curve has a bell shape where there is a maximum point that indicates the most critical moment of contagion in the population. It is important to anticipate this maximum point because it can exceed the capacity of the health system if the number of simultaneous infections is very large.
3.- The recovery curve always increases over time.

These three conditions reflect a situation where the epidemic eventually fades in time and we say that the population has reached what is called Herd immunity or herd immunity, which is a state where individuals have already recovered because the vast majority it has managed to acquire immunity against the virus that caused the epidemic.

When governments say that we must flatten the curve so as not to overload the health system, they refer to the curve of infected that we have just shown previously, we know that the most popular measure to control this has been through quarantine and social distancing and this It can be modeled in a certain way through the propagation constant of the β epidemic. In other words, these social distancing policies can be quantified with a smaller value of β, let's see a comparison of how a lower value of β affects the maximum peak of infected.

When governments say that we must flatten the curve so as not to overload the health system, they refer to the curve of infected that we have just shown previously, we know that the most popular measure to control this has been through quarantine and social distancing and this It can be modeled in a certain way through the propagation constant of the β epidemic. In other words, these social distancing policies can be quantified with a smaller value of β, let's see a comparison of how a lower value of β affects the maximum peak of infected.

![SIR2](https://user-images.githubusercontent.com/63415652/101246650-5282b400-36da-11eb-883b-be3d193e6c06.PNG)

And with this final graph we show that a reduction in the rate of spread has the effect that the curve becomes wider but also the maximum peak of infections is reduced, we place as an example a horizontal line that represents the theoretical capacity of a system of health only to show that the reduction in the rate of spread translates into that flattening of the curve that eventually implies that a health system under consideration is not saturated.
