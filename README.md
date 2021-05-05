# Ghost-String-Utility

We provide users a Java library that can be used for manipulating and searching strings in many ways that are not provided by the default Java libraries. 

The Ghost-String-Utility is created keeping in mind of the fact that current default Java libraries allow users to search for a smaller String from a larger String only if the String cases match. 

The Ghost-String-Utility object can be created by using:

GhostString <objectName>= new GhostString();

The various methods that can be invoked by this Utility are given below.

1. isStringIgnoreCasePresent:
   
   Usage:isStringIgnoreCasePresent(String mainString, String keyword)
   - This method returns a boolean value. 
   - It returns true if the key String is present in the main String regardless of the String cases.
   - The argument Strings will be UTF-8 encoded and hence the results will be accurate regardless of the dialects present in the String.
   
   

