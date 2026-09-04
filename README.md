# Student Project

## Description

### English

This project was created as a practical exercise for learning Git and GitHub.

During this exercise, I practiced creating a Git repository, making commits, modifying commits, creating and merging branches, using `git stash`, `git revert`, and `git reset`, working with GitHub remote repositories, cloning repositories, pushing and pulling changes, and resolving merge conflicts.

I also practiced GitHub authentication using both HTTPS with a Personal Access Token and SSH authentication.

### فارسی

این پروژه به‌عنوان یک تمرین عملی برای یادگیری Git و GitHub ایجاد شده است.

در طول این تمرین، مفاهیم مختلف Git از جمله ایجاد Repository، ایجاد Commit، مشاهده تغییرات با `git diff`، اصلاح Commit با `git commit --amend`، ایجاد و Merge کردن Branchها، استفاده از `git stash`، `git revert` و `git reset`، کار با Remote Repository در GitHub، Clone، Push، Pull و حل Merge Conflict تمرین شد.

همچنین احراز هویت GitHub با استفاده از HTTPS و Personal Access Token و همچنین SSH Authentication انجام شد.

---

## How to Run

### English

Make sure Python is installed on your system.

Run the main Python file using:

```bash
python main.py
```

### فارسی

ابتدا مطمئن شوید Python روی سیستم نصب شده است.

برای اجرای پروژه دستور زیر را اجرا کنید:

```bash
python main.py
```

---

## Git Concepts Used

### English

The following Git and GitHub concepts were practiced during this exercise:

* `git init` — Initialize a Git repository
* `git status` — Check repository status
* `git add` — Add changes to the staging area
* `git commit` — Create a commit
* `git log` — View commit history
* `git diff` — View file changes
* `git commit --amend` — Modify the latest commit
* Branch creation and switching
* Branch merging
* Merge conflict resolution
* `git stash` — Temporarily save uncommitted changes
* `git stash pop` — Restore stashed changes
* `git revert` — Create a new commit that reverses a previous commit
* `git reset --soft` — Move HEAD while preserving changes
* `git reset --hard` — Move HEAD and discard working-tree changes
* GitHub remote repositories
* `git remote`
* `git clone`
* `git fetch`
* `git pull`
* `git push`
* HTTPS authentication with Personal Access Token
* SSH key generation
* SSH authentication with GitHub

### فارسی

مفاهیم زیر در این تمرین به‌صورت عملی تمرین شدند:

* `git init` — ایجاد Git Repository
* `git status` — بررسی وضعیت Repository
* `git add` — اضافه کردن تغییرات به Staging Area
* `git commit` — ایجاد Commit
* `git log` — مشاهده تاریخچه Commitها
* `git diff` — مشاهده تغییرات فایل
* `git commit --amend` — اصلاح آخرین Commit
* ایجاد و تغییر Branch
* Merge کردن Branchها
* ایجاد و حل Merge Conflict
* `git stash` — ذخیره موقت تغییرات Commit نشده
* `git stash pop` — بازگرداندن تغییرات Stash شده
* `git revert` — برگرداندن تغییرات یک Commit با ایجاد Commit جدید
* `git reset --soft` — جابه‌جایی HEAD و حفظ تغییرات
* `git reset --hard` — جابه‌جایی HEAD و حذف تغییرات Working Directory
* کار با Remote Repository در GitHub
* `git remote`
* `git clone`
* `git fetch`
* `git pull`
* `git push`
* احراز هویت HTTPS با Personal Access Token
* ایجاد SSH Key
* احراز هویت SSH با GitHub

### Reset: Soft vs Hard

#### English

During the exercise, a temporary commit named `Temporary commit` was created and then undone using:

```bash
git reset --soft HEAD~1
```

`git reset --soft` moves `HEAD` back to the previous commit but preserves the changes from the removed commit.

In contrast:

```bash
git reset --hard HEAD~1
```

moves `HEAD` back and also resets the staging area and working directory, so the changes are discarded.

The `--soft` option was actually used during this exercise. The `--hard` option was studied for comparison and was not used on the final project history.

#### فارسی

در طول تمرین، یک Commit موقت با نام `Temporary commit` ایجاد شد و سپس با دستور زیر Undo شد:

```bash
git reset --soft HEAD~1
```

دستور `git reset --soft`، `HEAD` را به Commit قبلی برمی‌گرداند، اما تغییرات Commit حذف‌شده را حفظ می‌کند.

در مقابل:

```bash
git reset --hard HEAD~1
```

علاوه بر جابه‌جایی `HEAD`، Staging Area و Working Directory را نیز به وضعیت Commit قبلی برمی‌گرداند و تغییرات را حذف می‌کند.

در این تمرین `reset --soft` واقعاً استفاده شد و `reset --hard` فقط برای مقایسه و درک تفاوت آن بررسی شد و روی History نهایی پروژه اجرا نشد.

### Revert vs Reset

#### English

`git revert` does not remove the previous commit from history. Instead, it creates a new commit that reverses the changes.

`git reset` moves the branch pointer (`HEAD`) to another commit.

Therefore, `revert` is generally useful when changes have already been shared with a remote repository, while `reset` is commonly used for changing local history.

#### فارسی

`git revert` Commit قبلی را از History حذف نمی‌کند؛ بلکه یک Commit جدید ایجاد می‌کند که تغییرات Commit قبلی را برمی‌گرداند.

در مقابل، `git reset` اشاره‌گر Branch یعنی `HEAD` را به Commit دیگری منتقل می‌کند.

بنابراین `revert` معمولاً برای برگرداندن تغییراتی که قبلاً با دیگران Share شده‌اند مناسب‌تر است، در حالی که `reset` بیشتر برای تغییر History محلی استفاده می‌شود.

---

## Author

**Sara Oliay**

GitHub: **SaraOliay**

Repository: **student_project**

