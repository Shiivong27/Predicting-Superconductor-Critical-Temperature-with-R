# Predicting-Superconductor-Critical-Temperature-with-R

For this task at hand, the underlying problem is to estimate the critical temperature given a new conductor’s properties. There are eight properties that can be used: Atomic Mass, First Ionization Energy, Atomic Radius, Density, Electron Aﬃnity, Fusion Heat, Thermal Conductivity, Valence.

For each property, ten features are extracted: Mean, Weighted mean, Geometric mean, Weighted geometric mean, Entropy, Weighted entropy, Range, Weighted range. Standard deviation, Weighted standard deviation.

We are required to build 2 to 3 models which can predict the critical temperature and compare the models based on MSE (Measn Squared Error). The purpose of the description task is identify the key properties for a superconductor. In other words, which property contributes the most to your model’s performance?
