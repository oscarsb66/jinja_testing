python3 -m venv env \
  && env/bin/python3 -m pip install --upgrade pip \
  && env/bin/pip3 install -r local_requirements/localRequirements.txt \
  && env/bin/ansible-galaxy collection install -r local_requirements/galaxyRequirements.yaml
