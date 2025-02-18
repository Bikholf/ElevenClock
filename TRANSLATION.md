# Translate ElevenClock
Since ElevenClock is an app that wants to reach every single person in the world running Windows 11, on issue [#111](https://github.com/martinet101/ElevenClock/issues/111) it was requested to add this feature. And here we are.

## How to contribute
This is the translation program. The language packs will be .py files containing dictionaries with the translated sentences. 

## Adding a new language
To translate ElevenClock to a language:
1. Download [this](https://github.com/martinet101/ElevenClock/blob/main/elevenclock/lang/lang_sample.py) file
2. Rename so it matches the following pattern: `lang_[LANG_CODE].py`. For example, `lang_en.py` for english or `lang_ca.py` for catalan. More information about language codes can be found [Here](http://www.mathguide.de/info/tools/languagecode.html)
3. Translate every sentence in between the two `""` that you will find on every line*. Please follow the rules established in the [Rules section](#rules)
4. In order to publish changes, you can either submit a pull request (If you know how to) or, if you don't know how to, just send me the translated file at [marticlilop@gmail.com](mailto:marticlilop@gmail.com). I'll review it and publish it with the new version.
<br>
* Example file:<br>

![image](https://user-images.githubusercontent.com/53119851/138136366-6e340c02-a94b-477f-b0c2-c892f2acd044.png)


## Updating/improving a language translation
1. Go to [this](https://github.com/martinet101/ElevenClock/blob/main/elevenclock/lang/) folder and download the approppiate language file to update
3. Translate every non-translated sentence in between the two `""` that you will find on every line. The non-translated sentences will be at the top of the document. Please follow the rules established in the [Rules section](#rules)
4. In order to publish changes, you can either submit a pull request (If you know how to) or, if you don't know how to, just send me the updated file at [marticlilop@gmail.com](mailto:marticlilop@gmail.com). I'll review it and publish it with the new version.
<br>

## Rules:
 - Make sure **not to modify the original strings**. If this happened the translation wouldn't work at all.
 - Make sure to add any final stop/colon/semicolon/hyphen/etc.
 - Make sure to add the {0} symbols, since they code for variable values
 - If  you are creating a new translation, you can give you credits in a specific place (marked in the file). If you update a language file, you can also add your credits but without removing the previous one. Thi could be achieved by writing something like "Translated to Catalan by @user1 and @user2"!<br>
![image](https://user-images.githubusercontent.com/53119851/138136413-41046a99-f5e6-434f-8cea-7e85ee0b6238.png)


