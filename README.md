

Run ansible-galaxy as:

`ansible-galaxy install -r requirements.yml --ignore-errors --roles-path roles --force`

Full File listing:
```
roles/
- galaxy_test.yml
- galaxy_test_role.yml
tasks/
- create_galaxy_test.yml
- galaxy.yml
- galaxy_test.yml
- galaxy_test_deploy.yml
- galaxytest.yml
- testgalaxy_test.yml
vars/
- galaxy.yml
- galaxy_test.yml
- main_galaxy_test.yml
```


Actual result will be several files missing the string `galaxy_test` from the file names.
