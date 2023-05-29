
# sdf-bt-mesh-experimental
Some experimental material for making conversions between SDF and Bluetooth Mesh models

YAML-folder: manually generated YAML files for Bluetooth Mesh Models, using the Mesh Model specification (https://www.bluetooth.com/specifications/specs/mesh-model-1-0-1/)

Some notes:

* currently the "in" and "out" parameters are explicitly marked in the file
* Mesh model does not define "boolean" except in the text part, so this is now parsed from the description. This may change in the future
* sdfData for messages (incoming and outgoing) is now collected into object types
