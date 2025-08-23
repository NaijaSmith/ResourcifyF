# Resourcify Frontend

Resourcify is a community platform for efficient resource sharing and impact. This frontend provides a beautiful and user-friendly interface for users to access, request, track, and manage resources, while connecting communities, organizations, and individuals.

## Features

- **Modern UI**: Responsive and visually appealing interface using HTML5, CSS3, and JavaScript.
- **Resource Request**: Users can request resources by selecting type, location, and quantity.
- **Real-Time Updates**: Supports real-time chat and notifications using WebSocket (STOMP/SockJS).
- **Resource Listings**: Browse available items and detailed information.
- **Navigation**: Multi-page navigation: Home, Services, About, Terms, etc.
- **Interactive Map**: Integration with Leaflet.js for location selection and visualization.
- **Role-Based Views**: (If supported by backend) Users, donors, and volunteers can access tailored dashboards.
- **Accessibility**: Responsive design for desktop and mobile devices.

## Tech Stack

- **HTML5 & CSS3**: Semantic markup and modern styling.
- **JavaScript**: For interactivity and API communication.
- **WebSocket (STOMP/SockJS)**: For real-time chat and live updates.
- **Leaflet.js**: For map visualization.
- **Boxicons**: For iconography.
- **Google Fonts (Poppins)**: For modern typography.
- **Static Assets**: Images and favicons.

## Folder Structure

```
.
├── About.html
├── About.css
├── Home.html
├── Home.css
├── Services.html
├── Services.css
├── Terms.html
├── Terms.css
├── style.css
├── dashboard.css
├── favicon_io/
├── Pics/
└── (other static files)
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- Backend server (see [Resourcify Backend](https://github.com/NaijaSmith/ResourcifyB) for API and WebSocket endpoints)

### Running Locally

1. **Clone this repository:**
    ```bash
    git clone https://github.com/NaijaSmith/ResourcifyF.git
    cd ResourcifyF
    ```

2. **Open `Home.html` in your browser:**
    - Double-click `Home.html` or use a live server extension (e.g., VSCode Live Server) for best experience.

3. **Connect to Backend:**
    - Ensure the backend server is running and accessible. Update any endpoint URLs in the JavaScript if needed.

4. **Configuration:**
    - If API URLs or WebSocket endpoints need to be customized, edit the corresponding JavaScript in the HTML files.

### Deployment

To deploy as a static site:
- Host the contents of this repository on GitHub Pages, Netlify, Vercel, or any static file hosting service.

## Customization

- **Branding:** Replace the `Pics/` and `favicon_io/` assets with your own.
- **Styling:** Modify the CSS files to match your theme.
- **Integrations:** Connect with any REST or WebSocket backend by adjusting the endpoints in JavaScript.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

[MIT](LICENSE)

## Sponsorship

If you'd like to support the development of Resourcify, consider sponsoring or buying me a coffee:

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-@NaijaSmith-ea4aaa?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/NaijaSmith)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy_Me_a_Coffee-naijasmith-yellow?logo=buy-me-a-coffee&style=for-the-badge)](https://www.buymeacoffee.com/naijasmith)

## Acknowledgements

- [Leaflet.js](https://leafletjs.com/) for mapping.
- [Boxicons](https://boxicons.com/) for icons.
- [Poppins Font](https://fonts.google.com/specimen/Poppins).
- Unsplash/Pexels for images.

---

> **Resourcify** – Bridging communities through smarter resource sharing.