<div align="center">
  
# Azure Mask GPS CW (Az Mask GPS CW)

</div>

This is a fork of the excellent azure-mask project by Brian Clark (https://github.com/clarkio/azure-mask)
Originally forked from 1.10.0 on Tue Dec 6th 2022 - Please ensure you check upstream for any known vunerabilities etc.

From Brian's original README:

    This is a browser extension that will do its best to find and mask GUIDs (such as Subscription IDs), email addresses, keys, and connection strings with a blur. The intention of the extension is to make it easier to do screen recordings without revealing sensitive, personal, account information that may show up on screen. It will only run and apply against Azure portal URLs ([see manifest.json for specifics](https://github.com/clarkio/azure-mask/blob/master/src/manifest.json#L32)). It's available in Chromium based browsers and Firefox.

    ## Features

        * Blurs GUIDs (such as Subscription IDs)
        * Blurs your account email
        * Hides the "Report a Bug" button (if found)
        * Toggle the mask on/off and store this state
        * Apply the mask (if enabled) after Document Object Model (DOM) mutations

This fork is intended for use by the US GPS Code-With team at Microsoft while recording content for publication.
It remains under MIT license and we may commit improvements upstream, at this time though that is not planned as our changes are likely to be domain specific.

Currently we add the following functionality for the team:

    ## GPS US Code-With specific features

        * Updated/Migrated to the v3 SDK for Chrome Extensions (tested in Edge/Chrome) - https://developer.chrome.com/docs/extensions/mv3/mv3-migration/
        * TBA
 
