## This is the AI usage section. I will try to make it as flowing as possible (TREVOR OAKUM)

AI USED: CLAUDE

1. Asked Claude if my idea on my approach for each section made sense for the program efficiency and readability.
   Imports, Data Cleaning and Preparation, Setup, Build, Training, Interference, Results
   Response: Claude said this would be efficient
2. Asked Claude if YOLO would be wise to run what I wish to.
   Response: YOLO rejected the idea of running this build due to it feeling that the program would waste time and effort on something another program could do.
   As a result, I instead looked back through notes and the internet, and decided ResNet would be the model to run
3. When running initial Data Preparation and Cleaning, I noticed I wasn't getting the feedback I wanted. I prompted AI to ask what tools I could use. I made it a rule for the AI to not give me the solution until I could give the name of the module being used when doing stuff like this for the assignment. For example: If I wanted to import pandy, but I didn't know what pandy was, I could not get the code import pandy until I could both name pandy and describe what it is.
4. Issues with Epoch Scores (1st). On my first run, I had accuracy scores as low as 40-45%, while losses for both training and validation were above 1.00 in some cases. I asked Claude to give me reasons on why this was an issue. 
Response: I took out code that was hindering my process.
5. I had issues with results where the code would run fine, but no images would display.
   Claude's Response was to suggest moving some code around.
6. Epoch (2nd): My Scores improved to around 60-65%, but I was satisfied. I couldn't figure out what the problem was. 
   Claude: Suggestion was to remove a piece of code
7. My Training set was not running for a while (Curving into 4, but this one had issues on its own). The Feedback was popping up the same error message, despite it being fixed in that cell.
     Response: Claude pointed me out a bunch of case sensitive mistakes. In addition, an error was found earlier that caused issues. This was due to the fact that I hadn't ran the cells in order again after that.
8. A lot of Trackback and Naming Errors
    Claude: Pointed those out and fixed them without the help of it.
