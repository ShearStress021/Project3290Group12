# Group 12
Fundamental of Machine Learning



## How to Access Project

To switch to a specific branch in the repository, follow these steps:

1. **Clone the Repository** (if you haven't already):

   ```bash
   git clone https://github.com/ShearStress021/Project3290Group12.git
   ```
   &emsp; or

   ```bash
   gh repo clone ShearStress021/Project3290Group12.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Project3290Group12
   ```
2. **Create Virtual Environment**
    ```bash
    python3 -m venv env
    ```
   
3. **Activate Virtual Environment**
    ```bash
    source env/bin/activate
    ```
     &emsp; or
     ```bash
     .\env\Scripts\Activate

     ```
4. **Link env to ipykernel**
    ```bash
     python3 -m ipykernel install --user --name=env

     ```
5. **Install the necessary packages.**
    ```bash
    pip install -r requirements.txt
    ```

6. **Open jupyter notebook**
   ```bash
   jupyter notebook
   ```

## Working on the project



1. **Pull Latest Changes from Main**
   - Fetch the latest updates from the `Main` branch:
     ```bash
     git fetch origin main
     ```
   - Merge the latest changes from `Main` into your branch:
     ```bash
     git merge origin/main
     ```
2. **Create a new Branch and switch to the branch**
    ```bash
   git checkout -b <branch-name/feature-name>
   ```
3. **Resolve Any Conflicts**
   - If there are any merge conflicts, resolve them in your local environment and commit the changes.

3. **Push Updated Branch**
   - After ensuring everything is working, push your updated branch:
     ```bash
     git push origin <branch-name/feature-name>
     ```
### Additional Tips
- Regularly check for updates in the `main` branch and repeat the steps above if there are any new changes.
- Always test your code after merging to make sure everything is functioning as expected.
- Reach out to the team if you encounter issues during the merge process.


---

