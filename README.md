# ansible-Learning

Forked from [Alennelson/ansible-](https://github.com/Alennelson/ansible-), this repository contains Ansible practice playbooks, experiment directories, and sample deployment files.

## Contents

### Playbooks & Files
- `alen.yml` — Practice playbook
- `create.yml` — Resource or file creation playbook
- `loop.yml` — Ansible loop experiments
- `syennfo.yml` — System information playbook
- `website.yml` & `website.html` — Static web content and deployment playbook
- `git` — Git-related practice file
- `.gitignore` — Ignored files configuration

### Directories
- `ironman/`
- `kar-test/`
- `test/`
- `test1/`
- `vision/`

## Usage

Run a playbook against your inventory with `ansible-playbook`:

```bash
ansible-playbook -i <inventory_file> <playbook.yml>
