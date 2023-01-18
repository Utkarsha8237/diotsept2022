Sahi hai!!!
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~$ mkdir python-code
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~$ rm python-code/
rm: cannot remove 'python-code/': Is a directory
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~$ rmdir python-code/
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~$ cd Desktop/
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ mkdir pyhton-code
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ code .
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ sudo apt install git
git                      git-el                   git-mediawiki
git2cl                   git-email                git-merge-changelog
git-all                  git-extras               gitolite3
git-annex                git-flow                 git-phab
git-annex-remote-rclone  git-ftp                  gitpkg
gitano                   gitg                     git-publish
gitbatch                 git-gui                  git-quick-stats
gitbrute                 github-backup            git-reintegrate
git-buildpackage         gitinspector             git-remote-gcrypt
git-buildpackage-rpm     gitit                    git-repair
git-build-recipe         gitk                     git-restore-mtime
git-cola                 gitlab-cli               git-review
git-crecord              gitlabracadabra          git-revise
git-crypt                gitlab-runner            git-secret
git-cvs                  gitlab-shell             git-secrets
git-daemon-run           gitlab-workhorse         git-sizer
git-daemon-sysvinit      gitless                  gitso
git-debpush              git-lfs                  gitsome
git-debrebase            gitlint                  git-svn
git-doc                  gitmagic                 gitweb
git-dpm                  git-man                  
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ sudo apt install git
[sudo] password for diot: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  bridge-utils libdlt2 libllvm9 libwebsockets15 libwsutil9 libxmlb1 ubuntu-fan
Use 'sudo apt autoremove' to remove them.
Suggested packages:
  git-daemon-run | git-daemon-sysvinit git-doc git-el git-email git-gui gitk
  gitweb git-cvs git-mediawiki git-svn
The following packages will be upgraded:
  git
1 upgraded, 0 newly installed, 0 to remove and 18 not upgraded.
Need to get 4,541 kB of archives.
After this operation, 4,096 B of additional disk space will be used.
Get:1 http://in.archive.ubuntu.com/ubuntu focal-updates/main amd64 git amd64 1:2.25.1-1ubuntu3.7 [4,541 kB]
Fetched 4,541 kB in 2s (2,546 kB/s)
(Reading database ... 273392 files and directories currently installed.)
Preparing to unpack .../git_1%3a2.25.1-1ubuntu3.7_amd64.deb ...
Unpacking git (1:2.25.1-1ubuntu3.7) over (1:2.25.1-1ubuntu3.6) ...
Setting up git (1:2.25.1-1ubuntu3.7) ...
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ git status
fatal: not a git repository (or any of the parent directories): .git
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ git init .
Initialized empty Git repository in /home/diot/Desktop/.git/
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	220940126021_ELP.zip
	220940126021_ELP/
	Cloud Comuputing/
	IoT_Protocol_MQTT/
	Iot Security/
	duplibashrc
	mydesktop/
	openlogic-openjdk-8u352-b08-linux-x64/
	pyhton-code/

nothing added to commit but untracked files present (use "git add" to track)
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ git config --global user.name Utkarsha8237



(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ git config --global user.email utkarshakhatavkar@gmail.com
(base) diot@diot-HP-ProDesk-600-G5-PCI-MT:~/Desktop$ git config --list
user.name=Utkarsha8237
user.email=utkarshakhatavkar@gmail.com
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true








git token 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