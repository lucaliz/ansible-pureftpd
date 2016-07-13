CHANGELOG
=========

v1.2.0:

* 961da11: Fix value omitting
* d080a9f: Allow to explicitly set UID of the user Update README
* 588b408: Re-introduce creation of a ftp user and group
* 19ef9dd: Add ability to define an upload script

v1.1.0:

* 200e2a9: Use package name as service name
* c79391c: Really fix the test
* fffc6a0: Try to fix the build
* 4535f5a: The service name is depndent on the package that is installed
* 71944a9: Make build more verbose
* 66b9cd7: Update README to match defaults
* 8ad3f01: Add hint for missing certificate file when TLS was enabled
* f26765e: And so we should specify them in the test as well
* e280a0e: uid and gid should be always specified
* 22057bf: Only (re)create user database if users are defined
* 07f7657: Config directory is created by installing the package
* e082e26: Works without adding an FTP user and group
* 0853047: `pure-ftpd-common` will be installed as dependency anyway
* f7bfc12: Sort options and only activate those that are activated by default
* e64fc80: Make it possible to install other pure-ftpd packages

v1.0.1:

* 634cffc: Re-add meta info to make ansible-galaxy command work again

v1.0.0:

* 0b283a2: init
* c8bdf03: Rename template to show that it's Jinja2
* afc3080: Deactivate FTP test for now
* 05aa411: Always set options, because the auth ones are symlinked and have to be there
* 41ff104: Set sensible default values that are set anyway by the packaged version
* 1fd77a8: Finally fix that travis build
* d7715c5: Fix ansible-lint issues
* 8b8c0ad: Don't write files for boolean options
* 3f0f016: Disable color output of ansible-lint since this breaks the build
* 029ccbb: Fix .travis.yml again
* 6de569f: Install ansible-lint and remove notification hooks
* 3292605: Fix tests and pin Ansible version to 1.9.6 for now
* 9e83df6: We are not on Ansible Galaxy
* b484029: test
* 2995d50: Use new travis infrastructur

