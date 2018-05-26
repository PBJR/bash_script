# Network Trace script
This is a BASH script to print the routing trace from the source to a given destination node. To use the script, it must be uploaded to the desired source node in a given network topology. For the purpose of our project, the desired source node is the "bellman-ford" node. 
1. Upload the script onto the "bellman-ford" node. I recommend this GENI[link](http://groups.geni.net/geni/wiki/GENIExperimenter/Tutorials/GENI_Desktop_and_GEMINI_runcmd/ExecuteExperiment) for reference. 
2. Run the following on the command line to change the permissions of the script file: ```chmod 755 destination.bash```. 
3. Run the script: ```./destination.bash```. 
4. The user will then be prompted to enter a destination node, and once the destination is inputted the script will print the desired output.
