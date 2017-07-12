# HierarchicDataHandler
Hierarchic Fixed Width Data Handler for IBM Business Process Manager Advanced

The zip file contains:

the HierarchicFixedWidthDataHandler.rar deployable Resource Adapter Archive, in order to test and use the custom data handler.
the CWYFF_FlatFile is the BPM Flat File adapter to be used in the TestMovieSource module
the websphere_default_messaging_provider is the adapter for use JMS testing in the TestMovieSource module
the TestMovieSource module is a BPM module in order to test the HierarchichFixedWidth Data Handler reading the hierarchic byte stream both
from a text file (using the Flat File Adaptr) and a JMS queue (using the webshpere default messaging provider)
