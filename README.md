# 🚀 Cómo Subir a Vercel en 5 Minutos

## Método 1: GitHub + Vercel (Recomendado)

### Paso 1: Crear Repo GitHub
```bash
git init
git add .
git commit -m "Binance referral landing page"
git branch -M main
git remote add origin https://github.com/tu-usuario/binance-referidos.git
git push -u origin main
```

### Paso 2: Deploy en Vercel
1. Ve a [vercel.com](https://vercel.com)
2. Login con GitHub
3. "New Project" → selecciona tu repo
4. "Deploy" ✅

### Paso 3: Obtener URL
Tu web estará en:
```
https://binance-referidos-tu-usuario.vercel.app
```

## Método 2: Subdominio en Proyecto Existente

Si ya tienes un SaaS, añade esta carpeta como:
```
/tu-saaS/public/referidos/
```

Acceso: `tu-saaS.com/referidos`

## Configuración Adicional

### Custom Domain (Opcional)
1. En Vercel: "Domains" → "Add"
2. Apunta tu dominio: `referidos.tudominio.com`
3. Configura DNS según instrucciones de Vercel

### Analytics (Gratis)
1. Activa Vercel Analytics
2. Google Analytics: Añade código en index.html
3. Bitly para acortar enlaces

## Archivos Necesarios
- ✅ index.html (landing page)
- ✅ README.md (este archivo)
- ✅ vercel.json (configuración automática)

## Tiempo Total: 5-10 minutos
- GitHub: 2 minutos
- Vercel: 1 minuto  
- Configuración: 2 minutos

¡Listo para empezar a conseguir referidos! 🚀
