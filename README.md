# Scaleable Dispatcher
Scaleable dispatcher is designed to help a company scale beyond the out-of-the-box dispatcher configuration provided by Adobe. *This is provided with no warrany.*

# Notes of Interest
* These configurations support two websites at two different cache locations.
* All configurations are near identical copies of what Adobe supplies with a Dispatcher Apache module.

# Differences with OOTB dispatcher.any
* Structure has been organized into discrete files for a given section.
* All comments have been removed. This includes _most_ commented out configurations.
* Naming of configuration IDs has been cleaned up. Most follow a 0010, 0020, 0030, etc. naming convention.
* Renders use port 4503 instead of 8080.
* Cache location is set to `/apps/aem/dispatcher/cache/website-1` and `/apps/aem/dispatcher/cache/website-2`

# Dispatcher Version
* dispatcher-apache2.4-4.2.1