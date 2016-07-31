# Dokku Static

An empty container for hosting static sites with [Dokku](http://dokku.viewdocs.io/).

## Usage

1. Clone this repo
2. Make any changes to the [nginx config](./nginx.conf.sigil) as required
3. Set the `PUBLIC_HTML` env var on your dokku app to the directory with your files
4. Add the Dokku remote and push

## Snippets

You can add these to your `$app/nginx.conf.d/` directory to make additional changes to your nginx config.

### Cloudflare

Correctly sets the request IP after being proxied through Cloudflare.

## License

© Jono Warren 2016

This program is free software: you can redistribute it and/or modify it under the terms of the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0-standalone.html) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
