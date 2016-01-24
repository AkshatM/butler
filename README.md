# butler

This is a Chrome extension that attempts to let you
easily put "This is an answer, not a comment" text as a
reply to a comment. For instructions on how to install and use,
see 'doc/howto.html'.

## Introduction<

The _Quora Butler_ is a litle Chrome extension that gives you a 1-click way to send a reply to a comment. You can customize what that reply is, the default is "Thanks for the input. Did you want this to be an answer, instead of a comment?".
    
## Installation (For Devevelopment Purposes)

Installation is clunky right now, sorry about that. Do these steps:

- **Download the files**. Go to `https://github.com/kfishkin/butler`, and click the button that says 'Download ZIP'. Extract that zip file somewhere, note that it gave you a directory called `butler-master`.

- **Install the extension**. In Chrome (this is Chrome only),
    go to `chrome://extensions</code>`. Make sure you click the box that says 'Developer mode'.
    
    ![Developer mode](https://github.com/kfishkin/butler/blob/master/doc/pix/developer_mode.png)
- Now click the button that says `Load unpacked extension...`. Navigate to the `butler-master` directory you just made, and select it. You should now see info about the butler appearing on that page:
    ![Butler extension loaded](https://github.com/kfishkin/butler/blob/master/doc/pix/butler_extension_loaded.png)
    
- And you should also see the butler icon appear in your chrome toolbar:
    ![Butler extension loaded](https://github.com/kfishkin/butler/blob/master/doc/pix/butler_icon_toolbar.png)

## Use

Once the extension has been installed, using it is, well, still kinda clunky, but here you go:

- **Navigate to some Quora page with comments that you might want to reply to**. This could be some answer of yours with lots of comments, some notification about some comment added to an answer of yours, whatever. For example, here's one that Akshat Mahajan did for me to help in testing this plugin, you can see it at [this page](https://www.quora.com/What-are-the-most-funny-and-bizarre-road-signs-worth-slowing-down-for/answer/Ken-Fishkin). I've also added some other bogus comments so you can see how this work when there's more than one comment on an answer:

    ![Comment before](https://github.com/kfishkin/butler/blob/master/doc/pix/comments_before.png)    

- ** Click on the butler icon in the toolbar.** You will see a little form that looks like this:

    ![Popup dialog](https://github.com/kfishkin/butler/blob/master/doc/pix/popup_dialog.png) 

- Stuff in whatever text you'd like the 1-step reply to have for its reply. There is a default, you don't have to do this. In this case, I'll use the default.

- Now, hit the 'Click to decorate' button. You will now see that little 'butler' icons now appear on your Quora page, one per comment:

    ![Comments after decoration](https://github.com/kfishkin/butler/blob/master/doc/pix/comments_after_decoration.png) 

- If you then click on one of these icons, it will 'reply' to the comment that it is next to, with the text you specified in the popup.

For example, suppose we click on the icon by Akshat's comment. Then you will quickly see your page change to look like this:

    ![After Reply](https://github.com/kfishkin/butler/blob/master/doc/pix/after_reply.png) 

And there you have it! Try it out, let me know what you think, also it's on Github so I welcome improvements.