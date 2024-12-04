tarted by user galal-shalby-ezz
Running as SYSTEM
Building in workspace /var/jenkins_home/workspace/java-ecommerce
The recommended git tool is: NONE
using credential githube-credintial
 > git rev-parse --resolve-git-dir /var/jenkins_home/workspace/java-ecommerce/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/galalshalaby/jave-smal-project.git # timeout=10
Fetching upstream changes from https://github.com/galalshalaby/jave-smal-project.git
 > git --version # timeout=10
 > git --version # 'git version 2.39.5'
using GIT_ASKPASS to set credentials 
 > git fetch --tags --force --progress -- https://github.com/galalshalaby/jave-smal-project.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/master^{commit} # timeout=10
 > git rev-parse origin/master^{commit} # timeout=10
ERROR: Couldn't find any revision to build. Verify the repository and branch configuration for this job.
Finished: FAILURE
