ENV_PYTHON = python -W ignore::DeprecationWarning -W ignore::RuntimeWarning

requirements:
	@echo "Installing requirements"
	@pip install --exists-action=s -r ../requirements/requirements-dev.txt

run:
	$(ENV_PYTHON) manage.py runserver

runpub:
	$(ENV_PYTHON) manage.py runserver 0.0.0.0:8000
