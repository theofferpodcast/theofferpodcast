#The Offer Podcast Website Documentation

##Guests
How do I add a new guest?

1. add their name in the "Guests" secction in _config.yml
2. add the name of their picture un the same section
3. Add a title
4. Paste a picture of the guest in the "img/team" folder. Don't forget to name the image the same as it was in the guest info

---------------------------------------------------------

##Episodes
How do I add a new episode?
> Episodes are displayed on the website by creating a file in the /portfolio/ folder. if the file is created correctly, it will display on the website automatically

1. Paste the image corresponding to the episode in img/portfolio
    1.a paste a picture with the name of the episode, no spaces (images must be .png) e.g: thepilot.png
    1.b paste another picture with the same name ending in "-thumbnail" e.g: thepilot-thumbnail.png
2. download the template file from [LINK TO DRIVE]
3. name the file following the convention YYYY-MM-DD-episode-number.markdown e.g: 2019-12-23-episode-8.markdown
4. in the file you've just renamed, just follow the instructions from each field. Instructions are marked by starting with a "#". Don't worry, the texto following the "#" will not show up, it's just to explain what each field does. all you need to edit is what comes after ":"

Common problems:
* Pictures now showing? make sure the images are .png and not .jpg
* When I click on an episode, another shows up? make sure the modal-id: isn't the same as another episode
