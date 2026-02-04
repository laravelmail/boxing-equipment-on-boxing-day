# Boxing Equipment On Boxing Day

Professional email template for promoting Boxing Day sales in the retail and leisure & sport industries.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Retail, Leisure & Sport
- **Message Type:** Marketing
- **Tags:** promotion, discount, boxing day sale

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/boxing-equipment-on-boxing-day.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/boxing-equipment-on-boxing-day/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.boxing-equipment-on-boxing-day',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
