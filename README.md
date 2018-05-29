# PRASD
This is a program for protein reconstruction using ASD/scaledASD algorithm (PRASD) from NOESY distance. The source code (in MATLAB ) is in the zip file "source_code.zip". 

The standalone installations and usages of PRASD (No need to install MATLAB) for different platforms are as follows:

1) For MacOS       
  (1)  Download the installation package from the website "http://physics.bit.edu.cn/docs/20180529023026979223.zip"        
  (2)  Install the PRASD program by double clicking "MyAppInstaller_mcr" (MCR (Matlab Compile Runtime) included in the package) or "MyAppInstaller_web" (MCR will be downloaded through internet);       
  (3) For running
          i.  Copy the file "ainfo.mat" to the installation folder where "PRASD" and "./run_PRASD.sh" are located             
          ii. Open the command line terminal, and in the terminal go to the installation folder using command "cd your_installation_pathway".          
          iii. Type "./run_PRASD.sh your_MCR_folder_pathway your_protein_folder_pathway your_protein_name start_resid end_resid your_output_pathway algorithm_option" to run the program.             
              Two examples:                
              ./run_PRASD.sh /Applications/MATLAB/MATLAB_Runtime/v85 ~/Downloads/standalone_test1/proteins/ 1g6j 1 76 PRASD_output ASD        
              ./run_PRASD.sh /Applications/MATLAB/MATLAB_Runtime/v85 ~/Downloads/standalone_test1/proteins/ 1g6j 1 76 PRASD_output ScaledASD        

2) For Windows     
  (1)  Download the PRASD installation package  from "http://physics.bit.edu.cn/docs/20180529022919550172.zip"    
  (2)  Install the PRASD program by double clicking "MyAppInstaller_mcr.exe" ( MCR included in the package) or "MyAppInstaller_web.exe" (MCR will be downloaded through internet)    
  (3)  For running,     
          i.  Copy the file "ainfo.mat" to the installation folder where "PRASD.exe" is located.   
          ii.  Open the command line terminal, and go to the installation folder from terminal using command "pushd your_installation_pathway"    
          iii. Type "PRASD.exe your_protein_folder_pathway your_protein_name start_resid end_resid your_output_pathway algorithm_option" to run the program    
          Two examples:    
            PRASD.exe D:\Input_examples\proteins 1g6j 1 76 D:\PRASD_output ASD     
            PRASD.exe D:\Input_examples\proteins 1g6j 1 76 D:\PRASD_output ScaledASD    
 
3) For Linux       
  (1)  Download the application PRASD package from "http://physics.bit.edu.cn/docs/20180529022809537051.zip" and the MCR2014b-Linux package from "https://ww2.mathworks.cn/products/compiler/matlab-runtime.html".       
  (2)  For running, open a command terminal, go to the PRASD package folder and type command:        
        "./run_PRASD.sh your_MCR_folder_pathway your_protein_folder_pathway your_protein_name start_resid end_resid your_output_pathway algorithm_option"        
     Two examples:                
        ./run_PRASD.sh /usr/local/MATLAB/R2014b /user_name/Input_examples/proteins 1g6j 1 76 PRASD_output ASD       
        ./run_PRASD.sh /usr/local/MATLAB/R2014b /user_name/Input_examples/proteins 1g6j 1 76 PRASD_output ScaledASD       
  


http://physics.bit.edu.cn/docs/20180529022559638863.zip input examples
