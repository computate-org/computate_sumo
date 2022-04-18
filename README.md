
# Install the sumo ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_sumo

# Clone the sumo ansible role. 
git clone git@github.com:computate-org/computate_sumo.git ~/.ansible/roles/computate.computate_sumo
cd ~/.ansible/roles/computate.computate_sumo
```

# Run the sumo ansible playbook to install sumo locally. 

```bash
ansible-playbook install.yml
```

