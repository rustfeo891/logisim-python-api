# logisim-python-api
logisim python api

# Build Logic Gate throuh code instead of gui

# How to use

python3 "file" > "your circ filename".circ

```python
from logisim import *

open_project()
build_default_toolbar()
circuit.start("main")

add_pin(100,100,"east",False,"PinA")
add_pin(100,200,"east",False,"PinB")

wire.add(100,100,150,100)
wire.add(150,100,150,150)

add_gate(200,200,ToolNameAndGate,facing="east")
add_clock(300,300,facing="east")

circuit.end()
close_project()

```
