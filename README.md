# Basketboll Sverige

En responsiv webbplats som presenterar svensk basketboll, elitlag och kommande tävlingar. Projektet är byggt med HTML och CSS och används i utbildningssyfte.

## 🏀 Syfte

Webbplatsen är uppdelad i tre sidor:

- **index.html** – Startsida med introduktion, lagbilder och matcher
- **om_basket.html** – Fakta om basketboll och grundläggande regler
- **lag.html** – Svenska elitlag och kommande tävlingar

## 🧱 Struktur

Projektmappar och filer:


## 🎨 Teknik

- **HTML5** – Semantisk struktur med `header`, `nav`, `main`, `section`, `article`, `footer`
- **CSS3** – Flexbox, grid, media queries, box-shadow, färgteman
- **Responsiv design** – Anpassar sig för både mobil och desktop
- **Bildhantering** – Bilder visas sida vid sida med `flexbox` och `object-fit`

## 📱 Mobilanpassning

Vid skärmbredd under 768px:

- Navigationsmenyn staplas vertikalt
- Lagkort visas under varandra
- Padding minskas för bättre läsbarhet

## 🖼️ Bakgrundsbild (valfritt)

För att använda en bakgrundsbild i `header`, lägg till i CSS:

```css
header {
  background-image: url("images/header-bg.jpg");
  background-size: cover;
  background-position: center;
}
