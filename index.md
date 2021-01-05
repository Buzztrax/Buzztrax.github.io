# About 

Buzztrax aims to be a music studio that allows one to compose songs using only a computer with a soundcard. If you’ve used [tracker](http://en.wikipedia.org/wiki/Tracker) programs like FastTracker, Impulse Tracker, or the original AMIGA SoundTracker, that will give you an idea of how one can sequence music in Buzztrax.

The Buzztrax editor uses a similar concept, where a song consists of a sequence with tracks and in each track one uses patterns with events (musical notes and control changes). In contrast to other Tracker programs, tracks are not simply sample players: a user can make a song using an arrangment of virtual audio plugins that are linked together to create different effects. Each of these machines can be controlled realtime or via patterns in the sequencer.

[![bt-edit-0-4-0-01](/assets/images/thumbs_bt-edit-0-4-0-01.png)](/assets/images/bt-edit-0-4-0-01.png){:target="_blank"}
[![bt-edit-0-4-0-02](/assets/images/thumbs_bt-edit-0-4-0-02.png)](/assets/images/bt-edit-0-4-0-02.png){:target="_blank"}
[![bt-edit-0-4-0-01](/assets/images/thumbs_bt-edit-0-6-0-01.png)](/assets/images/bt-edit-0-6-0-01.png){:target="_blank"}
[![bt-edit-0-4-0-02](/assets/images/thumbs_bt-edit-0-6-0-02.png)](/assets/images/bt-edit-0-6-0-02.png){:target="_blank"}

The buzztrax editor will be just one possible application of the framework we are implementing. Tools like a dj mixing application or a live session composer are other things that can be built using our framework.

# Modules

All the code is contained in a single git repo. Head over to the [buzztrax module](https://github.com/Buzztrax/buzztrax/blob/master/README.md) to learn how to build the software from the sources. If you don't want to build the latest git snapshot, you can find stable versions in the [releases section](https://github.com/Buzztrax/buzztrax/releases).

Besides the main repository the [buzzmachines module](https://github.com/Buzztrax/buzzmachines/blob/master/README.md) conatains a collection of open-source plugin in the buzzmachine format that can be used with buzztrax. This modules does not have releases. The conde contained here is considered finished.

Finally the [design module](https://github.com/Buzztrax/design/blob/master/README.md) is mostly interesting for developers and contains short code snippet for bug reproduction, testing new features or sketching algorithms. You can also find a bunch of python notebooks with dsp algorithms in there. Non of this is required to build and run the main application.

