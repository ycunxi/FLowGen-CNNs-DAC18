#### How to get data points using your own design and Technlogy library?
##### Command: **./abc -c "read i10.aig; synthesis_rand_1"**
##### Notes: make sure you have "yourLib.genlib" at the your env
<sub><br/>*stout by ABC shown bellow*<br/>
*ABC command line: "read i10.aig; synthesis_rand_1".<br/>
Entered genlib library with 15 gates from file "yourLib.genlib".<br/>
Converting "yourLib.genlib" into supergate library "yourLib.super".<br/>
Maximum level: Original = 35. Reduced due to choices = 35.<br/>
Choice stats:  Choice nodes = 0. Total choices = 0.<br/>
Nodes =   2063.  Total 5-feasible cuts =      28104.  Per node = 13.6. Time =     0.01 sec<br/>
Delay    : Delay =     0.00  Flow =     63162.9  Area =     11799.0   0.0 %   Time =     0.00 sec<br/>
AreaFlow : Delay =   218.63  Flow =      8340.9  Area =      8892.0  24.6 %   Time =     0.01 sec<br/>
Area     : Delay =   218.63  Flow =         0.0  Area =      7415.0  37.2 %   Time =     0.01 sec<br/>
Area     : Delay =   218.63  Flow =         0.0  Area =      7172.0  39.2 %   Time =     0.01 sec<br/>
Output  V435(0)    : Delay = (218.63, 218.63)  NEG<br/>
Output  V398(0)    : Delay = (218.52, 218.52)  NEG<br/>
Output  V432       : Delay = (217.67, 217.67)  POS<br/>
Output  V393(0)    : Delay = (216.03, 216.03)  NEG<br/>
Output  V357       : Delay = (205.00, 205.00)  POS<br/>
Total runtime =     0.06 sec<br/>
i10                           : i/o =  257/  224  lat =    0  nd =  1581  edge =   3676  area =7172.00  delay =218.63  lev = 21*<br/></sub>
