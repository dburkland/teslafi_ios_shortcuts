README
=========

The TeslaFi shortcut(s) were created to integrate Siri with some of TeslaFi's capabilities and recorded vehicle data.

In order to import the shortcuts, you will first need to allow the import of untrusted shortcuts. This can be done by completing the steps documented [here](https://9to5mac.com/2019/08/14/allow-untrusted-shortcuts-ios-13/). You can then click on the link next to "Download Latest TeslaFi Shortcuts" to download & install the shortcut downloader. With the shortcut downloader installed please execute it via the Shortcuts app to download each of the shortcuts. Once each shortcut has been imported into the Shortcuts app on your device, you will then need to execute the "Store TeslaFi Token" shortcut. This results in the storing of the provided authentication token that is used to communicate with TeslaFi. Once that is complete you can then execute any of the other TeslaFi shortcuts.

TeslaFi iOS Shortcut Inventory:

* [Download Latest TeslaFi Shortcuts](https://www.icloud.com/shortcuts/6d25b48732e94e98bc8cab1e32ef687b)
  * Allows you to download each of the published TeslaFi shortcuts, right from the Shortcuts app.
  * NOTE: Anytime a new version of the TeslaFi shortcuts is released you simply need to re-run this shortcut and re-download the appropriate shortcut(s) replacing the existing copies.

* Store TeslaFi Token
  * Stores the provided TeslaFi.com username and authentication token

* State Of My Tesla
  * Pulls the most recently recorded vehicle information from TeslaFi and displays the vehicle's current state which includes:
    * Vehicle State
    * Battery State of Charge (%)
    * Battery Charge Limit (%)
    * Current Rated Range (Miles)
    * HVAC Status
    * Door Lock Status
    * Front Driver-Side Window Status
    * Front Passenger-Side Window Status
    * Rear Driver-Side Window Status
    * Rear Passenger-Side Window Status    
  
### FAQs

* How can I call these shortcuts using "Hey Siri"?
  * The name of the shortcut is automatically setup as the voice command phrase that Siri recognizes. 
  * If you would prefer another shortcut voice command phrase, you can simply rename the shortcut (after it is imported) in the Shortcuts app to whatever you like.
  * Once the shortcut is named appropriately, simply say "Hey Siri <Name of Shortcut>".
  * NOTE: Please keep in mind that the shortcut name must be unique from other shortcuts in your library.
* How secure are these shortcuts?
  * The authentication token that is stored by the "Store TeslaFi Token" shortcut is stored in your personal Reminders App. The token is only visible to apps or services that have access to your Reminders App meaning folks cannot publicly access this data by default. 
  * Each of the shortcuts leverage TLS when communicating with TeslaFi as if you were browsing TeslaFi.com yourself via a web browser.
  * I do not log or record any usage data, nor do I log or record any of the stored TeslaFi API tokens.

