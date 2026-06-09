**Gas Equation**
- An equation used in physics and chemistry that relates pressure, volume, and temperature of a gas is PV = nRT. P is the pressure, V the volume, T the temperature, n the number of moles, and R a constant. The function below outputs the temperature of a gas given the other values.

**Figure 11.17.1: PV = nRT. Compute the temperature of a gas**
```
gas_constant = 8.3144621  # Joules / (mol*Kelvin)

def convert_to_temp(pressure, volume, mols):
    """Convert pressure, volume, and moles to a temperature"""
    return (pressure * volume) / (mols * gas_constant)

press = float(input("Enter pressure (in Pascals): "))
vol = float(input("Enter volume (in cubic meters): "))
mols = float(input("Enter number of moles: "))

print(f"Temperature = {convert_to_temp(press, vol, mols):.2f} K")
```

**Trajectory of Object on Earth**
- Common physics equations determine the x and y coordinates of a projectile object at any time, given the object's initial velocity and angle at time 0 with the initial position of x=0 and y=0. The equation for x is...
$$v*t*sin(a) - 0.5*g*t*t$$
- The program's code asks the user for the object's initial velocity, angle, and height (y position), and prints the object's position for every second until the object's y position is no longer greater than 0 (meaning the object fell back to Earth).