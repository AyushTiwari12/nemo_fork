NEMO is a toolbox for stellar dynamics, particle simulations, image processing and
tabular data manipulation. See also https://teuben.github.io/nemo

This is the 4th major release of NEMO,  and although data are compatible
with earlier releases, source code will generally need to be tweaked a
bit to compile and link in the newer releases. 

   * NEMO V1:	IAS release (Barnes, Hut & Teuben; appr. 1987)
   * NEMO V2:	UMD release (Teuben 1994)
   * NEMO V3:	UMD release (Teuben 2001) with autoconf support and
		hooks into manybody.org modules starlab and partiview
   * NEMO V4:        UMD/ESO release (2017) now maintained within github

A related package, ZENO, was spun off NEMO V1, and is maintained by Barnes.

  	  NEMO:     ascl:1010.051
	  ZENO:     ascl:1102.027

Packages we optionally use:

	 PGPLOT:    ascl:1103.002
	 CFITSIO:   ascl:1010.001
	 WCSLIB:    ascl:1108.003
	 HDF:	    ascl:1502.009
	 glnemo2:   ascl:1110.008
	 gyrfalcON: ascl:1402.031 (included with NEMO)
	 unsio
	 uns_project

See README.install for installation guidelines. In it's simplest the following commands may work:


	 wget https://teuben.github.io/nemo/test_a_new_nemo_git
	 chmod +x test_a_new_nemo_git
	 ./test_a_new_nemo_git nemo=$HOME/opt/nemo
