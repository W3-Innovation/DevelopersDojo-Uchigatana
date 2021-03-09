# Developer's Dojo: Uchigatana

<br>

> + **Homepage:** _https://github.com/W3-Innovation/AjayChambers_
> + **Repository:** _https://github.com/W3-Innovation/DevelopersDojo-Uchigatana_
> + **Email Contact:** _AChambers.W3Innovation@Gmail.com_
> + **Developed By: A Jay Chambers**

<br>
<br>

### _Version Control Highlighting_
---
<p>I styled the version control tad and filename decorations in a way that I suppose could be considered unique. Its not all that much different from what could be considerd the standard way. Tab decorations, which were released just a couple of months before I wrote this, highlight a handful of resource statuses, among them are the 2 more important and common statuses: **Added & Modified**. When a new resource is added its status is not added, but untracked, and when a resource is modified its status is unstaged-modified. When the developer stages, or adds his changes via the git command: </p>
    
    ~/$ git add .

<p>the added resources statuses change from **Untracked** to **Added**, and Modified resources change from **Modified-Unstaged** to **Modified-Staged**. So the way I do the highlighting in my theme is by assigning a unique color to each of the unstaged statuses, and a single color to all of the statuses that ared staged, and ready to be commited. I find this approach helps to make the version controll decorations be more clear, and consise in there meaning, as well as helping to keep the editor from becoming visualy cluttered.</p>

---
<br>
<br>