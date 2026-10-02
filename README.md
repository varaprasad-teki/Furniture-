# VARAPRASAD FURNITURE — Website

A responsive, single-file furniture storefront built with plain **HTML, CSS and JavaScript**.

## Files

- `index.html` — complete website. HTML, CSS and JavaScript are all contained in this one file.
- `README.md` — setup and customization instructions.

## Features

- Premium responsive furniture-store design
- Mobile navigation menu
- Product categories: Beds, Dining, Dressing and Chairs
- Product search
- Product cards with images and prices
- Add to cart
- Quantity increase/decrease
- Remove from cart
- Cart total
- Cart saved in browser `localStorage`
- Buy Now via WhatsApp
- Full cart order via WhatsApp
- Contact WhatsApp button
- Responsive mobile/tablet/desktop layouts
- No framework or build process required

## How to run

1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, Firefox or another modern browser.
3. The website works as a static site; no server is required for local testing.

For hosting, upload `index.html` to your web hosting/public website folder.

## IMPORTANT: Change the WhatsApp number

Open `index.html` and find:

```js
const SHOP = {
  whatsapp: "919876543210"
};
```

Replace `919876543210` with the real WhatsApp number.

Use the international format **without** `+`, spaces or dashes.

Example for an Indian number:

```js
whatsapp: "919812345678"
```

## Change products and prices

All products are inside the `PRODUCTS` array in `index.html`.

Example:

```js
{
  id: 9,
  name: "New Wooden Sofa",
  category: "chair",
  price: 19999,
  image: "https://example.com/sofa.jpg"
}
```

Available category keys in the current design:

- `bed`
- `dining`
- `dressing`
- `chair`

If you add another category, also add it to the `LABELS` object.

## Change business information

Search the HTML for:

```text
VARAPRASAD FURNITURE
```

and replace/update the business text where needed.

You can also update:

- About Us description
- Contact information
- Delivery statement
- Footer text

## Product images

The demo products use remote Unsplash image URLs. For a real business website, replace them with your own furniture photographs or images hosted by your website.

Example:

```js
image: "images/royal-double-cot.jpg"
```

If you use local images, create an `images` folder beside `index.html` and put the image files there.

## Important production notes

This is a **front-end/static website**. It does not include:

- Online payment processing
- Customer database
- Admin dashboard
- Inventory management
- Automatic order storage on a server
- User accounts
- Delivery tracking

Orders are prepared as WhatsApp messages. You should confirm product availability, final price, delivery charges and payment terms with the customer.

## Publishing

You can host this site on any normal static hosting service. Because the project contains only one HTML file, deployment is simple.

Before publishing:

1. Replace the demo WhatsApp number.
2. Replace demo product images with your own images.
3. Verify all product names and prices.
4. Add your real address/phone number if desired.
5. Test WhatsApp links on a phone.
6. Test the cart on mobile and desktop.

## Browser support

The site is intended for modern Chrome, Edge, Firefox and Safari browsers.

## License

This starter website is provided for customization and use by VARAPRASAD FURNITURE. Replace the sample images/content with assets you have permission to use.
