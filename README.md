# gvtg-fork
Currently its a patch to intel graphics virtualization(XenGT-Preview-kernel) that allows simultaneous output of different VMs on different displays.
Intel's mediator kernel module does allow output only from one VM at a time. So if you want to output one VM on first video port and another VM onto different port, you can't do that.
This patch should be applied to 
