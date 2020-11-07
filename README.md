# encode-resolve
This is a tool that makes videos support to import for davinci resolve free version

[Usage]
<pre>
cd [your_video_location]
encode-resolve [your_video_format]
</pre>

example :

<pre>
cd ~/Video
encode-resolve mp4
</pre>

And this tool will convert all your video in that folder. So, make sure you prepare special folder for it!

[How to install]
Follow the instruction below! </br>
<pre>
git clone https://github.com/DLandDS/encode-resolve.git
cd encode-resolve
ln -s $(pwd)/encode-resolve ~/.local/bin
</pre>
Make sure the ~/.local/bin is exist and inculde on your environment variable!
