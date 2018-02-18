Jenkins
=======

1. Uruchom jenkins-a:

   ::

     make build_jenkins
     make run_jenkins

2. Otwórz w przeglądarce 127.0.0.1:8080, jeśli zostaniesz poproszony o hasło dla admina, wybierz:

   ::

     cat jenkins/secrets/initialAdminPassword

3. Wybierz *Suggested plugins*.


Related
-------

- https://github.com/sheehan/job-dsl-gradle-example

1.  Fork, git clone, plik README.rst, instalowanie,
wejście do jenkins (haslo z cat jenkins/secrets/initialAdminPassword, login admin)
docker rm jenkins-wsb - remowe dockera
2. New item -> github Organisation i nazwa
3. Add jenkins (credencials), owner jako asajewicz (nazwa githuba) i save
4. Mozan sprawdzic na github (zielone ptaszki w commitach), że sprawdza 2 ścieżki - travis i jenkins
