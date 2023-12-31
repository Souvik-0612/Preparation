# Preparation
Prepare for Physics MSc exams

> ##### Albert Einstein
>
> *I have no special talents. I am only passionately curious.*
## Classical mechanics
### Newton's law
* Plane polar form of position, velocity and accelaration
* Collision and linear momentum conservation
### Non-inertial forces aka pseudo force
* Fictitious forces
    * Centrifugal
    * **Coriolis force**
    * Azimuthal force
* Cools facts due to Coriolis force:
    * Effect on weather in Earth
![Earth](Earth.jpg)
    * Bands of Jupyter due to high angular speed than the Earth.
![Jupyter](Jupiter.jpg)
    * Simple pendulum can't stay in a plane. It changes the plane of motion. **Faucault pendulum**
* Science behind tides 
### Central force
* Newton Gravitional problem(inverse square law, $V(r) = -\frac{\alpha}{r^2}$)(Klepler's problem )(Eccentricity $e = \sqrt{1+\frac{2EL^2}{m\alpha^2}}$)
* Effective potential, $V_{eff}(r) = \frac{L^2}{2mr^2} + V(r)$
* Three **Conserved** quatity
    * Energy
    * Angular momentum
    * Runge-Lenz Vector($\vec A =$ constant *vector*)(for inverse square law $\vec A = \vec p \times \vec L - m \alpha \hat r$)
* Cool problems in Central force field
    * Captaring cross-section
    * Scattering in a central force field
### All about rigid body motion
* Torque and angular momentum
* Moment of inertia
* Ellipsoid of inertia $$I = I_{xx}\cos^2\alpha + I_{yy}\cos^2\beta + I_{zz}\cos^2\gamma + 2I_{xy}\cos\alpha\cos\beta + 2 I_{yz}\cos\beta\cos\gamma + 2I_{zx}\cos\gamma\cos\alpha$$
* Euler equation 
``` math
\begin{bmatrix}\tau_1 \\ \tau_2 \\ \tau_3 \end{bmatrix} = \begin{bmatrix}I_1\dot\omega_1 + (I_3 - I_2)\omega_2 \omega_3 \\ I_2\dot\omega_2 + (I_1 - I_3)\omega_1 \omega_3 \\ I_3\dot\omega_3 + (I_2 - I_1)\omega_1 \omega_2 \end{bmatrix}
```
* Free symetric top spin(Chandler Wobble of earth)
![Earth is wobble](EarthWobble.gif)
### Special theory of relativity
* Kinematics 
* Dynamics
* STR and eletro-magnetism
### Lagrangian and Hamiltonian mechanics
* Euler Lagrange equation
    * From D'Alembert's principle
    * From Stationary-action principle
* Legendre transformation 
* Hamiltonian
* Advanced topics:
    * **Noether's theorem**:*For each symmetry of the Lagrangian, there is a conserved quantity.*
        * Homogeneity of space $\rightarrow$ conservation of linear momentum
        * Isotropy of space $\rightarrow$ conservation of angular momentum
        * Time invarience $\rightarrow$ conservation of energy

## Classical Electrodynamics
### Math for Electrodynamics
* Dirac Delta
> Some cool problem can be dealt with Dirac delta function
### Electrostatics
   * Coulomb's Law
   * Electric Field
   * Gauss's Law
   * Electric Potential
   * **Electrostatic Boundary Conditions**
   * Work & Energy in Electrostatics
   * Conductors
   * **Laplace's Equation**
   * Boundary Conditions & Uniqueness Theorem
   * *The Method of Images*
   * *Multipole Expansion*
   * Dielectrics & Polarization
   * Field of a Polarized Object
   * Gauss's Law in Presence of Dielectrics
   * Boundary Conditions
   * Linear Dielectrics
   * Energy in Dielectric Systems
   * Forces on Dielectrics
### Magnetostatics
   * The Lorentz Force Law
   * The Biot-Savart Law
   * The Divergence and Curl of B
   * Magnetic Vector Potential
   * Magnetostatic Boundary Conditions
   * Multipole Expansion of The Vector Potential
   * Magnetization
   * Torques and Forces on Magnetic Dipoles
   * The Field of a Magnetized Object
   * The Auxiliary Field H
   * Ampere's law in Magnetized Materials
    * Boundary Conditions 
   *  Linear and Nonlinear Media 
      * Magnetic Susceptibility and Permeability
      * Ferromagnetism 

### Electrodynamics(Electromagnetism)
   * Electromotive Force
     * Ohm's Law 
     * Electromotive Force
     * Motional emf 
   * Electromagnetic Induction 
     * Faraday's Law 
     * The Induced Electric Field
     * Inductance 
     * Energy in Magnetic Fields
   * Maxwell's Equations
     * Electrodynamics Before Maxwell
     * How Maxwell Fixed Ampere's Law
     * Maxwell's Equations
     * Magnetic Charge 
     * Maxwell's Equations in Matter
     * Boundary Conditions

## Electronics
### Op-Amp
### Analog
* Solid state physics
* Diode
* Transistor
### Digital
* Sequential
    * Clock
    * Flipflop
    * Register

* Combinational

## Mathematical Physics
### Probability
### Fourier
### Differential equation
### Complex analysis
### Vector analysis
### Linear algebra
* Eigen value & Eigen vector

## Optics
### Wave Optics
> Huygen's principle: each point of a wavefront is a *source* of secondary disturbance and the wavelets emanating from these points spread out in all directions with the speed of the wave. The *envelope* of these wavelets gives the shape of the new wavefront.
* Interference
    * Division of wavefront
        * Young's double slit experiment
        * Lloyd's mirror
        * Fresnel biprism
        * Fresnel two mirror
    * Division of amplitude
        * Thin flim interference
        * Newton's ring
        * Michelson's interferometer
    * Multiple beam interferometer
        * Febry-Perot interferometry
* **Diffraction**
    * Fraunhofer diffraction
    * Fresnel diffraction
* Polarization
### Matrix method in optics(ray optics)
* The heart:
    * Translational matrix
    ```math
    \begin{bmatrix}\lambda_2 \\ y_2 \end{bmatrix} = \begin{bmatrix}1 & 0 \\ \frac{L}{n} & 1 \end{bmatrix} \begin{bmatrix}\lambda_1 \\ y_1 \end{bmatrix}
    ```
    * Refraction matrix
    ```math
    \begin{bmatrix}\lambda_2 \\ y_2 \end{bmatrix} = \begin{bmatrix}1 & \frac{n_1 - n_2}{R} \\ 0 & 1 \end{bmatrix} \begin{bmatrix}\lambda_1 \\ y_1 \end{bmatrix}
    ```
* **Consequence from system of lens**
    * Unit planes and nodal plane
    * Establish the lens maker formula
* Thin lens
    * Equivalent focus of two thin lenses

## Waves
* Oscilations
    * Simple Pendulum 
    * Damped oscillator
    * Forced oscillator
* Wave on a string

## Kinetic theory of gas and Thermodynamics
### Kinetic theory of gas
* Maxwell's distribution
* Einstein brownian motion
### Thermodynamics

## Modern physics
### Quantum Mechanics
#### QM history(Famous experiments)
* Quantization of light
    * Black-body radiation; Rayleigh-Jeans law
    * Photoelectric effect
    * Crompton effect
    * Bohr model and atomic spectra
> **De Broglie's hypothesis** brings the particle and wave theory into two sides of a *same coin*!
* Wave charecter of electron(i.e, matter wave)
    * Davisson-Germer experiment
#### Modern QM(i.e, from Schrödinger equation)
* Hisenberg uncertainty principle
* Boundary-value problems(1D problems)
    * Infinite square well
    * Step-potential
        * Tunneling effect
    * 
### Nuclear physics

## Statistical mechanics
