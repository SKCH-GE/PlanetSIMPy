# Planet Simulation

An interactive solar system simulation built with Python and Pygame, designed to teach programming concepts to kids. This project demonstrates fundamental physics principles, object-oriented programming, and real-time graphics rendering while creating an engaging educational experience.

## Overview

This project simulates the orbital mechanics of planets in our solar system, including:
- The Sun
- Mercury
- Venus
- Earth
- Mars

Each celestial body is modeled with accurate mass and velocity data, creating realistic orbital patterns using gravitational physics calculations.

## Educational Value

This simulation serves as an excellent teaching tool for various concepts:
- Basic Physics (gravitational forces, orbital mechanics)
- Object-Oriented Programming
- Mathematical concepts (trigonometry, vectors)
- Real-time graphics programming
- Scientific constants and scale modeling

## Features

- Real-time planet orbit visualization
- Distance tracking from Sun
- Accurate gravitational physics calculations
- Scale modeling of the solar system
- Orbit trail visualization
- Interactive window with smooth animation

## Technical Details

### Key Components

- **Astronomical Unit (AU)**: Scaled representation of the distance between Earth and Sun
- **Gravitational Constant (G)**: Used for force calculations
- **Time Step**: Simulation runs in day-long increments
- **Scale Factor**: Converts astronomical distances to pixel measurements

### Physics Implementation

The simulation calculates:
- Gravitational forces between bodies
- Velocity vectors
- Position updates
- Orbital trajectories

## Getting Started

### Prerequisites

```bash
pip install pygame
```

### Running the Simulation

1. Clone the repository
2. Run the script:
```bash
python planet_simulation.py
```

## Code Structure

### Planet Class
The core of the simulation is the `Planet` class, which handles:
- Position tracking
- Force calculations
- Orbital path drawing
- Visual representation

### Key Methods

- `draw()`: Renders the planet and its orbit
- `attraction()`: Calculates gravitational forces
- `update_position()`: Updates planet position based on forces

## Controls

- Close window to exit simulation
- Watch as planets orbit in real-time
- Distance measurements are shown in kilometers

## Customization

You can modify various parameters to experiment with the simulation:
- Planet masses
- Initial velocities
- Planet colors
- Time step values
- Scale factors

## Credits

- Inspired by Tech with Tim's planet simulation stream
- Uses real astronomical data for accurate simulations

## Future Enhancements

Potential additions could include:
- [ ] Additional planets
- [ ] User-interactive controls
- [ ] Planet information display
- [ ] Velocity vectors visualization
- [ ] Time control (speed up/slow down)

## Contributing

Feel free to contribute to this educational project by:
- Adding new features
- Improving physics calculations
- Enhancing the visualization
- Adding educational content

## License

[MIT]

## Acknowledgments

Special thanks to Tech with Tim for the original inspiration for this educational project.
