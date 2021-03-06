# Client Locations Plugin for OctoberCMS

**Background**  
This plugin extends the Albright Client plugin and replaces the single address input with multiple location support. When this plugin is installed, multiple locations can be attached to a single client model and each client can have a default location set.

**Requirements**
- AlbrightLabs.Client

**Features**  
- Remove single location input from client
- Adds multiple location input and attachment to client
- Allows each client to have a default location
- Each location can have a title, street line 1, street line 2, city, state, zip, and default checkbox
- When plugin is installed, it will create new default location for each client with a location

**Install**  
There are two options:
1. `git clone https://github.com/albrightlabs/client-locations-plugin.git plugins/albrightlabs/clientlocations` and run `php artisan october:up` or
2. `git submodule add -b master https://github.com/albrightlabs/client-locations-plugin.git plugins/albrightlabs/clientlocations` and run `php artisan october:up`

**Contribute**  
Feel free to fork and contribute to this plugin! Please email support@albrightlabs.com with any and all questions.
