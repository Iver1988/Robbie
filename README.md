# Robbie

> Robbie is Artificial Inteligence [IoT] framework for all purposes. Is written in [Python] and uses [Alicebot AIML 2.0]. Robbie needs no screens. Just type or say commands like to normal people. Robbie do command, tell you something or do another action depending on his installed modules for sensors and devices. Developers can write own modules and enhance Robbie. Possibilities are endless. From home assistant (primary use), car assistants, airplanes assistants, interactive robots to clever space ships like in Star Trek in future :)

## Here is Amazon Echo and Google Home where are differencies compare to them?
> So. It's simple. Amazon Echo and Google Home are closed systems with own harware and software policies. Robbie is framework. You can build own UNIX like device with own sensors and parts (for example speaker and microphone) and use Robbie's code. You can sale this devices as your product if you want. You can create own modules for devices compatibility and share this modules for free, do edits in Robbie's code or create own forks and versions. All without policies and bureaucracy.

## Features
  - Open Source
  - Based on [Alicebot AIML 2.0]
  - Robbie understand your sentences and reacts (Just tell him "Prepare some coffee for me", or "How many people live on Earth"...)
  - Text to speech
  - Running on all [UNIX] devices include [MacOS]
  - Primary used for [Intel Edison], but can run on another device - small or big one
  - Prepared for [IoT] manufacturers (just connect your sensors and devices using Robbie's methods)
  
## Videos
[First Look]
  
## To-do
- Support for [Answers.com], [Wolfram Alpha], [Wikipedia] and other services
- Using of another bots in network (Your home instance of Robbie can ask for closing of doors in your company for example. There can be closing IoT device for door closing or just another Robbie server managing this IoT device himself.)
- Voice recognization
- Support for sensors and devices using [Intel Edison]
- Support for sensors and devices using protocols
- Web Admin based on Python's Flask with configurable IP address (public IP can be set), login screen, graphs, console and online modules + wysiwig AIML editor. You can manage and program Robbie using web admin only
- Libraries for main programming languages (one can use communicate with Robbie using mobile phone microphone and text input for example + Robbie can show informations on display and use mobile phone speaker)
- [Python] GUI for desktop platforms using libraries and nice design
- User profiles with users swithching ("Hello, here is Thomas. Can you do some notes for me?", "Hi Thomas, what do you want to note?")

> More info about features is in GitHub's issues list.

## Dependencies
- [Python 3]
- [pyyaml]
- [python-dateutil]
- [requests]
- [pydub]
- [wikipedia]
- [flask]
- [libav] or [ffmpeg]

> Setup script will be prepared later

## Installation

### Linux
- Install [Python 3] first
and then:

```sh
$ sudo apt-get install python3-pip
$ pip3 install pyaml
$ pip3 install python-dateutil
$ pip3 install requests
$ pip3 install pydub
$ pip3 install wikipedia
$ pip3 install flask
$ apt-get install libav-tools libavcodec-extra-53
or
$ apt-get install ffmpeg libavcodec-extra-53
```

### MacOS
- Install [Python 3] first
and then:

```sh
$ pip3 install pyaml
$ pip3 install python-dateutil
$ pip3 install requests
$ pip3 install pydub
$ pip3 install wikipedia
$ pip3 install flask
$ xcode-select --install
$ brew install libav --with-libvorbis --with-sdl --with-theora
or
$ brew install ffmpeg --with-libvorbis --with-ffplay --with-theora
```

## Running
- CD to Robbie folder in terminal 
and then:

```sh
$ sh start.sh
```

>You can set automatic lauching of this script on restart as well.

## Stopping
- Hit CTRL+C in terminal

>Do not close Robbie. He can not respond on you and can not learn when is closed. Let him live on old PC or own [Intel Edison] board for example.

## Help us
Want to help us with this amazing project? [Contact us](mailto:tomas.triska@icloud.com). We like investors as well.

## License
Robbie is build upon [program-y] AIML project and [GNU LGPL v3.0] license is used.

   [Internet of Things]: <https://en.wikipedia.org/wiki/Internet_of_things>
   [IoT]: <https://en.wikipedia.org/wiki/Internet_of_things>
   [Python]: <https://www.python.org>
   [Python 3]: <https://www.python.org/download/releases/3.0/>
   [Unix]: <https://en.wikipedia.org/wiki/Unix>
   [MacOS]: <https://cs.wikipedia.org/wiki/Mac_OS>
   [Intel Edison]: <https://software.intel.com/en-us/iot/hardware/edison>
   [Wolfram Alpha]: <https://www.wolframalpha.com>
   [Wikipedia]: <https://www.wikipedia.org>
   [pyyaml]: <http://pyyaml.org>
   [python-dateutil]: <https://dateutil.readthedocs.io/en/stable/>
   [requests]: <http://docs.python-requests.org/en/master/>
   [program-y]: <https://github.com/keiffster/program-y>
   [GNU LGPL v3.0]: <https://www.gnu.org/licenses/lgpl-3.0.en.html>
   [Alicebot AIML 2.0]: <https://docs.google.com/document/d/1wNT25hJRyupcG51aO89UcQEiG-HkXRXusukADpFnDs4/pub>
   [Answers.com]: <http://www.answers.com>
   [pydub]: <http://pydub.com>
   [First Look]: <https://www.youtube.com/watch?v=iqWow03RaaM>
   [wikipedia]: <https://pypi.python.org/pypi/wikipedia/>
   [flask]: <http://flask.pocoo.org>
   [libav]: <https://libav.org>
   [ffmpeg]: <https://www.ffmpeg.org>