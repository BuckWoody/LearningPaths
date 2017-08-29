Learning Path - Create an Intelligent Windows Application
=================================================================================
Audience: Developer
---------------------------------
Type: Solution
--------------------
### Summary
In this learning path, you'll learn how to use the Acquire, Process, Respond process to create an intelligent Windows application with Cognitive Services. You'll be guided through articles, documentation, videos, tutorials, and sample applications. It is recommended that you complete all tutorials and create all sample applications to get the most out of this learning path.


### Lesson Path
| Objective                                                                        | Topic                                                                   | Resource                                                                                                                                                                                                                                                          | Technologies                                                                                                                                                                           | Level        | Pre-Requisites                                                                                                                                                                                              |
|----------------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Set up your machine to be able to create Windows applications with Visual Studio | Install and configure Visual Studio                                     | [This resource shows how to install Visual Studio](https://www.visualstudio.com/downloads/)                                                                                                                                                                       | Visual Studio                                                                                                                                                                          | Beginner     | None                                                                                                                                                                                                        |
|                                                                                  |                                                                         | [This resource provides a tutorial on how to open Visual Studio and create a simple application](https://msdn.microsoft.com/en-us/library/jj153219.aspx)                                                                                                          | C\#, Visual Studio                                                                                                                                                                     | Beginner     | None                                                                                                                                                                                                        |
|                                                                                  | Copy the sample application for tutorial purposes in this learning path | [This resource page explains the Sample application, Family Notes, that will be used for demonstration and tutorial purposes in this learning path](https://github.com/Microsoft/Windows-appsample-familynotes)                                                   | SpeechRecognizer, SpeechSynthesizer, MediaCapture, FaceDetectionEffect, Microsoft Face API, Cortana, InkCanvas API, DataContractJsonSerializer, UWP, Cognitive Services, Visual Studio | Beginner     | None                                                                                                                                                                                                        |
|                                                                                  |                                                                         | [This zip file contains the Sample application files for Family Notes](https://github.com/Microsoft/Windows-appsample-familynotes/archive/master.zip)                                                                                                             | Visual Studio                                                                                                                                                                          | Beginner     | None                                                                                                                                                                                                        |
|                                                                                  | Working with the Universal Windows Platform SDK                         | [This resource page explains the Universal Windows Platform (UWP) app and provides guidance on how to set it up](https://docs.microsoft.com/en-us/windows/uwp/get-started/whats-a-uwp)                                                                            | UWP                                                                                                                                                                                    | Beginner     | None                                                                                                                                                                                                        |
|                                                                                  |                                                                         | [This tutorial takes you through the "Hello, world" creation of a sample C\# app for UWP on Windows 10](https://docs.microsoft.com/en-us/windows/uwp/get-started/create-a-hello-world-app-xaml-universal)                                                         | UWP, C\#, Visual Studio                                                                                                                                                                | Intermediate | Familiarity with Visual Studio, programming background                                                                                                                                                      |
| Be able to take in information and acquire data                                  | Accessing the camera in Windows                                         | [This resource page provides an end-to-end sample to show how to write a camera application using Windows.Media.Capture API in conjunction with orientation sensors](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/CameraStarterKit) | Windows.Media.Capture API, UWP, Visual Studio, C\#                                                                                                                                     | Intermediate | Familiarity with Visual Studio, programming background, familiarity with MediaCapture https://docs.microsoft.com/en-us/windows/uwp/audio-video-camera/basic-photo-video-and-audio-capture-with-mediacapture |
|                                                                                  | Working with handwriting                                                | [The MVA course teaches you, through a series of videos, about Inking and the InkCanvas for Windows 10 applications](https://mva.microsoft.com/en-us/training-courses/windows-10-inking-and-the-inkcanvas-14586?l=LRhlWJFsB_5205632527)                           | UWP, C\#, Visual Studio                                                                                                                                                                | Intermediate | Familiarity with Visual Studio, programming background                                                                                                                                                      |
|                                                                                  |                                                                         | [This resource page shows how to use ink functionality in UWP apps using C\#](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/SimpleInk)                                                                                               | UWP, C\#, Visual Studio                                                                                                                                                                | Experienced  | Familiarity with Visual Studio, C\# experience                                                                                                                                                              |
|                                                                                  | Acquiring speech with Cortana                                           | [This resource explains activating a background app using Cortana voice commands](https://docs.microsoft.com/en-us/cortana/voicecommands/launch-a-background-app-with-voice-commands-in-cortana)                                                                  | Visual Studio, VCDs, App Service                                                                                                                                                       | Intermediate | Familiarity with Visual Studio, Cortana, and APIs                                                                                                                                                           |
|                                                                                  |                                                                         | [This resource page shows how to integrate with Cortana by providing Voice Command Definitions (VCDs) that allow an app to be invoked in a variety of ways](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/CortanaVoiceCommand)       | UWP, C\#, Visual Studio, VCDs                                                                                                                                                          | Experienced  | Familiarity with Visual Studio, C\# experience                                                                                                                                                              |
| Be able to process the acquired data                                             | Processing speech                                                       | *This resource explains the best practices for designing speech interactions*                                                                                                                                                                                     | None                                                                                                                                                                                   | Intermediate | Familiarity with app construction and design                                                                                                                                                                |
|                                                                                  |                                                                         | [This resource page explains how to set up an audio feed and recognize speech with the Windows.Media.SpeechRecognition Namespace](https://docs.microsoft.com/en-us/windows/uwp/input-and-devices/speech-recognition#related-articles)                             | UWP, C\#, Visual Studio                                                                                                                                                                | Experienced  | Familiarity with Visual Studio, C\# experience                                                                                                                                                              |
|                                                                                  |                                                                         | [This article explains how to go from talking to a UWP app to conversing with a UWP app](https://blogs.windows.com/buildingapps/2016/05/23/using-speech-in-your-uwp-apps-from-talking-to-conversing/#03A4VRZP4Dv3bi87.97)                                         | UWP, C\#, Visual Studio                                                                                                                                                                | Experienced  | Familiarity with Visual Studio, C\# experience                                                                                                                                                              |
|                                                                                  | Recognizing a face                                                      | [This resource page explains how to detect and trace faces in an image or sequence of frames](https://docs.microsoft.com/en-us/windows/uwp/audio-video-camera/detect-and-track-faces-in-an-image)                                                                 | UWP, C\#, Visual Studio                                                                                                                                                                | Experienced  | Familiarity with Visual Studio, C\# experience                                                                                                                                                              |
|                                                                                  |                                                                         | [This resource page provides an end-to-end sample to show how to write a camera app and shows a simple way to use the Face Detection effect included in Windows](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/CameraFaceDetection)  | UWP, C\#, Visual Studio                                                                                                                                                                | Experienced  | Familiarity with Visual Studio, C\# experience                                                                                                                                                              |
|                                                                                  | Working with the Cognitive Services API                                 | [This resource provides an overview/quickstarts/tutorials for how to use the Face API](https://docs.microsoft.com/en-us/azure/cognitive-services/face/overview)                                                                                                   | C\#, Visual Studio                                                                                                                                                                     | Experienced  | Familiarity with Visual Studio, C\# experience or programming background                                                                                                                                    |
| Be able to set up a system that responds and performs some action                | Compiling and running the sample application                            | [Use this resource to download the Family Notes application, compile the application, set the API key, and try it out](https://github.com/Microsoft/Windows-appsample-familynotes)                                                                                | UWP, C\#, Visual Studio                                                                                                                                                                | Experienced  | Familiarity with Visual Studio, programming background                                                                                                                                                      |
|                                                                                  | Other Cognitive Services APIs                                           | [Use this resource as a starting point to adding other Cognitive Services APIs to your apps. You can link from here to the documentation for each API](https://azure.microsoft.com/en-us/services/cognitive-services/#all-cognitive-services)                     | Cognitive Services                                                                                                                                                                     | Intermediate | Familiarity with Visual Studio, programming background                                                                                                                                                      |


You can also click one of the Links below to see other Lesson Paths. 
- [Executive Sponsor](https://github.com/BuckWoody/LearningPaths/tree/master/Executive%20Sponsor)
- [IT Director](https://github.com/BuckWoody/LearningPaths/tree/master/IT%20Director)
- [IT Architect](https://github.com/BuckWoody/LearningPaths/tree/master/IT%20Architect)
- [Data Scientist](https://github.com/BuckWoody/LearningPaths/tree/master/Data%20Scientist)
- [Developer](https://github.com/BuckWoody/LearningPaths/tree/master/Developer)

Enjoy the journey. If you find something we're missing or a Resource doesn't work, please let us know.