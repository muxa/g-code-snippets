# g-code-snippets

* Return to 0 (X-Y plane): `G90 G0 X0 Y0`
* Reset work offset G54 to 0 at current position: `G10 L20 P1 X0 Y0 Z0`

# My xPro v2 settings
```
$0 = 10    (Step pulse time, microseconds)
$1 = 255    (Step idle delay, milliseconds)
$2 = 0    (Step pulse invert, mask)
$3 = 6    (Step direction invert, mask)
$4 = 0    (Invert step enable pin, boolean)
$5 = 0    (Invert limit pins, boolean)
$6 = 0    (Invert probe pin, boolean)
$10 = 3    (Status report options, mask)
$11 = 0.020    (Junction deviation, millimeters)
$12 = 0.002    (Arc tolerance, millimeters)
$13 = 0    (Report in inches, boolean)
$20 = 1    (Soft limits enable, boolean)
$21 = 0    (Hard limits enable, boolean)
$22 = 1    (Homing cycle enable, boolean)
$23 = 1    (Homing direction invert, mask)
$24 = 25.000    (Homing locate feed rate, mm/min)
$25 = 500.000    (Homing search seek rate, mm/min)
$26 = 250    (Homing switch debounce delay, milliseconds)
$27 = 3.000    (Homing switch pull-off distance, millimeters)
$30 = 1000    (Maximum spindle speed, RPM)
$31 = 0    (Minimum spindle speed, RPM)
$32 = 0    (Laser-mode enable, boolean)
$100 = 26.667    (X-axis travel resolution, step/mm)
$101 = 26.667    (Y-axis travel resolution, step/mm)
$102 = 200.000    (Z-axis travel resolution, step/mm)
$110 = 4000.000    (X-axis maximum rate, mm/min)
$111 = 4000.000    (Y-axis maximum rate, mm/min)
$112 = 2500.000    (Z-axis maximum rate, mm/min)
$120 = 50.000    (X-axis acceleration, mm/sec^2)
$121 = 50.000    (Y-axis acceleration, mm/sec^2)
$122 = 50.000    (Z-axis acceleration, mm/sec^2)
$130 = 557.000    (X-axis maximum travel, millimeters)
$131 = 775.000    (Y-axis maximum travel, millimeters)
$132 = 67.000    (Z-axis maximum travel, millimeters)
```
