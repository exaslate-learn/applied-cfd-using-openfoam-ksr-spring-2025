Project - 2: OpenFOAM: Solving Convection equation using OpenFOAM

* solver
  * Run 'wmake' command inside 'simpleConvectionSolver'
 
* case
  * blockMesh              // this command will generate the mesh in OpenFOAM
  * cp -r 0_orig 0         // copying the *0_orig* as *0*
  * setFields              // set the initial wave field
  * simpleConvection       // this command will run the compiled convection solver 
  * touch convection.foam  // this command will generate the .foam extension to run the post-processing
 
* post-processing
  * Open 'paraview'
  * Generate the contour and line plot 

