<img width="415" height="234" alt="image" src="https://github.com/user-attachments/assets/3de7077d-2bb2-4928-90d8-20f1b7c7d6a7" />
<img width="415" height="234" alt="image" src="https://github.com/user-attachments/assets/97153d40-cb15-4a8d-a514-34cf44455d56" />
<img width="415" height="234" alt="image" src="https://github.com/user-attachments/assets/284f1080-02dd-420c-9c72-ca089de38a3a" />
<img width="415" height="234" alt="image" src="https://github.com/user-attachments/assets/a261a6fc-94f7-4221-8e49-a58c46bafbb6" />
![Uploading image.png…]()
Issues faced and solved 
First of all azure is new to me so it is tough for creating the VM
Creating whole pipeline is also a challenging 
While creating the docker i forgot to add the copy command in my file and it ended up failure of my pipeline
By seeing the console output i cleared the issue
I don't know how to use the Rollback for genuinity i skipped that
Ymal pipeline explaination :
The cicd pipeline starts with the name pipeline and the using any agent
And following the stages first i cloned the code from the git hub
Then i used the docker to build the images using the command docker build -t images
Then i push the code to my docker hub with the user credentials and used the command docker push image
At last i used the docker expose to deploy my hello world application
Summary what I learned :
Azure is new for so i learned how to create a Vm 
I need want to learn more in devops and it is quite enjoyable 


