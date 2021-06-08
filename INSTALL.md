# Installation

```bash
    cd handson-ml
    pip3 install --user ipykernel virtualenv
    virtualenv env-handson-ml
    . ./env-handson-ml/bin/activate
    pip3 install -r requirements.txt
    python -m ipykernel install --user --name=env-handson-ml
    ./env-handson-ml/bin/jupyter-notebook
```

Puis, bien sélectionner le noyau `env-handson-ml` dans le menu sous `Noyau > Changer de noyau`
