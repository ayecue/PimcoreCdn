# PimcoreCdn

> Compatible with Pimcore 3.x.x

Easy CDN Plugin for Pimcore. Before it's useful you need to install it and configurate these website properties:

* cdnDomain - Path to your CDN
* cdnFolders - Which of your folders should be in the CDN. For example you got a file in a folder named scripts. Then just add the string "scripts" to this property. If you got multiple folders seperate them with a comma. ("scripts,otherFolder")
* cdnExtensions - Which file extensions should be in the CDN. For example you just want to have images in your cdn then add this string: "png,jpeg,gif"