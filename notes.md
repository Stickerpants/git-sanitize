Install vector via curl | bash
	Still need to figure out how to grab filepaths and stuff

Manage primarily by a config. Have options. Here map keypairs for target data to sanitize.
	What happens if there's a conflict between the passwords and text in the source code?
	Should it require a file specifier? Say "this password in this file..."
	Maybe have option where data is always kept only in the config?
	Have a "warn only" mode where only a warning is given pre-commit?
	
Use pre-commit and post-receive to do the thing.

Config should be kept in gitignore. But then how to version control it?
	What about maybe encrpyting it and then pushing out?

Probably writing in bash to avoid extra deps. PERL?
