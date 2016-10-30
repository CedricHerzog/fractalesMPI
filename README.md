# fractalesMPI

##Pour lancer le calcul basique:
```
  mpicc mandel-basic-mpi.c
  mpirun -np [nombre de coeur] a.out
```
##Pour lancer le calcul ligne par ligne:
```
  mpicc mandel-basic-mpi-ligne.c
  mpirun -np [nombre de coeur] a.out
  ```

##Pour lancer le calcul plusieurs lignes par plusieurs lignes:
```
  mpicc mandel-basic-mpi-multi-ligne.c
  mpirun -np [nombre de coeur] a.out [nombre de ligne à calculer]
  ```
