Source: https://github.com/DrDub/mtlpy_56_tuto

* Jupyter notebook
** Install
   virtualenv mtlpy56
   source mtlpy56/bin/activate
   pip install jupyter
** Deploy
   jupyter notebook --no-browser

* pywidgets
** Install
   pip install ipywidgets
** Use
   git clone https://github.com/ipython/ipywidget
   jupyter notebook --no-browser
     master/examples/notebooks

   HTML
   Button
   Text
   Box

   Interaction

** Filebrowser.py

   https://gist.githubusercontent.com/DrDub/6efba6e522302e43d055/raw/bf9fd5584363ec9f99625d6a4ffd60e70a9417b9/selectfile.py
   

* Use cases
** Poisson Magique
   commit 38e309f9e4103f0b9ddcf4ae08be08177191d0ab, notebooks folder

   See MtlPy #42

   Play-by-Post RPG email gateway

   Send email to John.Carter@poissonmagique.net -> gets intercepted -> sent to pablo.duboue@gmail.com

   Virtual email addresses for players and non-player characters

** Onboarding Use Case

   Gamemaster wants to add a new user

   pip install django-extensions

   in settings.py:
   
   INSTALLED_APPS = (
     ....
    'django_extensions'
   )
   ~/poissonmagique$ PYTHONPATH=$PWD python webapp/manage.py shell_plus --notebook --no-browser


** Multi-email Reply Use Case

   Gamemaster receives multiple emails and makes a combined response
