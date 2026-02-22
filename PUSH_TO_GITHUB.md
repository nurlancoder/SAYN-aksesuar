# GitHub-a push etmək

Layihə artıq commit edilib, remote əlavə olunub. Push üçün **terminalda** bu əmri işə salın:

## 1. Terminal açın

- **Cursor:** `Ctrl+`` (backtick) və ya View → Terminal
- Və ya **PowerShell** / **Git Bash** açın

## 2. Layihə qovluğuna keçin

```powershell
cd "C:\Users\User\Desktop\SAYN Aksusuar"
```

## 3. Push edin

```powershell
git push -u origin main
```

## 4. GitHub girişi (ilk dəfə soruşsa)

- **Username:** `nurlancoder`
- **Password:** GitHub **Personal Access Token** (adi şifrə işləmir)
  - Token yaratmaq: https://github.com/settings/tokens → Generate new token (classic) → `repo` qutusunu seçin → Generate → tokenı kopyalayıb "Password" kimi yapışdırın

## SSH ilə (alternativ)

Əgər SSH açarınız varsa, remote-u dəyişin və push edin:

```powershell
git remote set-url origin git@github.com:nurlancoder/SAYN-aksesuar.git
git push -u origin main
```

---

Push uğurla bitəndə sayt burada görünəcək:  
https://github.com/nurlancoder/SAYN-aksesuar
