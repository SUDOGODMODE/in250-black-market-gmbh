# Git-Branching-Strategie: GitHub Flow

Um das Chaos im Reich der Black Market Software GmbH zu beenden, gilt ab sofort folgende Strategie:

## 1. Der Main-Branch (Das Heiligtum)
Der `main` Branch enthält immer den stabilen, produktiven Code. Direkte Commits auf `main` sind strengstens untersagt!

## 2. Feature-Branches (Die Werkstatt)
Jede neue Funktion und jeder Bugfix erhält einen eigenen Branch, der von `main` abzweigt.
* Namensschema: `feat/name-der-funktion` oder `bugfix/name-des-fehlers`

## 3. Pull Requests (Die Grenzkontrolle)
Änderungen werden ausschließlich über Pull Requests (PRs) zurück in den `main` geführt. Ein PR muss von mindestens einem anderen Mitstreiter (oder dem Lord selbst) geprüft werden.

## 4. Releases (Die Krönung)
Stabile Stände im `main` werden mit Git-Tags (z.B. v1.0) markiert, um Releases eindeutig zu kennzeichnen.
