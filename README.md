# leeFoam
Linearized Euler Equations (LEE) solver for Computational Aeroacoustics (CAA) applications within OpenFOAM framework.
 

## Installation

1. Clone the directory with
    `git clone https://github.com/SamSalehian/leeFoam.git`
2. Execute `chmod +x Allwclean` and `chmod +x Allwmake`
3. Execute `Allwclean` to cleanup the library 
4. Execute `Allwmake` to build the library


## Tutorials

### 1D Wave
One dimentional wave convecting through a stagnant mean flow

https://github.com/SamSalehian/leeFoam/assets/50889406/13da6394-2a70-4878-8d97-9f90d591f122

Acoustic pressure signal at x=100 computed using leeFoam compared with the analytical solution.
![1Dwave_leeFoam_vs_Analytical](https://github.com/SamSalehian/leeFoam/assets/50889406/b73b8c19-5d02-4dd0-8b6f-33049c66b924)

### 2D Pulse
The convection of the Gaussian pulse in uniform flow

https://user-images.githubusercontent.com/50889406/230478080-1b14b1d7-1ec8-498f-ac5c-1bf5b965e206.mp4

Acoustic pressure along the x-axis at t=60 computed using leeFoam for L/N=4,2,1, and 0.5, compared with the analytical solution.
![Picture1](https://user-images.githubusercontent.com/50889406/230476710-e3e5361a-e416-4601-972c-02aac15d159c.png)


## License
This OpenFOAM library is under the GNU General Public License.

## Citation
When using this work please cite:

* Salehian, S., Good, P. P., Golubev, V. V., & Mankbadi, R. R. (2023). An OpenFoam-Based LEE Solver for Prediction of Noise Generated by a Supersonic Jet Issued from a Rectangular Nozzle. AIAA SCITECH 2023 Forum. (AIAA 2023-0613)
* https://doi.org/10.2514/6.2023-0613 
