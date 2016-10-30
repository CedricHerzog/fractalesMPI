# fractalesMPI

##Pour lancer le calcule basique:
```
  mpicc mandel-basic-mpi.c
  mpirun -np [nombre de coeur] a.out
```
##Pour lancer le calcule ligne par ligne:
```
  mpicc mandel-basic-mpi-ligne.c
  mpirun -np [nombre de coeur] a.out
  ```

##Pour lancer le calcule plusieurs lignes par plusieurs lignes:
```
  mpicc mandel-basic-mpi-multi-ligne.c
  mpirun -np [nombre de coeur] a.out [nombre de ligne à calculer]
  ```
