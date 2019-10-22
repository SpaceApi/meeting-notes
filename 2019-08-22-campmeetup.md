# SpaceAPI ChaosCamp 2019 Meetup

# New website

 * Feel free to contribute and give us feedback
 * Written with the static site generator lektor
 * Add a wishlist / ideas section

# New Schema Version

 * How to upgrade
 * Validator that tells you what you'd need to change for the new version would be nice
 * Multi version endpoint support?
     * Would need new directory schema
     * We probably should provide the directory update first


# Issues
 * Space logo should be provided in a raster format, svg doesn't work. We should document this.
     * Check how many endpoints use SVG.


# How are you using the SpaceAPI?

 * Use MyHackerspace to check status
 * Humidity / Temperature sensor
     * How does one know if the value is current?
     * Maybe we should provide a timestamp field for sensors
 * Open / close status via IRC bot, physical buttons and website
 * Custom python server
 * Member count
 * MQTT for sensors
 * Try to use it for calender event aggregation
 * Count people with WiFi devices
 * Most people wrote their own server implementation
 * Languages
     * Rust
     * Go
     * Python
     * Ruby / NodeRed
     * PHP
 * If you are in a new town you can easily check the local spaces
     * A "hackerspaces close to you" feature would be awesome
 
# What do you expect from the SpaceAPI project?

 * Only one domain!!!
     * spaceapi.net will expire in May 2020
 * A flexible query API. Query all space names, logos, etc.
     * Needs cached data to work reasonably
 * The issue report channel should work
     * We remove the fields from the schema 0.14 since it doesn't work currently
     * Could be added back *to the directory* (just a contact email) along with multi-version support
 
# Anyone wants to join the core team?

 * Hauro: In principle yes, but has time contraints
 * metalgamer: dennis.fink@c3l.lu

# Help Needed

 * Improve the website (https://github.com/SpaceApi/website/issues)
 * JS validator frontend: Improve (https://github.com/SpaceApi/website/issues/42)
 * Python validator backend: Allow validating URLs directly (https://github.com/SpaceApi/validator/issues/32)
