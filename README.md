knife-wsfusion demo
===================

To try out [knife-wsfusion](https://github.com/chipx86/knife-wsfusion) with
this demo repository, first follow the installation instructions listed on
the knife-wsfusion page.

Once that's done, set up a 64-bit Ubuntu 12.04 VM, and configure a
```vmware``` user with sudo permissions. Set the password for that user to
```vmware123```.

This setup assumes that VM will live in
```$HOME/Documents/Virtual Machines.localized/Chef Ubuntu Template.vmwarevm```.
You'll probably want to edit ```run-demo.sh``` and change that path.

Then, run:

    $ ./run-demo.sh

Cross your fingers.
