**Accessibility solution for Android tablet**

**Overview**

This project has the end goal of making an android tablet accessible for
users with motor impairment. The final product should be a software
layer that allows complete control of an android tablet using just gaze.

**Background**

Users with motor disability are often unable or severely handicapped to
use their hands to interact with a tablet device. While some
accessibility solutions exist for motor disabilities in Windows
environments, comprehensive accessibility solutions for Android are
conspicuously lacking. Gaze interaction is a very promising interaction
modality for subjects with motor disability since eye movements are
relatively spared in spinal cord traumatic injuries and diseases such as
motor neuron disease or muscular dystrophy. In order to use gaze as an
interaction mechanism, this project will need a piece of hardware called
an eye tracker. Basically a camera with some infrared leds that use
clever tricks to infer the point of regard of the user on the screen. A
company in Denmark has recently launch a low-cost eye tracker with an
Android API.

<https://theeyetribe.com/>

This piece of hardware basically provides the gaze X and Y coordinates
of a subject on the screen.

**Deliverables**

-   This project would require the creation of a GUI layer on top of the
    android interface where users could select interaction tasks such as
    finger touch, long finger touch or swipes, via gaze, and then use
    gaze to trigger the previously gaze selected task at the specific
    point on the screen they are gazing at. Such a mechanism would allow
    a subject to control an android tablet just using gaze without the
    need to use hands, hence fulfilling its accessibility premise.

-   Engine managing the firing of interaction events

-   Writing a driver/client to communicate with the eye tracker and
    obtain X, Y gaze coordinates

![](media/image1.png)

Eye tracker hardware:

![](media/image2.png)
