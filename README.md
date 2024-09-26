# a list of things real-time renderers are not good at
- subsurface scattering: most materials are translucent in real life, but games only make effort to simulate SSS for skin
- ambient occlusion: a crude hack of a concept to begin with, separating visibility from the light transport makes no sense
- split sum approximation: pretending the product of integrated BRDF and integrated irradiance is equal to single integral of both, also that V=N
- Lambertian diffuse: does not exist in real life, infinitely short subsurface scattering mathematically corresponds to Chandrasekhar BRDF
