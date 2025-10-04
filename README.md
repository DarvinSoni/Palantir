# Palantir - 3D Asteroid Impact Simulator 🌍💥

An enhanced, interactive **3D web-based** asteroid impact simulator that visualizes the devastating effects of asteroid collisions with Earth. This tool features a fully 3D globe with real buildings, real-time physics calculations, and spectacular destruction visualizations to help understand the scale and consequences of asteroid impacts.

## Features

### 🌐 Full 3D Globe Experience
- **Interactive 3D Earth**: Rotate, zoom, and explore the planet in real-time
- **Real 3D Buildings**: Uses OpenStreetMap Buildings data to show actual city structures
- **Building Destruction**: Watch buildings get destroyed by your asteroid impact
- **Multiple Camera Modes**: Switch between orbital and ground-level views
- Click anywhere on Earth to drop your asteroid
- Smooth 3D animations and cinematic camera movements

### ⚙️ Advanced Physics Simulation
- **Impact Energy**: Calculates kinetic energy in megatons of TNT
- **Crater Formation**: Accurate crater diameter calculations based on energy, angle, and target type
- **Fireball Radius**: Immediate vaporization zone
- **Air Blast Radius**: Overpressure wave calculations (20 psi)
- **Thermal Radiation**: 3rd-degree burn radius
- **Seismic Effects**: Richter scale earthquake magnitude

### 🎛️ Customizable Parameters
- **Asteroid Diameter**: 10m - 10km
- **Impact Velocity**: 11-72 km/s (cosmic velocities)
- **Impact Angle**: 15° - 90° (grazing to perpendicular)
- **Composition Types**: 
  - Iron (7,800 kg/m³)
  - Stone (3,000 kg/m³)
  - Ice (1,000 kg/m³)
  - Carbon-rich (2,000 kg/m³)
- **Target Selection**: Land or water impacts

### 🌟 Famous Asteroid Presets
- **Tunguska Event (1908)**: 60m icy body that leveled 2,000 km² of Siberian forest
- **Chelyabinsk (2013)**: 20m meteor that exploded over Russia
- **Barringer Crater**: Created Arizona's famous meteor crater
- **Chicxulub Impact**: The dinosaur-killer - 10km asteroid

### 📊 Real-Time Impact Analysis
- Energy comparisons (TNT equivalent, nuclear weapons)
- Estimated casualties based on affected area
- Multiple damage zones visualized with color-coded circles
- Detailed statistics panel

### 🎨 Modern, Beautiful UI
- Dark space-themed design
- Smooth animations and transitions
- Glassmorphism effects
- Responsive controls
- Professional gradient styling

## How to Use

1. **Open `index.html`** in any modern web browser (Chrome, Firefox, Safari, Edge)
2. **Explore the 3D Globe**: Click and drag to rotate, scroll to zoom in/out
3. **Adjust Parameters**: Use the left control panel to set asteroid properties
4. **Drop Your Asteroid**: Click anywhere on the 3D globe to create an impact
5. **Watch the Destruction**: See buildings destroyed, debris scatter, and damage zones appear
6. **View Results**: Check the right panel for detailed impact statistics
7. **Change Camera**: Toggle between orbital and ground-level views
8. **Try Presets**: Click famous asteroid buttons for historical impacts
9. **Experiment**: Use the "Random Asteroid" button for quick simulations
10. **Clear Impact**: Click "Clear Impact" or press 'C' to reset

### Keyboard Shortcuts
- **R**: Generate random asteroid parameters
- **C**: Clear current impact visualization
- **Mouse Drag**: Rotate the globe
- **Mouse Scroll**: Zoom in/out
- **Right Click + Drag**: Pan the camera

### What You'll See
When you drop an asteroid, you'll witness:
- 🔥 **Flash Effect**: Screen flashes orange/red during impact
- 💥 **Impact Point**: Bright marker showing exact impact location
- ⭕ **Damage Zones**: Three color-coded circles (fireball, blast, thermal)
- 🏢 **Building Destruction**: Estimated number of destroyed buildings
- 💨 **Debris**: Gray particles scattered across the impact zone
- ☁️ **Smoke Clouds**: Dark dust clouds rising from the destruction
- 🕳️ **Crater**: Black crater marking ground zero
- 🎥 **Camera Animation**: Automatic zoom to view the full devastation

## System Requirements

### Recommended
- **Modern Web Browser**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **WebGL 2.0 Support**: Required for 3D rendering (check at [get.webgl.org](https://get.webgl.org))
- **GPU**: Dedicated graphics card recommended for smooth performance
- **RAM**: 4GB minimum, 8GB recommended
- **Internet Connection**: Required to load Cesium.js library and map tiles

### Troubleshooting
If the 3D Earth doesn't load:
1. **Check WebGL**: Visit [get.webgl.org](https://get.webgl.org) to ensure WebGL is working
2. **Try Chrome**: Chrome generally has the best WebGL support
3. **Update Drivers**: Update your graphics card drivers
4. **Disable Extensions**: Try disabling browser extensions that might block WebGL
5. **Check Console**: Open browser console (F12) to see any error messages
6. **Wait for Loading**: The globe may take 10-30 seconds to fully load depending on your connection

### Note
The simulator uses **free OpenStreetMap imagery** and **no authentication required**! It works out of the box without needing any API keys or Cesium Ion accounts. Buildings are represented as simple 3D boxes in the destruction zone.

For advanced features (real 3D buildings from actual city data), you can optionally:
1. Sign up for a free account at [Cesium Ion](https://cesium.com/ion/signup)
2. Get your access token and replace it in the HTML file
3. Uncomment the OSM Buildings code

## Technical Details

### Physics Calculations
The simulator uses scientifically-based equations to calculate:
- Kinetic energy from mass and velocity
- Crater scaling laws
- Blast wave propagation
- Thermal radiation distance
- Seismic energy conversion

### Technologies Used
- **Cesium.js**: Advanced 3D globe rendering and terrain visualization
- **OpenStreetMap Buildings**: Real 3D building data from cities worldwide
- **WebGL**: Hardware-accelerated 3D graphics
- **Vanilla JavaScript**: Physics engine and calculations
- **CSS3**: Modern animations and effects
- **HTML5**: Semantic structure

## Improvements Over Original

This enhanced version includes:
1. ✅ **Full 3D Globe** with realistic terrain and lighting
2. ✅ **Real 3D Buildings** that can be destroyed
3. ✅ **Debris and particle effects** showing destruction
4. ✅ **Smoke/dust clouds** after impact
5. ✅ **Cinematic camera animations** (orbital and ground views)
6. ✅ **Screen flash effects** during impact
7. ✅ More detailed physics calculations
8. ✅ Beautiful modern UI with gradients and animations
9. ✅ Multiple asteroid composition types
10. ✅ Land vs water impact options
11. ✅ Seismic effect calculations
12. ✅ Energy comparison contexts
13. ✅ Famous asteroid presets
14. ✅ Building destruction counter
15. ✅ Smooth visual effects and transitions
16. ✅ Professional information panels
17. ✅ Real-time parameter updates
18. ✅ Keyboard shortcuts
19. ✅ Random asteroid generator
20. ✅ Responsive design
21. ✅ Casualty estimates

## Future Enhancements

Potential additions:
- Integration with NASA NEO API for real asteroid data
- USGS datasets for tsunami and seismic predictions
- More realistic building collapse physics
- Fire and smoke particle systems
- Historical impact database
- Share impact scenarios
- Sound effects and shockwave audio
- Multiple simultaneous impacts
- Atmospheric entry trail visualization
- Fragmentation modeling
- VR/AR support for immersive experience
- Real-time weather and atmospheric effects

## Educational Value

This tool helps understand:
- The devastating power of asteroid impacts
- Why asteroid detection and deflection are crucial
- Scale differences between various asteroids
- How impact parameters affect outcomes
- The importance of planetary defense

## License

Open source - feel free to use and modify!

---

**⚠️ Disclaimer**: This is a simplified simulation for educational purposes. Actual asteroid impacts involve complex physics including atmospheric entry, fragmentation, and varied geological effects. Real impact predictions require sophisticated modeling.
