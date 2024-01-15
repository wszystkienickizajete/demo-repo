# demo-repo
Repo poświęcone nauce Git i GitHub

## udało się skonfigurować klucze ssh

## dodawanie nowego repogit 
utworzyć katalog zgodny z nazwą planowanego repo
```
mkdir nowe
cd nowe
```
potem tworzymy nowe repo na GH i 
```
git remote add origin git@githiub.com:wszystkie/nowe 
```
potem mozna sprawdzic zdalne repo 
```
git remote -v
```

potem juz tylko
```
git push origin main
```
lub po zdefiniowaniu upstreaam, czyli miejsca do którego standardowo będę wykonywał _push_ przez flage ```-u```, jedynie
```
git push
```