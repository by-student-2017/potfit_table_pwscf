potfit_table_pwscf


------------------------------------------------------------------------------
# potfit (need "intel MKL")


(ubuntu 18.04 LTS (64 bit) (on Windows 10 (64 bit)))


(https://www.potfit.net/wiki/doku.php)


(Edit: 28/Jul/2020)


## Install
1. sudo apt update
2. sudo apt install -y git
3. cd ~
4. git clone https://github.com/by-student-2017/potfit_table_pwscf.git
5. cd ~/potfit_table_pwscf
6. chmod +x run_pwscf_potfit_table


Please, install and set PATH of potfit for PWscf and cif2cell-informal.


## Run
1. cd ~/potfit_table_pwscf
2. export OMP_NUM_THREADS=1
3. gedit table
4. ./run_pwscf_potfit_table Al eam 100


  (e.g., Al, EAM potential, k-resolution=100(In this case, allmost 1 k point calculation))


  or


  ./run_pwscf_potfit_table Al eam


  (e.g., Al, EAM potential)


  or


  ./run_pwscf_potfit_table Mg_H eam


  (e.g., Mg_H, EAM potential)


  or


  ./run_pwscf_potfit_table Mg_H adp


  (e.g., Mg_H, ADP potential)


  or


  ./run_pwscf_potfit_table Mg_Ni_H eam


  (e.g., Mg_Ni_H, EAM potential)


  or


  ./run_pwscf_potfit_table Mg_Ni_H adp


  (e.g., Mg_Ni_H, ADP potential)


