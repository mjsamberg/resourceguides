---
layout: page
title: Accessibility
---
## General Accessibility Guidelines
[![Accessibility Guideline Posters via the UK Accessibility Office https://accessibility.blog.gov.uk/2016/09/02/dos-and-donts-on-designing-for-accessibility/][image-1]][1]
Remember these accessibility guidelines from the [U.K. Accessibility Office][2], including:
* Use clear language and consistent layouts
* Use bullet points and simple sentences
* Avoid bright, busy layouts
* Use readable font sizes and good contrast
* Don’t bury information in downloads
* Use headings, subheadings, and videos
* Spread interactive out over a document

## Videos and Video Chats
Videos and video chats need two primary supports: captions and accessible visuals.

### Captioning
In addition to benefiting [d/Deaf and hard of hearing users][3], captions can benefit users who are who are in noisy environments, users who get distracted and miss a word, and supports users in taking notes. Captions also have [tremendous value for users with autism, ADHD, Down’s Syndrome, and English Learners][4].

Captions should contain the following elements:
* All spoken words from a video call or presentation
*  Any _relevant_ background noise (i.e. if someone is speaking in a crowded room, the crowd noise doesn’t have to be transcribed **but** if a noise (like a school bell) is relevant and adds value to the video, it should be included in the captions in italics and in square brackets.
* Song lyrics in the background should be included in captions as well.
* Speaker indications. If the person speaking is not the person on the screen in italics and parentheses. 
* It is not necessary to include words that are already on the screen from a slide or visual aid. 
* [Video Captioning Style Guide from University of Melbourne][5]

Captions can either be human-generated or machine-generated. Human-generated captions are the gold standard as machine-generated captions are prone to error and have trouble transcribing accents and sounds over a video conference or from noisy environments. Human-generated captions, however, are time consuming to create and services to create them can be expensive. Students do have a right to request human-generated transcriptions. In live meetings, you have a few options for generating live captions:
* Human-Generated Captions
	* [Zoom has built-in functionality to type captions in the meeting][6]. A person can be assigned to type captions live in a meeting.
	* Companies exist that will provide this as a service. [NC State has convenience contracts for live captioning][7].
* Machine-Generated Captions
	* [Otter.ai will generate a transcript page for a meeting][8] in Zoom live. The transcript will be in a separate window.
	* [Google Meet has live support for closed captioning][9]. 
	* [Google Slides][10] and [Microsoft PowerPoint][11] have built-in caption support. These captions are limited as they will not display if you switch applications away from the slide deck, and have trouble recognizing other speakers on the Zoom call. Additionally, because they’re embedded in the slide show, they’re “burned in” to the recording and cannot be removed. This may create issues for you later if you want to add human-generated captions to a recording.
	* Using [Open Broadcaster Software (OBS)][12], and a website called [WebCaptioner][13], it is possible to [add a caption window to your webcam image][14], and [use this as a camera in Zoom or Google Meet][15]. Like PowerPoint and Google Slides, these captions only recognize the speaker on one computer and are “burned in” to the recording.   

In a pre-made video or a meeting recording,  captions are a bit easier:
* Machine-Generated Captions
	* [Zoom will automatically create a webpage with captions for cloud recordings, if enabled][16].
	* When uploading a video to YouTube, [YouTube will automatically create captions][17] within a few hours after upload.
* Human-Generated Captions
	* [Rev.com][18] offers a service that will transcribe video and audio files for you. Rev.com can automatically push corrected captions to YouTube. 
	* Automatic [captions in YouTube can be corrected][19] to be more accurate. If a video is kept unlisted or private, you can keep it from being discoverable while enabling these features.

### Accessible Visuals
Keep in mind that the PowerPoints and other materials shared on screen sharing during a Zoom call, or embedded in a video, are not accessible. It’s recommended that you share slide decks with users ahead of time and share the link in the chat so that users can access them. If you share your screen during a presentation, narrate your actions so that someone can recreate them.  If necessary, you may need to [create an audio description track][20] to narrate actions separate from the main video. 

## Images
In presentations, reports, and web pages, images need to be annotated with alternative text (also called an alt-tag) that describes the content of the image. This allows users who can’t access the image (due to a visual impairment, low bandwidth connection, etc.) to understand the contents. Alternative text **must** be used for every image in a document unless the image is purely decorative and serves no functional purpose in the document. Alt text should also describe the _contents_ of the image, and not the image itself. Consider the example below. Using alt-text of “The water cycle” for this image is inadequate because it does not describe the contents of the image. You would need to use a describe tag such as “The water cycle: the process by which water in the oceans evaporates, condenses to form clouds, falls to the ground as rain, and is again collected in the ocean.” The content of an image should also be reflected in a document. For example, a graph can be alt-tagged, but the description of the key findings (and ideally, a data table) should be included in a document. For complicated charts, it is acceptable to reference the discussion section of a paper if the information conveyed there will explain the chart. Alt tags are added differently in different applications. In Moodle, there is an alt-text field when adding an image. In Office and Google Docs, you can right-click on an image to add the alt text. You can also add alt-text on [Twitter][21], [Facebook][22], and [Instagram][23]. 
![Illustration of the water cycle, showing the process by which water in the oceans evaporates, condenses to form clouds, falls to the ground as rain, and is again collected in the ocean.][image-2]

In addition, it is a best practice to avoid images that are all text, and creating these elements as text instead. Consider the example below. Instead of using an HTML table, this school posted an image of their bell schedule. However, because the text is contained within the image, it is unable to be read by screen readers or translation software.
![Sample image containing text that cannot be read by a screen reader.][image-3]

### Use of Color, Charts and Graphs
In addition to creating accessible images, the use of color in resources creates accessibility issues as well. To support those with color blindness and other visual impairments, foreground and background colors in documents should always be high-contrast. The [WebAIM Contrast Checker][24] can tell you based on the font size if a foreground and background color are high enough contrast. 

In a chart, each visual element should also contrast sufficiently. For example, in a bar graph, each bar should be sufficient contrast from each other bar (see [this guide from Penn State][25]). In addition, color should not be the only indicator of information. For example, labeling your axes, using shedding patters, etc. to differentiate between data points. 

## Headings
Screen readers, table of contents tools, and keyboard navigation use headings to navigate the screen. In addition to using proper heading styling, headings should be _nested_ such that Level 1, Level 2, Level 3 headings, etc. do not appear out of order. Level 2 headings should only appear under level 1 headings, and Level 3 headings should only appear under Level 2 headings. 

## Microsoft Office and Google Drive
Whether in webpages or in documents, many of the same accessibility rules above apply - images should have alt text, table rows should be labeled, etc. In addition, you should use _semantic styling_ in **all** documents, including Word Docs, Google Docs, and HTML files. Semantic styling involves identifying elements in a document by what they are, rather than how they look. Whereas typically, to designate a header in Google Docs, you might simply bold the text, when styling semantically, you would use the styles pane to designate an element as a header, and then style the header through the styles pane.
* [Using and editing styles in Word][26]
* [Using and editing styles in Google Docs][27]

## Accessibility Checking
[Microsoft Office features a built-in accessibility checker][28] across all Office apps. This tool will check accessibility features in your document 

## PDF Files
The PDF format has significant problems with accessibility, especially when designed natively in Acrobat. The best practices are to [design in Word, and then export to PDF][29]. Confirm accessibility in Word before exporting. Additionally, it is recommended to make documents available in another format.

Documents that are scanned to PDF are not accessible.  

## The Checklists
* [University of Washington][30]
* [SUNY Broome][31]
* [Cornell][32]

[1]:	https://accessibility.blog.gov.uk/2016/09/02/dos-and-donts-on-designing-for-accessibility/
[2]:	https://accessibility.blog.gov.uk/2016/09/02/dos-and-donts-on-designing-for-accessibility/
[3]:	https://blog.ai-media.tv/blog/the-difference-between-deaf-and-hard-of-hearing
[4]:	https://www.rev.com/blog/how-captions-benefit-more-than-the-deaf-and-hard-of-hearing
[5]:	https://www.unimelb.edu.au/accessibility/video-captioning/style-guide
[6]:	https://support.zoom.us/hc/en-us/articles/207279736-Closed-Captioning
[7]:	https://accessibility.oit.ncsu.edu/transcript-and-captioning-providers/
[8]:	https://blog.otter.ai/zoom/
[9]:	https://support.google.com/meet/answer/9300310?co=GENIE.Platform%3DDesktop&hl=en
[10]:	https://support.google.com/docs/answer/9109474?hl=en
[11]:	https://support.microsoft.com/en-us/office/add-closed-captions-or-subtitles-to-media-in-powerpoint-df091537-fb22-4507-898f-2358ddc0df18
[12]:	https://obsproject.com
[13]:	https://webcaptioner.com
[14]:	https://webcaptioner.com/help/integrations/add-captions-in-obs/
[15]:	https://streamshark.io/blog/using-obs-as-a-virtual-webcam-on-windows-and-macos/
[16]:	https://support.zoom.us/hc/en-us/articles/115004794983-Automatically-Transcribe-Cloud-Recordings-?zcid=1231
[17]:	https://support.google.com/youtube/answer/6373554?hl=en
[18]:	https://www.rev.com
[19]:	https://support.google.com/youtube/answer/2734705?hl=en
[20]:	https://digital.gov/2014/06/30/508-accessible-videos-how-to-make-audio-descriptions/
[21]:	https://help.twitter.com/en/using-twitter/picture-descriptions
[22]:	https://publish.illinois.edu/accessibility-training/2019/11/11/how-to-add-alt-text-in-facebook/
[23]:	https://blog.iconosquare.com/instagram-alt-text/
[24]:	https://webaim.org/resources/contrastchecker/
[25]:	https://accessibility.psu.edu/images/charts/
[26]:	https://www.dummies.com/software/microsoft-office/how-to-apply-styles-and-style-sets-in-word-2019/
[27]:	https://gsuitetips.com/tips/docs/customise-your-styles-in-google-docs/
[28]:	https://support.microsoft.com/en-us/office/improve-accessibility-with-the-accessibility-checker-a16f6de0-2f39-4a2b-8bd8-5ad801426c7f
[29]:	https://www.howtogeek.com/352668/how-to-convert-a-microsoft-word-document-to-a-pdf/
[30]:	https://depts.washington.edu/uwdrs/faculty/online-course-accessibility-checklist/
[31]:	http://www3.sunybroome.edu/online/wp-content/uploads/sites/11/2019/05/Accessibility-Checklist-for-Online-Courses.pdf
[32]:	http://www3.sunybroome.edu/online/wp-content/uploads/sites/11/2019/05/Accessibility-Checklist-for-Online-Courses.pdf

[image-1]:	https://mjsamberg.github.io/courses/dlprograms/content/karwai-infographics.png
[image-2]:	https://study.com/cimages/videopreview/videopreview-full/q9lhim9769.jpg
[image-3]:	bellschedule.png