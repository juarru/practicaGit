11- git reset --hard HEAD~1<br />
12- git reset --hard HEAD@{1}. Porque me llevaba directamente a la posición en el paso anterior.<br />
13- git merge master. No ha dado ningún conflicto porque estaba en el mismo sitio.<br />
19- Si, por tener el mismo archivo en dos ramas diferentes con versiones diferentes en diferentes líneas.<br />
21- No causó ningún conflicto, estaba en la misma línea e hizo un merge fast forward<br />
25- git log --graph<br />
26- No, porque no se encuentran en la misma línea.<br />
27- git reflog para conocer a que commit tengo que ir (tres antes) y git reset HEAD <identificador_commit> para deshacer el merge<br />
28- git checkout --git-nuestro.md<br />
29- git branch -D title<br />
30- git reflog para localizar el identificador donde se hizo el merge y volver allí. Después reset --hard a ese identificador<br />
32- git reset --hard al identificador del primer commit.<br />
33- git reflog para buscar el id del commit donde se añadió el título y git reset --hard a ese identificador.<br />
