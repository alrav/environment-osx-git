# environment-osx-git
Git environment tweaks for OS X

1. Copy git-completion.bash into a folder of your preference
2. Copy git-prompt.sh into a folder of your preference
3. Update your .bash_profile with the following:

	```
	source <path>/git-completion.bash
  	source <path>/git-prompt.sh
	export PS1='[\u@\h \W$(__git_ps1 " (%s)")]\$ 's
	```
4. Re-run your .bash_profile
