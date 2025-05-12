## sdf2pgm
Python Script fo Converterting `.world` to `.pgm` `.yaml` Map 

<div align="center">
  <table>
    <tr>
      <td><b>3D World in Gazebo</b></td>
      <td><b>Generated 2D Map</b></td>
    </tr>
    <tr>
      <td><img src="world.png" width="400" alt="3D World Example"/></td>
      <td><img src="pgm.png" width="400" alt="Generated PGM Map"/></td>
    </tr>
  </table>
</div>

```{yaml}
image: obstacle_world.pgm
resolution: 0.05
origin: [-10.0, -10.0, 0.0]
occupied_thresh: 0.65
free_thresh: 0.196
negate: 0
```

## Usage
```
python3 sdf_to_pgm.py path/to/world.sdf
```
