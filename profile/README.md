Experiments on 3d commerce validation and schemas by @fire

1. Investigate CUE to allow validation of composition of glTF 2.0 standards.

Smallest demonstration.

1. Take a fox and save it as json embedded
2. Validations from 3DC:
    1. File Size (min/max)
    2. Triangle Count (max)
    3. Material Count (max)
    4. Texture Map Resolution Power of 2
    5. Dimensions (min/max)
    6. Dimensions (product within tolerance)
3. Input and validation check in gltf.
    1. Return the input.
    2. Change the source asset.
        1. "generator" : "Khronos glTF Blender I/O v3.2.43 and by fire-3dc-validator version AAA FAILED" 
        2. "generator" : "Khronos glTF Blender I/O v3.2.43 and fire-3dc-validator version AAA PASSED"
    3. Return a report.
