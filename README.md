# ⭐ Stellar Classification ⭐
Hey, welcome to this repository!
For this project I haven't thought of anything that it could inspire me. But in one day I was doing one the things that I enjoy the most, looking at the night sky, and suddenly just I had an idea💡!\
\
"What if I did a project studying the *SKY*🌃?"\
\
Well it's not quite "the sky" the main topic, but what we can see in it: the STARS✨. So thinking of a way to relate the stars with Data Science I started to search for it online, then I bumped into this [Stellar Types dataset](https://www.kaggle.com/datasets/deepu1109/star-dataset) which contains 6 star types (Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence , SuperGiants, HyperGiants). In this repo I utilized Deep Learning neural networks to predict the classification of the stars given a set of 6 features:

*  `Temperature (K)`: Star's surface temperature;
*  `Luminosity (W)`: (L/Lo) Star's luminosity (L) calculated with respect to the sun (Lo);
*  `Radius (m)`: (R/Ro) Star's radius (R) calculated with respect to the sun (Ro);
*  `Absolute Magnitude (Mv)`: Star's Absolute visual magnitude;
*  `Star Color`: Shades of each star's colors each star after a spectral analysis;
*  `Spectral Class`: Star's spectral class

Lo = 3.828 * 10^26 W (Avg Luminosity of Sun)
Ro = 6.9551 * 10^8 m (Avg Radius of Sun)

The `Star Type` column is a categorical/numerical column, numbers from 0-5 that represents each of the star types, we can see the label of it below:
*  0 = Brown Dwarf
*  1 = Red Dwarf
*  2 = White Dwarf
*  3 = Main Sequence
*  4 = Supergiant
*  5 = Hypergiant

