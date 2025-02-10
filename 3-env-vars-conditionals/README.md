## Run playbook

```
ansible-playbook env-vars-conditionals-playbook.yml
```

## Run playbook with run time variables

```
ansible-playbook -env-vars-conditionals-playbook.yml --extra-vars '{"new-var":"foo-world"}' 
```

## Run playbook with vars from YAML file

```
ansible-playbook env-vars-conditionals-playbook.yml --extra-vars "@prop-vars.yml"
```