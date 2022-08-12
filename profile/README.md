Experiments on 3d commerence validation and schemas by @fire

1. Investigate CUE to allow validation of composition of glTF 2.0 standards.

Smallest demonstration.

1. Take a fox and save it as json embedded
2. Validations from 3DC:
    File Size (min/max)
    Triangle Count (max)
    Material Count (max)
    Texture Map Resolution Power of 2
    Dimensions (min/max)
    Dimensions (product within tolerance)
3. Input and validation check in gltf.
  1. Return the input.
  2. Change the source asset.
     "generator" : "Khronos glTF Blender I/O v3.2.43 and by fire-3dc-validator version AAA FAILED" 
     "generator" : "Khronos glTF Blender I/O v3.2.43 and fire-3dc-validator version AAA PASSED"
  3. Attach a report.
