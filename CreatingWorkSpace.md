# Workspace Creation  
Follow below steps:  
1) create workspace directory, and enter to that directory  
2) Create new directory named **src**  
-   This directory will contain source code  
3) Create new directory named **bin**  
-   This directory will contain executables  
4) create new directory named **pkg**  
-   This will contain package objects, intermideate form of code that cached
-   This helps reduce compilation time pulling packages from remote reposotories
5) Set GOPATH environment variable as below:  
-   export GOAPTH=<em>workspace</em> path
-   see lisint of env variable  
    -   go env  


# creating pakage  
- name should be all small case and single word, no special characters or spaces
- more details about rules are avaialble [here](https://blog.golang.org/package-names)
- e.g. in current workspace palindrome.go has package named main.


# creating executable  
- Run command  
    - go install
- It will create executables in <em>bin</em> directory


