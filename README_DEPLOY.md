# Portfolio — Déploiement (Vercel / Netlify)

## Contenu
- `index.html` : site complet (CSS + JS intégrés)
- `netlify.toml` : headers de sécurité + cache (Netlify)
- `vercel.json` : headers de sécurité + cache (Vercel)
- `robots.txt` + `sitemap.xml`

## Important
Pense à ajouter tes assets dans le même dossier si tu les utilises :
- `photo1.png`
- `favicon.jpg`
- (optionnel) `og-image.jpg` (image pour le partage sur LinkedIn/Twitter)

## Déployer sur Netlify
1. Glisse-dépose ce dossier dans Netlify (ou connecte un repo Git)
2. Publish directory : `.` (déjà défini dans `netlify.toml`)

## Déployer sur Vercel
1. Import le dossier (ou un repo Git) dans Vercel
2. Framework : "Other"
3. Output : statique, pas de build nécessaire
