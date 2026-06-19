# OPPGAVER
- Last ned git
- Fork repoet
- Klon repoet til maskinen din
- Åpne index.html i nettleser

### OPPGAVE 1
- `git reset --hard start`
- Lag en ny feature branch og gjør endringen der: endre tekstfargen til lilla
- Push den nye branchen
- Merge endringen til master, men ikke push (gjør en `git pull` i master før merging)
- Slett feature branchen, både lokalt og remote

### OPPGAVE 2
- `git checkout master​`
- `git reset --hard origin/master​`
- Merge inn branchen med navn «branch-med-mergekonflikt» til master
- Se hvordan filen blir seende ut under konflikten
- Løs konflikten og fullfør mergingen (commit, men ikke push)

### OPPGAVE 3
- `git reset --hard origin/master​`
- `git checkout branch-med-mergekonflikt​`
- Gjør en rebase med main
- Løs konflikten
- Push endringene

### OPPGAVE 4
- `git reset --hard origin/master​`
- Lag en ny feature branch og gjør endringen der: endre tekstfargen til grønn
- Push den nye branchen
- Gå inn på repoet ditt i github og lag en Pull Request
- Gjennomfør pull requesten.
