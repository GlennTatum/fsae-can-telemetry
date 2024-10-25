https://docs.openvehicles.com/en/latest/components/vehicle_dbc/docs/dbc-primer.html

## TODO

decode hex data stream (type ASCII) into a hex array 

```python

byte = [0xd0, 0xc8, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00]
```

use cantools to read byte array and decode the can message. refer to `.ipynb` file for how to decode a hex (bytearray) datastream with a dbc file
