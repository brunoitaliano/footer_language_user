# Footer language switcher

This Drupal sdc_component is a very basic component that create a sticky footer with the language switcher and user user account menu

## Usage

Prerequisite:

Drupal 10
Tailwindcss Theme

Install this component in a folder with the name [your_theme]/components
Use this component in your twig template with:
{{ include ('[your_theme]:footer_language_switcher') }}

You have to set in the secondary menu region of your Drupal Theme these blocks
- Advanced Language Selector
- User Menu Account

Set theme as you like

## Additional information

Dependecies:
- drupal/advanced_language_selector
