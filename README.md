# Multi-user-Blog

#Blog Roll

Multi User Blog is a web application which I have created as part of the Udacity, Fullstack Web Developer Nano Degree program. I have called my blog `Blogroll`, the blog allows users to do the following:

* Create a user account,
* Sign in if user is an existing user,
* Create a blog post,
* Edit and delete their own blog posts,
* Browse other user blog posts,
* Comment on blog posts,
* Edit and delete their own comments,
* Like and unlike blog posts of other users.

## In order to run the web site, the user is required to:

 * Install `Python 2.7` and **Google's** `Google App Engine`,
 * Run Google App Engine localy, or you can deploy your project to Google App Engine server,
 * In the `salt.py` file the SECRET parameter is used to hash cookies, it is advised to set this variable to a more unique and secure string.

#Installation

Installation is simple please follow the below instructions:

##Installing Python

In your browser, browse to [python/downoads] (https://www.python.org/) > Downloands > A dropdown list will appear with various operating systems.

##Installing Python on Windows

1.From this list select either `Windows X86` or `Windows X86-64`
2.Once downloaded locate the file in your download file,(or prefered location) double clicking the file and pressing Run when the dialog box pops up.
3.Next select the `Install for all users`option if you are allowing `all user's` who access your computer, access to the `python` program then leave this option selected. If you have multiple users and wish to not install `python` accross all accounts then select the `Install just for me` option then press `Next.`
4.Feel free to change the location path however, it is best to leave it as is and simply select 'Next'.
5.Scroll down in the window and find the 'Add Python.exe to Path' and click on the small red 'X' Choose the 'Will be installed on local hard drive' option then press 'Next'.
6.You will notice that the installation will bring up a command prompt window while Python downloads and installs 'Pip'. 'Pip' is just a package management tool. This will allow you to install all the additional Python packages that are available for download through PyPI (Python Package Index).
7.Once the install is complete press 'Finish'.

##Installing Python on a Mac Machine

1.From the download list at `python.org` select Mac OSX 64.32 bit installer.
2.A pop up screen will appear for you to select the installers file location, once you have selected the location press the `save` button.
3.Once the installer package has been donloaded click on the completed donload.
4.The installer will promp you to press `Continue`, until you reach the license agreement.At this point press agree to continue with the install.
5.The install package will then ask you to `install a standard instillation`, if you are happy with this then click install
6.Once the install is complete the installer will exit.

#Installing Google App Engine

##Installing App Engine on a Windows based machine

1. In your browser, browse to [google-app-engine](https://cloud.google.com/appengine/downloads),
2. scroll down to `Google App Engine SDK for Python` select the latest download package file for `Windows`, in ths case `GoogleAppEngine-1.9.40.msi`.
3. Once downloaded locate the file in your download file,or prefered location.
4. Double-click the SDK file you downloaded (GoogleAppEngine-1.9.40.msi) and follow the prompts to install the SDK.
You will need Python 2.7 to use the App Engine SDK, because the Development Server is a Python application. Download Python 2.7.X (don't use a higher version) from the Python web site.

##Installing App Engine on a Mac os x

Note: The App Engine SDK is under active development; please keep this in mind as you explore its capabilities. See the Java | Python | Go | PHP SDK Release Notes for information on the most recent changes to the App Engine SDK. If you discover any issues, feel free to notify us via our Issue Tracker.
By downloading, you agree to be bound by the Terms that govern use of the App Engine SDK.



## Browsing the web site:
 * Browse http://syf-udacity-cs253.appspot.com/
(or http://localhost:8080 for local deployment)
 * Users should sign up in order to send new posts and comments, Sign Up link exists
on the top right corner
 * Login / Sign Up links are on the top right corner when user not logged in
 * Logout link are on the top right corner when user logged in
 * User can post new blog post clicking the New Post navigation button after logged in
 * Posts can be viewed in detail by clicking their subjects
 * In detail view comments of posts can be seen
 * New comments can be added by clicking Add Comment button located under each post
 * Posts and Comments can be modified if they are created by the logged in user.
If user is authorized to modify Post or Comment, Edit and Delete links are located under
content at bottom right corner
 * Users may like and unlike a post by clicking Like and Unlike buttons. It is required
to logged in, in order to perform like operation. In addition, users should't like or
unlike their own posts.
 * After the content of a post, at bottom right corner there exists,
 	* Edit / Delete links if user owns that post
 	* Like / Unlike links if user doesn't own that post
 * Like link changes to Liked link if user Liked that post before and Unlike link changes
to Unliked if user Unliked that post before. If user clicks the Liked or Unliked link
they take their like or unlike back.
 * When there are Liked and Unlike links, user Liked that post before, if user clicks
Unlike, the Like is taken back and Unlike recorder.
Same condition applies for the opposite.
