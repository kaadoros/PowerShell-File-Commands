# PowerShell-File-Commands
This repository houses Powershell commands I used for a Statistics project on tracking time of transferring files to a separate hard drive.

The first line grabs whatever is within the filepath (useful for grabbing multiple files within a folder).

The second line measures the time it takes for the desired item to copy from one filepath to another.

The third line spits out the result into an object where it has a source name (which puts the filepath for the file
for a single object and an object array for multiple objects) and the time it took for the copy to happen in seconds.

The fourth line exports the result object created and puts it into a CSV file at the desired filepath.



# The next three lines are a separate command set for making a dummy file of desired size.

The first line makes an object of desired filetype (depends on what file extension is added at the end of the path) at the desired location of "0 size".

The second line sets the length of the object (in bytes, ex. SetLength(1000KB) or SetLength(10GB))

The final line closes the object creation.
