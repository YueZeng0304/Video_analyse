# Fall-detection
Fall-detection in the room

 this fall-detection is based on [darknet](https://pjreddie.com/darknet/yolo/).


## Examples
   we first detect humans in the room, then we use some simple ways to judge whether he or she is falling down.
![fall detection example](https://github.com/qiaoguan/Fall-detection/blob/master/demo.gif)

### fall-detection algorithms

  * detect human
  * classify whether fall down or not(still on the way)/custom rules  
## Installation

### Requirements

  * Python and opencv, 
  * Linux (Windows and Mac os are not officially supported, but should work)

### Installation Options:

#### Install on Linux

First, make sure you have install python and opencv environment(p.s. if you do not have GPU support, change the first line and second line of Makefile  value from 1 to 0)


Then, install this module :

```bash
git clone https://github.com/qiaoguan/Fall-detection
cd Fall-detection
sudo make
```


### run the demo

  Install this module :

  ```bash
  python gq.py
  ```
  for opencv3 users, you can refer to this [code](https://github.com/qiaoguan/Fall-detection/pull/16/commits/01187a0c16e5ead6d1faeb2f47665fab9a1ba2da)
### the speed is about 12fps using GPU(GTX 1080)
## Thanks

* Many, many thanks to [pjreddie](https://pjreddie.com/darknet/yolo/) for his Great work!
