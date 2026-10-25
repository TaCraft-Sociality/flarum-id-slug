# ID Slug for Flarum

Use the discussion ID as the slug in discussion URLs instead of the title-based slug.

## Features

- Discussion URLs use the numeric ID (e.g. `/d/123`) instead of the title slug
- Old title-style URLs with an ID prefix (e.g. `/d/123-some-title`) still resolve correctly
- Simple and lightweight, with no additional configuration required

## Installation

```bash
composer require tacraft-sociality/flarum-id-slug
php flarum cache:clear
```
