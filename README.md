Note: Hi Prof, Assignment 1 is complete. We are working on assignment 2,3. It is particularly hard as we keep on encountering some errors. Requesting you to kindly grade 2,3 on 19th Dec. Huge Thanks.

### Team Details
1).  Ahmed Zaytoun - did the main coding part  
2).  G Sai Krishna - researched and set up the environment. Contributed to the coding part and helped troubleshoot errors

### Steps taken
- First we initiated the instance from the GCP console and did all the steps and we found out that nested virtualization is not enabled

- We created a new instance with the folowing command  gcloud compute instances create instance-7 --enable-nested-virtualization --zone=us-central1-a --min-cpu-platform="Intel Haswell" to create a new instance with nested virtualization  
- using "apt install" we installed "git" 
- Cloned the linux repo from git hub
- using "apt install" we installed the missing libraries and modules we needed whenever we faced an error during the steps
- We copied the config file from boot to the linux DR as .config
- ran make prepare 
- solved all errors we faced 
- ran make modules 
- solved all errors we faced "apt install" all missing libs
- ran make to build the kernal 
- ran make modules install 
- ran make install 
- rebooted the kernal 
- we ran make command on our c file
- insmod the .ko file
- ran dmesg to copy the result
