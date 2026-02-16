# Invoice Generator 🚗

Simple invoice maker for car repairs and services. No fancy backend, no database, just HTML and JavaScript.
Not intended for anyone but myself to use. For a more polished invoicing app check out `10ij/BillSync`

## What it does

- Collects customer info (name, address, phone)
- Records car details (make, model, reg, etc.)
- Add as many service items as you need
- Calculates VAT automatically (each item has their own rates)
- Prints out a nice looking invoice
- Everything runs in your browser, no server needed

## How to use it

### You'll need

- a device of some sort
- a web browser installed

### Setup

1. Clone or download this repo
2. Maybe edit `invoice.html` so that the placeholder text is more personalised
3. Double-click `index.html`

## Files

```
├── index.html       # The form where you enter everything
├── invoice.html     # The pretty invoice
├── logo.webp        # Put your logo here
└── README.md        # You're reading it
```

## Making it yours

### Your logo

Replace `logo.webp` with your own. Any image format works but keep it reasonable size (like 300x100px ish).

### Your company name

Open `invoice.html` and find these lines:

```html
<h2 class="text-2xl font-bold">company</h2>
<p class="text-lg">address</p>
```

Change them to your actual company name and address.

## Tech stuff

Built with HTML, CSS (Tailwind), and vanilla JavaScript.

The form sends data as URL params to the invoice page. Invoice page reads it and displays it nicely.

## Works on

Chrome, Firefox, Safari, Edge. Possibly not Internet explorer
