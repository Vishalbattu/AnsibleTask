# Ansible Collection - figment.take_home_test

This is a take home breakfix exam. But somehow it does not work as expected. Please work through the collection and identify the problems, and correct issues.

## Success Criteria

0. Install this collection
1. Run the `run-test.yml` playbook.
   1. When executing the roles within the collection the roles should converge resulting in a running NGINX server which presents the breakfix html welcome page.
   2. As you work through the collection, if you find areas to improve please add enhancements.
      1. Add a comment to the files explaining any enhancements you make.
   3. Create a new role within the collection named `system` which does the following
      1. Deploys a firewall (any firewall solution is acceptable).
      2. Opens ports 22, 80, and 443 in the firewall.
         1. All other ports should be closed.
      3. Sets the `vm.swappiness` to 10.
      4. Install the htop package.

### Notice

As you work through the breakfix please feel free to communicate with your recruiter and ask questions.
The goal here is to see you think critically and solve the problems, not create undue stress or present
you with a brain teaser. We're looking forward to seeing you succeed and are more than happy to help or
answer questions to ensure the best possible outcome.

### Time expectations

We don't expect this breakfix to last more than an hour. This is a take home test and while it goes
without saying, please use all resources available to you to help as needed.

The upstream ansible documentation is a great place to get quick information on tasks, modules, and filters.
* https://docs.ansible.com

Stack overflow us a good resource to query when looking into specific things
* https://stackoverflow.com/questions/tagged/ansible

You can ask questions to the Ansible community as well in their community channels
* https://docs.ansible.com/ansible/latest/community/communication.html
# AnsibleTask
# AnsibleTask
