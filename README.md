Accent Homes


Luxury short-let booking platform for premium apartment rentals in Asaba, Nigeria.



A full-stack booking platform for Accent Homes Ltd, featuring a public-facing site for apartment discovery and booking, and a private admin portal for managing reservations and guest data.

Live Site: accenthomesltd.com


Stack


Frontend: HTML, CSS, Vanilla JavaScript
Backend/Database: Firebase Firestore + Firebase Auth
Media: Cloudinary (image hosting and optimization)
Payments: Paystack (live key deployment with Secret Manager)
Deployment: Cloudflare Pages
Email: Firebase-triggered notifications



Features


Public apartment listing pages with image carousels
Real-time booking flow with availability checking
Paystack payment integration (live mode)
Firebase Auth for admin access
Admin portal — view, manage, and update bookings
Apartment descriptions for all units (Mercy Milan, Hope London, Goodness Tokyo, Grace Paris)
Mobile-responsive design
DKIM email verification configured on subdomain



Apartments

UnitThemeMercy MilanItalian minimalismHope LondonBritish contemporaryGoodness TokyoJapanese zenGrace ParisFrench elegance


Key Technical Decisions


Cloudflare Pages: Edge deployment for fast load times across Nigeria without expensive server infrastructure.
Paystack over Stripe: Nigeria-native payment processor with NGN support and local bank transfer options.
Cloudinary: Handles image optimization and responsive delivery without manual compression workflows.



Known Issues Resolved


DKIM verification failure caused by subdomain NS delegation shadowing — resolved by adjusting DNS record scope
Error 522 on www subdomain — resolved by adding www to Cloudflare Pages custom domains list
Paystack modal debugging — resolved callback handling for successful and failed payment states



Status

Live and operational. Post-launch phase with ongoing technical maintenance and Instagram content management.


Client

Mr. Joe — Accent Homes Ltd, Asaba, Nigeria.


Built By

Capricorn Hub — design-forward web platforms for modern brands.
Content

## Project Structure
/
├── public/          # Frontend pages
├── admin/           # Admin portal
├── js/              # Firebase, Paystack, UI logic
├── css/             # Stylesheets
└── .env.example     # Environment variable template

## Environment Variables
FIREBASE_API_KEY=
FIREBASE_PROJECT_ID=
CLOUDINARY_CLOUD_NAME=
PAYSTACK_PUBLIC_KEY=
