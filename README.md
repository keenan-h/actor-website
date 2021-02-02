# Actor Website
Simple, clean one page website for an actor or creative. 

## Acknowledgments & Structure
I forked the basic Python and [Flask](http://flask.pocoo.org/) structure as well as the [Frozen-Flask](https://pythonhosted.org/Frozen-Flask/) and [Netlify](https://www.netlify.com/) deployment from [engfragui](https://github.com/engfragui/personal-website). I made this for an actor friend, Ian. I have his permission to offer it as template. You can see the result at [ianedlund.com](http://ianedlund.com/). 

## Design
I designed the site using [Bootstrap](https://getbootstrap.com/) and included several different CSS style pages with different color palettes. Currently the link is set to ```Blue.css```.

## Functionality
The name, information, and links for the site are all inputed into the `actorinfo.py` file. Add a resume, headshot, and headshot cropped to a square into the static folder and replace the placeholder. Either replace the links in ```templates/home.html``` or name your files:

PDF Resume File - ```resume.pdf``` \
JPG Headshot - ```headshot.jpg``` \
JPG Headshot Cropped - ```square.jpg``` 


## Development

If you install new packages, remember to update `requirements.txt`:

```sh
pip freeze > requirements.txt
```

## Deployment

<a href="https://www.netlify.com">
  <img src="https://www.netlify.com/img/global/badges/netlify-dark.svg"/>
</a>

### Netlify settings

* Build command: `python freeze.py`
* Publish directory: `build`
