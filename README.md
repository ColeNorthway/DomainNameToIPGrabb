# DomainNameToIPGrabb
This was a project I created regarding OSINT capabilities. It basically will grab all domains under a main domain with crt.sh's JSON api and write them to a file.
This is done with the Grbb.java class.


It then will parse all of these domains from the certificates associated with them and write them to a file with FileAdd.java class. 


After that all repeat domains are filtered and written to another file with the FileSanitize.java class.


Then finally it will DNS query every domain in the last file and write them to a file with the corresponding domain witht the IPGrbb.java class.
