# My Project

## Команды для скриншотов Git-лабораторной

### 1) Первый коммит
```bash
git status
git log --oneline
```

### 2) Ветка и merge
```bash
git branch
git merge feature
git log --oneline --graph --all
```

### 3) Отмена последнего коммита
```bash
git reset --soft HEAD~1
git status
git log --oneline
```

### 4) GitHub
- Открыть страницу репозитория;
- показать список файлов;
- показать историю коммитов;
- показать ветки.

### Вариант для PowerShell, если Git не распознается
```powershell
& "C:\Program Files\Git\bin\git.exe" status
& "C:\Program Files\Git\bin\git.exe" log --oneline
& "C:\Program Files\Git\bin\git.exe" branch
& "C:\Program Files\Git\bin\git.exe" merge feature
& "C:\Program Files\Git\bin\git.exe" reset --soft HEAD~1
& "C:\Program Files\Git\bin\git.exe" status
& "C:\Program Files\Git\bin\git.exe" log --oneline
```

### Короткий итог
После инициализации репозитория сделан первый коммит, создана ветка feature, выполнено слияние с main, затем показана отмена последнего коммита через `git reset --soft HEAD~1`.
