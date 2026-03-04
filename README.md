## Ansible Playbooks

### Layered (recommended)
Uses separate `tasks/` and `handlers/` folders for organisation.
```bash
ansible-playbook playbooks/site.yaml
```

### Single File
All tasks and handlers in one file, good for simpler deployments.
```bash
ansible-playbook playbooks/master.yaml
```

## Examples
Simple standalone playbooks to test and demonstrate core Ansible concepts.
```bash
ansible-playbook playbooks/examples/debug.yaml
ansible-playbook playbooks/examples/command.yaml
ansible-playbook playbooks/examples/copy.yaml
ansible-playbook playbooks/examples/multiple.yaml
ansible-playbook playbooks/examples/register.yaml
ansible-playbook playbooks/examples/when.yaml
ansible-playbook playbooks/examples/jinja.yaml
```