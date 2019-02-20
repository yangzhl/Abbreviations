# Abbreviations
A Dictionary of Abbreviations

![screenshot.jpg](./screenshot.jpg)

## Install 

 1. Download: [Abbreviations.dictionary.zip](https://github.com/fangpeishi/Abbreviations/releases)
 2. Unzip
 3. Drag-and-drop .dictionary file into `~/Library/Dictionaries/`
 4. Restart Dictionary.app
 5. Enable Abbreviations:`Dictionary -> Preferences`
 6. Type a word 


## Build

1.  [Register as apple developer](https://developer.apple.com)
2. [Download Additional Tool for Xcode](https://developer.apple.com/downloads)
3. Move `Utilities/Dictionary Development Kit` to `/Application/Utilities/Dictionary Development Kit`  as defined `DICT_BUILD_TOOL_DIR =   "/Applications/Utilities/Dictionary Development Kit"` in `AppleDictionary/Makefile`
4.  `cd AppleDictionary` 
5. make  && make install 

## Reference

 - [public.oed.com](http://public.oed.com/how-to-use-the-oed/abbreviations/)
 - [easypacelearning.com](https://www.easypacelearning.com/english-books/english-books-for-download-pdf/category/33-3-dictionaries-to-download-in-pdf)
 - [BluntSporks/abbreviation](https://github.com/BluntSporks/abbreviation)
 - [stackexchange](https://apple.stackexchange.com/questions/80099/how-can-i-create-a-dictionary-for-mac-os-x)
