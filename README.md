# 📱 KLANT PAGINA

Publieke klant interface (los te deployen).

## 🚀 VERCEL DEPLOYMENT:

1. Upload deze folder naar Vercel
2. Deploy
3. **Update `index.html` regel ~94:**
   ```javascript
   const BACKEND_URL = 'https://jouw-backend.onrender.com';
   ```
4. Redeploy

## 🧪 LOKAAL TESTEN:

```bash
npx http-server . -p 3000
```

Open: http://localhost:3000

**LET OP:** Backend moet ook draaien!

## ✅ WERKT MET:

Backend op: `http://localhost:3001` (lokaal)
Backend op: `https://jouw-backend.onrender.com` (productie)

**Publiek toegankelijk!**
