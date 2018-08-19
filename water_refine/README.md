Water refinement: Software XPLOR is used here.

The procedure for water refinement using XPLOR:

1) Install XPLOR 2.26 (If you are using later version, please change the corresponding information in wrefine.py)
2) Put the input pdb file into the folder "proteins";\\
   Put the restraints files into the folder "constraints" (See examples in folder "constraints"):

3) In current directory, run the command:
   ./run_wrefine.sh proteins
   The final results will be generated under the current directory.
