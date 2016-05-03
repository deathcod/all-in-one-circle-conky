# all-in-one-circle-conky
this is a widget which is based on conky which has the same look as LG G3 style.

This is the preview of the widget:  
![input](https://github.com/deathcod/all-in-one-circle-conky/blob/master/Screenshot%20from%202016-05-04%2003:20:55.png)

# installation

from software center install conky-all  
then install  
``` 
sudo apt-add-repository ppa:teejee2008/ppa  
sudo apt-get update && sudo apt-get install conky-manager
```

after having done you can now enjoy this widget.  
open conky-manager through terminal  
``` $conky-manager ```  
open zip file through conky-manager.  
and its ready to use.But few this to do before use change the key and city name,go to the website ``` http://openweathermap.org/ ``` get the key and replace, now you will be able to see the temperature and weather condition.

In the earlier version on All-in-one conky there was slight issue as the window flickering as well the temperature not working ,the issues have been fixed here. I have added a new feature as you can now see the weather condition as well which was absent in the previous version.

# features changed

* effective xml data extraction by improving the regular expression.  
* expression involving decimal substraction.
* change of the window size and positions of underling objects and also managed the flickering issue.
* changed the earlier used yahoo api to openweathermap api as yahoo api had been reconfigured and didnot support the direct access to api.
* included the icons as per the openweathermap site.

