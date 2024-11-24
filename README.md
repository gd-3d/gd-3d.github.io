# gd-3d.github.io
website for gd-3d


under construction!

_if you can see this, what the heck_


# Bless Documentation

## Overview
Bless is a powerful level editor addon for Blender, designed to streamline the creation of game levels and assets. It provides advanced tools for physics setup, collision management, and glTF export with game-specific extensions.

## Installation

1. Download the latest version of Bless
2. In Blender, go to Edit > Preferences > Add-ons
3. Click "Install" and select the downloaded file
4. Enable the addon by checking the box

## Getting Started

### Basic Setup
1. Open the Bless panel in the 3D View sidebar (N-panel)
2. Configure your grid settings
3. Set up your default collision types

### Creating Level Geometry
1. Use the greybox tools for rapid prototyping
2. Apply physics properties to objects
3. Configure collision layers and masks

### Exporting
1. Set up your export settings
2. Configure required extensions
3. Export to glTF format with game-specific data



## Features

### 1. Physics System
- **Collision Types**
  - Trimesh: Static level geometry
  - Convex: Dynamic collision shapes
  - Custom: User-defined collision shapes
  - None: No collision

- **Physics Properties**
  - Body Properties: Configure physics bodies
  - Shape Properties: Define collision shapes
  - 32 Configurable Collision Layers
  - Collision Masks for Layer Interaction

### 2. Level Editor Tools
- **Grid System**
  - Customizable grid settings
  - Snapping tools
  - Unit size configuration

- **Greybox Mode**
  - Quick prototyping tools
  - Unified greybox workflow

- **View Controls**
  - Camera lock functionality
  - Grid visibility toggles
  - Custom view settings

### 3. glTF Export System
Supports various extensions for game development:

#### Core Extensions
- KHR_node_visibility: Hidden nodes
- GODOT_node_lock: Locked nodes
- KHR_audio_emitter: Audio support

#### Physics Extensions
- OMI_physics_body: PhysicsBody3D support
- OMI_physics_shape: CollisionShape3D support
- OMI_physics_filter: Physics filtering system

#### Bless-specific Extensions
- OMI_seat: Seat3D functionality
- OMI_spawn_point: SpawnPoint3D support
- OMI_vehicle: Vehicle3D support




## Contributing
Contributions are welcome! The addon is developed by the gd-3d team:
- aaronfranke
- michaeljared
- valyarhal
- yankscally

  
## Version History
Current Version: 0.1.3
Blender Compatibility: 4.2.0+
