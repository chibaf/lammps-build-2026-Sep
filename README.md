# lammps-build-2026-Sep

cmake -S cmake -B build -D PKG_KSPACE=yes -D FFT=fftw3  
cmake --build build -j12
