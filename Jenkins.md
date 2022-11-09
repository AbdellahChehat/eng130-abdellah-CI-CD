## Jenkins

Jenkins is a free and open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.

--- 

## How to create a new job on jenkins

- Step 1: Create new item (On the left you should see New item, select that.)
  
- Step 2: Create job. (Under Enter an item name write the appropriate name for your job)

--- 

## How to SSH connect Between Github and Jenkins

- Step 1: Generate a new key

    - Generate a new ssh key in your localhost and name format eng130-abdellah-jenkins. Steps to gerating a key can be found here in my How to create SSH key README.

- Step 2: Copy Key into Github

    - Open up the correct repo select Settings on that repo
    - Select `Deploy Keys` and select `Add deploy key`
    - Copy the public ssh key into key and name it
    - Now select `Add key`

- Step 3: Connect to Jenckins

    - Create a new Jenkins item and select Freestyle Project
    - Set up the following configurations:

        - Discard old builds: 3
        - Github project: Insert GitHub HTTPS repo link
        - Restrict where this project can be run: logical expression to specify which agent to execute builds of the project (e.g. sparta-ubuntu-node)
        - Git:
            - Repository URL: Insert GitHub SSH repo link
            - Credential: Add -> Jenkins -> Key -> Insert private ssh key
        - Branches to build: */main
        