# Linux-Assignment01
question-01 
Creating and Renaming Files/Directories
Create a directory named test_dir using mkdir.
Inside test_dir, create an empty file called example.txt.
Rename example.txt to renamed_example.txt using mv

Answer:
step1: mkdir test_dir
step2: touch example.txt
step3: mv example.txt renamed_example.txt

question-02
Viewing File Contents
Use cat to display the contents of /etc/passwd.
Display only the first 5 lines of /etc/passwd using head.
Display only the last 5 lines of /etc/passwd using tail.

Answer:
step1: cat /etc/passwd
step2: haed -n 5 /etc/passwd
step3: tail -n 5 /etc/passwd

question-03
Use grep to find all lines containing the word "root" in /etc/passwd.

Answer:
step1: grep 'root' /etc/passwd

question-04
Zipping and Unzipping
Compress the test_dir directory into a file named test_dir.zip using zip.
Unzip test_dir.zip into a new directory named unzipped_dir.

Answer:
step1: zip -r test_dir.zip test_dir
step2: unzip test_dir.zip -d unzipped_dir
step3: ls       ---Verify

question-05
Downloading Files
Use wget to download a file from a URL (e.g., https://example.com/sample.txt)

Answer:
step1: wget https://example.com/sample.txt

question-06
Create a file named secure.txt and change its permissions to read-only for everyone using chmod.

Answer:
step1: touch secure.txt          ---Create a file named secure.txt
step2: chmod 444 secure.txt      ---Change its permissions to read-only
step3: ls -l secure.txt          ---Verifying

question-07
Use export to set a new environment variable called MY_VAR with the value "Hello, Linux!".

Answer:
step1: export MY_VAR='Hello, Linux!!'
step2: echo $MY_VAR
output: Hello, Linux!!















