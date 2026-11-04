# Cozy Game Station

An interactive rainy-night gaming room and a small guide to six video game genres: action, horror, survival, simulation, crime and racing. Select a genre from the collection or click across the controller; drag to look around. The sound button generates rain locally after user interaction. Genre navigation remains available if WebGL fails.

## Run locally

Serve this folder over HTTP, for example `python3 -m http.server 8000`, and visit `http://localhost:8000/`. Internet access is required for the Three.js modules, fonts and the controller model. If the model cannot load, a basic built-in controller is displayed. Modern WebGL-capable browsers are recommended.

## Deployment

The repository includes a GitHub Actions workflow for GitHub Pages. In repository Settings → Pages, set the source to **GitHub Actions**. Pushes to `main` deploy automatically. The expected project address is `https://saaeiddev.github.io/Cozy-Game-Station/` once Pages has been enabled and the workflow succeeds.

## Assets

The externally hosted controller model is credited in [ASSET_ATTRIBUTION.md](ASSET_ATTRIBUTION.md). The room and fallback controller are generated at runtime using Three.js. Three.js is MIT licensed; Google Fonts provide DM Sans and Playfair Display.

## فارسی

یک اتاق بازی تعاملی در شبی بارانی با شش ژانر اکشن، ترسناک، بقا، شبیه‌سازی، جنایی و مسابقه‌ای. با انتخاب ژانرها یا کلیک روی دسته می‌توانید بازی‌های پیشنهادی را ببینید و با کشیدن صفحه زاویه دوربین را تغییر دهید. صدا با انتخاب کاربر فعال می‌شود. برای اجرای محلی، پوشه را با یک سرور HTTP اجرا کنید. بارگذاری مدل و کتابخانه به اینترنت نیاز دارد؛ در صورت بارگذاری نشدن مدل، نسخه ساده جایگزین نمایش داده می‌شود.
