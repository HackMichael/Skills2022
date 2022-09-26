<head> TASK 1 </head>

Firstly I have created git repository and fie "README.MD". after taht I make a new commit.
![1](https://user-images.githubusercontent.com/102226081/191988120-119a3093-0710-4f04-a51d-b276da7da6d6.png)

Second step I added a Git URL as a remote alias. Then I used the git push origin master command to send the file to my GitHub repository.
![2](https://user-images.githubusercontent.com/102226081/191989134-509e774b-4bdd-4221-b0d7-a6bd2a2aa925.png)

And then I have checked my repository on GitHub.
![3](https://user-images.githubusercontent.com/102226081/191989229-603dd901-3b55-4bb9-9763-93ec7dd6a2a1.png)

TASK 2

Firstly we need to do some preparation. On the screenshot below you can see that I make hosts file where I establish my web servers parameters.
![2](https://user-images.githubusercontent.com/102226081/192366308-4b66879e-c8d7-4d9b-9a2d-f8a27c736655.png)

Then I make ansible.cfg file for my playbook, to establish hosts for playbook.
![1](https://user-images.githubusercontent.com/102226081/192366063-1bf24480-1782-4bd2-b193-d5ca7aeb072e.png)

Here you can see my WEBSERVER_INSTALATION_AND_TESTING.yaml file which install Apache and testing it.
![3](https://user-images.githubusercontent.com/102226081/192366558-9e33eca2-ac4e-4f7d-b41a-ad565a84fb0d.png)

After that I have used command: "ansible-playbook -v WEBSERVER_INSTALATION_AND_TESTING.yaml". The output of this command shows that webserver was successfully installed and tested.
![4](https://user-images.githubusercontent.com/102226081/192366771-b6b2d252-4ff3-4af7-b696-6d489b9ea603.png)
![5](https://user-images.githubusercontent.com/102226081/192366953-d3cf5cd1-33d9-4d82-a194-a623dce19c61.png)

TASK 3
Firstly we need a pull our ntp server.
![1](https://user-images.githubusercontent.com/102226081/192367176-95e2a7f2-2577-4dee-97dd-028b15efcb57.png)

After some configuration we will start our docker. On the screenshot below you can see details on our ntp servers status.
![3](https://user-images.githubusercontent.com/102226081/192367347-54a7e0a6-d6ee-481f-9796-2d656c1f2c55.png)

 
 TASK 4
 
To create a Jenkins pipeline firstly we need to pull Jenkins by command:"docker pull jenkins/jenkins".
![1](https://user-images.githubusercontent.com/102226081/192367723-dc9e151f-c00e-4115-b7e9-a0ba6bbb869e.png)
 
After that I have connected to the Jenkins and made a new item, which will be our pipeline. Here I have established URL of my repository.
![2](https://user-images.githubusercontent.com/102226081/192367918-f8240e1c-7993-4373-af85-6095af7b3052.png)

Then in cofiguration part I wrote a startup.sh file, which you can find in Task4 dictionary.
![3](https://user-images.githubusercontent.com/102226081/192368115-b4c6ef68-c8bc-4193-8952-0b8468eac110.png)

Now we can build our pipeline. After 1 min and 6 sec it was successfully built.
![4](https://user-images.githubusercontent.com/102226081/192368477-a2807b23-33fe-40e1-a170-5c93457156c8.png)


TASK 5

Here we need to wrote test.py to test our main.py.
All files you can find in Task5 dictionary.
![1](https://user-images.githubusercontent.com/102226081/192368799-f8b69a69-4da3-4dcd-841c-1c459f2aa375.png)
![2](https://user-images.githubusercontent.com/102226081/192368826-8df7ba68-07e3-4fe4-8348-6dad02a67353.png)

After coding we can launch our program.
Here you can see results of the test.
![3](https://user-images.githubusercontent.com/102226081/192369029-351bb3d2-25d4-4e0b-9a83-5e4b77c5d6f6.png)



