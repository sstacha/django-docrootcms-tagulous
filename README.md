# django-docrootcms-tagulous
Fork of tagulous with patch for Django3

WARNING: this project fork is no longer used or needed.  The original project from radiac now supports python3 and there is no need for this copy.  It will not be kept up to date!

NOTE: this should not be used unless you are installing the docrootcms which requires django2.2 or above.  I am using this fork until the official tagulous branch is updated to remove legacy code and support django3.  

NOTE: I have since changed the requirements in version 1.0.5 and above to use the original django-tagulous instead of this forked copy.  You should do the same.  Even if you are on an older version you can uninstall this version and install the other version and change one line in your settings file to switch them out without upgrading.

Official Repo: http://radiac.net/projects/django-tagulous/

Source: https://github.com/radiac/django-tagulous


Bug Report for not supporting Django 3.x: https://github.com/radiac/django-tagulous/issues/85


Special thanks to ensignavenger for providing a patch for python3.8 django3.x here:  https://github.com/ensignavenger/tagulous

I will remove this dependency and reference the official library once this bug is resolved.
