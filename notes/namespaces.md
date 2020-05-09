## Namespaces
    # Namespace
    1. Basic purpose of namespace is to differentiate kuberentes objects with a   perticular name.
    
    # ResourceQuota
    1. We can have limit over how many resources a namesapce can use with this k8s object
    2. This makes sure that a perticular namespace doesn't utilize more resources
    than it has.
    3. This can avoid over resource utilization for a perticular namesapce.

    # Some useful commands

    kubectl config set-context $(kubectl config current-context) -n dev
        This will set namespace context as dev so we no longer need to pass it in command. For other namespaces we still have to pass it.
