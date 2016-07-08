CHANGELOG
=========

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

