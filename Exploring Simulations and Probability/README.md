# Exploring Simulations and Probability

## [Link to Project in Kaggle](https://www.kaggle.com/code/snailonrock/exploring-simulations-and-probability)

### Abstract

This notebook is a basic introduction to simulations and probability using the Monte Carlo method. Topics that have been covered are The Monty Hall problem and it's extension Monty's Revenge, Monte Carlo Integration and Trapezoid Rule Integration. For all the examples there are simulations in Python.

# Audio Recorder

## *Viktor Nikolov*

**AudioRecorder** records audio using your built in microphone. It's also able to save and delete your recordings.

## Functionality

The following **required functionality** is completed:
* [x] Create a new audio recording.
* [x] Create a list of recordings.
* [x] Listen to recording.
* [x] Delete recording.
* [x] Rename recording.
* [x] Show details about recording.


The following **functionality** is completed:

In MainActivity:
* [x] User can press the record button and record audio. Pause if pressed again.
* [x] User can press the done button and a bottom sheet layout will appear in which the save, rename or cancel options are available.
* [x] User can press the delete button which will stop the recording and delete audio.
* [x] User can press the list button and go to GalleryActivity.
   
In GalleryActivity:
* [x] User can swipe to delete recording.
* [x] User can short click a recording and go to AudioPlayerActivity.
* [x] User can long click a recording whcih will activate the edit mode and show the hidden toolbar.
* [x] User can search for a recording using the search bar.

In Toolbar:
* [x] User can press the select all button and select all rows.
* [x] User can press the rename button only if single row is selected and rename recording.
* [x] User can press the info/details button and go to DetailsActivity where details about the selected recording a shown.
* [x] User can press the X button and exit edit mode.
    
In AudioPlayerActivity:  
* [x] User can press the back, play/pause, forward, change speed and seek bar to change audio state and speed.

**TO DO**
* [x] Fix recycle view bugs. (Can't hold more than 12/13 items without changing order. I belive the problem comes from DiffUtils beacuse other apps that I have made have the same bug for example NoteApp and BudgetTracker)
* [x] Some other small bugs. 

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/viktornikolov069/Audio-Recorder/blob/main/audio_recorder_6.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

There are some bugs that have to be fixed like the RV bug and others and there are improvements that can be made like using fragments and others.

## License

    Copyright [2022] [Viktor Nikolov]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


