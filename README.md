# Al-Kautsar Mosque Website

## Project Overview

This project is a **digital information website for Masjid Al-Kautsar**, located in Cilegon, Banten, Indonesia. The website is designed to provide mosque-related information in a simple, modern, and responsive interface while making important information such as prayer schedules, preaching content, mosque gallery, location, and donation access easier to reach.

The project focuses on fundamental frontend development practices using **HTML5, CSS3, and JavaScript**, combined with responsive layouts, semantic HTML elements, accessibility attributes, animation effects, embedded multimedia, and external services such as YouTube, Google Maps, and WhatsApp.

## 🔗 [Online Version](https://al-kautsar-mosque.vercel.app)

## Project Goals

The main goals of this project are to:

- Provide a digital information platform for Masjid Al-Kautsar.
- Make mosque prayer schedules easy to access.
- Provide access to Islamic preaching and educational videos.
- Showcase photos and videos of the mosque.
- Provide mosque location information through Google Maps.
- Provide a direct donation channel through WhatsApp.
- Create a responsive website that can be accessed from desktop and mobile devices.
- Apply frontend development concepts learned through an academic project.

## Main Features

- **Mosque Landing Page**
  Introduces Masjid Al-Kautsar through a hero section containing the mosque name, welcome message, background image, and donation call-to-action.

- **Donation Button**
  Provides a direct WhatsApp link for visitors who want to make donation-related inquiries or contribute to the mosque.

- **Prayer Schedule**
  Displays prayer times for the Cilegon and surrounding area, including Subuh, Dzuhur, Ashar, Maghrib, and Isya.

- **Preaching Videos**
  Provides embedded YouTube videos containing Islamic lectures and educational content.

- **Partner Section**
  Displays partner logos representing organizations that support or collaborate with the project.

- **Mosque Gallery**
  Showcases photos of the mosque and its facilities, including the interior, exterior, courtyard, Qur'an shelves, ablution area, and surrounding areas.

- **Mosque Video Gallery**
  Provides locally stored mosque videos that visitors can play directly through HTML5 video controls.

- **Location Map**
  Integrates Google Maps to display the location of Masjid Al-Kautsar.

- **Responsive Navigation**
  Includes a mobile hamburger menu that can be opened and closed through JavaScript.

- **Scroll Animation**
  Uses the AOS (Animate On Scroll) library to add entrance animations to different website elements.

- **Responsive Layout**
  Uses CSS Grid, Flexbox, media queries, and flexible sizing to adapt the website to different screen sizes.

## Technologies Used

- **HTML5** — Structure and semantic organization of the website.
- **CSS3** — Styling, layout, animations, responsive design, and visual components.
- **JavaScript** — Mobile navigation interaction and menu state management.
- **CSS Grid** — Layout for video content, partners, and gallery sections.
- **CSS Flexbox** — Navigation, cards, footer, and responsive component layouts.
- **CSS Custom Properties** — Centralized color variables and design values.
- **AOS (Animate On Scroll)** — Scroll-based animation effects.
- **Google Fonts** — Inter and Merriweather typography.
- **YouTube Embed** — Islamic preaching video integration.
- **Google Maps Embed** — Mosque location integration.
- **WhatsApp Link** — Direct donation communication.

## Project Structure

```text
al-kautsar-mosque/
├── image/
│   ├── foto_masjid/
│   │   ├── dalam-masjid-1.jpg
│   │   ├── dalam-masjid-2.jpg
│   │   ├── dalam-masjid-3.jpg
│   │   ├── depan-masjid-1.jpg
│   │   ├── depan-masjid-2.jpg
│   │   ├── depan-masjid-3.jpg
│   │   ├── depan-masjid-4.jpg
│   │   ├── depan-masjid-5.jpg
│   │   ├── halaman-masjid.jpg
│   │   ├── rak-al-quran-masjid-1.jpg
│   │   ├── rak-al-quran-masjid-2.jpg
│   │   ├── samping-masjid.jpg
│   │   └── tempat-wudhu-masjid.jpg
│   ├── video_masjid/
│   │   ├── video_1.mp4
│   │   ├── video_2.mp4
│   │   ├── video_3.mp4
│   │   └── video_4.mp4
│   ├── icon_ashar.png
│   ├── icon_dzuhur.png
│   ├── icon_isya'.png
│   ├── icon_maghrib.png
│   ├── icon_subuh.png
│   ├── icon_video.png
│   ├── logo-partner-informatika_2025.png
│   └── logo-partner-untirta.PNG
├── js/
│   └── script.js
├── index.html
├── style.css
└── README.md
```

> The `.git/` directory may also exist in the repository but is not required for the website to run.

## Website Sections

### 1. Header and Hero Section

The header introduces the website with the **Al-Kautsar** brand name and a navigation menu containing links to:

- Donasi
- Jadwal Shalat
- Galeri
- Kontak

The hero section contains a welcome message for visitors and a donation button connected to WhatsApp. A mosque photograph is used as the background visual.

### 2. Jadwal Shalat

The prayer schedule section displays five daily prayer times:

- Subuh 
- Dzuhur 
- Ashar 
- Maghrib 
- Isya 

The current implementation presents fixed times for **Kota Cilegon dan sekitarnya**. The schedule is not connected to a real-time prayer-time API.

### 3. Video Dakwah

The website provides four embedded YouTube videos containing Islamic lectures. Each video card contains:

- Embedded YouTube player
- Video title
- Video description
- Link to view more content on the referenced YouTube channel

The video section uses a responsive grid that changes based on screen width.

### 4. Partners

The Partners section introduces organizations that collaborate or support the project. The current implementation displays partner logos including:

- Universitas Sultan Ageng Tirtayasa (UNTIRTA)
- Informatika 2025

### 5. Galeri Masjid

The gallery showcases visual documentation of Masjid Al-Kautsar, including:

- Interior of the mosque
- Front/exterior views
- Mosque courtyard
- Qur'an shelves
- Ablution facilities
- Side area of the mosque

The gallery also includes several local mosque videos using native HTML5 `<video>` elements with playback controls.

### 6. Lokasi Masjid

The website integrates Google Maps using an embedded `<iframe>` so visitors can view the mosque's location directly from the website.

### 7. Footer and Contact Information

The footer contains mosque contact information, navigation links, donation information, and copyright information. It provides an additional navigation area for the main website sections.

## JavaScript Functionality

The project uses JavaScript through `js/script.js` to control the responsive navigation menu.

The implementation provides:

- Hamburger menu toggle.
- `aria-expanded` state updates for accessibility.
- Automatic menu closing when a navigation link is selected.
- Automatic menu closing when the user clicks outside the navigation area.
- Body scroll locking while the mobile menu is open.

The JavaScript file is loaded using the `defer` attribute so that the HTML document can be parsed before the script executes.

## Animation

The project uses **AOS (Animate On Scroll)** to provide visual transitions when elements enter the viewport.

Animations are applied to elements such as:

- Navigation items
- Hero content
- Prayer schedule cards
- Video cards
- Partner logos
- Gallery images
- Map section

This gives the website a more dynamic presentation while maintaining a simple visual structure.

## Responsive Design

The website uses CSS media queries to support different device sizes.

### Desktop

On larger screens, the website uses multi-column layouts for content such as videos, partner logos, gallery items, and footer information.

### Tablet

At medium screen widths, the layout is adjusted by:

- Reducing the number of columns.
- Changing the video section to a single-column layout.
- Adjusting gallery and partner layouts.
- Reducing spacing and component sizes.

### Mobile

On smaller screens, the website provides:

- Hamburger navigation.
- Single-column content layouts.
- Flexible gallery items.
- Responsive video embeds.
- Adjusted typography and spacing.
- Mobile-friendly footer content.

## Color Scheme

The website uses CSS custom properties to maintain a consistent green-based visual identity:

```css
:root {
    --paleGreen: #f9fcf2;
    --lightGreen: #8fc332;
    --mediumGreen: #0a4b3a;
    --darkGreen: #094434;
    --gray: #5f686d;
}
```

The green palette is used to create a visual identity that is appropriate for a mosque information website while maintaining good contrast between content areas and navigation elements.

## Typography

The project uses two Google Fonts:

- **Inter** — Used primarily for body text and interface elements.
- **Merriweather** — Used for headings and prominent textual elements.

This combination provides a balance between readability and a more formal heading style.

## External Resources

The website depends on several external resources:

### AOS

The AOS library is loaded through jsDelivr:

```html
https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.min.css
https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.min.js
```

### Google Fonts

The website loads Inter and Merriweather from Google Fonts.

### YouTube

The Video Dakwah section embeds YouTube videos using `<iframe>` elements.

### Google Maps

The mosque location is displayed using a Google Maps embedded map.

### WhatsApp

The donation button uses a WhatsApp URL to provide direct communication with the mosque.

Because these services are external, an internet connection may be required for all website features to work correctly.

## How to Run

No package manager, build tool, or backend server is required for the current implementation.

### 1. Clone the Repository

```bash
git clone https://github.com/aditnurdiansyah/al-kautsar-mosque.git
```

### 2. Navigate to the Project

```bash
cd al-kautsar-mosque
```

### 3. Open the Website

Open `index.html` in a modern web browser.

For development, it is recommended to use a local development server such as **Live Server** in Visual Studio Code.

## Customization

The website can be customized by modifying:

- Mosque name and introductory text.
- Prayer schedule.
- Donation WhatsApp number and message.
- YouTube video URLs and descriptions.
- Partner logos.
- Gallery images and videos.
- Google Maps location.
- Mosque address and contact information.
- Color variables in `style.css`.
- Responsive breakpoints and layout behavior.

### Updating Prayer Times

Prayer times are currently written directly in `index.html`. To update them, edit the corresponding `<time>` elements in the prayer schedule section.

### Replacing Gallery Images

Place new images in:

```text
image/foto_masjid/
```

Then update the corresponding image paths in `index.html`.

### Replacing Mosque Videos

Place new `.mp4` files in:

```text
image/video_masjid/
```

Then update the `src` attribute of the relevant `<video>` elements.

## Current Implementation Notes

The current project is a **single-page static website**. The navigation links point to sections within `index.html` rather than separate HTML pages.

The project currently does not include:

- A backend or database.
- A content management system.
- Dynamic prayer-time API integration.
- Admin dashboard.
- User authentication.
- Database-backed donation management.
- Automated contact form processing.
- A dedicated multi-page architecture.

The donation functionality currently acts as a direct WhatsApp communication link rather than an online payment gateway.

## Accessibility Considerations

Several accessibility practices are already present, including:

- `lang="id"` on the HTML document.
- Responsive viewport metadata.
- Alternative text for images.
- Semantic elements such as `<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`, `<address>`, and `<time>`.
- `aria-controls` and `aria-expanded` for the mobile navigation.
- A screen-reader-only menu label.

Further accessibility improvements can be implemented in future iterations, particularly for color contrast, keyboard navigation, focus states, video captions, and more descriptive alternative text.

## Future Improvements

Potential improvements for future development include:

- Connecting prayer schedules to a reliable prayer-time API.
- Adding a dedicated mosque admin dashboard.
- Adding dynamic content management.
- Adding a database for mosque activities and announcements.
- Adding an online donation/payment system.
- Adding event and kajian schedules.
- Adding an Islamic calendar.
- Adding search functionality.
- Adding a news or article section.
- Improving accessibility and keyboard navigation.
- Adding SEO metadata and Open Graph tags.
- Adding a favicon and web manifest.
- Optimizing image and video file sizes.
- Adding lazy loading for media content.
- Improving Core Web Vitals and overall performance.
- Separating reusable components if the project is migrated to a modern frontend framework.

## Project Context

This website was developed as a digitalization project for **Masjid Al-Kautsar, Cilegon, Banten**, with the purpose of making mosque information more accessible through a web-based platform.

The project demonstrates practical frontend development concepts including semantic HTML, responsive CSS, JavaScript interaction, multimedia integration, external service embedding, and user-oriented information architecture.

## Conclusion

The **Al-Kautsar Mosque Website** provides a digital platform for presenting essential mosque information in an accessible and responsive format. Visitors can view prayer schedules, watch preaching content, explore mosque documentation, view the mosque location, and access a direct donation channel.

By combining HTML5, CSS3, JavaScript, responsive design, AOS animations, YouTube integration, Google Maps, and local multimedia assets, this project provides a solid foundation for developing a more complete digital mosque information system in the future.
