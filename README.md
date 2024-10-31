# kernel_change_for_elasticsearch
Configuration DaemonSet for k8s
This DaemonSet will run on all k8s Nodes including the controlplane, it will change the kernel configuration of all k8s hosts to allow elasticsearch pod to run on all hosts.
I have tested it and it has worked super.
