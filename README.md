# Anilist List Converter
A simple Tool to Convert Anilist Lists from Manga to Anime or Anime to Manga. Written in C# & XAML.

Info: This tool only Converts Entries that have the status "Planned".

Warn: Due to Anilists API beeing a bitch & the API package beeing absolutly weird, 
</br>i had to implement my own bad ratelimit, that might not work correctly.
</br>If the Program is done, redo the whole Process again, just to make sure.

![image](https://github.com/user-attachments/assets/02baf1eb-1fae-4567-af5f-b9e605f3eee5)


## How it works
It opens a Website to authorize the App, you get an API Token back, paste that in the app in the correct field.

After that you simply select if you want to convert Anime to Manga or Manga to Anime

Now you see your list get converted, with a progress bar and everything.

Should the App not be able to find e.g. an Manga in Anime form, it will simply get deleted from the Manga List.
