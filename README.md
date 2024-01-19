# Understanding-PySpark

import OS

The OS module in python provides functions for interacting with the operating system. 

The below code will retrieve the OS environment variables

# importing os module  
import os 
import pprint 
   
# Get the list of user's 
env_var = os.environ 
   
# Print the list of user's 
print("User's Environment variable:") 
pprint.pprint(dict(env_var), width = 1)

The JAVA_HOME environment variable points to the file system location where the JDK or JRE was installed.
