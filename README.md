![Logo](admin/lgtv2011.png)
# ioBroker.lgtv-hdcp
=================


LG SmartTV adapter for ioBroker

Remote controlling an LG SmartTV (2011 models with HDCP API).

Merged from the following projects:

https://github.com/ubaransel/lgcommander

https://github.com/SebastianSchultz/ioBroker.lgtv11

https://github.com/dreamcat4/lgremote


---


## Usage:


1.) Download the adapter from Github.

2.) In the adapter config input the ip adress of your LG TV.

3.) Start the adapter

4.) Open the adapter config an click on "request pairing key"

5.) Insert the pairing key shown on your TV screen in the adapter config

6.) Restart the adapter.





## Some examples:
```setState('lgtv.0.turnOff', true);```

Switching off the TV.


```setState('lgtv.0.back', true);```

Goes back.


```setState('lgtv.0.mute', true);```

Mute the TV.


```setState('lgtv.0.mute', false);```

Unmute the TV.


```setState('lgtv.0.volumeUp', true);```

This will increase the volume of the TV.


```setState('lgtv.0.volumeDown', true);```

Decreasing the volume of the TV.


```setState('lgtv.0.channelUp', true);```

Increasing the current TV channel.


```setState('lgtv.0.channelDown', true);```

Decreasing the current TV channel.


```setState('lgtv.0.3Dmode', true);```

Activates the 3D mode on the TV


```setState('lgtv.0.3Dmode', false);```

Deactivates the 3D mode on the TV.


```setState('lgtv.0.input', true);```

Open the input list to switch to.



---


## Changelog

### 1.0.0 (2021-01-27)
* (calma76) Forked from ioBroker.lgtv11 and renamed to ioBroker.lgtv-hdcp


---


## License

The MIT License (MIT)

Copyright (c) 2019 Sebastian Schultz.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
