#color-palette
####Ruby script to get the color palette of any url.
#####This is an improved version from [Alyssa color-palette][alyssa] ruby script.<br><br>
- - -
####Running script:

`ruby color.rb 'url'`

####Colors extractor:
* The color palette considers **hex**, **rgb**, **rgba** and **english word** colors (ex. red, green, blue);
* All colors are translated to hex just for consistency;
* Search all colors within **External**, **Inline** and **Embedded** stylesheets;
* Will return in **JSON**;
* This script ignores opacity.

####Available urls:
* [http://www.google.com*][google-1]
* [https://www.google.com*][google-2]
* [http://google.com*][google-3]
* [https://google.com*][google-4]
* [www.google.com][google-4]
* [google.com][google-4]

[alyssa]:https://github.com/alyssa/color-palette/ "Alyssa Color Palette Ruby Script"
[google-1]:http://www.google.com "Google Webpage"
[google-2]:https://www.google.com "Google Webpage"
[google-3]:http://google.com "Google Webpage"
[google-4]:https://google.com "Google Webpage"
