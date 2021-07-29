# OSHOTA

An open source auto top off pump controller on the cheap.

This works with a single float switch (closed when the water level is high) and a 5-12v pump.
The pump will be activated at some time after the water level drops too low. This amount of time is
determined by the value of the capacitor and its self discharge rate. The pump will be deactivated after
the water level is high again.
