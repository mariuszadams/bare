# BARE #
## The BAsh scripts REpository ##
#### could be useful or at least interesting ####

## CFR ##
The CloudForms Runner script, adapted for the Red Hat OPEN TLC Labs System (decommissioned in June 2024).

It basically allowed to check information and credentials needed to access a test environment or extend the lifetime of an instance without leaving the command line.
The script is a simple demonstration of how to interact with an API using curl and bash.
### USAGE and ARGUMENTS ###
```
    Syntax: cfr -a|-h|-v|-y|keyword 
   
    (P) mariuszadams - The Cloudforms runner. 
    options: 
     -a|-A    Run all instances 
     -h|-H    Print this help info 
     -v|-V    view instance details only, do not run 
     -y|-Y    confirm each instance run 
     keyword  run only instance with keyword in description 
```