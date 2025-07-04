[![Java CI](https://github.com/Nianna/Karedi/actions/workflows/maven.yml/badge.svg?branch=master)](https://github.com/Nianna/Karedi/actions/workflows/maven.yml)
![Java](https://img.shields.io/badge/Java-17-informational)
![GitHub](https://img.shields.io/github/license/nianna/karedi)
![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![MacOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=white)

### 📖 [Documentation and tutorials](https://karedi.gitbook.io/karedi/)

# Karedi

Karedi is a new, improved graphical editor designed for creating songs for Ultrastar - one of the most popular karaoke games for PC.
Its main objective is to simplify the process of creation for both beginners and advanced users while assuring high-quality of the final txt files.

![karedi](https://github.com/Nianna/Karedi/assets/31940002/568093fb-43cd-4c1e-b8a7-69f188d7e9c2)


## Main features
Karedi's main features include:
  * support for multiple operating systems with no additional dependencies
  * full documentation and tutorials for beginners available in the project's [website](https://karedi.gitbook.io/karedi/)
  * two display modes:
     * line by line - visible area's bounds are adjusted automatically
     * continuous - they are set manually by you
  * multiple playback modes
  * support for songs with multiple tracks
  * intuitive new song wizard
  * tag features (e.g. rescaling to new BPM, setting medley from selection) & validation
  * copy & paste (in 2 modes: traditional and merge)
  * auto-syllabification of lyrics in most popular languages
  * automatic search for problems (errors & warnings)
  * solver that offers both safe and potentially risky (useful if safe fix is not available) solutions to almost all the problems
  * support for multiple audio files of various formats with adjustable volume
  * auxiliary note method support:
      * notes are sorted according to their startbeats
      * shortcuts for playing fragments before (alt + UP) or after (alt + DOWN) the selected note
  * extra modules:
      * Tap Notes - add notes by pressing a key while listening to playback
      * Write Tones - set tones of selected notes by pressing an appropriate key, e.g. "E".
      
Please refer to the [wiki](https://karedi.gitbook.io/karedi/) to learn more.

## Tutorial

For tutorials explaining how to use this software, please refer to the [project's wiki](https://karedi.gitbook.io/karedi/).

## Downloads

You can found the newest version in the [Releases](https://github.com/Nianna/Karedi/releases) section.

## Building
In order to build Karedi, you can run `mvn package`; this will create a JAR file in `target/dist`.

For example, you can run the built program like this:
```bash
mvn package  # Compile, build, and run tests
java -jar target/dist/Karedi-1.7.0.jar  # Replace "1.7.0" with current version
```

## Libraries

Karedi uses the following libraries:
* [JavaFX](https://github.com/openjdk/jfx) with [ControlsFX](https://github.com/controlsfx/controlsfx) & [RichTextFx](https://github.com/TomasMikula/RichTextFX) for GUI,
* [jFugue](http://www.jfugue.org) to simplify the process of creating MIDI sequences,
* [hyphenator](https://github.com/Nianna/hyphenator) for syllabification,
* [javasound-aac](https://github.com/Tianscar/javasound-aac) for m4a files support,
* mp3spi for mp3 files support,
* [java-vorbis-support](https://github.com/Trilarion/java-vorbis-support) for Ogg Vorbis support,
* [vavi-sound-flac-nayuki](https://github.com/umjammer/vavi-sound-flac-nayuki?tab=GPL-3.0-1-ov-file) for flac files support.

## License

The project is licensed under [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html).
