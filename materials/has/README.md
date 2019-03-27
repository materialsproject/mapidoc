Some properties are not computed for all materials.
This array contains keys for each of the properties computed and available for a material.
Example query: `{"has": "elasticity"}` for materials with elasticity data.

- **bandstructure**: electronic bandstructure, density of states
- **phonons**: phonon dispersion and density of states, heat capacity, entropy, dielectric tensor, born effective charges
- **xas**: X-Ray Absorption Near-Edge Spectrum (XANES) K-edge spectrum
- **surfaces**: surface energy, work function. Currently, elemental systems only.
- **elasticity**: tensor, bulk and shear moduli, Poisson's ratio
- **piezo**: piezoelectric tensor, max modulus and direction
- **diel**: dielectric tensor, dielectric constant, refractive index
- **eos**: equations of state (energy/atom vs volume/atom and fits)































## Example response in JSON

```json
[
    "xas",
    "elasticity",
    "piezo",
    "diel",
    "phonons",
    "bandstructure",
    "eos"
]
```

