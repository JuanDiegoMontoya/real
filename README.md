# a list of things real-time renderers are not good at
- subsurface scattering: most materials are translucent in real life, but games only make effort to simulate SSS for skin
- ambient occlusion: ambient lighting isn't real and a visibility approximation hardly makes it any more so
- split sum approximation: pretending the product of integrated BRDF and integrated irradiance is equal to single integral of both, also that V=N
