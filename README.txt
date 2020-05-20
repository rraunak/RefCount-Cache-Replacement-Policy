

Raunak
1217240245


1. Inside the assignment2 Folder, Install the gem5 from the following link by typing on the terminal:

     git clone https://github.com/gem5/gem5

2. Then go inside gem5 folder,

     cd gem5 

3. Change the version of gem5 through following command,    

     git checkout -b cse520 34b73dea1b144fcc5707d618acd950f7f1506806


4. Then copy the gem5_v2.patch inside the gem5 folder,
Apply the patch through the following command,

     patch -p0 -i gem5_v2.patch

5. Then go outside the gem5 folder,

     cd ..

6. Apply the patch RefCount.patch through the following command,

     patch -p0 -i RefCount.patch

7. Extract the benchmarks benchmarks_assign2.zip given in the canvas, inside the gem5 folder in the benchamarks directory,

8.Move the benchmarks folder outside of the benchmark_assign2 folder in the root gem5 directory,

9.copy the run.sh script inside the gem5 root directory.

10. Make the script executable by the following command,

     sudo chmod +x run.sh

11. Run the run.sh script to obtain the results.







