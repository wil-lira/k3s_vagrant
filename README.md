# k3s_vagrant

# * in the folder contain this `Vagrantfile`, run `vagrant up` and wait a bit for provisioning.
#   Once done, `vagrant ssh master` into the node and start using the k8s cluster,
 
# * To clean up, logout these nodes, then run `vagrant destroy` to destroy the VMs.
#   - next time run `vagrant up` again to provision again
#   - or run `vagrant halt` to halt these VMs, and bring them back to the same state 
#     by `vagrant up` next time.


# modified from https://gist.github.com/akaron/8f71bdfe29bcdb656107bd9e15484e2c