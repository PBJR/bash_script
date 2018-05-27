#### Instruction for interface script
`destination.bash` is a script to print the routing trace from the source to a given destination node. To use the script, it must be uploaded to the `bellman-ford` node in the project topology after the network has had all appropriate routing rules added. Below are the steps to get this script to work with the GENI project.
1. Upload the script onto the "bellman-ford" node. I recommend this GENI [link](http://groups.geni.net/geni/wiki/GENIExperimenter/Tutorials/GENI_Desktop_and_GEMINI_runcmd/ExecuteExperiment) for reference.
2. SSH onto the `bellman-ford` node.
3. Run the following on the command to change the permissions of the script file: ```chmod 755 destination.bash```.
4. Run the script: ```./destination.bash```.
5. The user will then be prompted to enter a destination node, and once the destination is inputted the script will print the desired output.
