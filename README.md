\# Personal QR \& Social Links Hub



A professional, lightweight static web project that centralizes personal and professional

social links with scannable QR codes for fast, reliable sharing.



This project is designed with simplicity, performance, and clean presentation in mind,

making it suitable for personal branding, developer portfolios, and offline sharing.



---



\## Overview



The Personal QR \& Social Links Hub is a static landing page that displays a curated list

of social or professional links, each paired with a high-quality QR code.



All QR codes are generated locally using Python, ensuring privacy, security, and full

control over the content. The project does not rely on any backend services or external APIs.



---



\## Features



\- Centralized hub for social and professional links

\- Locally generated high-resolution QR codes

\- Clean and modern dark-themed UI

\- Fully static and portable

\- Click-to-preview QR modal view

\- Easy customization and extensibility

\- No frameworks, no backend, no trackers



---



\## Technology Stack



\- HTML5

\- CSS3 (custom styling)

\- Python 3

\- QRCode + Pillow libraries



---



\## Project Structure



```

.

├── index.html          # Main landing page

├── core/

│   └── style.css       # UI styling and theme

├── generate\_qr.py      # QR code generation script

├── qrcodes/            # Generated QR code images

└── README.md

```



---



\## Requirements



\- Python 3.8 or higher

\- pip package manager



---



\## Installation \& Setup



\### Clone the Repository



```

git clone https://github.com/<username>/<repository>.git

cd <repository>

```



---



\### Install Dependencies



```

pip install qrcode\[pil]

```



---



\### Generate QR Codes



```

python generate\_qr.py

```



All QR codes will be generated and saved inside the `qrcodes/` directory.



---



\## Running the Project



This is a fully static project.



Simply open the main file:



```

index.html

```



You can also deploy it using any static hosting service such as:

\- GitHub Pages

\- Netlify

\- Vercel

\- Local web server



---



\## Customization



\### Editing Social Links



Modify the `links` dictionary inside `generate\_qr.py`:



```

links = {

&nbsp;   "github": "https://github.com/your-username",

&nbsp;   "linkedin": "https://linkedin.com/in/your-profile",

&nbsp;   "telegram": "https://t.me/your-handle"

}

```



Re-run the script after editing to regenerate QR codes.



---



\### Styling



All UI styling is contained in:



```

core/style.css

```



You can adjust colors, layout, animations, and typography without affecting functionality.



---



\## Security \& Privacy



\- Fully static project

\- No analytics or tracking scripts

\- No external APIs

\- QR codes generated locally

\- Suitable for offline and private use



---



\## Use Cases



\- Developer portfolio landing page

\- Cybersecurity professional profile

\- Personal branding hub

\- Conference or event QR sharing

\- Offline contact page



---



\## License



This project is licensed under the MIT License.

You are free to use, modify, and distribute it for personal or commercial purposes.



---



\## Author



Mahmoud Elgazar  

Cybersecurity | Ethical Hacking | Software Engineering



