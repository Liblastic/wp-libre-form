## 2019-10-11
- Hotfix for wp_mail() $headers initial value. Fixes array to string conversion.

# 1.5
- Better client side JavaScript bundle, polyfills are now only loaded when required
- Much more control for emails, straight on the invidual form level
- You can now import HTML to your forms, and thus you can commit your forms to Git
- Forms no longer accept dynamic fields, unless allowed with a filter
   - Old forms continue to work as they did
- Forms now save version at which they were created, this allows us to change functionalities without breaking forms
   - If a form is created with an older version, you will be prompted to update the creation version
- Forms are now exposed to REST API
- Plugins API
  - Any plugin can register itself as a WPLF plugin
  - Lets you expose your plugin methods
  - Settings page support
