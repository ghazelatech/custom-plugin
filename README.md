# Ansible plugins example

This is a repository of simple examples of how to write plugins for
[Ansible](https://docs.ansible.com/ansible/latest/index.html).
The plugin don't try to be useful or to be used, but rather show
the bare minimum for have a functional [Ansible plugin](https://docs.ansible.com/ansible/latest/dev_guide/developing_plugins.html).

## Considerations

The plugin's code is written in Python. This is a must.

We have two playbooks inside the directory. One without using the plugin and one using it. 
This way it'll be easier to see how the plugin works and what _problem_ it try to solve.