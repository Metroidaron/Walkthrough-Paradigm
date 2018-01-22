# Walkthrough-Paradigm

### Mission
A tool for elegantly displaying walkthrough or step by step instructions, Agnostic of the contents.

The current goal of this tool is generate a react application that can interpret a walkthrough or guide and display that information in a responsive design for front end consumption.  Several questions (Some listed below) need to be answered for this projects design.

- Where will the data live?  This tool is meant to be information agnostic, should the data be remote and there be one primary instance of this tool; or should the tool be duplicated and the data live inside the instance of the tool? 
- What kind of components do we want to be able to render?  See list below for some initial thoughts.

---
### Renderer Components
- Basic Markdown and HTML components
- Verbiage renderers (Display text as link and add a modal on mouse over with description or image)
- Map: displays an image and drops user defined markers on that image at coordinates.
- Image Stack w/ Fade slider: stack of images that the user is able to move a slider and see one image fade into another, useful for displaying multiple levels of a map or changes from one scene or image to another. Stack can have anywhere from one to many photos.
- Video Embed: Display video embeded in page