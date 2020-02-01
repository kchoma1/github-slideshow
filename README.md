basic Django installation process

1. Stworz katalog
**mkdir my_django_project
cd my_django_project**

2. Utworzednie virtaul environment
**python3 -m venv django_venv
cd django_venv
cd bin
source activate**

3. Upewniamy sie ze pip jest up to date
**python3 -m pip install --upgrade pip

4. Instalujemy Django
**pip install Django
python3 -m django --version

5. Konfiguracja pliku
w pliku settings.py dodajemy linijke
**ALLOWED_HOSTS = ['\*\']**

Tym sposobem mamy zainstalowe Django :)
