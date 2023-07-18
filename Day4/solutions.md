1. Explain in your own words and examples, what is Shell Scripting for DevOps.\
    Shell scripting for DevOps enables the automation of manual processes, reducing human effort and minimizing the potential for errors. It allows for the creation       of scripts that can execute a series of commands, interact with system resources, handle file operations, and perform other operations required for Devops
    activities.
Here are a few examples of how shell scripting can be used in DevOps:
    1. Automated Deployment: A shell script can be written to automate the deployment process of an application. It can handle tasks like pulling the latest code       from a repository, building the application, stopping the previous version, and starting the new version.
    2. Configuration Management: Shell scripting can be used to manage system configurations across multiple servers. It can update configuration files, install        software packages, and perform system-level configurations consistently.
    3. Continuous Integration/Continuous Deployment (CI/CD): Shell scripts can be utilized to automate the CI/CD pipeline. They can trigger the build process, run      tests, package the application, and deploy it to different environments.
    4. Log Analysis and Monitoring: Shell scripts can process log files, extract relevant information, and generate reports or trigger alerts based on specific         conditions. This helps in monitoring system health and identifying potential issues.
    5. Backup and Recovery: Shell scripts can be created to automate backup operations for databases, files, and system configurations. They can schedule backups,      compress data, transfer files to remote locations, and verify backup integrity.

   Shell scripting provides a powerful and flexible way to automate repetitive tasks and orchestrate complex workflows in the DevOps realm. By leveraging shell          scripting, DevOps engineers can save time, increase productivity, and maintain consistency in their operations.

2. What is #!/bin/bash? can we write #!/bin/sh as well?
#!/bin/bash A shebang line used in script files to set bash, present in the '/bin' directory, as the default shell for executing commands present in the file. It defines an absolute path /usr/bin/bash to the Bash shell.

Yes, you can use #!/bin/sh as the shebang line in your shell script.
The shebang line (#!/bin/sh) indicates the interpreter to be used to execute the script. In this case, it specifies that the script should be interpreted by the /bin/sh shell.
While #!/bin/bash explicitly specifies the Bash shell as the interpreter, #!/bin/sh is more generic and typically points to the default shell interpreter on most Unix-like systems.

 3.Write a Shell Script which prints I will complete #90DaysOofDevOps challenge\
Create a file with .sh extention ex. devops_challenge.sh and write #!bin/bash in it.\
![Screenshot 2023-07-18 145443](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/57174b5e-6fa2-4f55-b3cd-798cbddaad64)

Then, make the file executable using the following command:\
chmod +x devops_challenge.sh\
![Screenshot 2023-07-18 145638](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/b047d189-409e-4f8b-ad25-246830a4c411)

Finally, run the script by executing:\
./devops_challenge.sh\
![Screenshot 2023-07-18 145749](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/dc19465c-82c7-4c77-bcd9-e938da7db772)

You should see the following output:\
![Screenshot 2023-07-18 145850](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/85d6d162-909d-4c66-a832-b0e919c1f6bc)

4. Write a Shell Script to take user input, input from arguments and print the variables.\
Create a file named test_name.sh and write the following shell script in it.\
![Screenshot 2023-07-18 150339](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/f1740e63-4394-4a77-93dc-1549a933bdf3)

Then, Make it executable using the command : chmod +x test_name.sh\
![Screenshot 2023-07-18 150745](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/1b4cdd5f-12fc-408b-9f58-3d718ad69b42)

Finally, run the script by executing:\
./test_name.sh

You will see the following output. Enter your name and it will get print.\
![Screenshot 2023-07-18 151036](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/aaefd7cf-8919-45be-9f0f-f69803a442d1)

5.Write an Example of If else in Shell Scripting by comparing 2 numbers.\
![Screenshot 2023-07-18 151532](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/6a7f79eb-e23c-4742-a0ac-5e0a71fd881d)
