# Aion-Classic-Chat-Filter-NA

This is a chat filter data file for the NA Aion Classic Client intended to combat in-game kinah bot spam. If any bot spam makes it through the latest version of the filter, feel free to make a pull request adding new criteria for the filter. I am not terribly active on Github, so if you make a pull request please notify me via Discord: Yon#7259.

NCWest added their own copy of this file to the Aion Classic Client; however, they have not been keeping it up-to-date. Unfortunately, they have added their copy to a pak file -- this means that editing the chat filter on the fly has become more involved.

Note that this filter is just a built-in feature of the Aion Client; it is a text file that adds keywords to filter out of chat and private shops. You can edit this file with any simple text editor such as Notepad (built-in to Windows) and add any keywords you want; however, because NCWest added their version of this filter to a pak file, we must do the same -- for ease of editing, this repository's pak file is not XOR'd and is merely a PK Zip file in disguise.

Extra Contributors:
  Harleykinz (https://github.com/harleykin),
  Vinny#1714 (Discord),
  Forthyn#8727 (Discord),
  Tsukye#2063 (Discord),
  [Q]#5051 (Discord)

Here's a preview of the filter functioning on IS-A:
![Preview](https://user-images.githubusercontent.com/59666778/123615428-25067080-d7ba-11eb-99ca-f987b735c5d0.png)

To add this to your client, download the whole repository and merge the AION_CLASSIC folder from this repository with the one for your installation of Aion Classic. More detailed installation instructions may become available at a later date.

