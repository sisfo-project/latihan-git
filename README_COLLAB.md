# Introduction Repository ini

# Basic git & collaboration rules

### [Git Cheatsheet](https://quickref.me/git)

## Branch

- `main` untuk production
- `dev`
- `1 fitur` / `1 branch` atau `1 orang` /  `1 branch`(nanti disepakati)

## Rules

- Branch `main` dan `dev` bukan tempat eksperimen, jadi hanya untuk merge pull request dari branch
- Eksperimen di branch fitur

## How to commit to a branch

1. `git pull origin dev` dulu supaya code up to date dengan code branch `dev`
2. `git add -A` untuk semua file atau `git add app.js tes.js` misalnya untuk hanya beberapa file
3. `git commit -m "<message>"`
4. `git push origin <branch_name>`

## Merge to branch `dev`

1. Setelah commit di branch suatu branch,
2. Cek github dan pull request dari branch yang baru dicommit ke branch `dev`
3. done

## buat branch

git branch <nama_branch>
git checkout -b <nama_branch>

## pindah branch

git switch <nama_branch>
git checkout <nama_branch>
