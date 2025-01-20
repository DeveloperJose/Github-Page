---
title: "Physics-Informed Long-Short Term Memory Neural Network Performance on Holloman High-Speed Test Track Sled Study"
collection: publications
category: conferences
# permalink: /publication/2024-02-17-paper-title-number-4
# excerpt: 'This paper is about fixing template issue #693.'
date: 2022-09-30
venue: 'Proceedings of the ASME 2022 Fluids Engineering Division Summer Meeting'
paperurl: 'https://asmedigitalcollection.asme.org/FEDSM/proceedings-abstract/FEDSM2022/85840/V002T05A014/1147131'
slidesurl: 'https://docs.google.com/presentation/d/1TR6ffoWi43efkkBQ9_khVVzpSykAPMQp/edit#slide=id.p1'
citation: '<b>J. Perez</b>, R. Baez, J. Terrazas, A. Rodriguez, D. Villanueva, B. Paez, A. Cruz, O. Fuentes, V. Kumar, "Physics-Informed Long-Short Term Memory Neural Network Performance on Holloman High-Speed Test Track Sled Study". Proceedings of the ASME 2022 Fluids Engineering Division Summer Meeting, 2022.'
---

Physics Informed Neural Networks (PINNs) incorporate known physics equations into a network to reduce training time and increase accuracy. Traditional PINNs approaches are based on dense networks that do not consider the fact that simulations are a type of sequential data. Long-Short Term Memory (LSTM) networks are a modified version of Recurrent Neural Networks (RNNs) which are used to analyze sequential datasets. We propose a Physics Informed LSTM network that leverages the power of LSTMs for sequential datasets that also incorporates the governing physics equations of 2D incompressible Navier-Stokes fluid to analyze fluid flow around a stationary geometry resembling the water braking mechanism at the Holloman High-Speed Test Track. Currently, simulation data to analyze the fluid flow of the braking mechanism is generated through ANSYS and is costly, taking several days to generate a single simulation. By incorporating physics equations, our proposed Physics-Informed LSTM network was able to predict the last 20% of a simulation given the first 80% within a small margin of error in a shorter amount of time than a non-informed LSTM. This demonstrates the potential that physics-informed networks that leverage sequential information may have at speeding up computational fluid dynamics simulations and serves as a first step towards adapting PINNs for more advanced network architectures.