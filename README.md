# GPU Particles
A GPU Particle System for [Unity](https://unity3d.com/)

## Screenshots
<img src="Assets/Screenshots/screenshot3.png" width="400"/> <img src="Assets/Screenshots/screenshot1.png" width="400"/> <img src="Assets/Screenshots/screenshot2.png" width="400"/> <img src="Assets/Screenshots/screenshot0.png" width="400"/>

## Features
- GPU-accelerated - Able to handle millions of particles (even without a beast of a PC)
- Lots of customization options (more to come...)
- Fancy Editor:
<img src="https://user-images.githubusercontent.com/34353377/34125986-5fe653d8-e438-11e7-8218-fc62254efc5a.png" width="400"/>

## System Requirements
Made with Unity 2017.2 & .3. Might work with older versions. Only tested on Desktop with Nvidia GPU.

## To do
- [x] Implement 'Emission Extrapolation' to compensate emission at high velocities
- [x] Implement 'Linear Drag'
- [x] Implement 'Time Scale'
- [x] Use namespace
- [x] Add 'Dark Skin' option
- [x] Implement Size Module
- [x] Use DrawProcedural for draw calls
- [ ] Update particle count in System Module on Update instead of OnGUI
- [ ] ~~Use geometry shader for billboard particles~~ <- reduces performance
- [ ] Use time instead of CPU-generated seeds for pseudorandomness
- [ ] Document code
- [ ] Fix glitches caused by 'Inherit Velocity' after big timesteps
- [ ] Fix 'Max Particles' change at runtime
- [ ] Add 'Particle' Module to change appearance
- [ ] Make system run in Edit Mode
- [ ] Change 'Inherit Velocity' to work with transformation matrices
- [ ] Implement 'External Forces'
- [ ] Implement 'Screen Space Collision'
- [ ] Implement other rendering methods (Mesh)
- [ ] Implement other Emission Shapes
- [ ] Implement 'Direction Types' for all Emission Shapes

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The included sIBL images are from [sIBL Archive](http://www.hdrlabs.com/sibl/archive.html).
