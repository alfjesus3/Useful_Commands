#User Utils Linux

## Tips
* To consult the folders size in a given location use ```du -sh /path/to/dir/``` or ```du -ch /path/to/dir/ | grep total```
* Always install pip packages with the ```no-cache-dir``` option to prevent exceding the storage in /home folder
* To check mpirun processes use ```pgrep -u  \`whoami\` mpirun``` and then ```kill -9 <PID>``` . Alternatively it can used ``` ps -A | grep <PID>```
* To count the number of files in a directory use ```ls <path> | wc -l``` . To count the file is all subfolders ``` find . -type f | wc -l ```
* To untar files into the same folder/file structure user ``` tar -C <desired_name> -xvf ILSVRC2012_img_train.tar ```
