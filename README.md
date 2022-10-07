 ## Jinja Template Tester locally
 - Use pyenv to setup all your dependencies and ansible version so that this test can be as close to your CI as possible.
 - Change the content of of test_template.j2 to add your own.
 - Add your vars to `vars.yml`
 - run `ansible-playbook jinja_test_playbook.yml -e @vars.yml` (don't forget to run this using pyenv) this will output a file called `output_template.txt`

