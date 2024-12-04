# Ansible

## Usage

```bash
git clone https://github.com/linux-bangla/nextcloud-aio-user-survey.git
# git clone git@github.com:linux-bangla/user-survey.git
# python3 -m venv venv
# source venv/bin/activate
# pip install ansible ansible-lint
cp ansible.cfg.example ansible.cfg
# make modifications to ansible.cfg
mkdir -p ./.ansible/{roles,collections,logs,cache}
# ansible-galaxy collection install -r requirements.yaml
# ansible-galaxy role install -r requirements.yaml
ansible-playbook main.yml
```

## To DO

- [ ] Add `ufw` role to allow port 22, 8080, 80, 443
- [ ] Add `ansible` user
- [ ] Add `devsec.hardening` collection
- [ ] Add `hifis.unattended_upgrades` role
- [ ] Add `shibumi.systemd-conf` role
