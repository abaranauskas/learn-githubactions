# Learn github actions
## Section 3: GitHub Actions - basic building Blocks & Components 
### Key components
- workflow - susijusios su repositorijom ir galima ju turet kiek norima.
- job - workflow turi jobsus, ir gali ju tureti kiek tik iseina. jobsai by default runnin a paraleliai, gali but conditional
- step - jobsas turi 1 ar daugiau stepsu. executina shelcript arba actions. runina vinas po kito ir gali but conditional

runinamas skriptas per multiple lines.
```sh
run: |
    echo "First output"
    echo "Second output"
```
