# atr-mobile-detect

Wordpress plugin - Detect mobile devices.

Based on https://github.com/serbanghita/Mobile-Detect

Acivate the plugin and then you can use the condtion in functions.php or your plugin code.

Use: 

(see code examples at https://github.com/serbanghita/Mobile-Detect/wiki/Code-examples )

$mobile_detect = new ATR_Mobile_Detect; 

if ( $mobile_detect->isMobile() ) {	

  //Do something 
  
}
