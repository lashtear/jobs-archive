# Jobs Archive

An archiving tool for [Anomaly Jobs](http://code.google.com/p/anomalyjobs/) and [phpBB3](http://www.phpbb.com/) on [TinyMux 2.10](http://code.google.com/p/tinymux/).

This can be used for general forum posting from within the MUX, but is targetted at permanent archival of completed jobs.

Originally produced for [The Reach](http://thereachmux.org/)

## Interface
   
### Function interface
* fn_post_new_topic
* fn_post_reply
* fn_simple_post_new_topic
* fn_simple_post_reply
* fn_post_job

### Trigger interface
* trig_post_job

## Compatibility

Very little, currently, but feedback and patches are welcome.  We have this working with:

* Anomaly Jobs 6
* phpBB 3.0
* TinyMux 2.10
* MySQL 5.1 and 5.5

Source code is provided in the format of the general MUSH unformatter tools that we all use; attributes must be unwrapped before feeding into the MUX.

Loki has been investigating RHOST+SMF compatibility.  Patches are quite welcome.

## Acknowledgements

The idea of archiving AJ's completed jobs to a permanent forum was originally [Loki](http://github.com/kkragenbrink)'s (Nuitari@DLAoM), and he completed working versions on DragonLance: Age of Mortals MUSH and [Haunted Memories: Vienna by Night](http://www.haunted-memories.net/) for AJ5 and SMF.

This project is an effort to provide similar functionality for newer software on a different mush-- and make it more portable and available to others.
