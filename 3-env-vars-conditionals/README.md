## Run playbook

```
ansible-playbook env-vars-conditionals-playbook.yml
```

```
ansible-playbook env-vars-conditionals-playbook.yml --ask-become-pass
```


## Run playbook with run time variables

```
ansible-playbook env-vars-conditionals-playbook.yml --extra-vars '{"new-var":"foo-world"}'
```

```
ansible-playbook env-vars-conditionals-playbook.yml --extra-vars '{"new-var":"foo-world"}' --ask-become-pass
```


## Run playbook with vars from YAML file

```
ansible-playbook env-vars-conditionals-playbook.yml --extra-vars "@prop-vars.yml"
```

```
ansible-playbook env-vars-conditionals-playbook.yml --extra-vars "@prop-vars.yml" --ask-become-pass
```
