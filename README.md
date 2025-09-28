# 🌟 XAU Layering Simulator

[![Deploy with Vercel](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel)](https://xau-layering.vercel.app)
[![Made with TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Made with Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)

🚀 **XAU Layering Simulator** adalah web interaktif untuk mensimulasikan strategi layering *buy-only* pada **XAUUSD (Gold)**.  
Aplikasi ini membantu trader memahami **drawdown**, **pembagian modal tiap tahap**, dan **potensi stop-out** saat harga turun ekstrem.

<img src="./assets/Screenshot 2025-09-28 at 08.46.51.png" width="400"> 
<sub>Contoh tampilan</sub>

---

## ✨ Fitur Utama
- 📝 **Form input sederhana** 
- 📊 **Pembagian Modal otomatis**
- 📈 **Summary interaktif** → menampilkan layer STOP, floating loss, equity minimum, max drawdown, dll.
- 🔢 **Tabel Layer** → rincian per layer (harga, floating loss, equity).
- 📉 **Grafik Equity vs Harga** → memvisualisasikan penurunan modal secara real-time.
- 🎨 **UI bersih & responsif** dengan TailwindCSS + Chart.js.

---

## 🛠️ Cara Pakai
1. Buka [🌐 Demo di Vercel](https://xau-layering.vercel.app).
2. Isi parameter:
   - **Modal (USC)** → contoh: `70000`
   - **Lot per Layer** → contoh: `0.03`
   - **Harga Entry** → contoh: `3700`
   - **Spacing Awal** → contoh: `2`
3. Klik **Run Simulation** → hasil muncul:
   - Summary
   - Tabel Layer
   - Grafik Equity
