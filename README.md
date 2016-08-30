# directory-replication
This repo helps in copying the contents of One Directory To another and Continuously updating the contents if they are updated in Main directory to its replicas.
The task this repo does are:
1. Copy the contents of one directory to another.
2. If the content of main directory changes then the contents of the backup directory are also updated.
3. If someone alters the contents of backup directory then the altered content is deleted.

If you want to use this jar file then just type the follwing line on the command prompt "java -jar ReplicationServer.jar" followed by atleast two directory names in double quotes, the first one being served as Main directory and the following being treated as replication directories.

Example: java -jar ReplicationServer.jar "path1" "path2" "path3"
