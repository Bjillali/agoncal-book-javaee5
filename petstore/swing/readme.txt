L'application Swing utilise une librairie externe qui n'est pas au format Maven. Pour compiler, il faut donc effectuer les �tapes suivantes :

1) T�l�charger la librairie � cette adresse

2) Executer la commande Maven suivante pour recopier la librairie dans le repos Maven

mvn install:install-file  -Dfile=vstm-xscore-0.5.0.jar -DgroupId=org.vstm -DartifactId=vstm-xscore -Dversion=0.5 -Dpackaging=jar -DgeneratePom=true