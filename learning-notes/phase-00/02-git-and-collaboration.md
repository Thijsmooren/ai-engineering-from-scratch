# Phase 0 · Les 2 — Git & samenwerken

Geschatte tijd: 30 minuten. [Open de originele les](../../phases/00-setup-and-tooling/02-git-and-collaboration/docs/en.md) voor de volledige uitleg.

## Wat je in deze les leert

- Het verschil tussen je werkmap, de staging area, lokale commits en GitHub.
- Een wijziging bekijken, toevoegen en vastleggen met `git status`, `git add` en `git commit`.
- Een aparte branch gebruiken voor een experiment.
- Begrijpen waarom grote modelbestanden niet in Git thuishoren.

## Belangrijk voor jouw werkmap

Deze cursus staat al lokaal. Je hoeft hem dus **niet opnieuw te clonen**. De remote `origin` wijst naar jouw fork (`Thijsmooren`); `upstream` wijst naar de openbare repo van de auteur. Push je oefenbranch alleen naar `origin`. De bestaande `.gitignore` sluit bestanden zoals `*.pt`, `*.pth` en `*.safetensors` al uit.

## Begin met veilige kijkopdrachten

Voer deze uit in de hoofdmap van de cursus:

```bash
git status
git remote -v
git log --oneline -5
git check-ignore -v voorbeeld.pt
```

De volledige Git-geschiedenis is inmiddels opgehaald, dus `git log` kan ook oudere commits laten zien.

## Oefening

1. Leg in je eigen woorden uit wat `git add`, `git commit` en `git push` elk doen.
2. Controleer met de opdrachten hierboven welke remote is ingesteld en of `voorbeeld.pt` genegeerd wordt.
3. Je fork bestaat al. Controleer met `git remote -v` dat `origin` naar `Thijsmooren/ai-engineering-from-scratch` wijst.
4. Maak lokaal een branch `my-progress`, voeg een klein oefenbestand toe, commit het en push die branch naar `origin`.

## Klaar wanneer

- [ ] Ik kan uitleggen waar een commit wordt opgeslagen en wat een push toevoegt.
- [ ] Ik heb mijn remotes en `.gitignore` gecontroleerd.
- [ ] Ik heb de Git-geschiedenis bekeken.
- [ ] Optioneel: ik heb een oefencommit naar mijn eigen fork gepusht.
