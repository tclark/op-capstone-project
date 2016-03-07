**Gaze swipes for text input via gaze**

**Overview**

This project has the end goal of making a Windows desktop gaze mediated
text input system for users with motor impairment. The final product
should be a software layer that allows fast and efficient text input via
gaze using an onscreen keyboard in a Windows computer.

**Background**

Users with motor disability are often unable or severely handicapped to
input text in a computer. While some text input solutions exist for
motor disabilities in Windows environments, they are often cumbersome
and very slow. Often entering a single word can take a minute of time.
This project proposes the merging of swipe like text input (as existing
in Android devices) with gaze text input. The user could type a word by
gazing sequentially at the letters of the word. The idea of swipe text
input is introduced in the following video:

<https://www.youtube.com/watch?v=SOMkilE1wUY>

This project would substitute the finger for gaze movements as a means
to input text. In order to use gaze as an interaction mechanism, this
project will need a piece of hardware called an eye tracker. Basically a
camera with some infrared leds that use clever tricks to infer the point
of regard of the user on the screen.

This piece of hardware basically provides the gaze X and Y coordinates
of a subject on the screen.

An alternative for this project would be to extend the open source
project OptiKey.

<https://github.com/OptiKey/OptiKey/wiki>

OptiKey is an assistive on-screen keyboard which runs on Windows. It is
designed to be used with a low cost eye-tracking device to bring
keyboard control, mouse control and speech to people with motor and
speech limitations, such as people living with Amyotrophic Lateral
Sclerosis (ALS) / Motor Neuron Disease (MND). The extension should allow
input in text in the OptiKey application through gaze swipes.

**Deliverables**

-   on screen keyboard system responsive to gaze swipes for text input

-   the gaze input text is injected in a given application text input
    field

![](media/image1.jpeg)

Eye tracker hardware:

![](media/image2.png)
