# pwg_cookieconsent
Simple cookie consent for Piwigo

Due to the recent GDPR / Cookie law , websites must show a banner when it uses cookies. This plugin might resolve some issues related to a missing banner/notification
Please be aware that, for as far as I can see, it is not possible to disable cookies without impacting the functional aspects of Piwigo.

On the admin configuration page you can set the size (fullscreen or banner), a custom message and a link to a specific page related to your cookie policy.


Piwigo uses two types of cookies:


| Name        | Purpose           | Data  | Server data |
| ------------- |:-------------:| -----:| -----:|
| pwg_id    | session cookie  | random 32 alfanumeric id |  pwg_device\|s:7:"desktop";<br> pwg_mobile_theme\|b:0;<br> pwg_uid\|i:1;<br><b>pwg_cconsent\|b:1;</b> | 
| pwg_remember     | auto login cookie      |   ~57 some value |

The bold value in 'Server data' is due to this plugin. 


