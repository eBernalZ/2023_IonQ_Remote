# 2023_planning_ionq
IonQ's repository for iQuHACK 2023 (private planning)


## Working on qBraid
[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/iQuHACK/2023_planning_ionq.git)
1. If you're working on qBraid, first fork this repository and click the above `Launch on qBraid` button. It will take you to your qBraid Lab with the repository cloned.
2. Once cloned, open terminal (first icon in the **Other** column in Launcher) and `cd` into this repo. Set the repo's remote origin using the git clone url you copied in Step 1, and then create a new branch for your team:
```bash
cd  <ionq_git_repo_name>
git remote set-url origin <url>
git branch <team_name>
git checkout <team_name>
```

3. Use the environment manager (**ENVS** tab in the right sidebar) to [install environment](https://qbraid-qbraid.readthedocs-hosted.com/en/latest/lab/environments.html#install-environment) "IonQ". The installation should take ~2 min.
4. Once the installation is complete, click **Activate** to [add a new ipykernel](https://qbraid-qbraid.readthedocs-hosted.com/en/latest/lab/kernels.html#add-remove-kernels) for "IonQ".
5. From the **FILES** tab in the left sidebar, double-click on the IonQ repository directory.
6. Open and follow instructions in [`verify_setup.ipynb`](verify_setup.ipynb) to verify your "IonQ" environment setup.
7. You are now ready to begin hacking! Work with your team to complete the challenges.

For other questions or additional help using qBraid, see [Lab User Guide](https://qbraid-qbraid.readthedocs-hosted.com/en/latest/lab/overview.html), or reach out on [Discord](https://discord.gg/gwBebaBZZX).
<<<<<<< HEAD

### qBraid Auto Grader Submission Process To Leaderboard:

**PLEASE MAKE SURE TO DO THE FOLLOWING BEFORE YOU SUBMIT**

- Your team name, task #, and a point person's slack name (just in case we need to reach out).
Once you have completed any of the tasks and have added the team name, task # and a point person's slack name, if you are confused). Please got to File (**File** on the top left of the topbar) and click on the `Share notebook` button.
<img width="319" alt="スクリーンショット 2023-01-26 午後4 42 50" src="https://user-images.githubusercontent.com/32727721/214967319-3d2f64ec-19f8-4a06-bf20-0690f8f0e29e.png">

- Enter `rickyyoung@qbraid.com` and share the file. If it shares successfully, the Ricky will periodically run the autograder and the leaderboard will be updated accordingly.

- Then submit the remote project submission form that will show up on the iQuHACK website during the last 8 hours of hacking. The form will ask for a link to your repository and your team members (all of whom have to be remote iQuHACK participants to maintain elligibility).
=======
>>>>>>> 020a64c8ea4511bff179e592a820395925cff4d3
