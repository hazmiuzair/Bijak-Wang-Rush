# BijakWang Rush

## Upload ke GitHub Pages
1. Upload `index.html` dan folder `data` ke repository.
2. Pastikan `data/questions.json` kekal dalam folder `data`.
3. GitHub → Settings → Pages → Deploy from branch → pilih `main` / root.
4. Buka URL GitHub Pages.

## Edit bank soalan
Edit `data/questions.json`.

Format:
- category: `easy`, `medium`, atau `hard`
- question: soalan
- options: 4 jawapan
- answer: index jawapan betul (0 = A, 1 = B, 2 = C, 3 = D)

## Scoring
Betul = 100 base points + speed bonus sehingga 100 points.
Semakin cepat jawab, semakin tinggi speed bonus.
Salah = 0.
