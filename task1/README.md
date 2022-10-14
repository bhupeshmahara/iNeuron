### Here are some basic git commands

1. **git --version** : display version information about Git

    ![git version](https://user-images.githubusercontent.com/70663493/195586627-83c066be-5735-4b30-8479-d7c8db1b12c7.png)

2. **git init** : create an empty Git repository or reinitialize an existing one

    ![git init](https://user-images.githubusercontent.com/70663493/195586920-596faadb-e579-4a2a-aeb0-53214b15d068.png)

3. git config : set the username and user email for a particular repository
- **git config --global user.name** : set the username for a particular repository
- **git config --global user.email** : set the user email for a particular repository

    ![git config](https://user-images.githubusercontent.com/70663493/195588363-01e72c27-6974-4310-a8d0-81388f90cf65.png)

4. **git status** : show the working tree status

    ![git status](https://user-images.githubusercontent.com/70663493/195588979-c4439fc8-2ed5-46a0-bfa8-4f73e59ee312.png)

5. **git add .** or **git add "filename"** : add file contents to the index
  
    ![git add](https://user-images.githubusercontent.com/70663493/195589176-76bf682c-f02e-45c4-b853-95ff6aafc69c.png)
  
6. **git commit -m "message"** : captures a snapshot of the project's currently staged changes with a passed commit message
  
    ![git commit](https://user-images.githubusercontent.com/70663493/195590248-8b13a2ce-f461-4ad2-a3ca-3ffbcb0ea68e.png)

7. **git branch** : list all of the branches in your repository

    ![git branch](https://user-images.githubusercontent.com/70663493/195591536-6d18d4eb-3fb1-443b-9905-f0053c2f529f.png)

8. **git branch -M main** : rename the current branch
  
    ![git branch main](https://user-images.githubusercontent.com/70663493/195592162-79a780ce-5ded-498a-a37c-5acc23c286dc.png)

9. **git remote -v** : list the remote connections you have to other repositories (include the URL of each connection)
  
    ![git remote](https://user-images.githubusercontent.com/70663493/195592268-805f666a-d79f-4725-ba70-944156223417.png)
  
10. **git push origin main** : push the specified branch to , along with all of the necessary commits and internal objects
  
    ![git push](https://user-images.githubusercontent.com/70663493/195592710-d508ec0f-bf4c-4cd7-b378-b87ba17f0c4e.png)

11. **git restore -staged .** : helps to unstage or even discard uncommitted local changes
  
    ![git restore](https://user-images.githubusercontent.com/70663493/195593562-a00236c9-4011-4e2d-8629-80b024099c01.png)

12. **git branch "branchname"** : create a new branch called "branchname"
  
    ![add new branch](https://user-images.githubusercontent.com/70663493/195593728-9df5b4ca-3f55-4b0d-aa33-423046f1cd71.png)

13. **git checkout "branchname"** : switch to the particular branch

    ![switch to different branch](https://user-images.githubusercontent.com/70663493/195595213-6fd92da0-0f7b-4446-81af-daceb444185a.png)

14. **git merge "branchname"** : lets you take the independent lines of development created by git branch and integrate them into a single branch

    ![git merge](https://user-images.githubusercontent.com/70663493/195595686-7257eac3-8ba7-49cf-a94b-f7559fc6537d.png)

15. **git log** : display the changes you've done in your commits/push

    ![git log](https://user-images.githubusercontent.com/70663493/195596353-c6f676fc-e57b-4845-873d-a8dcca1d4a38.png)
