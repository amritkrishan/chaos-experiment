# Chaos Experiment
This Demo project is used for running Chaos Experiment

# REST endpoints
/actuator/chaosmonkey - Chaos Monkey for Spring Boot
/employee/all - Return employees from DB (H2)
Chaos Experiments
Set virtual environment in python and install chaostoolkit-spring

```sh
python3 -m venv ~/.venvs/chaostk
source  ~/.venvs/chaostk/bin/activate
pip install chaostoolkit
pip install chaostoolkit-spring
Run the experiment: chaos run experiments.json
```
