Some Plugins for vim and config file vimrc

	include:  

		ctags, cscope, nerdtree, imnicppcomplete 
                winmanager, taglist, supertap, syntax, minibufexpl

        config file:
        	vimrc 
        	path: /etc/vim/

		config plugin directory:
			plugin
			path: ~/.vim/

        CSDN Blog Refrence：
        	http://www.cnblogs.com/zhaoyl/p/4078164.html
        	http://blog.csdn.net/namecyf/article/details/7787479


Usage

	Ctags:
	   1. Init ctags,at the root-directory 
	           $ctaps -R --c++-kinds=+p--fields=+ias --extra=+q

	   2. Common command:
				:ts			 tags list
				:tp			 tags preview
				:tn			 tags next
				.Ctrl + ]	 goto definition
				.Ctrl + T    goto back
				:ta x        goto label x
				:ts x		 list the definition of label x
				:tj x		 list the definition of label x and jump to the first location.
	   3. If the directory run vim not contain the tags file, 
				:set tags=tags; 
				:set tags+=your path 


	Taglist:
		1. Open and Close
				:TlistToggle


	Cscope:
		1. Init Cscope, at the root-directory
				$cscope -Rbq -f path/projectname.out 
				:cs add path/projectname.out

		2. Common command:
				.Ctrl-\ s	look up all the label the curson at
				.Ctrl-\ c	look up all the function who Call the function the curson at
	




																				ZHAOCHAO 
																					2016-6-3



