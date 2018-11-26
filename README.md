# Deleted Video Finder for YouTube™

A simple chrome extension that tries to find old versions of deleted or private YouTube videos.

## How It Works
* When right clicking a video link on youtube, a new context item will appear on the context menu called "Find Video" 
* Once clicked, the extension will use the Wayback Machine API to see if there is an old version of that video available.
* If a Wayback link exists, two new tabs will open. One with the video loaded into the Wayback machine, another with a
google search of that video's url. 

## Future Features
* Settings page that lets you choose between a new wayback tab, new google search tab, or both
* Popup menu that allows you to enter a youtube link instead of having to right click it

## Built With

* [Wayback Machine API](https://archive.org/help/wayback_api.php) - 
* [jQuery](https://jquery.com/download/) 


## Author

* **Al Sharairi** - [alshar](https://github.com/alshar)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspiration - [Reddit Thread](https://www.reddit.com/r/starterpacks/comments/9yi9lq/youtube_favorites_playlist/ea1znja/)
