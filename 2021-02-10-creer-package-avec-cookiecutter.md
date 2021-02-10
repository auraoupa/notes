# Créer un package avec cookie cutter

Le tuto : https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html

- créer nouveau repo sur github pseudo-ARGO-floats-in-eNATL60
- créer un compte PyPI
- créer un environnemnt conda avec cookiecutter :

```
conda create --name cookiecutter
conda activate cookiecutter
conda install pip
pip install cookiecutter
```

- générer le package : cookiecutter https://github.com/audreyr/cookiecutter-pypackage.git (répondre pseudo-ARGO-floats-in-eNATL60 à project_name)
- dans le repertoire ainsi créé :

```
git init .
git add .
git commit -m "Initial skeleton."
git remote add origin git@github.com:auraoupa/pseudo-ARGO-floats-in-eNATL60
git push -u origin master
``` 

(générer la clé SSH pour l'ordi où ça se passe et la rajouter dans github)

- `pip install -r requirements_dev.txt` 

- travis : https://travis-ci.org/github/auraoupa/pseudo-ARGO-floats-in-eNATL60/settings
- docs : https://readthedocs.org/projects/pseudo-argo-floats-in-enatl60/
