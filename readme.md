# DC WiFi Social

<img src="https://travis-ci.org/benbalter/dc-wifi-social.png">


### A collaborative list of DC bars and restaurants that don't have televisions (or the TV is at least very easy to ignore).

*Because coding together is better than coding alone (TM)*

### [The Map](bars.geojson)

## License

CC-BY-SA

## How to contribute

1. Fork the project
2. Create a new branch
3. Add or edit a location by editing and following the format in `bars.geojson` (hint, it's geoJSON)
4. Submit a pull request

## Validating the geoJSON

When you submit a pull request, it will automatically check to ensure your geoJSON is valid.

If you'd like to check yourself, you can run `./script/cibuild` locally, or pasting the contents of `bars.geojson` into http://geojsonlint.com.

## How to find the lat/long of a location

Pop it into http://geocoder.us/. Boom.

## Why?

Because I have ADHD.
