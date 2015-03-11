# Journey
A blog engine written in Go, compatible with Ghost themes.

## About
Please note that Journey is still in alpha and has not been tested in production.

### Easy to work with
Create or update your posts from any place and any device. Simply point your browser to yourblogurl/admin, log in and start typing away!

### Good stuff to use right away
Use Ghost themes to design your blog. There's already a great community of designers working on Ghost compatible themes. Check out the [Ghost Marketplace](http://marketplace.ghost.org) to get an idea.

### Good stuff to come
Hopefully. Planning the future of Journey, high priority goals are: Plug-in support, MySQL and PostgreSQL support, and Google App Engine support.

### Easily secure
Other blog engines require you to install Nginx or Apache just to enable Https. With Journey, simply enable Https in the configuration and start using it for development purposes. For production, simply replace the generated certificates with your own and you are ready to go.

### No dependencies
Don't worry about installing the correct version of Node.js, Python, or anything else. Just download the [latest release](https://www.github.com/kabukky/journey/releases) for your operating system and cpu architecture, then place the folder anywhere you like and run the Journey executable. Done!

### Lightweight and fast
Journey is still in an early stage of development. However, initial tests indicate that it is about 10 times faster at generating pages than Ghost running on Node.js. It eats very little of your precious memory. For example: Testing it on a MacBook, it takes about 3.5 MB of it and then happily carries on doing its job.

This slimness makes Journey an ideal candidate for setting up micro blogs or hosting it on low-end vps machines or micro computers such as the Raspberry Pi.

### Deployable anywhere
[Download the release package](https://www.github.com/kabukky/journey/releases) for Linux (AMD64, i386, ARM), Mac OS X (AMD64, i386) or Windows (AMD64, i386) and start using Journey right away. Build Journey from source to make it work on a multitude of other operating systems!

## Installing Journey
Go to the the [Releases Page](https://github.com/kabukky/journey/releases) and download the zip file corresponding to your operating system and cpu architecture.

Then extract that zip file anywhere you like. You may also rename the extracted folder into "journey" if you so desire.

Why not place it in your home folder? E.g. /home/your-user/journey/.

## Using Journey
Please refer to the [Setting up Journey](https://github.com/kabukky/journey/wiki/Setting-up-Journey) Wiki page for detailed instructions on how to set up and use Journey.

## Troubleshooting
Please refer to the [FAQ](https://github.com/kabukky/journey/wiki/FAQ) Wiki page if exeperience any trouble running Journey.

If your issue isn't discussed there, please create a [New Issue](https://github.com/kabukky/journey/issues).

## Building from source
Please refer to the [Building Journey from source](https://github.com/kabukky/journey/wiki/Building-Journey-from-source) Wiki page for instructions on how to build Journey from source.
