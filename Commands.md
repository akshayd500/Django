\#cd to correct dir path

\#then run this cmd to create virtual env

\#if you want to proceed then type Y/N

conda create --name myDjangoEnv python=3.5



\#To check total envs

conda info -envs



\#To activate env

conda activate myDjangoEnv



\#To deactive env

conda deactivate	



\#To remove env 'MyDjangoEnv' is env name and '--all' will remove all package install in venv 

conda remove --name MyDjangoEnv --all







\#Django

\#To create base project in Django where 'first\_project' is project's name

django-admin startproject first\_project



\#To create app or module under base project 

django-admin startapp first\_app  

\#or

python manage.py startapp first\_app







