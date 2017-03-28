# g-code-snippets

* Return to 0 (X-Y plane): `G90 G0 X0 Y0`
* Reset work offset G54 to 0 at current position: `G10 L20 P1 X0 Y0 Z0`

# My xPro v2 settings
```
$0 = 10    (step pulse, usec)
$1 = 255    (step idle delay, msec)
$2 = 0    (step port invert mask:00000000)
$3 = 6    (dir port invert mask:00000110)
$4 = 0    (step enable invert, bool)
$5 = 0    (limit pins invert, bool)
$6 = 0    (probe pin invert, bool)
$10 = 3    (status report mask:00000011)
$11 = 0.020    (junction deviation, mm)
$12 = 0.002    (arc tolerance, mm)
$13 = 0    (report inches, bool)
$20 = 1    (soft limits, bool)
$21 = 0    (hard limits, bool)
$22 = 1    (homing cycle, bool)
$23 = 1    (homing dir invert mask:00000001)
$24 = 25.000    (homing feed, mm/min)
$25 = 500.000    (homing seek, mm/min)
$26 = 250    (homing debounce, msec)
$27 = 3.000    (homing pull-off, mm)
$100 = 33.333    (x, step/mm)
$101 = 26.667    (y, step/mm)
$102 = 200.000    (z, step/mm)
$110 = 4000.000    (x max rate, mm/min)
$111 = 4000.000    (y max rate, mm/min)
$112 = 2500.000    (z max rate, mm/min)
$120 = 50.000    (x accel, mm/sec^2)
$121 = 50.000    (y accel, mm/sec^2)
$122 = 50.000    (z accel, mm/sec^2)
$130 = 557.000    (x max travel, mm)
$131 = 775.000    (y max travel, mm)
$132 = 67.000    (z max travel, mm)
```
