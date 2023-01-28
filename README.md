# ABA

An executable program to solve BA problems with some datasets. Should work on an Ubuntu OS with minimum 8G of memory.

The source code will be open SOON.

### Usage

Open an "terminal" and go to the folder of ABA. Select a line in the file “run.sh" and call ”sh run.sh".

### Notes

* Incremental solver is not fully paralleled, and it may take a long to time to complete.
* Distributive extension of the method is straight forward. However, implementation is non-trivial because for example network programming. **A simple demo will be provided when we open the source code.**
* The BAL dataset, which is not given here, is available at [Bundle Adjustment in the Large (washington.edu)](https://grail.cs.washington.edu/projects/bal/)

* The files with names like "model_output_*.txt" are the output 3D structure and camera poses. They can be open by using [CloudCompare - Open Source project](https://www.cloudcompare.org/)
