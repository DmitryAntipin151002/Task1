Started by user Dmitry
Running as SYSTEM
Building in workspace /var/lib/jenkins/workspace/tomcad
The recommended git tool is: NONE
No credentials specified
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/tomcad/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/DmitryAntipin151002/Task1.git # timeout=10
Fetching upstream changes from https://github.com/DmitryAntipin151002/Task1.git
 > git --version # timeout=10
 > git --version # 'git version 2.34.1'
 > git fetch --tags --force --progress -- https://github.com/DmitryAntipin151002/Task1.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/main^{commit} # timeout=10
Checking out Revision 81dd4620caec424f365f761e6f14d035a4cdf84b (refs/remotes/origin/main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 81dd4620caec424f365f761e6f14d035a4cdf84b # timeout=10
Commit message: "ver1"
 > git rev-list --no-walk 81dd4620caec424f365f761e6f14d035a4cdf84b # timeout=10
[tomcad] $ /usr/share/maven/bin/mvn mvn clean install
[[1;34mINFO[m] Scanning for projects...
[[1;33mWARNING[m] 
[[1;33mWARNING[m] Some problems were encountered while building the effective model for edu.javacourse.ext:city-register:war:1.0
[[1;33mWARNING[m] 'build.plugins.plugin.version' for org.apache.maven.plugins:maven-compiler-plugin is missing. @ line 80, column 21
[[1;33mWARNING[m] 'build.plugins.plugin.version' for org.apache.maven.plugins:maven-war-plugin is missing. @ line 89, column 21
[[1;33mWARNING[m] 
[[1;33mWARNING[m] It is highly recommended to fix these problems because they threaten the stability of your build.
[[1;33mWARNING[m] 
[[1;33mWARNING[m] For this reason, future Maven versions might no longer support building such malformed projects.
[[1;33mWARNING[m] 
[[1;34mINFO[m] 
[[1;34mINFO[m] [1m------------------< [0;36medu.javacourse.ext:city-register[0;1m >------------------[m
[[1;34mINFO[m] [1mBuilding city-register 1.0[m
[[1;34mINFO[m] [1m--------------------------------[ war ]---------------------------------[m
[[1;34mINFO[m] [1m------------------------------------------------------------------------[m
[[1;34mINFO[m] [1;31mBUILD FAILURE[m
[[1;34mINFO[m] [1m------------------------------------------------------------------------[m
[[1;34mINFO[m] Total time:  0.438 s
[[1;34mINFO[m] Finished at: 2024-05-25T21:32:18+03:00
[[1;34mINFO[m] [1m------------------------------------------------------------------------[m
[[1;31mERROR[m] Unknown lifecycle phase "mvn". You must specify a valid lifecycle phase or a goal in the format <plugin-prefix>:<goal> or <plugin-group-id>:<plugin-artifact-id>[:<plugin-version>]:<goal>. Available lifecycle phases are: validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy, pre-clean, clean, post-clean, pre-site, site, post-site, site-deploy. -> [1m[Help 1][m
[[1;31mERROR[m] 
[[1;31mERROR[m] To see the full stack trace of the errors, re-run Maven with the [1m-e[m switch.
[[1;31mERROR[m] Re-run Maven using the [1m-X[m switch to enable full debug logging.
[[1;31mERROR[m] 
[[1;31mERROR[m] For more information about the errors and possible solutions, please read the following articles:
[[1;31mERROR[m] [1m[Help 1][m http://cwiki.apache.org/confluence/display/MAVEN/LifecyclePhaseNotFoundException
Build step 'Вызвать цели Maven верхнего уровня  ' marked build as failure
[DeployPublisher][INFO] Build failed, project not deployed
Finished: FAILURE
