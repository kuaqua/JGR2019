1) PIV analysis

Folder "PIV"

1-1) filenames, "u_vel_a.txt", "u_vel_b.txt" and "u_vel_c.txt" with the Coriolis effect
matrix data, 51 x 76, interval = 0.0152 m x 0.0020 m
horizontal velocity, unit (m/s)

1-2) filenames, "W_vel_a.txt", "w_vel_b.txt" and "w_vel_c.txt" with the Coriolis effect
matrix data, 51 x 76, interval = 0.0152 m x 0.0020 m
vertical velocity, unit (m/s)

1-1) filenames, "u_vel_d.txt", "u_vel_e.txt" and "u_vel_f.txt" without the Coriolis effect
matrix data, 51 x 76, interval = 0.0152 m x 0.0020 m
horizontal velocity, unit (m/s)

1-2) filenames, "W_vel_d.txt", "w_vel_e.txt" and "w_vel_f.txt" without the Coriolis effect
matrix data, 51 x 76, interval = 0.0152 m x 0.0020 m
vertical velocity, unit (m/s)

2) Computational outputs from Fantom

2-1) Computational outputs without the Coriolis effect

Folder "withoutCoriolis"

Filenames:
kelvinwaves-0005000.dat
kelvinwaves-0005400.dat
kelvinwaves-0005800.dat

2-2) Computational outputs with the Coriolis effect of 2pi/20 (1/s)

Folder "withCoriolis_020" 

Filenames:
kelvinwaves-0004640.dat
kelvinwaves-0004880.dat
kelvinwaves-0005040.dat
kelvinwaves-0005400.dat

2-3) Computational outputs with the Coriolis effect of 2pi/30 (1/s)

Folder "withCoriolis_030" 

Filenames:
kelvinwaves-0004780.dat
kelvinwaves-0004940.dat
kelvinwaves-0005000.dat
kelvinwaves-0005120.dat
kelvinwaves-0005400.dat
kelvinwaves-0005800.dat

2-4) Computational outputs with the Coriolis effect of 2pi/40 (1/s)

Folder "withCoriolis_040" 

Filenames:
kelvinwaves-0004820.dat
kelvinwaves-0004940.dat
kelvinwaves-0005060.dat
kelvinwaves-0005400.dat

2-5) Computational outputs with the Coriolis effect of 2pi/80 (1/s)

Folder "withCoriolis_080" 

Filenames:
kelvinwaves-0005400.dat

2-6) Computational outputs with the Coriolis effect of 2pi/160 (1/s)

Folder "withCoriolis_160" 

Filenames:
kelvinwaves-0005400.dat

3) Format of computatinal outputs

Filename, "no1_kelvinwaves-000####_ws.txt", #: 0-9
row 1: time	"computational time"
row 2: dz	"vertical mesh interval from the bottom to the top of computational domain"
row 3: limit_depth	0.001
row 4: items	number	k_offset	center_x	center_y	delta_x	delta_y	btm_k	sfc_k	btm_z	sfc_z	container_i	container_j	local_i	local_j	dry_wet
row 5 up to row 17604: column	"corresponding number to row 4"
row 17604 up to row 35204: "column number"	temperature	"temperature at each vertical mesh"
row 35205 up to row 52804: "column number"	w	"vertical velocity at each vertical mesh"
row 52805 up to row 70404: "column number"	u	"horizontal velocity at each vertical mesh"

Filename, "no2_kelvinwaves-000####_uv.txt", #: 0-9
row 1 up to row 17600: "column number"	salinity	"salinity at each vertical mesh"
row 17601 up to row 35200: "column number"	v	"width direction velocity at each vertical mesh"

4) Comparisons of uB between computations and theoretical solutions at x = 3.5 m

ub_stokesdrift.txt:
column 1: uB from computations
column 2: ub from Stoke's drift

ub_proposed.txt:
column 1: uB from computations
column 2: ub from proposed equation in this study

5) Normarized amplitude and Coriolis parameter 

a_f.txt:
column 1: Normarized amplitude
column 2: Coriolis parameter 


6) Normarized amplitude and eta_B 

a_eta.txt:
column 1: Normarized amplitude
column 2: eta_B


