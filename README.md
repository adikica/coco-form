# CocoForm - WordPress Contact Form Plugin

A lightweight, secure WordPress contact form plugin with advanced spam protection including Google reCAPTCHA v3 integration.

## Features

- **Easy to Use**: Simple shortcode implementation `[coco_form id="123"]`
- **Multi-Form Support**: Create and manage multiple forms on the same page
- **Advanced Spam Protection**:
  - Google reCAPTCHA v3 integration
  - Honeypot fields
  - Time-based submission checks
  - Disallowed words filtering
  - Email provider restrictions
- **Email Notifications**:
  - Customizable admin notifications
  - Automated thank-you emails to users
  - HTML email templates
- **Form Entry Management**:
  - Store and view all form submissions
  - Detailed spam logs with reasons
  - Export capabilities
- **Responsive Design**: Works on all devices and screen sizes

## Installation

1. Upload the `coco-form` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to 'CocoForm' in your admin menu to create forms
4. Use the shortcode `[coco_form id="YOUR_FORM_ID"]` to display forms

## reCAPTCHA v3 Setup

1. Obtain your reCAPTCHA v3 Site Key and Secret Key from [Google reCAPTCHA Admin](https://www.google.com/recaptcha/admin)
2. Go to CocoForm → Settings → reCAPTCHA
3. Enter your Site Key and Secret Key
4. Optionally adjust the minimum score threshold (default: 0.5)

## Usage

Basic shortcode:
```
[coco_form id="123"]
```

With custom CSS class:
```
[coco_form id="123" class="my-custom-form"]
```

## Customization

Form fields, email templates, and CSS can be customized through the admin interface. For advanced customization, templates can be overridden in your theme directory.

## Support

For questions, feature requests, or bug reports, please open an issue on the [GitHub repository](https://github.com/yourusername/coco-form).

## License

This project is licensed under the GPL v2 or later - see the LICENSE file for details.
