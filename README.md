# WawaMelon

This is a "Reviews" Module of WawaMelon.

## Related Modules

  - https://github.com/fec3-galadriel/mike-photo-carousel
  - https://github.com/fec3-galadriel/matt-item-summary
  - https://github.com/fec3-galadriel/garrett-related-products


## Usage

Ensure you have mysql and node installed.
You can check by running the command which mysql/which node from inside the terminal.

Navigate to database, make a copy of "config.example.js" file, rename it to "config.js" and enter your username and password to gain access to MySQL RDBMS on your local machine.

Run in the different terminal windows within the root directory:
- "npm install", then "npm run reset:db", and then "npm run seed:db"
- "npm run build:dev" OR "npm run prod:dev" (depending on mode)***
- "npm run start:dev"

 *** Option 'development' sets process.env.NODE_ENV on DefinePlugin to value development. Enables NamedChunksPlugin and NamedModulesPlugin.
 Option 'production' sets process.env.NODE_ENV on DefinePlugin to value production. Enables FlagDependencyUsagePlugin, FlagIncludedChunksPlugin, ModuleConcatenationPlugin, NoEmitOnErrorsPlugin, OccurrenceOrderPlugin, SideEffectsFlagPlugin and TerserPlugin .
 You can read more at https://webpack.js.org/configuration/mode/